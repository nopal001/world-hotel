# Hotel Website

## Deskripsi Proyek
Proyek ini adalah sebuah website untuk pemesanan kamar hotel yang memungkinkan pengguna untuk melihat ketersediaan kamar, melakukan pemesanan, dan melakukan pembayaran secara online atau tunai.

## Fitur Utama
### Halaman User
1. **Halaman Dashboard**
   - Menampilkan ringkasan data dan visualisasi utama terkait pemesanan hotel.
   - Fitur: Banner Gedung Hotel, Tombol "Booking Sekarang", Card Jenis Kamar, Tombol "Pesan Sekarang".

2. **Halaman Booking**
   - Memungkinkan pengguna untuk memilih kamar, mengisi form booking, dan lanjut ke checkout.

3. **Halaman Checkout**
   - Memeriksa kembali pesanan dan memilih metode pembayaran.

4. **Halaman Selesaikan Pembayaran**
   - Metode Transfer Bank: Untuk pembayaran dengan transfer bank.
   - Metode Pembayaran Tunai: Untuk pembayaran langsung dengan tunai.

5. **Halaman Pesanan Saya**
   - Menampilkan riwayat pesanan pengguna dengan opsi untuk menyelesaikan transaksi.

### Halaman Admin
1. **Halaman Dashboard Admin**
   - Menampilkan ringkasan data transaksi, pendapatan, dan pengunjung hotel.
   - Visualisasi: Pie Chart (bandingkan lunas transfer dan tunai), Line Chart Pendapatan Per Hari.

2. **Halaman Booking Admin**
   - Melihat data pemesanan kamar dengan filter berdasarkan status dan tanggal.

3. **Halaman Detail Pesanan**
   - Melihat detail pesanan, mengubah status pembayaran dan booking, melihat bukti pembayaran.

4. **Halaman Data Kamar**
   - Melihat, tambah, dan hapus data kamar yang tersedia.

## Database
Menggunakan MySQL untuk menyimpan data:
- Tabel `bookings`: Informasi pemesanan kamar.
- Tabel `rooms`: Detail kamar yang tersedia.
- Tabel `users`: Informasi pengguna.

## Cara Menjalankan Proyek
1. Clone repositori ini.
2. Import database ke MySQL.
3. Jalankan aplikasi menggunakan server XAMPP atau sejenisnya.

## Lisensi
Proyek ini dilisensikan di bawah [Apache-2.0 license]. Lihat file `LICENSE` untuk detail lebih lanjut.

## Pengembang
- Noval (Full Stack Web Developer)
  
## Kontak
Jika ada pertanyaan atau masukan, silakan hubungi kami di [naufalshofy38@gmail.com](mailto:naufalshofy38@gmail.com).
