# Cluster PPh 21 — Struktur & Outline

> **Status:** Draft outline
> **Dibuat:** 2026-06-07
> **Sumber utama:**
> - PP No. 58 Tahun 2023 (Tarif Pemotongan PPh 21)
> - PMK No. 66 Tahun 2023 (Natura & Kenikmatan)
> - PMK No. 168 Tahun 2023 (Petunjuk Pelaksanaan Pemotongan / TER)

---

## Struktur Folder

```
clusters/pph-21/
├── outline.md              ← file ini
├── 01-pengertian-dasar.md
├── 02-siapa-yang-dipotong.md
├── 03-penghasilan-kena-pajak.md
├── 04-ptkp.md
├── 05-tarif-pph-21.md
├── 06-ter-tarif-efektif.md
├── 07-cara-hitung-pegawai-tetap.md
├── 08-cara-hitung-pegawai-tidak-tetap.md
├── 09-cara-hitung-pegawai-harian.md
├── 10-natura-kenikmatan.md
├── 11-bupot-pph-21.md
├── 12-spt-tahunan-pph-21.md
├── 13-pp-58-2023.md
├── 14-pmk-66-2023.md
├── 15-pmk-168-2023.md
└── 16-faq.md
```

---

## Outline per Artikel

---

### 01 — Pengertian Dasar PPh 21

**Slug:** `/pph-21/pengertian-dasar/`

**Tujuan:** Pembaca memahami apa itu PPh 21, dasar hukumnya, dan di mana posisinya di sistem perpajakan Indonesia.

**Outline:**
1. Apa itu PPh Pasal 21?
   - Definisi sederhana: pajak atas penghasilan dari pekerjaan/jasa/kegiatan
   - Pajak yang dipotong pihak lain (pemberi kerja), bukan dibayar sendiri
2. Dasar Hukum
   - UU No. 7 Tahun 1983 tentang Pajak Penghasilan (berbagai perubahan terakhir: UU HPP No. 7/2021)
   - PP No. 58 Tahun 2023 (tarif)
   - PMK No. 168 Tahun 2023 (petunjuk pelaksanaan)
3. PPh 21 vs PPh 21 vs PPh Final vs PPh Badan — posisi di sistem perpajakan
4. Siapa yang terlibat?
   - Pemotong pajak (pemberi kerja / pemberi imbalan)
   - Penerima penghasilan (karyawan, freelancer, pejabat, dll)
5. Alur sederhana: Pemberi kerja bayar gaji → potong PPh 21 → setor ke kas negara → buktikan lewat bukpot

**Internal links ke:**
- 02-siapa-yang-dipotong.md
- 05-tarif-pph-21.md
- 13-pp-58-2023.md

---

### 02 — Siapa yang Dipotong PPh 21

**Slug:** `/pph-21/siapa-yang-dipotong/`

**Tujuan:** Pembaca tahu apakah mereka termasuk objek PPh 21 atau tidak.

**Outline:**
1. Subjek Pajak PPh 21
   - Orang pribadi (dalam negeri & luar negeri)
   - BUT (Badan Usaha Tetap) untuk pegawai BUT
2. Jenis penerima penghasilan:
   a. **Pegawai tetap** — kontrak tidak terbatas, menerima gaji rutin
   b. **Pegawai tidak tetap / tenaga kerja lepas** — kontrak terbatas, freelancer
   c. **Pegawai harian** — dibayar per hari kerja
   d. **Pejabat negara** — menteri, gubernur, bupati, dll
   e. **PNS, TNI, Polri** — termasuk pensiunannya
   f. **Pensiunan** — penerima pensiun berkala
   g. **Anggota dewan komisaris/direksi** — yang bukan pegawai tetap
   h. **Peserta kegiatan** — narasumber, moderator, panitia, dll
3. Yang **bukan** objek PPh 21:
   - Penghasilan di bawah PTKP
   - Penghasilan yang sudah dikenakan PPh Final (UMKM PP 23/2018, PP 55/2022)
   - Penghasilan yang dikenakan PPh Pasal 22, 23, 25, 26
4. Status kewajiban pajak: dalam negeri vs luar negeri

**Internal links ke:**
- 04-ptkp.md
- 07-cara-hitung-pegawai-tetap.md
- 08-cara-hitung-pegawai-tidak-tetap.md

---

### 03 — Penghasilan Kena Pajak (PKP) PPh 21

**Slug:** `/pph-21/penghasilan-kena-pajak/`

**Tujuan:** Pembaca memahami apa saja yang termasuk penghasilan bruto PPh 21 dan apa saja pengurangnya.

**Outline:**
1. Penghasilan Bruto PPh 21 — apa saja yang masuk?
   - Gaji, tunjangan, lembur, THR, bonus, jasa produksi, gratifikasi
   - Natura & kenikmatan (dengan pengecualian PMK 66/2023)
   - Tunjangan pajak & reimburse yang bersifat penghasilan
2. Pengurang penghasilan bruto:
   - Biaya jabatan / biaya pensiun (5% dari bruto, max Rp24.000/tahun → Rp2.000/bulan)
   - Iuran pensiun / iuran THT/JHT
   - PTKP (Penghasilan Tidak Kena Pajak)
3. Rumus dasar:
   ```
   Penghasilan Bruto
   - Biaya Jabatan (5%, max Rp24.000/tahun)
   - Iuran Pensiun
   = Penghasilan Neto
   - PTKP
   = Penghasilan Kena Pajak (PKP)
   ```
4. Contoh perhitungan sederhana

**Internal links ke:**
- 04-ptkp.md
- 05-tarif-pph-21.md
- 10-natura-kenikmatan.md

---

### 04 — PTKP (Penghasilan Tidak Kena Pajak)

**Slug:** `/pph-21/ptkp/`

**Tujuan:** Pembaca tahu berapa batas penghasilan yang tidak kena pajak sesuai status mereka.

**Outline:**
1. Apa itu PTKP?
2. Besaran PTKP (berlaku saat ini):
   | Kode | Status | PTKP/Tahun |
   |------|--------|------------|
   | TK/0 | Tidak kena pajak / sendiri | Rp54.000.000 |
   | TK/1 | + 1 tanggungan | Rp58.500.000 |
   | TK/2 | + 2 tanggungan | Rp63.000.000 |
   | TK/3 | + 3 tanggungan | Rp67.500.000 |
   | K/0 | Kawin, istri tidak bekerja | Rp112.500.000 |
   | K/1 | + 1 tanggungan | Rp117.000.000 |
   | K/2 | + 2 tanggungan | Rp121.500.000 |
   | K/3 | + 3 tanggungan | Rp126.000.000 |
3. Aturan tanggungan: max 3 orang, harus ada hubungan keluarga, penghasilan tanggungan gabung
4. Kapan PTKP berubah? (penyesuaian oleh Menteri Keuangan)
5. Contoh: gaji Rp5 juta/bulan, status TK/0 → apakah kena PPh 21?

**Internal links ke:**
- 03-penghasilan-kena-pajak.md
- 05-tarif-pph-21.md

---

### 05 — Tarif PPh 21 (PP No. 58 Tahun 2023)

**Slug:** `/pph-21/tarif/`

**Tujuan:** Pembaca tahu tarif progresif PPh 21 terbaru berdasarkan PP 58/2023.

**Outline:**
1. Dasar hukum: PP No. 58 Tahun 2023 (mencabut sebagian PP 80/2010)
2. Tarif progresif Pasal 17 UU PPh:
   | Lapisan PKP | Tarif |
   |-------------|-------|
   | s.d. Rp60.000.000 | 5% |
   | Rp60.000.001 – Rp250.000.000 | 15% |
   | Rp250.000.001 – Rp500.000.000 | 25% |
   | Rp500.000.001 – Rp5.000.000.000 | 30% |
   | Di atas Rp5.000.000.000 | 35% |
3. Tarif Pasal 17 ayat (1) huruf a — untuk penghitungan tahunan / kelebihan pembayaran
4. Tarif efektif (TER) — untuk pemotongan bulanan (lihat artikel khusus)
5. Tarif non-resident: 20% dari penghasilan bruto (PPh 26)
6. Perbandingan tarif lama vs baru (jika ada perubahan di PP 58/2023)

**Internal links ke:**
- 06-ter-tarif-efektif.md
- 13-pp-58-2023.md

---

### 06 — Tarif Efektif (TER) PPh 21

**Slug:** `/pph-21/tarif-efektif-ter/`

**Tujuan:** Pembaca memahami cara penghitungan PPh 21 bulanan menggunakan TER dari PMK 168/2023.

**Outline:**
1. Apa itu Tarif Efektif (TER)?
   - Tarif rata-rata yang sudah memperhitungkan PTKP & tarif progresif
   - Digunakan untuk mempermudah pemotongan PPh 21 per bulan
2. Dasar hukum: PMK No. 168 Tahun 2023
3. Kategori TER: TER A, TER B, TER C (berdasarkan status Kawin/Tidak Kawin & tanggungan)
4. Tabel TER bulanan (lengkap, per kategori)
   - TER A: TK/0, TK/1, TK/2, TK/3
   - TER B: K/0, K/1, K/2, K/3
   - TER C: untuk pegawai yang tidak memiliki NPWP (tarif 20% lebih tinggi)
5. Kapan menggunakan TER vs tarif Pasal 17?
6. Contoh perhitungan dengan TER

**Internal links ke:**
- 05-tarif-pph-21.md
- 07-cara-hitung-pegawai-tetap.md
- 15-pmk-168-2023.md

---

### 07 — Cara Hitung PPh 21 Pegawai Tetap

**Slug:** `/pph-21/cara-hitung-pegawai-tetap/`

**Tujuan:** Panduan langkah-demi-langkah menghitung PPh 21 untuk pegawai tetap.

**Outline:**
1. Siapa yang termasuk pegawai tetap?
2. Data yang dibutuhkan:
   - Gaji pokok per bulan
   - Tunjangan tetap (jabatan, transport, makan, dll)
   - Tunjangan tidak tetap (lembur, dll) — perlakuan berbeda
   - Iuran pensiun / JHT / THT
   - Status PTKP (TK/K & jumlah tanggungan)
3. Langkah penghitungan:
   - Step 1: Hitung penghasilan bruto bulanan
   - Step 2: Hitung biaya jabatan (5%, max Rp24.000/tahun)
   - Step 3: Kurangi iuran pensiun → penghasilan neto
   - Step 4: Kalikan 12 (proyeksi tahunan) atau kumulatif
   - Step 5: Kurangi PTKP → PKP
   - Step 6: Tarif Pasal 17 × PKP → PPh terutang setahun
   - Step 7: Bagi 12 → PPh 21 bulan berjalan
   - ATAU gunakan TER langsung
4. Contoh kasus 1: Pegawai TK/0, gaji Rp10 juta/bulan
5. Contoh kasus 2: Pegawai K/1, gaji Rp25 juta/bulan + tunjangan
6. Contoh kasus 3: Pegawai dapat THR & bonus (penghitungan tidak rutin)
7. Penghitungan PPh 21 untuk bulan pertama kerja & terakhir kerja

**Internal links ke:**
- 06-ter-tarif-efektif.md
- 08-cara-hitung-pegawai-tidak-tetap.md

---

### 08 — Cara Hitung PPh 21 Pegawai Tidak Tetap / Tenaga Kerja Lepas

**Slug:** `/pph-21/cara-hitung-pegawai-tidak-tetap/`

**Tujuan:** Panduan penghitungan PPh 21 untuk pegawai kontrak, freelancer, dan tenaga kerja lepas.

**Outline:**
1. Siapa yang termasuk pegawai tidak tetap?
2. Perbedaan perlakuan pajak vs pegawai tetap
3. Penghitungan harian:
   - Penghasilan bruto harian
   - Tarif efektif harian (lampiran PMK 168/2023)
   - Akumulasi per bulan
4. Penghitungan mingguan
5. Penghitungan bulanan (pegawai kontrak > 1 bulan)
6. Contoh kasus: freelancer dapat proyek Rp15 juta sekaligus
7. Contrak berulang vs sekali — perlakuan berbeda

**Internal links ke:**
- 07-cara-hitung-pegawai-tetap.md
- 09-cara-hitung-pegawai-harian.md

---

### 09 — Cara Hitung PPh 21 Pegawai Harian

**Slug:** `/pph-21/cara-hitung-pegawai-harian/`

**Tujuan:** Panduan khusus untuk pegawai harian / harian lepas.

**Outline:**
1. Definisi pegawai harian
2. Penghitungan per hari kerja:
   - Uang harian ≤ Rp450.000 → tidak kena PPh 21
   - Uang harian > Rp450.000 → kena PPh 21
3. Akumulasi harian → bulanan
4. Tarif efektif harian dari PMK 168/2023
5. Contoh kasus: tukang bangun, buruh harian, cleaning service

**Internal links ke:**
- 08-cara-hitung-pegawai-tidak-tetap.md

---

### 10 — Natura & Kenikmatan (PMK No. 66 Tahun 2023)

**Slug:** `/pph-21/natura-kenikmatan/`

**Tujuan:** Pembaca memahami perlakuan PPh 21 atas imbalan non-tunai.

**Outline:**
1. Apa itu natura dan kenikmatan?
   - Natura: barang (mobil, rumah, gadget, dll)
   - Kenikmatan: fasilitas (asuransi kesehatan, klub kebugaran, dll)
2. Dasar hukum: PMK No. 66 Tahun 2023 (mencabut PMK 167/2018)
3. Aturan umum: natura & kenikmatan = objek PPh 21
4. **Pengecualian** — yang **bukan** objek PPh 21:
   - Makan/minum untuk seluruh pegawai
   - Natura di daerah tertentu (daerah terpencil, dll)
   - Natura yang harus disediakan untuk pelaksanaan pekerjaan
   - Natura yang dibiayai APBN/APBD/APBDes
   - Natura dengan jenis & batasan tertentu (akan diatur lebih lanjut)
5. Bagaimana pemberi kerja mencatat natura di bukpot?
6. Dampak ke perhitungan PPh 21 pegawai
7. Contoh kasus: perusahaan beri asuransi kesehatan Rp5 juta/tahun

**Internal links ke:**
- 03-penghasilan-kena-pajak.md
- 14-pmk-66-2023.md

---

### 11 — Bukti Potong (Bupot) PPh 21

**Slug:** `/pph-21/bukti-potong/`

**Tujuan:** Pembaca memahami jenis, format, dan tata cara bupot PPh 21.

**Outline:**
1. Apa itu bukti potong PPh 21?
2. Jenis bupot:
   - **1721-A1** — untuk pegawai tetap & penerima pensiun berkala
   - **1721-A2** — untuk pegawai tetap (jika ada perubahan data)
   - **1721-VI** — untuk pegawai tidak tetap / tenaga kerja lepas
   - **1721-II** — untuk bukan pegawai
3. Kapan bupot diterbitkan?
   - Akhir tahun (Desember) atau saat hubungan kerja berakhir
4. Isi bupot: NPWP pemotong, NPWP penerima, penghasilan bruto, PPh dipotong
5. Bupot digital di e-Bupot PPh 21
6. Cara mengisi SPT Tahunan dengan bupot

**Internal links ke:**
- 12-spt-tahunan-pph-21.md

---

### 12 — SPT Tahunan & PPh 21

**Slug:** `/pph-21/spt-tahunan/`

**Tujuan:** Pembaca memahami hubungan antara pemotongan PPh 21 dan pelaporan SPT Tahunan.

**Outline:**
1. Hubungan PPh 21 dengan SPT Tahunan Orang Pribadi
2. PPh 21 sebagai kredit pajak di SPT
3. Cara mengisi SPT Tahunan dengan bukpot 1721-A1
4. Lebih bayar vs kurang bayar — kapan terjadi?
5. Pembetulan SPT karena kesalahan bupot
6. Batas waktu pelaporan SPT: 31 Maret tahun berikutnya

**Internal links ke:**
- 11-bupot-pph-21.md

---

### 13 — PP No. 58 Tahun 2023 (Deep Dive)

**Slug:** `/pph-21/pp-58-2023/`

**Tujuan:** Analisis mendalam Peraturan Pemerintah No. 58 Tahun 2023.

**Outline:**
1. Metadata:
   - Judul lengkap
   - Tanggal penetapan: 27 Desember 2023
   - Tanggal pengundangan: 27 Desember 2023
   - Sumber: LN 2023 No. 163, TLN No. 6904
   - Status: Berlaku
2. Apa yang diatur?
   - Tarif pemotongan PPh 21 atas penghasilan sehubungan dengan pekerjaan/jasa/kegiatan WP orang pribadi
3. Apa yang dicabut/diubah?
   - Mencabut sebagian PP No. 80 Tahun 2010 (Pasal 2 ayat 3)
4. Isi pokok:
   - Tarif berdasarkan Pasal 17 ayat (1) huruf a UU PPh
   - Tarif efektif pemotongan PPh 21
5. Siapa yang terdampak?
   - WP orang pribadi penerima penghasilan dari pekerjaan/jasa/kegiatan
   - Termasuk pejabat negara, PNS, TNI, Polri, pensiunan
6. Link download PDF resmi

**Internal links ke:**
- 05-tarif-pph-21.md
- 06-ter-tarif-efektif.md

---

### 14 — PMK No. 66 Tahun 2023 (Deep Dive)

**Slug:** `/pph-21/pmk-66-2023/`

**Tujuan:** Analisis mendalam PMK No. 66 Tahun 2023 tentang Natura & Kenikmatan.

**Outline:**
1. Metadata:
   - Judul lengkap
   - Tanggal penetapan: 27 Juni 2023
   - Tanggal pengundangan: 27 Juni 2023
   - Tanggal berlaku: 27 Juni 2023
   - Sumber: BN 2023 No. 495
   - Status: Berlaku
2. Apa yang diatur?
   - Perlakuan PPh atas imbalan dalam bentuk natura dan/atau kenikmatan
3. Apa yang dicabut?
   - PMK No. 167/PMK.03/2018
4. Isi pokok:
   - Natura & kenikmatan = objek PPh (bisa dikurangkan dari bruto pemberi kerja)
   - 5 kategori pengecualian (bukan objek PPh)
5. Dampak ke pemberi kerja & karyawan
6. Link download PDF resmi

**Internal links ke:**
- 10-natura-kenikmatan.md

---

### 15 — PMK No. 168 Tahun 2023 (Deep Dive)

**Slug:** `/pph-21/pmk-168-2023/`

**Tujuan:** Analisis mendalam PMK No. 168 Tahun 2023 tentang Petunjuk Pelaksanaan Pemotongan PPh 21.

**Outline:**
1. Metadata:
   - Judul lengkap
   - Tanggal penetapan: 29 Desember 2023
   - Tanggal pengundangan: 29 Desember 2023
   - Tanggal berlaku: 01 Januari 2024
   - Sumber: BN 2023 No. 168
   - Status: Berlaku
2. Apa yang diatur?
   - Ketentuan umum, pemotongan & penerima penghasilan
   - Dasar pengenaan & pemotongan PPh 21 dan/atau PPh 26
   - Penghitungan PPh 21
   - Penghasilan & pemotongan untuk pejabat negara, PNS, TNI, Polri, pensiunan
   - Saat terutang & tata cara pemotongan
3. Apa yang dicabut?
   - PMK 102/PMK.010/2016
   - PMK 250/PMK.03/2008
   - PMK 252/PMK.03/2008
   - Sebagian PMK 262/PMK.03/2010
4. Isi pokok:
   - Tabel TER lengkap (TER A, TER B, TER C)
   - Aturan penghitungan untuk berbagai jenis pegawai
   - Contoh perhitungan
5. Link download PDF resmi

**Internal links ke:**
- 06-ter-tarif-efektif.md
- 07-cara-hitung-pegawai-tetap.md

---

### 16 — FAQ PPh 21

**Slug:** `/pph-21/faq/`

**Tujuan:** Jawaban singkat untuk pertanyaan yang sering diajukan.

**Outline:**
1. Apa bedanya PPh 21 dan PPh 21?
2. Saya dapat gaji di bawah PTKP, apakah tetap dipotong PPh 21?
3. Saya bekerja di 2 perusahaan sekaligus, bagaimana PPh 21-nya?
4. Kapan PPh 21 harus disetor?
5. Apa yang terjadi jika perusahaan tidak memotong PPh 21?
6. Bagaimana PPh 21 untuk ekspatriat / WNA?
7. Apa itu PPh 21 atas peserta kegiatan?
8. Bagaimana penghitungan PPh 21 untuk direktur yang juga pegawai tetap?
9. Apakah THR kena PPh 21?
10. Bagaimana jika ada kesalahan di bukpot 1721-A1?

**Internal links ke:** semua artikel terkait

---

## Catatan untuk Penulisan

- **Tone:** Langsung, jelas, tanpa jargon berlebihan. Sesuai gaya diskusipajak.com.
- **Format angka:** Rp10.000.000 (titik sebagai pemisah ribuan)
- **Sumber:** Cantumkan link ke peraturan resmi (BPK, DJP, Kemenkeu)
- **Internal linking:** Setiap artikel minimal 3 internal link ke artikel lain di cluster
- **Tag:** `pph-21`, `pph`, `perpajakan`, `pemotongan-pajak`
- **Jenis konten:** Cluster pillar + supporting articles (topikal)
