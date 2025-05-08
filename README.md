# Gambaran Proyek
Dekoor Furniture adalah website e-commerce furnitur modern yang menampilkan produk furnitur premium dengan animasi halus dan desain responsif. Proyek ini menggunakan HTML, CSS, dan JavaScript dengan Tailwind CSS untuk styling.

Fitur Utama
Desain responsif untuk semua perangkat

Animasi scroll yang halus

Carousel produk interaktif

Menu navigasi yang mobile-friendly

Validasi form

Integrasi API untuk data produk

Memulai Proyek
Prasyarat
Node.js (versi 14 atau lebih baru direkomendasikan)

npm (sudah termasuk dengan Node.js)

Browser web modern

Instalasi
Clone repository

bash
git clone https://github.com/namauser/dekoor-furniture.git
cd dekoor-furniture
Instal dependensi

bash
npm install
(Catatan: Jika hanya menggunakan file HTML/CSS/JS langsung tanpa build tools, langkah ini bisa dilewati)

Menjalankan Proyek
Karena ini adalah website statis, ada beberapa pilihan:

Opsi 1: Buka langsung di browser
Buka file index.html langsung di browser favorit Anda.

Opsi 2: Gunakan Live Server (direkomendasikan untuk pengembangan)
Install ekstensi Live Server di VS Code

Klik kanan pada index.html dan pilih "Open with Live Server"

Opsi 3: Gunakan server lokal
Install http-server secara global:

bash
npm install -g http-server
Jalankan server:

bash
http-server
Buka http://localhost:8080 di browser

Pengembangan
Jika ingin memodifikasi proyek:

Edit HTML di index.html

Edit styles di style.css

Untuk perubahan besar, pertimbangkan untuk menginstall Tailwind CSS dengan benar:

bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
Struktur Proyek
dekoor-furniture/
├── index.html         # File HTML utama
├── style.css          # CSS custom
├── assets/            # Folder untuk gambar
│   └── sm.png         # Logo
Dependensi
Tailwind CSS - Framework CSS utility-first

Font Awesome - Library ikon

Google Fonts - Font family Montserrat

jQuery - Library JavaScript (digunakan untuk API calls)

API yang Digunakan

Proyek ini mengambil data produk dari API DummyJSON untuk bagian produk furnitur.

Pemecahan Masalah
Jika gambar tidak muncul: Periksa koneksi internet karena beberapa gambar dimuat dari URL eksternal

Jika animasi tidak bekerja: Pastikan JavaScript diaktifkan di browser

Jika tata letak rusak: Bersihkan cache browser dan muat ulang halaman

Lisensi
Proyek ini open source dan tersedia di bawah Lisensi MIT.
