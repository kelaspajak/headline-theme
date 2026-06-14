## Color Palette System

- [x] **Define mapping layer di `:root`** — `assets/css/screen.css:4-22`. Tambah 8 CSS variables baru (`--bg-color`, `--card-bg`, `--text-color`, `--text-muted`, `--accent-color`, `--heading-color`, `--border-color`, `--code-bg`) yang me-map ke `--color-*` eksisting. Contoh: `--bg-color: var(--color-white)`, `--text-color: var(--color-primary-text)`, `--border-color: var(--color-light-gray)`. Foundation agar palette bisa override tanpa merusak CSS lama.

- [x] **Isi `palette-default` dengan nilai mapping** — `assets/css/screen.css`. Saat ini nilainya kosong. Isi dengan nilai warna default theme yang sudah ada (light theme).

- [x] **Tambah `.palette-cyberpunk`** — `assets/css/screen.css`. 8 variables: `--bg-color: #0d0d12`, `--card-bg: #16161f`, `--text-color: #d0d0e0`, `--text-muted: #5a5a7a`, `--accent-color: #ff2a6d`, `--heading-color: #e0e0f0`, `--border-color: #1f1f2e`, `--code-bg: #08080d`.

- [x] **Tambah `.palette-ollama`** — `assets/css/screen.css`. Light theme: `--bg-color: #ffffff`, `--card-bg: #f5f5f5`, `--text-color: #262626`, `--text-muted: #6b7280`, `--accent-color: #2563eb`, `--heading-color: #171717`, `--border-color: #d4d4d4`, `--code-bg: #f5f5f5`.

- [x] **Tambah `color_palette` setting di `package.json:44-102`** — Daftarkan `color_palette` sebagai custom setting type `select` dengan opsi `"Default"`, `"Cyberpunk"`, `"Ollama"`. Ini muncul di Ghost Admin → Design → Theme settings.

- [x] **Tambah class `palette-*` di `default.hbs:15`** — Di body class, tambah `{{#match @custom.color_palette "Cyberpunk"}}palette-cyberpunk{{else match @custom.color_palette "Ollama"}}palette-ollama{{/match}}`. Agar Ghost bisa inject palette dari Admin.

- [x] **Buat `partials/palette-switcher.hbs`** — Dropdown `<select>` dengan opsi palette. Dilengkapi JS inline yang: (a) baca `localStorage.getItem('headline-palette')` on load → terapkan class, (b) on change → simpan ke localStorage + panggil `applyPalette()`. Include partial di `default.hbs`.

- [x] **Integrasi palette-switcher di `default.hbs`** — Include `{{> "palette-switcher"}}` di dalam `.gh-head-actions`.

- [x] **Refactor: ganti `var(--color-light-gray)` untuk border → `var(--border-color)`** — ~5 lokasi (gh-head-inner, gh-topic-footer, gh-card.large, gh-topic-header, input border).

- [x] **Refactor: ganti `var(--color-whitegrey)` → `var(--border-color)`** — ~9 lokasi untuk border di resource sections.

- [x] **Refactor: ganti `var(--color-lighter-gray)` untuk border → `var(--border-color)`** — 2 lokasi (resources section, resources post).

- [x] **Refactor: ganti `var(--color-secondary-text)` → `var(--text-muted)`** — ~6 lokasi.

- [x] **Fix typo: rename `pallette-color.md` → `palette-color.md`** — Juga fix `pallete-default` → `palette-default` di konten file.

- [x] **Build & verify** — CSS & Tailwind build sukses. gscan: 1 error false-positive (`color_palette` tidak terdeteksi di `default.hbs` karena nested `else match`), 2 warnings pre-existing.

- [x] **Affected files:** - partials/related-posts.hbs: Missing Custom Theme Setting: "related_posts_show_excerpt" (L3  - Custom theme settings defined in package.json must be used at least once in the theme templates.

- [x] **Affected files:**  package.json: Found unused variables: @custom.enter_tag_slugs_for_primary_sections, @custom.enter_tag_slugs_for_secondary_sections, @custom.show_featured_post_class
