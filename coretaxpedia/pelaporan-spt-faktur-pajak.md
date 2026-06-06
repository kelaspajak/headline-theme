---
title: "Spt Faktur Pajak"
category: "PELAPORAN SPT"
description: "Kumpulan FAQ Spt Faktur Pajak dari Coretaxpedia"
source: "https://pajak.go.id/coretaxpedia"
lastScraped: "2026-06-06"
---

### Faktur tanggal mundur

Terakhir diupdate pada: 17 Sep 2025

**Q: Apakah pembuatan faktur pajak dengan tanggal mundur bisa dilakukan?**

A: Faktur Pajak paling lambat diunggah (di-upload) paling lambat tanggal 20 bulan berikutnya setelah tanggal pembuatan e-Faktur.

---

### Uang muka legacy, pelunasan Coretax

Terakhir diupdate pada: 17 Sep 2025

**Q: Apa saja yang perlu diketahui terkait penerbitan faktur pajak pelunasan di Coretax DJP atas faktur pajak uang muka yang telah diterbitkan di sistem lama (*****legacy*****)?**

A: Wajib pajak dapat memperhatikan beberapa hal sebagai berikut:

1. Faktur pajak pelunasan di Coretax DJP tidak terhubung dengan faktur pajak uang muka yang dibuat di sistem lama.
2. Wajib pajak membuat faktur pajak keluaran di Coretax DJP tanpa perlu mencentang “Pelunasan.”
3. Nilai transaksi yang diinput adalah sejumlah pembayaran atas pelunasan.

---

### Faktur pajak uang muka dan pelunasan

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara pembuatan faktur pajak uang muka dan pelunasan yang keduanya dibuat di Coretax DJP?**

A: Pada isian e-Faktur Coretax DJP, Anda dapat membuat faktur pajak uang muka atau pelunasan dengan memberi tanda centang pada *checkbox* yang sesuai.

***Checkbox *****uang muka**

1. Digunakan untuk transaksi dengan pembayaran bertahap (termin) atau pembayaran sebelum penyerahan BKP/JKP.
2. Faktur uang muka pertama mencantumkan total nilai kontrak/order, yakni memuat seluruh detail transaksi barang/jasanya.
3. Jika terdapat lebih dari satu kali pembayaran uang muka/tahap/termin:Faktur kedua dst tetap centang *checkbox* "Uang Muka".
4. Harus selalu masukkan nomor faktur uang muka pertama pada kolom “Nomor Faktur.”
5. Data detil transaksi akan terisi otomatis (dari FP UM pertama sebagai referensi).
**Pengisian faktur uang muka (pertama dan selanjutnya):**

1. Rekam seluruh detil transaksi di kontrak layaknya faktur pajak biasa.
2. Centang "DPP Nilai Lain" setiap penambahan transaksi detail barang/jasa.
3. Masukkan hasil kalkukasi nilai 11/12 x harga jual/DPP/penggantian secara manual pada baris DPP Nilai Lain setiap transaksi. Kecuali untuk FP uang muka kedua dan seterusnya, tidak perlu menambah transaksi lagi karena sudah terisi otomatis dari detail di FP UM pertama.
4. Pada isian "Uang Muka" di bawah daftar transaksi: isikan nilai uang muka yang diterima.
***Checkbox***** Pelunasan:**

Khusus untuk pembayaran terakhir dari sebuah pembayaran bertahap, sistem akan otomatis menampilkan nilai sisa pembayaran baik itu DPP, DPP nilai lain, maupun PPN.

1. Dibuat saat pelunasan.
2. Centang *checkbox* "Pelunasan" dan input nomor faktur uang muka pertama.
3. Sistem akan otomatis mendeteksi hingga faktur uang muka yang terakhir.
4. Secara otomatis, sistem mencantumkan seluruh detail dan perhitungan transaksi.
5. PPN pelunasan dihitung dari tarif 12% x sisa nilai DPP nilai kontrak/total order setelah dikurangi total pembayaran uang muka.
**Pengisian Faktur Pelunasan:**

1. Tidak perlu menambah detil transaksi karena sudah terisi otomatis.
2. DPP dan PPN terisi otomatis sesuai perhitungan dari total DPP nilai Lain kontrak/total order dikurangi pembayaran uang muka nilai lain yang telah diterbitkan sebelumnya.
3. Hasil akhir pada cetakan faktur pajak pelunasan terhitung otomatis:DPP = Total DPP Nilai Lain (pada FP UM-1) dikurangi "Uang Muka Nilai Lain" ke-1, ke-2 dst.
4. PPN = DPP x 12% (atau 11% x harga jual).

---

### Pencantuman NITKU pada faktur pajak

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana ketentuan pengisian NPWP dan NITKU pada faktur pajak?**

A: Secara umum identitas penjual dan pembeli menggunakan NPWP pusat dan alamat NITKU pusat dengan memperhatikan syarat material yaitu mencantumkan keterangan sesuai dengan transaksi yang sebenarnya terjadi.

Apabila pembeli adalah entitas cabang yang berada di kawasan berikat (FP 07) dan PPN diberikan fasilitas tidak dipungut maka faktur pajak tetap menggunakan NPWP pusat, dengan mencantumkan NITKU cabang pembeli di kawasan berikat tersebut.

---

### Approval faktur pajak

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara melakukan *****approval *****faktur pajak pada Coretax DJP? Mengapa tombol upload tidak ada tetapi hanya tombol Simpan Konsep?**

A: *Upload* faktur pajak hanya dapat dilakukan oleh PIC pusat atau pihak yang diberikan wewenang (*role*) sebagai penandatangan faktur pajak.

Apabila Anda adalah wakil/kuasa wajib pajak yang ditugaskan untuk menandatangani faktur pajak, pastikan bahwa PIC pusat telah memberikan *role *sebagai *taxinvoice signer *kepada Anda.

---

### Daftar faktur dan SPT tidak sinkron

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana jika daftar faktur pajak keluaran dan masukan tidak sepenuhnya sinkron dengan isi SPT atau terjadi faktur pajak yang ganda?**

A: Untuk memastikan data faktur pajak sinkron dengan SPT masa PPN, Anda dapat menggunakan tombol **Posting **yang ada pada formulir induk SPT masa PPN.

Silakan klik tombol **Posting** sekali dan tunggu hingga seluruh data terisi sempurna.

---

### XML transaksi digunggung

Terakhir diupdate pada: 17 Sep 2025

**Q: Apakah isian format XML untuk transaksi digunggung harus dirinci satu per satu per *****invoice *****atau dapat langsung totalnya?**

A: Pencantuman detil transaksi digunggung dalam SPT masa PPN merupakan fitur yang disediakan di Coretax DJP untuk memfasilitasi pengusaha kena pajak dalam menyampaikan detil transaksi penyerahan kepada konsumen akhir.

Namun demikian, Anda tetap dapat menyampaikan data secara digunggung (total) dalam satu baris dengan menggunakan skema upload XML pada SPT masa PPN.

---

### Daftar faktur tidak muncul

Terakhir diupdate pada: 17 Sep 2025

**Q: Daftar faktur saya hilang, padahal sempat ada atau sudah berhasil import. Bagaimana solusinya?**

A: Klik tombol **↻** (*Refresh*) yang ada di bawah tombol **+ Buat Faktur**. Tunggu hingga proses *loading *berhasil dan data faktur akan kembali muncul pada tabel daftar faktur. Pastikan koneksi internet Anda lancar.

---

### Identitas pembeli faktur pajak digunggung

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara pengisian identitas pembeli pada XML faktur pajak pedagang eceran (digunggung) untuk XML Induk IA5 padahal pembeli konsumen akhir tidak diketahui identitasnya?**

A: Pencantuman detil transaksi yang digunggung dalam SPT masa PPN merupakan fitur yang disediakan dalam Coretax DJP bagi pengusaha kena pajak untuk dapat menyampaikan detil transaksi penyerahan kepada konsumen akhir.

Pengusaha kena pajak tetap dapat menyampaikan data secara digunggung atau total dalam satu baris dengan menggunakan skema *upload *XML pada SPT masa PPN atas pembelian yang dilakukan oleh pembeli yang memenuhi kriteria konsumen akhir tersebut.

**Pengisian kolom Identitas Pembeli mengikuti format sebagai berikut:**

- BuyerName: "-"
- BuyerIdOpt: "NIK"
- BuyerIdNumber: "0000000000000000"

---

### Nomor seri faktur pajak

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara meminta nomor seri faktur pajak bagi PKP?**

A: Coretax DJP memberikan nomor seri faktur pajak (NSFP) secara otomatis ketika faktur pajak telah ditandatangani dan berhasil *upload* (*approved*) sehingga tidak lagi diperlukan permintaan NSFP secara manual.

---

### Pencantuman identitas pembeli

Terakhir diupdate pada: 17 Sep 2025

**Q: Kapan harus memilih NPWP/NIK pada bagian informasi pembeli dan kapan harus mengisi jenis ID pembeli TIN/*****National ID *****pada XML, saat perekaman faktur pajak keluaran untuk pembeli orang pribadi?**

A: **Saat merekam identitas pembeli secara *****key in*****:**

- Isi NPWP 16 digit atau NIK (jika pembeli terdaftar NPWP) pada kolom NPWP.
- Nama, alamat, IDTKU dan email akan terisi otomatis sesuai *database* Coretax DJP.
**Saat merekam identitas pembeli secara import XML:**

- Pengisian identitas pembeli berupa NPWP/NIK ada di kolom J.
- Pilih Jenis ID Pembeli "TIN" pada kolom K
- Jika muncul notif "Error NPWP tidak ditemukan!" cek ulang pengisian. Pastikan 16 digit:WP badan atau WNA terdaftar NPWP isikan 0 + 15 digit NPWP lama
- NIK pembeli sudah padan dengan NPWP 15 digit
**Apabila penerima barang/jasa kena pajak belum memiliki NPWP, input *****key in*****:**

- Pada *toggle *identitas, pilih NIK.
- Kolom NPWP akan otomatis terisi 0000000000000000.
- Isikan NIK pembeli pada kolom nomor dokumen.
- Sistem akan memvalidasi NIK tersebut ke Dukcapil dengan notif "*Success National ID valid!*".
- Isi data nama dan alamat pembeli.
**Apabila penerima barang/jasa kena pajak belum memiliki NPWP, pengisian excel import XML:**

- Pengisian identitas pembeli yang tidak terdaftar NPWP berupa 0000000000000000 pada* *kolom J
- Pilih jenis ID pembeli "*National ID*" pada kolom K
Jika muncul notif "Error NIK tidak ditemukan!" Cek ulang pengisian.

**Dampak Penggunaan NIK/memilih Jenis ID Pembeli National ID:**

Jika orang pribadi pembeli ternyata PKP dan diterbitkan faktur pajak keluaran dengan identitas menggunakan National ID (bukan TIN):

- Pajak masukan tidak akan muncul di *dashboard*.
Jika orang pribadi pembeli bukan PKP dan diisikan menggunakan *National ID*:

- Tidak dapat memanfaatkan fitur retur dalam Coretax DJP.
**Solusi:**

- Pastikan identitas pembeli sesuai dengan status perpajakan yang sesungguhnya sebelum menerbitkan faktur pajak.
- Bila sudah terlanjur, dapat dilakukan pembatalan. *Approval *faktur pajak paling lambat tanggal 20 bulan berikutnya.
**Catatan:**

- Jika pembeli orang pribadi PKP  mengakui terdaftar NPWP namun tidak padan dengan NIK, silakan ke KPP terdekat untuk lakukan pemadanan NIK dan NPWP.

---

### Faktur pajak 07

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara pengisian nomor dokumen pada isian faktur pajak kode FP 07 atas penyerahan ke kawasan berikat, kawasan bebas atau kawasan ekonomi khusus?**

A: FP 07 digunakan untuk beberapa transaksi sebagai berikut.

**02 - Tempat Penimbunan Berikat**

Nomor dokumen pendukung: AJU

- Masukkan Nomor Pengajuan (AJU) dan tanggal AJU di kolom "tanggal faktur."
Dasar dokumen:

- AJU diperoleh dari BC 4.0 atau surat persetujuan pengeluaran barang (SPPB).
Proses pertukaran data:

- Data pembeli dan detail transaksi terisi otomatis melalui interoperabilitas antara Coretax DJP dan sistem Ditjen Bea dan Cukai (DJBC) menggunakan CEISA 4.0.
**18 - Kawasan Bebas PP nomor 41 Tahun 2021**

Nomor dokumen pendukung:

- Masukkan nomor pemberitahuan perolehan/pengeluaran BKP/JKP (PPBJ).
Proses pertukaran data:

- Data pembeli dan detail transaksi terisi otomatis melalui interoperabilitas antara Coretax DJP dan LNSW (INSW).
**17 - Kawasan Ekonomi Khusus PP nomor 40 Tahun 2021**

Nomor dokumen:

- Masukkan nomor pemberitahuan jasa KEK (PJKEK).
Proses pertukaran data:

- Informasi pembeli dan detail transaksi terisi otomatis melalui Coretax DJP yang terhubung dengan LNSW (INSW).
**Catatan:**

Saat input data dokumen:

- Pastikan memilih kode informasi tambahan yang sesuai.
- Masukkan nomor dokumen pendukung (sesuai kawasan) beserta tanggal dokumen pada kolom yang disediakan.
- Jika dokumen pendukung tidak ditemukan, kirim data ke DJP.

---

### Input tiga digit desimal

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara menginput transaksi dengan Kuantitas Satuan 3 digit di belakang koma, pada Coretax DJP?**

A: Kolom Kuantitas Satuan pada Coretax DJP hanya mendukung 2 angka di belakang koma.

**Solusi untuk transaksi dengan kuantitas 3 digit:**

- Gunakan pembulatan 2 digit
- Tambahkan Baris Baru untuk Selisih
- Jika pembulatan menyebabkan perbedaan dengan invoice komersial, tambahkan 1 baris barang baru untuk mengakomodasi selisih nilai pembulatan. Misalnya, tambahkan: Nama Barang: "Selisih Pembulatan Kuantitas", Nilai: +/- Selisih yang dihasilkan dari pembulatan kuantitas.

---

### Migrasi data faktur

Terakhir diupdate pada: 10 Sep 2025

**Q: Bagaimana proses migrasi faktur pajak dari e-Faktur desktop ke Coretax DJP, termasuk jadwal pemindahannya dan cara memastikan faktur dapat dikreditkan/diretur serta dilaporkan di Coretax DJP?**

A: Faktur pajak dari e-Faktur desktop dimigrasikan secara berkala ke Coretax DJP sehingga faktur pajak masukan atas transaksi dengan PKP tertentu yang menggunakan e-Faktur desktop akan tampil di Coretax DJP untuk dapat dikreditkan.

Setelah muncul di daftar pajak masukan/retur pajak masukan di Coretax DJP, pembeli kemudian dapat melakukan pengkreditan atau retur sesuai kebutuhan dan ketentuan.

---

### Unduh massal faktur pajak

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara mengunduh faktur pajak keluaran secara massal di Coretax DJP?**

A: Saat ini DJP menyediakan layanan *Generate Data Coretax* untuk memudahkan wajib pajak memperoleh data dari Coretax DJP termasuk data faktur pajak. Layanan ini dapat Anda akses pada sistem DJP Online pada menu **Lapor > Pra Pelaporan**.

---

### Kredit pajak masukan

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara memilih mengkreditkan atau tidak mengkreditkan faktur pajak masukan? Bagaimana bila terdapat pajak masukan yang belum dapat diyakini berasal dari transaksi yang dilakukan oleh wajib pajak yang bersangkutan?**

A: Faktur pajak masukan tersedia secara *real-time* di daftar pajak masukan setelah penjual melakukan *sign/approval*, meskipun SPT masa PPN penjual belum dilaporkan. Atas faktur pajak masukan tersebut dapat dilakukan:

- **Kreditkan faktur (B2):** Untuk faktur yang memenuhi ketentuan pengkreditan (masuk lampiran B2 SPT PPN).
- **Tidak kreditkan faktur (B3):** Untuk faktur yang tidak memenuhi ketentuan pengkreditan (masuk lampiran B3 SPT PPN).
- **Kembali ke status *****approved *****(netral):** Untuk mengembalikan faktur ke status netral (belum dikreditkan/tidak dikreditkan). Biarkan jadi *approved* dalam hal transaksi belum terkonfirmasi.
- ***Mark as invalid*****:** Untuk faktur yang diyakini bukan transaksi pembeli:Klik tanda pensil 🖉 (Edit) pada faktur dimaksud.
- Scroll ke bawah dan klik tombol **Tandai sebagai tidak valid**.
**Hal-hal yang perlu diketahui terkait retur atau pengkreditan faktur pajak masukan:**

- Hanya pajak masukan yang berstatus dikreditkan atau tidak dikreditkan yang dapat dilakukan retur.
- Pajak masukan dengan status *approved *belum dapat diretur karena belum diakui.
- Pajak masukan dikreditkan/tidak dikreditkan otomatis masuk ke SPT masa untuk dilaporkan.
- Faktur pajak yang dikreditkan/tidak dikreditkan setelah pelaporan SPT masa PPN, mengharuskan PKP untuk melakukan pembetulan SPT masa bersangkutan.
- Dalam hal terdapat lebih bayar setelah pembetulan, kompensasi akan otomatis masuk ke masa pajak berjalan yang belum terlapor.
- Manfaatkan fitur filter pada masa pajak dan tahun pajak, serta tombol **↻ **(*refresh*) saat mencari pajak masukan.
- Manfaatkan dasbor kompensasi pada menu **Surat Pemberitahuan (SPT)** **>** **Dasbor Kompensasi **untuk melakukan penelusuran asal kompensasi dan penggunaan saldo kompensasi serta saldo kompensasi yang tersedia.
- Dalam hal terdapat faktur pajak belum sinkron, minta bantuan KPP terdaftar untuk melakukan konfirmasi.
- Pantau status di kolom "Dilaporkan" untuk mengetahui pajak masukan yang dikreditkan/tidak dikreditkan tetapi belum terlapor dalam SPT.

---

### Retur barang

Terakhir diupdate pada: 17 Sep 2025

**Q: Bagaimana cara melakukan retur barang di Coretax DJP dalam hal terjadi pengembalian barang akibat ketidaksesuaian transaksi? Apa dampaknya bagi pembeli dan penjual?**

A: Sejak implementasi Coretax DJP, nota retur harus dibuat dan ditandatangani secara elektronik dan diunggah melalui Coretax DJP atau laman lain yang terintegrasi dengan sistem administrasi DJP.

Tidak hanya PKP, non-PKP baik orang pribadi maupun badan juga dapat mengakses e-Faktur untuk melihat faktur pajak masukan dan melakukan retur via Coretax DJP.

Retur hanya dapat dilakukan untuk faktur pajak yang statusnya sudah ditetapkan sebagai *credited* atau *uncredited* melalui dua cara berikut:

**1. Melalui submenu Pajak Masukan**

a. Tampilkan seluruh daftar FP PM: Filter Masa/Tahun Pajak > Klik tombol **↻ **(*refresh*)

b. Pastikan FP PM yang ingin diretur telah berstatus *credited/uncredited*

c. Klik tombol retur pada pajak masukan yang ingin diretur

d. Silakan input keterangan retur yang ingin dilakukan sesuai ketentuan:

- tanggal Retur adalah tanggal dilakukan pengembalian BKP
- klik tombol pensil 🖉 pada detail barang yang ingin diretur
- isikan jumlah barang diretur, potongan diretur (bila ada), lalu isikan PPN dan PPnBM yang diretur
- klik **Simpan**
e. Klik **Simpan > Upload Retur**

**2. Melalui submenu Retur Pajak Masukan**

a. Klik **Buat Retur**

b. Isikan nomor Faktur Pajak yang ingin diretur > Klik tombol "Cari"

c. Lakukan langkah seperti huruf 1.d di atas dan seterusnya.

**Dampak retur bagi pembeli dan penjual**

**1. Bagi pembeli**

- Retur yang dibuat akan tercatat pada submenu **Retur Pajak Masukan**, dan nilainya akan otomatis masuk ke dalam SPT masa PPN B.2/B.3 pada masa dilakukannya retur (tanggal retur).
**2. Bagi penjual**

- Setelah diajukan oleh pembeli, penjual dapat notifikasi melalui menu **Portal Saya > Notifikasi Saya** yang berisi informasi nomor faktur pajak, identitas pembeli yang melakukan retur, dan nomor nota retur.
- Penjual melakukan persetujuan atau penolakan atas retur tersebut melalui sub menu **Retur Pajak Keluaran** dan nilai retur akan otomatis masuk ke dalam SPT Masa PPN A.2 pada masa dilakukannya retur (tanggal retur).
Nota retur atas faktur pajak yang dibuat melalui e-Faktur desktop juga dilakukan melalui Coretax DJP.

---

### Status waiting for amendment/cancellation

Terakhir diupdate pada: 17 Sep 2025

**Q: Apa yang dimaksud dengan status "*****waiting for amendment/cancellation*****" dalam tabel pajak keluaran?**

A: Status "*waiting for cancellation/waiting for amendment*" menandakan faktur pajak sedang dalam proses penggantian atau pembatalan dan membutuhkan persetujuan dari pembeli.

Faktur pajak dapat dilakukan penggantian jika terdapat kesalahan dalam pengisian atau penulisan.

Faktur juga dapat dibatalkan jika terjadi pembatalan transaksi yang didukung dengan dokumen pendukung (misalnya, pembatalan kontrak) atau jika seharusnya tidak dibuatkan faktur pajak

Jika pembeli **belum **mengkreditkan faktur pajak masukan, maka penjual dapat melakukan penggantian/pembatalan sepihak sehingga tidak melalui proses *waiting for amendment/cancellation*.

Jika pembeli **sudah** mengkreditkan faktur pajak masukan maka penggantian atau pembatalan harus mendapat persetujuan dari pembeli. Faktur pajak yang berada pada proses ini akan ditandai dengan status *waiting for amendment/cancellation*.

**Konsekuensi terkait pelaporan SPT**

- Faktur pajak yang berstatus *waiting for cancellation/amendment* masih dianggap layaknya *approved *dan tetap terbawa ke SPT.
- Jika SPT **belum** dilaporkan (masih *draft*), faktur pajak yang telah disetujui pembeli untuk diganti/dibatalkan akan masuk otomatis ke dalam SPT, menggantikan faktur pajak sebelumnya.
- Dokumen faktur pajak yang diganti/dibatalkan akan berstatus "*amended/canceled*" dengan watermark *REPLACED/CANCELED*.
- Jika SPT sudah dilaporkan, maka penjual harus pembetulan SPT jika persetujuan pembeli setelah pelaporan.
Penjual dan pembeli harus berkoordinasi agar proses penggantian atau pembatalan berjalan dengan lancar.

---
