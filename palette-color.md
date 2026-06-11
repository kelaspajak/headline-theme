Berikut cara kerja color palette system `screen.css`:

### 1. Design Tokens (CSS Custom Properties)

Semua warna di theme menggunakan 7 CSS variables yang didefinisikan di `:root` (dark mode base):

```
--bg-color / --card-bg / --text-color / --text-muted
--accent-color / --heading-color / --border-color / --code-bg
```

### 2. Server-side: Ghost Setting → Body Class

Di `default.hbs:24`, `@custom.color_palette` dari Ghost Admin menghasilkan class `palette-*` di `<body>`:

```handlebars
{{#match @custom.color_palette "Dracula"}}palette-dracula{{/match}}
```

Jadi saat render, body langsung punya class palette sesuai setting admin.

### 3. CSS: Setiap Palette Override Variabel yang Sama

Setiap `.palette-*` class (baris 2070–2189) mendeklarasikan ulang 7 variables yang sama dengan nilai warna berbeda:

```css
.palette-dracula {
    --bg-color: #282a36;
    --accent-color: #bd93f9;
    ...
}
.palette-light {
    --bg-color: #f5f0eb;
    --accent-color: #6b4fbc;
    ...
}

/* SECTION: Color Palettes */
.palette-default {
    --bg-color: ;
    --card-bg: ;
    --text-color: ;
    --text-muted: ;
    --accent-color: ;
    --heading-color: ;
    --border-color: ;
    --code-bg: ;
}
.palette-dracula {
    --bg-color: #282a36;
    --card-bg: #343746;
    --text-color: #f8f8f2;
    --text-muted: #6272a4;
    --accent-color: #bd93f9;
    --heading-color: #f8f8f2;
    --border-color: #44475a;
    --code-bg: #1e1f29;
}

.palette-catppuccin {
    --bg-color: #1e1e2e;
    --card-bg: #313244;
    --text-color: #cdd6f4;
    --text-muted: #6c7086;
    --accent-color: #cba6f7;
    --heading-color: #cdd6f4;
    --border-color: #45475a;
    --code-bg: #181825;
}

.palette-nordic {
    --bg-color: #1a2421;
    --card-bg: #22302b;
    --text-color: #d4cfc4;
    --text-muted: #7a8c7e;
    --accent-color: #8fb573;
    --heading-color: #e8e2d6;
    --border-color: #2e3e37;
    --code-bg: #141d1a;
}

.palette-earth {
    --bg-color: #231c17;
    --card-bg: #2e2520;
    --text-color: #d4c8b8;
    --text-muted: #937e6a;
    --accent-color: #c67a4a;
    --heading-color: #e8ddd0;
    --border-color: #3a302a;
    --code-bg: #1a1511;
}

.palette-cyberpunk {
    --bg-color: #0d0d12;
    --card-bg: #16161f;
    --text-color: #d0d0e0;
    --text-muted: #5a5a7a;
    --accent-color: #ff2a6d;
    --heading-color: #e0e0f0;
    --border-color: #1f1f2e;
    --code-bg: #08080d;
}

.palette-nightowl {
    --bg-color: #011627;
    --card-bg: #0b2942;
    --text-color: #d6deeb;
    --text-muted: #637777;
    --accent-color: #7fdbca;
    --heading-color: #d6deeb;
    --border-color: #1d3b53;
    --code-bg: #001122;
}

.palette-nord {
    --bg-color: #2e3440;
    --card-bg: #3b4252;
    --text-color: #d8dee9;
    --text-muted: #7b88a1;
    --accent-color: #88c0d0;
    --heading-color: #eceff4;
    --border-color: #434c5e;
    --code-bg: #242933;
}

.palette-solarized {
    --bg-color: #002b36;
    --card-bg: #073642;
    --text-color: #839496;
    --text-muted: #7c9198;
    --accent-color: #268bd2;
    --heading-color: #93a1a1;
    --border-color: #094959;
    --code-bg: #00212b;
}

.palette-gruvbox {
    --bg-color: #282828;
    --card-bg: #3c3836;
    --text-color: #ebdbb2;
    --text-muted: #928374;
    --accent-color: #fabd2f;
    --heading-color: #fbf1c7;
    --border-color: #504945;
    --code-bg: #1d2021;
}

.palette-light {
    --bg-color: #f5f0eb;
    --card-bg: #ffffff;
    --text-color: #2d2a24;
    --text-muted: #8a8580;
    --accent-color: #6b4fbc;
    --heading-color: #1a1814;
    --border-color: #ddd8d0;
    --code-bg: #ffffff;
}

.palette-ollama {
    --bg-color: #ffffff;
    --card-bg: #f5f5f5;
    --text-color: #262626;
    --text-muted: #6b7280;
    --accent-color: #2563eb;
    --heading-color: #171717;
    --border-color: #d4d4d4;
    --code-bg: #f5f5f5;
}
```

Karena semua komponen CSS merujuk ke `var(--bg-color)` dst, mengganti class di `<body>` otomatis me-recolor seluruh halaman — tanpa satu pun `!important` atau `@media (prefers-color-scheme)`.

### 4. Client-side: Palette Switcher

`partials/palette-switcher.hbs` menyediakan `<select>` + JS yang:

- **On load**: membaca `localStorage.getItem('tidslinje-palette')` → override class di `<body>`
- **On change**: simpan ke localStorage → panggil `applyPalette()` yang hapus semua class `palette-*` lalu tambah yang baru
- Persistensi: pilihan user tetap ada walau reload

### 5. Palette Default
`palette-default` adalah palette yang digunakan sebagai fallback jika tidak ada palette yang dipilih oleh user. Ini adalah palette yang digunakan secara default saat halaman pertama kali dimuat. Palette ini merupakan warna default yang digunakan oleh ghost cms saat ini.
