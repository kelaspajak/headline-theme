# Diskusi Pajak — Ghost Theme

Custom Ghost CMS theme for [www.diskusipajak.com](https://www.diskusipajak.com), a tax discussion and resource platform focused on Coretax DJP, e-Faktur, PPh, PPN, and Indonesian tax regulations.

Built on top of the **Headline** theme framework by Ghost Foundation.

---

## Routing Architecture (`routes.yaml`)

### Collections (Post URL Assignment)

Ghost assigns each post to exactly **one** collection based on the **first matching filter** in `routes.yaml`.

```yaml
collections:
    /:
        permalink: '/{slug}/'
        template: index
        filter: tag:-[hash-wilayah,hash-tentang-pic,hash-coretaxpedia,hash-pemeriksaan]

    /resources/:
        permalink: /resources/{slug}/
        filter: tag:[hash-coretaxpedia, hash-pemeriksaan]
        template: resources
```

**How it works:**
1. A post tagged with `#coretaxpedia` (internal tag) hits the `/` collection filter first — it's **excluded** by `tag:-[hash-coretaxpedia]`, so it falls through.
2. It matches `/resources/` which includes `tag:[hash-coretaxpedia]` — assigned URL: `/resources/{slug}/`.
3. A regular post (no internal tags) matches `/` — assigned URL: `/{slug}/`.

**Critical:** Internal tags (`#hash-xxx`) make `primary_tag = null`, so use `tag:` not `primary_tag:` in filters.

### Routes (Category Channels)

```yaml
routes:
    /resources/coretaxpedia/:
        controller: channel
        template: resources-category
        filter: tag:hash-coretaxpedia

    /resources/pemeriksaan/:
        controller: channel
        template: resources-category
        filter: tag:hash-pemeriksaan
```

Channel routes create **filtered views** without changing post URLs. Posts appear in both the `/resources/` collection (for their canonical URL) and the channel route (for filtered browsing).

### Adding a New Resource Category

1. Create a new internal tag (e.g. `#ppn`) in Ghost Admin.
2. Add a channel route in `routes.yaml`:
   ```yaml
   /resources/ppn/:
       controller: channel
       template: resources-category
       filter: tag:hash-ppn
   ```
3. Add the tag to the `/resources/` collection filter:
   ```yaml
   filter: tag:[hash-coretaxpedia, hash-pemeriksaan, hash-ppn]
   ```
4. Restart Ghost.
5. Add a `ghTagData` entry in `resources-category.hbs` for the tag's hero section.

### Restart Required

`routes.yaml` is **cached in memory**. Changes take effect only after a Ghost restart.

---

## Templates

| Template | Route | Description |
|----------|-------|-------------|
| `home.hbs` | `/` | Landing page with letter, objection, Q&A grid, feature cards, subscribe |
| `resources.hbs` | `/resources/` | Parent resource collection index |
| `resources-category.hbs` | `/resources/coretaxpedia/`, `/resources/pemeriksaan/` | Per-category channel with featured posts + list feed |

### resources-category.hbs Layout

```
Hero (gh-tag-head, populated by JS ghTagData lookup)
  ├── Tag image + name + description
  └── "X posts" count

Featured posts (gh-featuredposts)
  └── 3-column grid of gh-card.post.featured (if any)

Post feed (gh-postfeed)
  └── resource-list-item links (non-featured posts)

Pagination (gh-category-pagination)
  └── Hidden via visibility:hidden (IntersectionObserver-safe)
```

---

## Custom Settings (`package.json` → `config.custom`)

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| `navigation_layout` | select | `Stacked` | Nav bar layout |
| `header_style` | select | `Light` | Header color scheme |
| `title_font` | select | `Modern sans-serif` | Heading font |
| `body_font` | select | `Elegant serif` | Body font |
| `enter_tag_slug_for_primary_sections` | text | — | Slugs for homepage topic grid |
| `enter_tag_slug_for_secondary_sections` | text | — | Slugs for secondary topic list |
| `show_featured_post_class` | select | `featured` | Toggle featured card styling |

---

## CSS

| File | Description |
|------|-------------|
| `assets/css/screen.css` | Main theme styles + Tailwind v4 build |
| `assets/css/ghost-resources.css` | Resource/category page styles (featured grid, list items, hero) |
| `assets/css/home.css` | Homepage custom styles (letter, objection, answers grid, features) |

CSS is built via Gulp/PostCSS with TailwindCSS v4 and `@tryghost/shared-theme-assets`.

```bash
# Build CSS
npx gulp css

# Or directly with Node
node -e "
const postcss = require('postcss'), tw = require('@tailwindcss/postcss'), nano = require('cssnano'), fs = require('fs');
const css = fs.readFileSync('assets/css/screen.css','utf8');
postcss([tw(),nano()]).process(css,{from:'assets/css/screen.css',to:'assets/built/screen.css'})
  .then(r => fs.writeFileSync('assets/built/screen.css',r.css));
"
```

---

## Development

```bash
# Install dependencies
yarn

# Watch & auto-build
yarn dev

# Build production zip
yarn zip
```

---

## Admin API Authentication

Used for bulk operations (e.g., marking posts as featured, changing status).

```python
import hmac, hashlib, base64, json, time

key_id = "your-api-key-id"
secret_hex = "your-hex-secret"

def ghost_jwt():
    def b64(d): return base64.urlsafe_b64encode(d).rstrip(b'=').decode()
    h = b64(json.dumps({"kid": key_id, "alg": "HS256"}).encode())
    now = int(time.time())
    p = b64(json.dumps({"iat": now, "exp": now + 300, "aud": "/admin/"}).encode())
    sig = b64(hmac.new(bytes.fromhex(secret_hex), f"{h}.{p}".encode(), hashlib.sha256).digest())
    return f"{h}.{p}.{sig}"

# Usage: curl -H "Authorization: Ghost $(ghost_jwt())" http://localhost:2368/ghost/api/admin/posts/
```

**Key gotcha:** The API secret must be **hex-decoded** (`bytes.fromhex()`) before HMAC signing, not used as a raw string.

**Updating posts** requires the `updated_at` field — omitting it returns HTTP 422.

---

## Key Ghost CMS Notes

- **Internal tags** (prefix `#`, slug `hash-xxx`) are NOT returned by `{{#get "tags"}}`.
- **`primary_tag` is `null`** for posts with only internal tags — use `tag:` in NQL filters.
- **Channel routes** do not influence post URLs (only collections do).
- **Infinity scroll** requires the observed element to NOT have `display: none` — use `visibility: hidden; height: 1px; overflow: hidden` instead.

---

## License

Based on [Headline](https://github.com/TryGhost/Headline) by Ghost Foundation — [MIT](LICENSE). Custom modifications for Diskusi Pajak.
