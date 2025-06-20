# Open Payment Portal Global Institute

Selamat datang di repositori Open Payment Portal! Ini adalah proyek simulasi antarmuka pembayaran front-end yang dibuat untuk tujuan demonstrasi dan pembelajaran. Aplikasi ini dibangun sepenuhnya menggunakan teknologi web standar (HTML, CSS, dan JavaScript) tanpa memerlukan backend.

## Fitur Utama

- **Formulir Pembayaran Dinamis:** Input nama pelanggan, email, pilihan produk, dan jumlah.
- **Kalkulasi Real-time:** Subtotal, diskon, dan total harga akan otomatis terhitung saat pengguna mengubah pilihan produk atau jumlah.
- **Sistem Kode Promo:** Menerapkan diskon dengan kode promo (mendukung diskon persentase dan nominal tetap).
- **Riwayat Transaksi:** Setiap pembayaran yang berhasil akan tercatat di riwayat transaksi, lengkap dengan detail nama, email, produk, dan total.
- **Penyimpanan Lokal:** Riwayat transaksi tidak akan hilang saat halaman di-refresh karena data disimpan menggunakan `localStorage` peramban.
- **Statistik Transaksi:** Menampilkan ringkasan data seperti jumlah total transaksi, total pendapatan, dan rata-rata nilai transaksi.
- **Tema Ganda (Dark/Light Mode):** Tampilan dapat diubah antara mode terang dan gelap, dan preferensi tema akan disimpan.
- **Desain Responsif:** Tampilan dioptimalkan untuk berbagai ukuran layar, dari desktop hingga mobile.
- **Modal Notifikasi:** Muncul notifikasi "Pembayaran Berhasil!" yang elegan setelah setiap transaksi sukses.

## Teknologi yang Digunakan

- **HTML5:** Untuk struktur dan kerangka konten halaman.
- **CSS3:** Untuk styling, layouting, dan tema. Menggunakan *CSS Custom Properties (Variables)* untuk manajemen tema yang mudah.
- **JavaScript (ES6+):** Untuk semua logika aplikasi, termasuk manipulasi DOM, kalkulasi, manajemen event, dan interaksi dengan `localStorage`.