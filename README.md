# SayurKu - Platform E-commerce untuk Sayuran dan Buah-buahan Organik

SayurKu adalah platform e-commerce frontend murni yang dirancang untuk menjual sayuran dan buah-buahan organik secara langsung dari petani lokal ke konsumen. Website ini menampilkan desain modern dan responsif dengan fungsionalitas belanja yang lengkap serta penekanan pada produk-produk organik yang sehat. Semua interaksi dilakukan di sisi klien tanpa adanya backend server.

## Tampilan Website

Berikut adalah beberapa tampilan dari website SayurKu:

![Tampilan Beranda](img/display/home.png.png)
*Halaman beranda dengan hero section dan produk-produk organis*

![Tampilan Checkout](img/display/checkout-form.png.png)
*Proses checkout dengan formulir informasi pelanggan*

## Fitur-fitur
### 1. Halaman Beranda (index.html)
- **Navigasi Responsif**: Navigasi yang mudah digunakan dengan logo, menu, dan akses ke keranjang belanja
- **Bagian Hero**: Pengenalan menarik tentang platform dengan tombol ajakan bertindak
- **Kategori Populer**: Slider yang menampilkan berbagai kategori sayur dan buah
- **Tampilan Produk Organik**: Tatanan produk organik segar dengan gambar, nama, harga, dan penilaian
- **Produk Tren**: Bagian produk-produk yang sedang tren dengan banner menarik
- **Produk Terlaris**: Carousel produk-produk paling populer dengan badge diskon
- **Banner Promosi Buah**: Bagian khusus untuk promosi buah
- **Langganan Newsletter**: Formulir bagi pengguna untuk berlangganan pembaruan dan penawaran
- **Footer Lengkap**: Tautan, informasi kontak, dan integrasi media sosial

### 2. Halaman Tentang Kami (about.html)
- **Informasi Perusahaan**: Deskripsi terperinci tentang misi dan nilai-nilai perusahaan
- **Misi & Nilai**: Komunikasi yang jelas tentang prinsip inti perusahaan
- **Mengapa Memilih Kami**: Penjelasan tentang kualitas, kesegaran, dan dukungan untuk petani lokal
- **Desain Responsif**: Dioptimalkan untuk semua ukuran perangkat

### 3. Halaman Layanan (services.html)
- **Kategori Layanan**: Tampilan layanan yang ditawarkan termasuk:
  - Pengiriman cepat
  - Produk 100% organik
  - Jaminan kualitas premium
  - Layanan petani ke rumah
  - Dukungan pelanggan
  - Kemasan higienis
- **Kartu Layanan Visual**: Representasi menarik dari setiap layanan dengan gambar
- **Tata Letak Responsif**: Bekerja di semua jenis perangkat

### 4. Halaman Kategori (categories.html)
- **Tampilan Kategori**: Presentasi terorganisir dari kategori produk:
  - Sayuran Daun
  - Sayuran Umbi
  - Sayuran Hidroponik
  - Produk Musiman
- **Filter Kategori**: Opsi untuk memfilter produk berdasarkan jenis
- **Deskripsi Kategori Terperinci**: Informasi tentang setiap kategori
- **Tautan Aksi**: Tautan langsung untuk berbelanja di setiap kategori

### 5. Halaman Kontak (contact.html)
- **Informasi Kontak**: Informasi kontak lengkap termasuk alamat, email, telepon, dan jam kerja
- **Formulir Kontak**: Formulir ramah pengguna untuk mengirim pesan, pertanyaan, atau permintaan kemitraan
- **Ikon Visual**: Ikon menarik untuk setiap item kontak
- **Informasi Lokasi**: Alamat dan jam kerja ditampilkan dengan jelas

### 6. Halaman Daftar Produk (product-list.html)
- **Filter Produk**: Filter produk berdasarkan kategori (sayuran daun, sayuran umbi, dll.)
- **Sortir Produk**: Urutkan produk berdasarkan nama, harga (rendah ke tinggi, tinggi ke rendah)
- **Tatanan Produk**: Tatanan responsif produk dengan gambar, nama, harga, dan penilaian
- **Paginasi**: Halaman ganda untuk daftar produk
- **Badge Diskon**: Indikator visual untuk produk yang sedang dijual
- **Aksi Belanja**: Tombol "Tambah ke Keranjang" dan "Beli Sekarang" untuk setiap produk

### 7. Halaman Checkout (checkout.html)
- **Formulir Informasi Pesanan**: Formulir lengkap untuk detail pelanggan
- **Manajemen Alamat**: Input alamat komplit dengan provinsi, kota, kecamatan, dan kode pos
- **Metode Pembayaran**: Berbagai opsi pembayaran termasuk:
  - Bayar di Tempat (COD)
  - Transfer bank dengan berbagai opsi bank
- **Ringkasan Pesanan**: Tampilan jelas item yang dipesan, subtotal, biaya pengiriman, dan total
- **Validasi Formulir**: Validasi sisi klien untuk memastikan informasi lengkap
- **Jaminan Keamanan**: Indikator visual penanganan transaksi yang aman

### 8. Otentikasi Pengguna
- **Halaman Login (login.html)**: Login pengguna yang aman dengan:
  - Kolom email dan kata sandi
  - Opsi "Ingat Saya"
  - Opsi pemulihan kata sandi
  - Opsi login sosial (Facebook, Google)
  - Tautan pendaftaran untuk pengguna baru
- **Halaman Registrasi (register.html)**: Pembuatan akun pengguna

### 9. Fitur Tambahan
- **Keranjang Belanja Simulasi**: Fungsionalitas keranjang belanja sisi klien yang dapat diakses dari mana saja
- **Desain Responsif**: Penuh responsif di perangkat mobile, tablet, dan desktop
- **UI Modern**: Antarmuka bersih dengan tema hijau yang mencerminkan alam organik produk
- **Framework Bootstrap**: Pemanfaatan Bootstrap 5 untuk desain responsif dan komponen-komponen
- **Interaksi JavaScript**: Validasi formulir dan elemen interaktif sisi klien
- **Integrasi Media Sosial**: Tautan ke Facebook, Instagram, Twitter, dan YouTube

### 10. Fitur Teknis
- **HTML5 Modern**: Elemen HTML semantik untuk struktur dan SEO yang lebih baik
- **CSS3 Styling**: Styling kustom dengan integrasi Bootstrap
- **Fungsionalitas JavaScript**: Validasi dan elemen interaktif sisi klien
- **Optimisasi Gambar**: Gambar produk yang dipasang dan dioptimalkan dengan benar
- **Aksesibilitas**: Label formulir yang tepat dan HTML semantik untuk aksesibilitas

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Bootstrap Icons
- Desain Web Responsif

## Arsitektur Aplikasi

Proyek ini merupakan aplikasi frontend murni tanpa adanya backend server atau database. Semua fungsionalitas berjalan di browser pengguna:
- Semua data produk disimpan dalam HTML masing-masing halaman
- Interaksi keranjang belanja disimulasikan menggunakan JavaScript sisi klien
- Formulir checkout hanya memiliki validasi sisi klien tanpa pengiriman data sebenarnya
- Tidak ada otentikasi server-side, hanya tampilan antarmuka login/registrasi

## Status Pengembangan

Website ini sepenuhnya fungsional sebagai prototipe frontend. Semua interaksi dilakukan di sisi klien tanpa memerlukan server backend. Ini cocok sebagai dasar untuk pengembangan lebih lanjut dengan integrasi backend atau sebagai website statis untuk keperluan informasi dan demo.