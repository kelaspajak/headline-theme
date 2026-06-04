# Coretaxpedia

Ensiklopedia FAQ Coretax DJP — konten di-scrape dari https://pajak.go.id/coretaxpedia dan digabung per submenu.

## Sumber Data

- **URL:** https://pajak.go.id/coretaxpedia
- **Terakhir di-scrape:** 2026-05-30
- **Total FAQ:** 228 item dalam 19 file gabungan

## Struktur File

Setiap `.mdx` merepresentasikan satu submenu dari sidebar Coretaxpedia. Di dalamnya, setiap item FAQ dijadikan heading `##`.

```
src/content/coretaxpedia/
├── README.md                          ← file ini
├── index.json                         ← metadata ordering
│
├── akses-dan-aktivasi-coretax-djp.mdx          (15 items)
├── pendaftaran-wajib-pajak.mdx                  (4 items)
├── impersonate.mdx                              (4 items)
├── role-dan-pihak-terkait.mdx                   (14 items)
├── kode-otorisasi-dan-sertifikat-digital.mdx    (9 items)
├── perubahan-status-dan-perubahan-data.mdx      (15 items)
├── bukti-potong.mdx                             (25 items)
├── faktur-pajak.mdx                             (21 items)
├── spt.mdx                                      (34 items)
├── contoh-kasus-spt.mdx                         (3 items)
├── kode-billing.mdx                             (12 items)
├── pemindahbukuan-dan-restitusi.mdx             (4 items)
├── deposit-dan-buku-besar.mdx                   (13 items)
├── jenis-dan-akses-layanan.mdx                  (6 items)
├── umum.mdx                                     (15 items)
├── kasus-tertentu.mdx                           (11 items)
├── solusi-error.mdx                             (21 items)
├── buku.mdx                                     (1 item)
└── templat.mdx                                  (1 item)
```

## Format MDX

```mdx
---
title: "Judul Submenu"
category: "Kategori Utama"
description: "Kumpulan FAQ ... dari Coretaxpedia"
source: "https://pajak.go.id/coretaxpedia"
lastScraped: "2026-05-30"
---

# Judul Submenu

## Judul Item FAQ 1

Terakhir diupdate pada: ...

**Q: Pertanyaan?**

A: Jawaban...

---

## Judul Item FAQ 2

...
```

## Routing (Astro)

- **Index:** `/coretaxpedia` — daftar semua entri (grid/list + search)
- **Detail:** `/coretaxpedia/{slug}` — halaman per submenu
- Content collection: `coretaxpedia` di `src/content.config.ts`
- Page files: `src/pages/coretaxpedia/index.astro` dan `src/pages/coretaxpedia/[slug].astro`

## Pembaruan

Untuk memperbarui konten:

1. Scrape ulang dari https://pajak.go.id/coretaxpedia
2. Jalankan scraper untuk menghasilkan file individual
3. Jalankan `combine-mdx.mjs` untuk menggabungkan per submenu
4. Hapus file individual lama, pertahankan hanya 19 file gabungan

## Sidebar Structure

| Kategori | Submenu | Items |
|----------|---------|-------|
| Registrasi | Akses dan Aktivasi Coretax DJP | 15 |
| Registrasi | Pendaftaran Wajib Pajak | 4 |
| Registrasi | Impersonate | 4 |
| Registrasi | Role & Pihak Terkait | 14 |
| Registrasi | Kode Otorisasi dan Sertifikat Digital | 9 |
| Registrasi | Perubahan Status dan Perubahan Data | 15 |
| Pelaporan SPT | Bukti Potong | 25 |
| Pelaporan SPT | Faktur Pajak | 21 |
| Pelaporan SPT | SPT | 34 |
| Pelaporan SPT | Contoh Kasus SPT | 3 |
| Pembayaran | Kode Billing | 12 |
| Pembayaran | Pemindahbukuan dan Restitusi | 4 |
| Pembayaran | Deposit dan Buku Besar | 13 |
| Layanan Perpajakan | Jenis dan Akses Layanan | 6 |
| Lain-Lain | Umum | 15 |
| Lain-Lain | Kasus Tertentu | 11 |
| Lain-Lain | Solusi Error | 21 |
| Berkas Digital | Buku | 1 |
| Berkas Digital | Templat | 1 |
