# Aplikasi-Penjualan-Merch-KPOP
Euphoria Verse adalah sistem informasi berbasis web yang dikembangkan untuk mempermudah proses jual beli merchandise KPOP resmi seperti album, lightstick, photocard, dan aksesoris lainnya secara online. Aplikasi ini dibangun menggunakan PHP dan MySQL, serta didukung oleh HTML, CSS, dan Bootstrap agar tampil modern, responsif, dan mudah digunakan oleh penggemar KPOP di seluruh Indonesia.

#  Fitur Unggulan
1. Menampilkan katalog produk berdasarkan kategori
2. Menambahkan produk ke keranjang dan mengatur jumlah pembelian
3. Form checkout dengan validasi data pembeli
4. Pembayaran digital menggunakan QRIS (dengan unggah bukti transfer)
5. Bukti transaksi digital dalam bentuk cetak atau unduh
6. Login admin dan otentikasi akses
7. Pengelolaan data produk, kategori, dan stok
8. Laporan transaksi untuk admin

#  Teknologi yang Digunakan
Backend: PHP (tanpa framework)
Frontend: HTML, CSS, JavaScript, Bootstrap
Database: MySQL
Arsitektur: Modular prosedural (tanpa MVC)

#  Struktur Folder (Singkat)
/admin         → Halaman backend untuk admin (CRUD, laporan)
/assets        → File CSS, gambar, dan font  
/config        → Konfigurasi koneksi database dan session  
/pages         → Halaman checkout, keranjang, detail produk, dll  
/uploads       → Folder penyimpanan bukti pembayaran  
index.php      → Halaman utama (daftar produk)

#  Cara Menjalankan
1. Clone repositori ini: git clone https://github.com/username/euphoria-verse.git
2. Import database euphoria_verse.sql ke MySQL melalui phpMyAdmin atau tools lainnya.
3. Sesuaikan konfigurasi koneksi database di /config/koneksi.php
4. Jalankan aplikasi melalui localhost menggunakan XAMPP/Laragon: http://localhost/euphoria-verse
