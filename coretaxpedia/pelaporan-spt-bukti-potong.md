---
title: "Spt Bukti Potong"
category: "PELAPORAN SPT"
description: "Kumpulan FAQ Spt Bukti Potong dari Coretaxpedia"
source: "https://pajak.go.id/coretaxpedia"
lastScraped: "2026-06-06"
---

### Bagaimana bukti potong dikirimkan

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana penerima penghasilan menerima bukti potong PPh dalam Coretax DJP?**

A: Dalam Coretax DJP, bukti potong PPh akan langsung dikirim ke akun wajib pajak pihak penerima penghasilan, sehingga tidak perlu lagi meminta atau menyimpannya secara manual. Penerima penghasilan akan menerima notifikasi yang berisi detail bukti potong yang diterbitkan pemberi penghasilan.

---

### Bagaimana membuat bukti potong

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara membuat bukti potong PPh di Coretax DJP?**

A: Berikut tata cara pembuatan bukti potong di Coretax DJP:

1. Setelah *login*, masuk ke menu **eBupot**
2. Pilih jenis bukti potong yang sesuai.
3. Klik tombol **Create eBupot** untuk mengisi bukti potong pajak penghasilan.
4. Isi formulir berdasarkan data yang valid termasuk informasi tentang pihak pemberi penghasilan, penerima penghasilan, jenis penghasilan, dan jumlah PPh yang dipotong.
5. Klik tombol **Submit**, dan bukti potong akan otomatis tersimpan dalam sistem.
![](/files/view/779243de-2ccb-4ac2-93fa-3c87c665168a.png)

---

### Dampak penggunaan NPWP sementara

Terakhir diupdate pada: 17 Sep 2025

**Q: Apa dampak penggunaan NPWP sementara saat membuat bukti potong?**

A: Penggunaan NPWP sementara memiliki dampak sebagai berikut:

- Bukti pemotongan PPh tidak akan terkirim ke akun wajib pajak penerima penghasilan.
- Bukti pemotongan tidak akan otomatis terisi dalam SPT Tahunan PPh penerima penghasilan.
Oleh karena itu DJP mengimbau kepada pemberi penghasilan untuk memastikan bahwa semua penerima penghasilan telah terdaftar dalam sistem Coretax DJP guna memperoleh manfaat optimal dari sistem ini.

---

### Skema pembuatan bupot

Terakhir diupdate pada: 17 Sep 2025

**Q: Apa saja skema pembuatan bukti potong PPh dalam Coretax DJP?**

A: Sama seperti pembuatan faktur pajak, pembuatan bukti potong PPh dalam Coretax DJP dapat dilakukan melalui tiga skema berikut:

1. Input manual untuk setiap bukti potong (*key in*) di Coretax DJP.
2. Pembuatan massal melalui unggah *file* *.XML pada Coretax DJP.
3. Pembuatan massal melalui penyedia jasa aplikasi perpajakan (PJAP) yang terhubung dengan sistem Coretax DJP.

---

### Informasi penerima penghasilan pada bupot

Terakhir diupdate pada: 17 Sep 2025

**Q: Untuk pembuatan bukti potong PPh, apa saja informasi penerima penghasilan yang wajib diisi oleh pihak pemotong?**

A: Untuk pembuatan bukti potong PPh di Coretax DJP, pihak pemotong wajib mengisi NPWP penerima yang sesuai dengan NIK terdaftar di Coretax DJP. Jika NIK yang diinput belum terdaftar, sistem akan meminta konfirmasi untuk penggunaan NPWP sementara (*temporary* TIN) yang disediakan oleh sistem. Untuk skema unggahan file *.XML, sistem secara otomatis menyesuaikan data NIK yang belum terdaftar dengan NPWP sementara tanpa memerlukan konfirmasi.

Contoh: jika NIK Bapak A (1111122222333338) belum terdaftar, sistem akan menampilkan konfirmasi penggunaan NPWP sementara. Jika disetujui, nama penerima pada bukti potong akan ditampilkan sebagai "PENERIMAPENGHASILAN#NIK16digit". Pihak pemotong perlu mengisi formulir bukti potong berdasarkan data yang valid.

---

### Penerima penghasilan belum terdaftar

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara menangani situasi di mana NIK penerima penghasilan belum terdaftar di Coretax DJP saat membuat bukti pemotongan?**

A: Saat menginput NIK penerima penghasilan, jika belum terdaftar, sistem akan menampilkan konfirmasi untuk penggunaan NPWP sementara (*temporary* TIN) yang disediakan oleh sistem.

![](/files/view/37a3ac1e-2e9f-45d8-8728-8170a9f72861.png)Jika Anda setuju maka nama penerima pada e-Bupot akan ditampilkan sebagai "PENERIMAPENGHASILAN#NIK16digit", dengan NIK yang belum terdaftar.

Perhatikan bahwa jika NPWP sementara digunakan, maka bukti pemotongan PPh tidak akan terkirim ke akun Coretax DJP dan tidak akan otomatis terisi dalam SPT tahunan penerima penghasilan. DJP menyarankan untuk memastikan penerima penghasilan telah terdaftar sebagai wajib pajak.

---

### Upload XML bupot

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara membuat bukti pemotongan PPh dengan skema *****upload***** XML?**

A: Langkah-langkah pembuatan bupot skema XML:

1. Siapkan file XML yang berisi detail bukti pemotongan PPh sesuai dengan format Coretax DJP.
2. *Login* ke akun Coretax DJP menggunakan akun pihak terkait yang ditunjuk sebagai *drafter* atau *signer*.
3. Pada menu **eBupot** pilih jenis bukti potong yang sesuai.
4. Unggah *file* XML dengan cara klik pada tombol **Impor data**.
Sistem akan memproses *file* untuk pembuatan bukti pemotongan.

![](/files/view/af1b36b3-775d-4328-907f-2c5da21c6355.png)

---

### Cara penerbitan bupot TKU

Terakhir diupdate pada: 17 Sep 2025

**Q: Apakah cabang wajib pajak dapat menerbitkan bukti potong? Bila ya, bagaimana langkah-langkahnya?**

A: TKU dapat menerbitkan bukti potong dengan syarat PIC pusat telah menunjuk PIC cabang dan telah memberikan hak akses sebagai *drafter* dan *signer*. PIC cabang dengan *role signer* juga harus dipastikan telah memiliki kode otorisasi/sertifikat digital untuk melakukan tanda tangan elektronik.

Langkah-langkah pembuatan bukti potong oleh PIC TKU:

1. PIC cabang *login *menggunakan akun pribadi kemudian melakukan *impersonate* ke akun badan.
2. Buat bukti potong melalui menu **e-Bupot**.
3. Pada bagian dokumen referensi, pilih Nomor Identitas TKU (NITKU) sesuai dengan cabang penerbit bukti potong.
4. Klik tombol **Submit**.
5. Pilih bukti potong yang akan diterbitkan dan klik tombol **Terbitkan**.
*Drafter* dapat membuat konsep bukti potong, tetapi untuk penandatanganan, pembetulan atau pembatalan bukti potong harus dilakukan oleh *signer*.

---

### Akses bupot untuk WP dengan banyak TKU

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana implementasi hak akses bupot bagi wajib pajak yang memiliki lebih dari satu tempat kegiatan usaha (TKU)?**

A: Kewenangan akses bupot bagi wajib pajak yang memiliki lebih dari satu TKU antara lain sebagai berikut:

- **Penanggung jawab pusat** dapat membuat, menandatangani dan melihat bupot PPh untuk semua TKU (pusat dan cabang).
- **Pihak terkait **yang diberikan *role* sebagai *drafter* atau *signer* hanya dapat membuat dan/atau menandatangani bupot PPh dari TKU pusat.
- **Pegawai** yang ditunjuk sebagai PIC cabang hanya dapat membuat dan menandatangani bupot PPh untuk TKU yang bersangkutan saja. Apabila wajib pajak menghendaki pegawai selain PIC utama untuk dapat membuat dan menandatangani bupot PPh dari TKU selain TKU pusat, maka pegawai bersangkutan harus didaftarkan sebagai PIC TKU lainnya tersebut.
Bupot TKU pusat Bupot TKU cabang Penanggung jawab/PIC pusat Ya Ya Pihak terkait (akses sesuai *role drafter/signer*) Ya Tidak PIC cabang (akses sesuai *role drafter/signer*) Tidak Ya* ***** Sesuai TKU yang ditentukan

---

### NITKU cabang tidak muncul

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana jika NITKU cabang tidak muncul saat membuat bukti potong padahal di profil wajib pajak sudah terdaftar TKU-nya?**

A: Silahkan cek kembali penetapan PIC di masing-masing NITKU badan/instansi pemerintah. Apabila belum ditetapkan, tambahkan pegawai yang ditugaskan sebagai *drafter/signer* sebagai PIC untuk TKU yang bersangkutan dengan cara:

1. Klik menu **Portal Saya >** **Profil Saya**.
2. Klik submenu **Informasi Umum**.
3. Klik tombol **Edit**.
4. Pilih dan edit tempat kegiatan usaha yang akan ditambahkan PIC dan input PIC.
5. Melalui menu **Wakil/Kuasa Saya **silahkan tetapkan peran untuk masing-masing pegawai pusat/cabang lalu simpan.
![](/files/view/d67c6f5d-c3dc-4322-bae3-6639d5fe8301.png)

---

### Bupot istri NPWP gabung suami

Terakhir diupdate pada: 05 Nov 2025

**Q: Bagaimana penerbitan bukti potong untuk istri dengan NPWP gabung suami?**

A: Hal-hal yang perlu diketahui terkait penerbitan bukti potong istri dengan NPWP gabung suami antara lain:

- Bukti potong dibuat dengan menggunakan data NIK istri.
- Pastikan NIK istri valid berdasarkan data dukcapil.
- Suami harus melakukan pembaruan data unit keluarga pada profil wajib pajak dan mencantumkan NIK istri.
- Apabila NPWP istri telah digabung ke suami, maka data bukti potong istri akan langsung terisi di SPT tahunan, dan hanya NPWP suami yang melaporkan SPT.
Apabila NPWP istri telah digabung dengan NPWP suami, maka data bukti potong istri akan terprepopulasi pada SPT Tahunan suami, dan suami yang melaporkan SPT Tahunan.

---

### Bupot pegawai yang pindah tempat kerja

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana pembuatan bukti potong BPA1/BPA2 bagi pegawai tetap yang pindah tempat kerja?**

A: Hal-hal yang perlu diketahui terkait penerbitan bukti potong BPA1/BPA2 bagi pegawai tetap yang pindah kantor antara lain:

1. Pada Coretax DJP berlaku pemusatan NPWP. Untuk pemindahan pegawai antar cabang (NITKU) yang masih dalam satu NPWP tidak perlu dibuatkan BPA1/BPA2. Cukup penyesuaian pemotongan bulanan dengan NITKU cabang yang membayarkan penghasilan pegawai.
2. Jika pegawai pindah ke pemberi kerja dengan NPWP berbeda, maka kantor lama membuat BPA1/BPA2.
3. Penggabungan BPA1/BPA2 sebelumnya oleh kantor baru dilakukan dengan memasukkan nomor bupot sebelumnya. Sistem akan memvalidasi dan melakukan penghitungan porsi PPh yang dipotong oleh kantor baru tersebut.
4. BPA1/BPA2 yang diterbitkan oleh kedua kantor tersebut dilaporkan pada SPT tahunan PPh pegawai.

---

### Pembetulan bupot

Terakhir diupdate pada: 17 Sep 2025

**Q: Apabila pihak yang dipotong telah mengkreditkan bukti potong dalam SPT tahunan, apakah pemotong pajak masih dapat melakukan pembetulan atau pembatalan atas bukti potong tersebut?**

A: Ya, pihak yang dipotong akan mendapatkan notifikasi jika telah terjadi pemotongan pajak ataupun pembetulan/pembatalan bukti potong. Bukti pemotongan terkait dapat diunduh melalui menu **Portal Saya > Dokumen Saya **pada akun penerima penghasilan.

Apabila pihak penerima penghasilan telah melaporkan SPT maka yang bersangkutan harus melakukan pembetulan SPT sesuai bukti potong hasil pembetulan tersebut.

---

### Pencantuman NITKU pada bukti potong

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana ketentuan pengisian NITKU pada bukti potong PPh Pasal 21?**

A: Pemotong pajak bisa pusat atau cabang, sesuai dengan lokasi pembayaran penghasilan/gaji sehingga pengisian NPWP dan NITKU mengikuti kondisi yang sebenarnya. NITKU cabang wajib dicantumkan dalam bukti potong yang dibuat oleh cabang yang membayar gaji/penghasilan. Ketentuan ini juga berlaku untuk pemotongan PPh unifikasi.

---

### Kerahasiaan bupot PPh 21

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara memastikan kerahasiaan pembuatan bukti pemotongan PPh 21 antar pegawai bila hanya memiliki satu tempat kegiatan usaha?**

A: Untuk menjaga kerahasiaan antar pegawai yang bertugas membuat bukti pemotongan PPh Pasal 21, Anda dapat menambahkan tempat kegiatan usaha sesuai jumlah pemisahan akses yang dibutuhkan, meskipun alamatnya sama.

Seorang PIC TKU (mis. 000001) tidak dapat melihat BP PPh Pasal 21 yang dibuat oleh PIC TKU lain (misalnya 000002) meskipun memiliki role akses pajak yang sama (EBUPOT_21/26).

**Catatan:**

- Untuk memastikan akses terpisah, PIC TKU tersebut hanya ditambahkan dalam TKU tersebut ***tidak sebagai pihak terkait di entitas pusat***.
- Penambahan PIC TKU dilakukan melalui menu "**Tempat Kegiatan Usaha/Sub Unit**", bukan melalui menu "**Edit > Pihak Terkait**".
- Setiap TKU dapat memiliki lebih dari 1 PIC.
- *Signer/drafter *SPT (*ARTICLE_21/26*) hanya diberikan kepada pihak yang diberi wewenang dalam pengelolaan pegawai secara keseluruhan, karena mereka dapat melihat semua bukti potong PPh 21 yang dibuat di seluruh TKU.

---

### Bupot PPh 21 Desember

Terakhir diupdate pada: 17 Sep 2025

**Q: Apakah di masa pajak akhir (bulan pegawai tetap berhenti bekerja/bulan Desember) perlu dibuat bukti potong PPh pasal 21 bulanan (BPMP) dan tahunan A1 atau cukup A1 saja?**

A: Untuk pemotongan PPh Pasal 21 pegawai tetap yang berhenti bekerja di tengah tahun atau bekerja hingga Desember, di masa pajak akhir tersebut cukup dibuatkan bukti pemotongan tahunan A1 (BP A1) dan tidak perlu bukti potong bulanan pegawai tetap (BPMP).

Hal-hal yang perlu diketahui terkait perekaman BP A1 di masa pajak akhir antara lain:

- Tidak ada isian penghasilan masa pajak akhir.
- Penghasilan masa pajak akhir terhitung otomatis ke Lampiran IB di SPT Masa PPh 21.
- Penghasilan Bruto dalam Lampiran IB = Total Penghasilan Bruto Setahun/Bagian Tahun pada BPA1 - Penghasilan Bruto pada BPMP yang telah diterbitkan.
- Bila buat BPMP dan A1 dalam masa pajak yang sama akan muncul pesan *error *"Sudah ada pemotongan BPMP pada masa pajak tersebut. Mohon batalkan BPMP terlebih dahulu."

---

### Bupot monthly payroll

Terakhir diupdate pada: 17 Sep 2025

**Q: Saya telah berhasil menerbitkan bukti potong pegawai tetap bulanan (BPMP) melalui e-Bupot 21, namun bukti potong tersebut tidak dapat diunduh, dan pegawai hanya menerima notifikasi tanpa dokumen. Apakah memang demikian?**

A: Ya, bukti pemotongan bulanan pegawai tetap (BPMP) tidak memerlukan cetakan dokumen. Proses bisnis BPMP di Coretax DJP berbeda dengan sistem e-Bupot 21 sistem lama (DJP Online). Penerima penghasilan yang dipotong akan menerima notifikasi di akun wajib pajaknya setelah pemotongan dilakukan oleh pemberi kerja. Tidak ada fitur unduhan PDF karena BPMP tidak dirancang untuk dicetak seperti bukti potong lainnya.

---

### Unduh Bukti Potong

Terakhir diupdate pada: 12 May 2026

**Q: Bagaimana cara melihat dan mengunduh bukti pemotongan PPh (bupot) yang diterbitkan oleh lawan transaksi di Coretax DJP? Apakah wajib pajak menerima notifikasi jika lawan transaksi melakukan perubahan atau pembatalan bupot?**

A: Wajib pajak dapat mengunduh bukti potong yang diterima dari lawan transaksi kapan saja melalui menu **Portal Saya > eBupot > Bukti Potong Saya**.

Notifikasi tentang pembuatan, perubahan, dan pembatalan bukti potong juga tersedia secara *real-time* pada menu **Portal Saya > Notifikasi Saya** atau dengan mengklik ikon lonceng.

Apabila dokumen atau notifikasi tidak muncul, lakukan refresh dengan cara klik tombol **↻** (*Refresh*) pada bagian atas tabel.

Langkah-langkah untuk mengunduh bukti potong adalah sebagai berikut:

1. Akses menu **Portal Saya > eBupot > Bukti Potong Saya**.
2. Filter bukti potong berdasarkan Jenis Bukti Potong, Masa Pajak, dan Tahun Pajak kemudian klik tombol **Cari**.
3. Klik ikon mata untuk melihat bukti potong dan logo pdf untuk mengunduh dokumen bukti potong.

---

### Input fasilitas pada ebupot

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara input fasilitas pada ebupot seperti pemotongan PPh 23 ke UMKM yang memiliki SUKET PP 55 atau ke lawan transaksi yang memiliki SKB?**

A: Anda tidak perlu melakukan input nomor dokumen SUKET PP 55 ataupun nomor SKB karena apabila wajib pajak memiliki fasilitas perpajakan yang aktif maka otomatis akan tersedia di dalam sistem ebupot.

Wajib pajak yang mendapatkan fasilitas pajak dapat melakukan pengecekan mandiri untuk fasilitas aktif yang dimilikinya melalui menu **Portal Saya > Profil Saya **pada tab **Fasilitas Aktif**.

---

### A1 untuk bupot dengan NPWP sementara

Terakhir diupdate pada: 17 Sep 2025

**Q: Saya tidak bisa membuat bukti pemotongan PPh pasal 21 1721-A1 untuk pegawai tetap yang berhenti di tengah tahun dengan NPWP sementara, padahal buat bukti potong bulanan pegawai tetap bisa dengan NPWP Sementara. Bagaimana solusinya?**

A: Pada Coretax DJP Bukti Potong A1 hanya bisa dibuat jika histori penghasilan menggunakan NIK yang sudah terdaftar di database Coretax DJP, bukan menggunakan NPWP sementara.

Apabila sebelumnya menggunakan NPWP sementara maka bukti pemotongan bulanan wajib dibatalkan terlebih dahulu lalu dibuat kembali dengan NIK valid. Setelah itu baru bisa membuat bukti pemotongan A1.

Untuk mendaftarkan NIK sebagai NPWP maka perlu melakukan proses pendaftaran sebagai wajib pajak baru mengikuti langkah-langkah pada artikel [Pendaftaran WP orang pribadi](/pendaftaran-wp-orang-pribadi).

---

### Bupot PPh salah masuk ke akun suami

Terakhir diupdate pada: 04 Feb 2026

**Q: Saya sudah mengaktifkan NIK sebagai NPWP dan memilih kewajiban pajak terpisah dari suami. Mengapa bukti potong PPh saya tetap muncul di akun Coretax DJP saya dan juga di akun Coretax DJP suami? Bagaimana pelaporan pajak atas bukti potong tersebut?**

A: Bagi istri yang menjalankan kewajiban pajak terpisah, maka penghasilan suami dan penghasilan istri dilaporkan secara terpisah melalui akun Coretax DJP masing-masing.

Bukti potong penghasilan istri masuk ke dalam akun suami dikarenakan status istri di Daftar Unit Keluarga masih tercatat sebagai “Tanggungan” sehingga sistem secara otomatis memasukkan bukti potong penghasilan istri ke SPT suami.

Agar bukti potong tidak lagi masuk secara otomatis ke akun suami, maka perlu dilakukan perubahan status istri di akun Coretax DJP mengikuti panduan [pada artikel ini](/ubah-status-ph-mt).

Dalam kasus seperti ini, bukti potong milik istri yang terlanjur masuk ke SPT suami dapat dihapus dan tidak perlu dilaporkan di SPT suami. Bukti potong penghasilan milik istri tersebut dilaporkan pada SPT istri melalui akun Coretax DJP istri.

**Artikel terkait:**

- [Lapor SPT tahunan orang pribadi](/lapor-spt-tahunan-orang-pribadi)
- [Lapor SPT bagi istri yang memilih terpisah](/lapor-spt-bagi-istri-yang-memilih-terpisah)

---
