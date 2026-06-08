# Cluster Faktur Pajak — Outline Artikel

> **Status:** Draft
> **Dibuat:** 2026-06-07
> **Jumlah artikel:** 16

---

## Daftar Artikel

| # | File | Slug | Topik |
|---|------|------|-------|
| 01 | `01-pengertian-faktur-pajak.md` | `/faktur-pajak/pengertian/` | Apa itu faktur pajak, fungsi, dasar hukum |
| 02 | `02-jenis-faktur-pajak.md` | `/faktur-pajak/jenis/` | Faktur keluaran, masukan, pengganti, gabungan, batal |
| 03 | `03-kode-faktur-pajak.md` | `/faktur-pajak/kode/` | Kode 010-090, hierarki pemilihan |
| 04 | `04-pembuatan-faktur-pajak.md` | `/faktur-pajak/cara-membuat/` | Tata cara membuat faktur pajak |
| 05 | `05-upload-faktur-pajak.md` | `/faktur-pajak/upload/` | Upload faktur, batas waktu, status |
| 06 | `06-pajak-masukan-yang-tidak-dapat-dikreditkan.md` | `/faktur-pajak/pajak-masukan-tidak-dapat-dikreditkan/` | Pasal 9 ayat 8 UU PPN |
| 07 | `07-faktur-pajak-keluaran.md` | `/faktur-pajak/keluaran/` | Kewajiban PKP penjual |
| 08 | `08-faktur-pajak-masukan.md` | `/faktur-pajak/masukan/` | Pengkreditan PPN masukan |
| 09 | `09-faktur-pajak-pengganti.md` | `/faktur-pajak/pengganti/` | Kapan & cara buat faktur pengganti |
| 10 | `10-coretax-system.md` | `/faktur-pajak/coretax-system/` | PMK 81/2024, sistem Coretax |
| 11 | `11-spt-masa-ppn.md` | `/faktur-pajak/spt-masa-ppn/` | Pengisian & pelaporan SPT Masa PPN |
| 12 | `12-faktur-pajak-dalam-coretax.md` | `/faktur-pajak/dalam-coretax/` | Membuat faktur di Coretax |
| 13 | `13-pmk-131-2024.md` | `/faktur-pajak/pmk-131-2024/` | Deep dive PMK 131/2024 |
| 14 | `14-ppn-12-persen.md` | `/faktur-pajak/ppn-12-persen/` | Tarif PPN 12%, dampak ke faktur |
| 15 | `15-per-11-pj-2025.md` | `/faktur-pajak/per-11-pj-2025/` | Deep dive PER-11/PJ/2025 |
| 16 | `16-faq.md` | `/faktur-pajak/faq/` | Pertanyaan umum |

---

## Sumber Resmi (Peraturan)

| Peraturan | Judul Singkat | Tanggal | Status |
|-----------|---------------|---------|--------|
| PMK 81/2024 | Coretax System | 14 Okt 2024, berlaku 31 Des 2024 | Berlaku |
| PMK 54/2025 | Perubahan Ketiga PMK 81/2024 | 25 Jul 2025, berlaku 1 Agu 2025 | Berlaku |
| PMK 53/2025 | Perubahan Kedua PMK 81/2024 | 2025 | Berlaku |
| PMK 1/2026 | Perubahan Keempat PMK 81/2024 | 2026 | Berlaku |
| PMK 131/2024 | Tarif PPN 12%, perlakuan PPN | 2024, berlaku 1 Jan 2025 | Berlaku |
| PER-11/PJ/2025 | Pelaporan PPh, PPN, PPnBM di Coretax | 22 Mei 2025 | Berlaku |
| PER-1/PJ/2025 | Petunjuk teknis pembuatan faktur | 2025 (berakhir) | Berakhir |
| UU HPP 7/2021 | Tarif PPN 12% (dasar hukum) | 29 Okt 2021 | Berlaku |
| UU PPN 42/2009 | PPN dasar | 2009 | Berlaku |

---

## Outline per Artikel

---

### 01 — Pengertian Faktur Pajak

**Slug:** `/faktur-pajak/pengertian/`
**Target:** Pembaca baru yang belum tahu apa itu faktur pajak

**Outline:**
1. Definisi faktur pajak (Pasal 1 angka 13 UU PPN 42/2009)
2. Fungsi faktur pajak:
   - Bagi penjual: bukti pungutan PPN (pajak keluaran)
   - Bagi pembeli: bukti PPN dapat dikreditkan (pajak masukan)
   - Dasar pengisian SPT Masa PPN
3. Dasar hukum:
   - UU PPN 42/2009
   - UU HPP 7/2021
   - PMK 81/2024
   - PER-11/PJ/2025
   - PMK 131/2024
4. Siapa wajib membuat: PKP yang menyerahkan BKP/JKP
5. Kapan dibuat: saat terutang PPN
6. Faktur pajak vs bukti potong vs buki setor

**Peraturan yang dirujuk:** UU PPN 42/2009, PMK 81/2024, PER-11/PJ/2025
**Internal links:** 02, 04, 07

---

### 02 — Jenis-Jenis Faktur Pajak

**Slug:** `/faktur-pajak/jenis/`
**Target:** PKP yang perlu tahu jenis faktur yang tepat untuk transaksinya

**Outline:**
1. Faktur Pajak Keluaran (kode 010, 020, 030, 040, 050, 060, 070, 080, 090)
2. Faktur Pajak Masukan
3. Faktur Pajak Pengganti
4. Faktur Pajak Gabungan
5. Faktur Pajak Sederhana (pedagang eceran)
6. Faktur Pajak Batal
7. Faktur Pajak Uang Muka
8. Faktur Pajak Pelunasan
9. Dokumen dipersamakan dengan Faktur Pajak (PIB, SSP, dll)

**Peraturan yang dirujuk:** UU PPN 42/2009, PER-11/PJ/2025
**Internal links:** 03, 07, 08, 09

---

### 03 — Kode Faktur Pajak

**Slug:** `/faktur-pajak/kode/`
**Target:** PKP yang bingung memilih kode transaksi

**Outline:**
1. Apa itu kode faktur pajak (3 digit)
2. Tabel kode:
   - 010: PPN dipungut sendiri oleh PKP penjual
   - 020: PPN dipungut pemungut PPN (instansi pemerintah)
   - 030: PPN ditanggung pemerintah (DTP)
   - 040: PPN dibebaskan
   - 050: PPN dipungut pemungut selain instansi pemerintah
   - 060: Tidak dipungut PPN (kawasan bebas, dll)
   - 070: Fasilitas PPN tidak dipungut
   - 080: Fasilitas PPN dibebaskan
   - 090: Penyerahan bersifat final
3. Hierarki pemilihan kode (urutan prioritas)
4. Kode faktur di era Coretax
5. Kesalahan umum

**Peraturan yang dirujuk:** PER-11/PJ/2025, PMK 131/2024
**Internal links:** 02, 04, 12

---

### 04 — Cara Membuat Faktur Pajak

**Slug:** `/faktur-pajak/cara-membuat/`
**Target:** Panduan teknis PKP

**Outline:**
1. Syarat penerbitan (PKP, ada penyerahan, akses e-Faktur/Coretax)
2. Isi wajib faktur (PER-11/PJ/2025):
   - Data PKP penjual
   - Identitas pembeli (NPWP/NIK/paspor)
   - Detail transaksi
   - Kode, nomor seri, tanggal
   - Tanda tangan
3. Langkah di e-Faktur (legacy)
4. Langkah di Coretax
5. Batas waktu: paling lambat 3 bulan setelah saat terutang
6. Nomor seri faktur

**Peraturan yang dirujuk:** PER-11/PJ/2025, PMK 81/2024
**Internal links:** 03, 05, 12

---

### 05 — Upload Faktur Pajak

**Slug:** `/faktur-pajak/upload/`
**Target:** PKP yang ingin memastikan faktur valid

**Outline:**
1. Apa itu upload faktur
2. Batas waktu upload:
   - Sebelum PER-11/PJ/2025: tanggal 20 bulan berikutnya
   - Setelah PER-11/PJ/2025: batas dihapus, pengkreditan maks 3 bulan
3. Cara upload di e-Faktur
4. Cara upload di Coretax
5. Status faktur: Pending, Approved, Rejected
6. Troubleshooting: gagal upload, sertifikat elektronik

**Peraturan yang dirujuk:** PER-11/PJ/2025
**Internal links:** 04, 10, 12

---

### 06 — Pajak Masukan yang Tidak Dapat Dikreditkan

**Slug:** `/faktur-pajak/pajak-masukan-tidak-dapat-dikreditkan/`
**Target:** PKP yang ingin tahu batasan pengkreditan

**Outline:**
1. Prinsip: Pajak Masukan vs Pajak Keluaran
2. Kriteria tidak bisa dikreditkan (Pasal 9 ayat 8 UU PPN 42/2009):
   - Tidak berhubungan langsung dengan usaha
   - Kendaraan bermotor (kecuali diperdagangkan)
   - Pemanfaatan JKP luar daerah pabean tidak terkait usaha
   - Faktur tidak memenuhi ketentuan formal
   - PPN dibebaskan
   - Hibah/sumbangan
3. Faktur tidak memenuhi syarat formal
4. Dampak jika tetap dikreditkan
5. Pengecualian (Pasal 9 ayat 9): pengkreditan diperpanjang maks 3 bulan
6. Contoh kasus

**Peraturan yang dirujuk:** UU PPN 42/2009
**Internal links:** 08, 11

---

### 07 — Faktur Pajak Keluaran

**Slug:** `/faktur-pajak/keluaran/`
**Target:** PKP penjual

**Outline:**
1. Definisi faktur pajak keluaran
2. Kewajiban PKP penjual
3. Saat terutang PPN (kapan faktur dibuat)
4. Penghitungan PPN Keluaran: 12% x DPP (PMK 131/2024)
5. Contoh perhitungan
6. Transaksi khusus: instansi pemerintah (020), DTP (030), bebas (040)

**Peraturan yang dirujuk:** UU PPN 42/2009, PMK 131/2024, PER-11/PJ/2025
**Internal links:** 01, 03, 11, 14

---

### 08 — Faktur Pajak Masukan

**Slug:** `/faktur-pajak/masukan/`
**Target:** PKP pembeli

**Outline:**
1. Definisi faktur pajak masukan
2. Syarat bisa dikreditkan
3. Cara mengkreditkan (e-Faktur & Coretax)
4. Batas waktu pengkreditan: maks 3 bulan setelah masa pajak
5. Faktur status "Pending"
6. Rekonsiliasi faktur masukan

**Peraturan yang dirujuk:** UU PPN 42/2009, PER-11/PJ/2025
**Internal links:** 06, 11

---

### 09 — Faktur Pajak Pengganti

**Slug:** `/faktur-pajak/pengganti/`
**Target:** PKP yang perlu memperbaiki faktur

**Outline:**
1. Definisi faktur pajak pengganti
2. Kapan harus buat pengganti (kesalahan pengisian)
3. Cara membuat di e-Faktur
4. Cara membuat di Coretax
5. Dampak ke SPT Masa PPN (pembetulan)
6. Batas waktu
7. Contoh kasus

**Peraturan yang dirujuk:** UU PPN 42/2009, PER-11/PJ/2025
**Internal links:** 04, 11

---

### 10 — Coretax System (PMK 81/2024)

**Slug:** `/faktur-pajak/coretax-system/`
**Target:** Semua PKP

**Outline:**
1. Apa itu Coretax
2. Dasar hukum: PMK 81/2024
   - Tanggal: 14 Okt 2024, berlaku 31 Des 2024
   - Mencabut 29 PMK sebelumnya
3. Perubahan bertahap:
   - PMK 53/2025 (perubahan 2)
   - PMK 54/2025 (perubahan 3)
   - PMK 1/2026 (perubahan 4)
4. Perubahan yang dibawa Coretax:
   - Faktur via portal (bukan desktop)
   - SPT Masa PPN terintegrasi
   - PPh + PPN dalam satu sistem
   - e-Bupot unifikasi
5. Siapa yang wajib pakai
6. Cara akses: https://coretax.pajak.go.id
7. Fitur utama

**Peraturan yang dirujuk:** PMK 81/2024, PMK 54/2025, PMK 53/2025, PMK 1/2026
**Internal links:** 12, 15

---

### 11 — SPT Masa PPN

**Slug:** `/faktur-pajak/spt-masa-ppn/`
**Target:** PKP yang akan melaporkan PPN

**Outline:**
1. Definisi SPT Masa PPN
2. Siapa wajib lapor
3. Komponen: Pajak Keluaran, Pajak Masukan, Selisih
4. Batas waktu: akhir bulan berikutnya
5. Cara mengisi di Coretax
6. Pembayaran via e-Billing
7. Sanksi terlambat lapor (Rp500.000)
8. Sanksi terlambat bayar

**Peraturan yang dirujuk:** PER-11/PJ/2025, UU KUP
**Internal links:** 07, 08, 10

---

### 12 — Faktur Pajak dalam Coretax

**Slug:** `/faktur-pajak/dalam-coretax/`
**Target:** PKP yang sudah pakai Coretax

**Outline:**
1. Perbedaan e-Faktur vs Coretax
2. Langkah membuat faktur di Coretax
3. Status faktur: Draft, Submitted, Approved, Rejected
4. Unduh faktur (PDF)
5. Faktur masukan di Coretax
6. Troubleshooting

**Peraturan yang dirujuk:** PMK 81/2024, PER-11/PJ/2025
**Internal links:** 04, 05, 10

---

### 13 — PMK 131/2024 (Deep Dive)

**Slug:** `/faktur-pajak/pmk-131-2024/`
**Target:** Pembaca yang ingin detail peraturan

**Outline:**
1. Metadata lengkap
2. Apa yang diatur: impor BKP, penyerahan BKP/JKP, pemanfaatan JKP
3. Tarif PPN 12% (berlaku 1 Jan 2025)
4. DPP Nilai Lain (11/12)
5. Dampak ke pembuatan faktur
6. Petunjuk teknis (PER-1/PJ/2025, sudah berakhir)
7. Link download PDF

**Peraturan yang dirujuk:** PMK 131/2024, UU HPP 7/2021
**Internal links:** 14, 04, 07

---

### 14 — PPN 12 Persen

**Slug:** `/faktur-pajak/ppn-12-persen/`
**Target:** Semua pihak yang terdampak kenaikan tarif

**Outline:**
1. Kronologi tarif: 10% → 11% → 12%
2. Dasar hukum: UU HPP 7/2021 Pasal 7, PMK 131/2024
3. Berlaku: 1 Januari 2025
4. Tarif 0% untuk ekspor
5. Barang/jasa dibebaskan (Pasal 16B)
6. Dampak ke faktur pajak
7. Contoh perhitungan sebelum vs sesudah
8. Penyesuaian di e-Faktur & Coretax

**Peraturan yang dirujuk:** PMK 131/2024, UU HPP 7/2021
**Internal links:** 13, 07

---

### 15 — PER-11/PJ/2025 (Deep Dive)

**Slug:** `/faktur-pajak/per-11-pj-2025/`
**Target:** Pembaca yang ingin detail peraturan pelaporan

**Outline:**
1. Metadata lengkap
2. Apa yang diatur: pelaporan PPh, PPN, PPnBM, Bea Meterai
3. Perubahan penting untuk PPN:
   - Bentuk & isi SPT Masa PPN
   - Penghapusan batas upload faktur
   - Faktur wajib elektronik
4. Dampak ke PKP
5. Link download PDF

**Peraturan yang dirujuk:** PER-11/PJ/2025, PMK 81/2024
**Internal links:** 10, 11

---

### 16 — FAQ Faktur Pajak

**Slug:** `/faktur-pajak/faq/`
**Target:** Pembaca yang cari jawaban cepat

**Outline:**
1. Apa bedanya faktur pajak dan faktur penjualan?
2. Kapan faktur pajak harus dibuat?
3. Apa sanksi tidak membuat faktur pajak?
4. Bisakah faktur dibuat mundur (backdate)?
5. Bagaimana jika faktur hilang?
6. Apa bedanya kode 010, 020, 030, 040?
7. Faktur untuk transaksi dengan instansi pemerintah?
8. Apa itu faktur gabungan?
9. Cara kreditkan faktur masukan?
10. Sanksi terlambat upload?
11. Faktur untuk ekspor?
12. Apakah UMKM (PP 55/2022) perlu buat faktur?
13. Transisi e-Faktur ke Coretax?
14. Sertifikat elektronik?

**Internal links:** semua artikel terkait

---

## Hierarki Regulasi

```
UU PPN 42/2009
  └── UU HPP 7/2021 (tarif)
        └── PMK 131/2024 (12%, perlakuan)
              └── PER-1/PJ/2025 (petunjuk faktur, berakhir)

PMK 81/2024 (Coretax)
  ├── PMK 53/2025 (perubahan 2)
  ├── PMK 54/2025 (perubahan 3)
  ├── PMK 1/2026 (perubahan 4)
  └── PER-11/PJ/2025 (pelaporan)
```

---

## Catatan Penulisan

- **Tone:** Langsung, jelas, sesuai gaya diskusipajak.com
- **Format angka:** Rp10.000.000
- **Sumber:** Cantumkan link ke peraturan resmi (BPK, DJP)
- **Internal linking:** Minimal 3 link per artikel
- **Tag:** `faktur-pajak`, `ppn`, `coretax`, `e-faktur`, `pajak-masukan`, `pajak-keluaran`
- **Target pembaca:** PKP, akuntan, staf keuangan, pemilik usaha
