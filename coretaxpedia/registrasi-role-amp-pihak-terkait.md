---
title: "Role Amp Pihak Terkait"
category: "REGISTRASI"
description: "Kumpulan FAQ Role Amp Pihak Terkait dari Coretaxpedia"
source: "https://pajak.go.id/coretaxpedia"
lastScraped: "2026-06-06"
---

### Tambah/hapus pihak terkait

Terakhir diupdate pada: 28 Apr 2026

**Q: Bagaimana cara menambah atau menghapus pihak terkait?**

A: Penunjukan atau penghapusan pihak terkait dapat dilakukan dari akun Coretax DJP orang pribadi yang ditunjuk sebagai penanggung jawab dalam mode *impersonating*.

1. Setelah berada dalam mode *impersonating*, klik pada submenu **Informasi Umum** pada panel sebelah kiri layar.
2. Pada layar “Informasi Umum”, temukan dan klik tombol **Edit** yang berada pada bagian kanan sebelah atas di bawah baris menu utama.
3. Pada layar “Pembaruan Data Wajib Pajak,” langkah pertama adalah melakukan pembaruan data dengan cara klik tombol **Ambil Data Terbaru** pada bagian informasi umum.
4. Gulir (*scroll*) ke bawah, dan buka bagian pihak terkait. Tabel menunjukkan daftar pihak terkait.
**Penghapusan**

- Klik tombol **Hapus** di sebelah kiri nama pihak terkait yang akan dihapus, dan konfirmasi.
**Penambahan**

1. Klik tombol **Tambah** di atas tabel daftar pihak terkait. Lengkapi isian. Klik tombol ***Save***** **untuk menyimpan data pihak terkait.
2. Setelah selesai melakukan penghapusan atau penambahan penanggung jawab, gulir ke bawah dan beri tanda centang pada pernyataan, kemudian klik tombol **Kirim**.
3. Apabila berhasil, layar akan menampilkan notifikasi "Data wajib pajak berhasil diperbarui."

**Artikel terkait**

- [Kendala data pengurus pada Lampiran L2 SPT Tahunan Badan](/kendala-data-pengurus-lampiran-l2-spt-tahunan-badan)

---

### Cek role akses yang diberikan

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara mengetahui role akses apa yang diberikan kepada saya?**

A: Ikuti langkah berikut untuk mengetahui role akses yang ditetapkan bagi Anda:

1. Pada akun pribadi Anda, akses menu **Portal Saya > Profil Saya > Wajib Pajak yang Diwakili**.
2. Sistem akan menampilkan daftar wajib pajak yang Anda wakili, yaitu wajib pajak yang telah menunjuk Anda untuk menjalankan *role *tertentu.
3. Klik nomor penunjukan untuk wajib pajak yang ada pada tabel
4. Gulir ke bawah untuk melihat peran yang diberikan.
Kode role akses yang paling umum adalah sebagai berikut:

**SPT Masa Bea Meterai**- ROLE_CTAS_PORTAL_STAMP_DUT_Y_TAX_RETURN_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_STAMP_DUT_Y_TAX_RETURN_SIGNER → Penandatangan

**SPT Masa PPh Unifikasi**- ROLE_CTAS_PORTAL_TAX_WITHOLDING_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_TAX_WITHOLDING_SIGNER → Penandatangan

**SPT Masa PPh 21**- ROLE_CTAS_PORTAL_ARTICLE_21/26_WITHHOLDING_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_ARTICLE_21/26_WITHHOLDING_SIGNER → Penandatangan

**SPT Masa PPN**- ROLE_CTAS_PORTAL_VAT_TAX_RETURN_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_VAT_TAX_RETURN_SIGNER → Penandatangan

**SPT Tahunan**- ROLE_CTAS_PORTAL_ANNUAL_TAX_RETURN_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_ANNUAL_TAX_RETURN_SIGNER → Penandatangan

**Bukti Potong PPh Unifikasi**- ROLE_CTAS_PORTAL_EBUPOT_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_EBUPOT_SIGNER → Penandatangan

**Bukti Potong PPh Pasal 21/26**- ROLE_CTAS_PORTAL_EBUPOT_21/26_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_EBUPOT_21/26_SIGNER → Penandatangan

**Faktur Pajak**- ROLE_CTAS_PORTAL_TAX_INVOICE_DRAFTER → Pembuat draft- ROLE_CTAS_PORTAL_TAX_INVOICE_SIGNER → Penandatangan

**Pendaftaran & Perubahan Data WP**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_REG_BASIC → Registrasi bagi Kuasa Wajib Pajak- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_REG_DATA_UPDATE → Permohonan Perubahan Data

**Permohonan Pengukuhan PKP**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_REG_VAT_APPOINTMENT

**Penunjukan/Pencabutan Pemungut PPN PMSE**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_REG_DOMESTIC_ECOMMERCE_VAT_COLLECTOR

**Layanan Perpajakan**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_TPS_BASIC → Role dasar layanan perpajakan (layanan Administrasi, Layanan Informasi Perpajakan, Layanan Pengaduan Saran dan Apresiasi, Materi Edukasi, Pengetahuan Dasar Perpajakan)- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_TPS_ADDITIONAL → Penyampaian Permohonan Edukasi

**Pembayaran**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_PAY_BASIC → Pembayaran Bagi Wakil/Kuasa (Layanan Mandiri Kode Billing, Pembuatan Kode Billing atas Tagihan Pajak, Daftar Kode Billing Belum Dibayar)- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_BALANCE_TRANSFER_SIGNER → Permohonan Pemindahbukuan

**Pengembalian Pajak**- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_REFUND_SIGNER → Permohonan Pengembalian Pajak Pendahuluan- ROLE_CTAS_PORTAL_REPRESENTATIVE_EXTERNAL_INTEREST_COMPENSATION_SIGNER → Permohonan Imbalan bunga

---

### Beri/cabut role

Terakhir diupdate pada: 02 Oct 2025

**Q: Bagaimana cara memberikan atau mencabut *****role***** (*****drafter***** atau *****signer*****) kepada pihak terkait?**

A: Penetapan atau pencabutan *role* dapat dilakukan dari akun Coretax DJP orang pribadi yang ditunjuk sebagai penanggung jawab dalam mode *impersonating*.

1. Setelah berada dalam mode *impersonating*, masuk pada menu **Profil Saya** kemudian klik pada submenu **Wakil/Kuasa Saya** pada panel sebelah kiri layar.
2. Pada layar “Wakil/Kuasa Saya,” sistem menampilkan daftar wakil atau kuasa yang dapat ditetapkan dalam *role* tertentu atau dicabut (*revoke*) dari *role* yang pernah ditetapkan.
**Pencabutan (*****Revoke*****)**

1. Klik pada tombol ***Revoke** *di sebelah kiri wakil/kuasa yang akan dicabut dari *role* yang sudah ditetapkan. Gulir ke bawah, dan beri tanda centang pada pernyataan, kemudian klik tombol **Batalkan proses**.
**Tetapkan *****Role***

1. Klik pada tombol **Tetapkan Role** di sebelah kiri wakil/kuasa yang akan diberi role sesuai kebijakan internal wajib pajak.
2. Pilih peran yang akan diberikan kepada wakil/kuasa yang bersangkutan.
3. Klik tombol **Simpan**.
Perhatikan bahwa dalam hal wakil/kuasa sedang login dalam Coretax DJP ketika penetapan *role* dilakukan, maka wakil/kuasa tersebut harus keluar (*logout*) terlebih dahulu kemudian *login* kembali agar penetapan *role* dapat mulai berlaku.

**Jenis-jenis *****role***** akses**

1. *Drafter*: wakil/kuasa yang ditunjuk wajib pajak untuk melakukan pengisian dan pembuatan konsep dokumen perpajakan
2. *Signer*: wakil/kuasa yang ditunjuk wajib pajak untuk melakukan penandatanganan dokumen perpajakan
Dokumen perpajakan termasuk:

- Bukti potong
- Faktur pajak
- SPT masa PPh
- SPT masa PPN
- SPT tahunan
- SPT bea meterai
Satu pihak dapat ditunjuk untuk lebih dari satu *role*. Satu *role* dapat diberikan kepada lebih dari satu pihak.

---

### Ketentuan pendelegasian wewenang

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana ketentuan pendelegasian wewenang pada Coretax DJP?**

A: Pendelegasian wewenang pada Coretax DJP dapat dilakukan sesuai peran dan hak akses yang Anda terima dari wajib pajak yang Anda wakili.

**1. Tempat kegiatan usaha pusat**

**a. Penanggung jawab/PIC pusat**

Satu orang yang memiliki hak akses penuh atas akun Coretax DJP wajib pajak yang diwakili.

**Tugas dan kewenangan:**

- Dapat menambah, mengubah, atau menghapus peran bagi pengguna lain di Coretax DJP melalui menu "Wakil/Kuasa Saya".
- Bertanggung jawab atas seluruh aktivitas perpajakan TKU pusat dan cabang (bila ada).
**Syarat:**

- Memiliki NPWP atau NIK yang terdaftar.
**b. *****Drafter/signer ***

Satu atau lebih pegawai atau pengurus lain yang ditunjuk oleh PIC untuk membantu pelaksanaan hak dan kewajiban pajak pusat.

**Tugas dan kewenangan:**

- Sesuai peran yang diberikan sesuai dengan ketetapan PIC pusat.
**Syarat:**

- Memiliki NPWP atau NIK terdaftar.
- Memiliki akun pada Coretax DJP.
- Sudah didaftarkan oleh PIC pusat pada menu Pihak Terkait.
- Mendapatkan hak akses sesuai penugasan dari PIC.

**2. Tempat kegiatan usaha cabang**

**PIC cabang**

Satu atau lebih pegawai atau pengurus cabang yang ditunjuk untuk membantu pelaksanaan hak dan kewajiban pajak di entitas cabang.

**Tugas dan Kewenangan:**

- Melaksanakan kewajiban perpajakan cabang sesuai peran yang ditetapkan oleh PIC Pusat.
**Syarat:**

- Memiliki NPWP atau NIK terdaftar.
- Memiliki akun Coretax DJP.
- Didaftarkan oleh PIC pusat pada menu Tempat Kegiatan Usaha/Sub Unit.
- Mendapatkan peran dari PIC melalui menu Wakil/Kuasa Saya.
**Catatan:**

Bukti Pemotongan/Pemungutan Pajak (Bupot) atau Faktur Pajak (FP) yang dibuat oleh PIC Cabang tidak dapat dilihat oleh cabang lain.

**3. Konsultan pajak**

Konsultan pajak profesional yang berlisensi resmi dan terdaftar di Sistem Informasi Konsultan Pajak pada situs [sikop.kemenkeu.go.id](https://sikop.kemenkeu.go.id).

**Tugas dan Kewenangan:**

- Memberikan konsultasi pajak atau bertindak sebagai perwakilan wajib pajak sesuai dengan jenis, masa/tahun pajak, dan peran yang diberikan.
**Syarat:**

- Memiliki NPWP, lisensi resmi, dan sertifikasi konsultan pajak yang aktif.
- Terdaftar sebagai kuasa dengan status "Penunjukan Perwakilan" sebelum diberikan peran.
- Melakukan persetujuan penunjukannya melalui menu Permohonan Tertunda (*Pending Request*).

---

### Bagaimana menunjuk PIC

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara menunjuk penanggung jawab/PIC untuk wajib pajak badan atau instansi pemerintah?**

A: Penunjukan penanggung jawab atau PIC pusat dapat dilakukan melalui akun Coretax DJP dari wajib pajak badan atau instansi pemerintah yang memberikan penugasan.

1. Dari menu **Profil Saya** buka **Informasi Umum** dan pilih tombol **Edit**.
2. Pilih submenu **Pihak Terkait**.
3. Klik tombol **Tambah** untuk menambahkan pihak terkait jika PIC yang diinginkan belum terdaftar.
4. Pada daftar *dropdown*, pilih orang terkait (*related person*).
5. Masukkan NIK/NPWP pegawai yang ingin Anda tambahkan sebagai PIC. Sistem akan secara otomatis mengisi nama, kewarganegaraan, negara asal, email, dan nomor telepon.
6. Beri tanda centang pada kotak di kolom “Apakah PIC?”
7. Tentukan masa berlaku awal (wajib) dan masa akhir berlaku status PIC yang baru ditunjuk tersebut (opsional).
8. Klik tombol ***Save***.
9. Gulir ke bawah, beri centang pada bagian pernyataan.
10. Klik tombol **Kirim**.
Selesai. Orang yang mendapat penugasan dari wajib pajak telah ditunjuk sebagai penanggung jawab/PIC dan dapat mengakses Coretax DJP mewakili wajib pajak yang bersangkutan.

![](/files/view/55be0fb4-2d92-43fe-a7a1-7b9f44023429.png)

---

### Bagaimana mengganti PIC

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara mengganti penanggung jawab/PIC pusat?**

A: Wajib pajak dapat melakukan penggantian PIC dengan mengikuti langkah-langkah sebagai berikut:

1. *Login* ke akun Coretax DJP wajib pajak badan atau instansi pemerintah.
2. Buka menu **Informasi Umum **dan pilih **Edit**.
3. Pilih submenu **Pihak Terkait**.
4. Cari PIC saat ini dalam daftar. PIC akan ditandai dengan tanda centang di kolom "Apakah Penanggung jawab".
5. Klik **Edit** di samping PIC saat ini.
6. Hapus tanda centang pada kotak di kolom “Apakah PIC?”
7. Klik ***Save***.
8. Klik **Edit **di samping nama pihak terkait yang akan ditunjuk sebagai PIC yang baru.
9. Beri centang pada kotak di kolom “Apakah PIC?”
10. Tentukan masa berlaku awal (wajib) dan masa akhir berlaku status PIC yang baru ditunjuk tersebut (opsional).
11. Klik ***Save***.
12. Gulir ke bawah, dan beri centang pada bagian pernyataan.
13. Klik **Kirim**.
Apabila berhasil, layar akan menampilkan notifikasi "Data wajib pajak berhasil diperbarui."

![](/files/view/16d7d8cb-bcc5-44a4-b7d8-86382ffc3b1f.png)

---

### Karyawan cuti panjang

Terakhir diupdate pada: 17 Sep 2025

**Q: Pegawai yang ditunjuk untuk *****role *****tertentu pada Coretax DJP mengambil cuti yang cukup lama. Bagaimana solusinya?**

A: Ketika karyawan yang mendapat hak akses pada Coretax DJP sedang cuti panjang (misalnya cuti melahirkan, wajib pajak tetap perlu memastikan bahwa semua kewajiban perpajakan berjalan dengan baik. Berikut langkah-langkah yang bisa dilakukan:

**1. Tunjuk pengganti sementara**

Perusahaan bisa menunjuk pengganti sementara melalui Coretax DJP. Penanggung jawab/PIC dapat memberikan akses kepada pengganti melalui menu Wakil/Kuasa Saya.

Yang perlu diperhatikan:

- Pengganti harus memiliki NPWP atau NIK yang sudah terdaftar di sistem Coretax DJP.
- PIC harus mendaftarkan pengganti sebagai pihak terkait pada Coretax DJP sebelum memberikan akses.
- Peran yang diberikan dapat dibatasi sesuai kebutuhan perusahaan, misalnya hanya untuk membuat atau mengelola e-Faktur.
**2. Jangan gunakan akun karyawan yang sedang cuti**

Penggunaan akun pribadi karyawan yang sedang cuti tidak diperkenankan. Selain melanggar prinsip keamanan dan tata kelola yang baik, hal ini juga berisiko terjadi penyalahgunaan data penting perusahaan.

**3. Cabut akses setelah cuti berakhir**

Setelah karyawan yang cuti telah kembali bekerja, penanggung jawab dapat memutuskan untuk mencabut hak akses pengganti apabila pengganti hanya diberikan penugasan sementara.

**4. Gunakan jasa konsultan pajak**

Jika wajib pajak tidak memiliki pengganti internal yang sesuai, alternatif solusi adalah menggunakan jasa konsultan pajak profesional. Pastikan konsultan pajak telah terdaftar di Sistem Informasi Konsultan Pajak ([sikop.kemenkeu.go.id](https://sikop.kemenkeu.go.id)).

---

### Akun wajib pajak badan

Terakhir diupdate pada: 17 Sep 2025

**Q: Apa saja yang dapat dilakukan dari akun wajib pajak badan di Coretax DJP?**

A: Login Coretax DJP dengan menggunakan akun wajib pajak badan dapat melakukan banyak hal, termasuk:

- Mengubah PIC Pusat
- Menambah pihak terkait
- Melihat konsep bukti potong unifikasi atau faktur
Oleh karena itu, penting diperhatikan:

- Kata sandi (*password*) untuk login akun wajib pajak badan hanya diketahui oleh penanggung jawab/PIC pusat, atau orang berwenang sesuai kebijakan wajib pajak yang bersangkutan.
- Akses ke email dan nomor HP yang terdaftar pada Coretax DJP harus dijaga dan tidak diberitahukan kepada pihak yang tidak berkepentingan.
Sebagai tambahan keamanan maka wajib pajak dapat mengaktifkan fitur verifikasi dua langkah pada menu **Portal Saya**.

**Artikel terkait: **

- [Mengamankan akses dengan verifikasi dua langkah](/mengamankan-akses-dengan-verifikasi-dua-langkah)

---
