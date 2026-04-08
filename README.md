Tugas 2: Pemrograman Web - Frontend Portofolio

Repositori ini berisi kode sumber untuk Tugas 2 mata kuliah Pemrograman Web, yaitu membuat halaman Frontend Web Portofolio Personal menggunakan HTML5, CSS3 murni (External CSS), dan bantuan framework Bootstrap 5.

Informasi Mahasiswa
Nama: Jauda Avaro Zufaru
NIM: F1D02410059
Kelas C
Teknik Informatika Universitas Mataram

Konsep Desain
Website portofolio ini mengusung konsep "Dark Header UI". Bagian atas (Navbar dan Hero Section) menggunakan tema gelap (Dark Mode) dengan elemen abstrak untuk memberikan kesan elegan dan fokus pada profil awal. Ketika digulir ke bawah, website bertransisi dengan garis tegas menjadi tema terang (Light Mode) menggunakan palet warna Ivory dan Putih bersih untuk memastikan teks konten (Pendidikan, Keahlian, Hobi, Pengalaman) sangat nyaman dibaca.

Implementasi Kriteria Tugas
Website ini telah memenuhi seluruh instruksi dan kriteria penilaian tugas:
Penggunaan External CSS: Seluruh gaya dan modifikasi visual dipisahkan secara rapi di dalam file style.css.
Implementasi Box Model: Penggunaan padding, margin, dan border diterapkan pada setiap kontainer, kartu (cards), dan tombol untuk menjaga ruang kosong yang proporsional (menggunakan class section-padding dan edu-card).
Penggunaan Flexbox dan Grid:
Flexbox: Digunakan secara ekstensif pada tata letak Navbar, Footer, dan penyejajaran ikon-ikon (alignment).
Grid System: Menggunakan sistem Grid bawaan Bootstrap (row, col-md-6, col-lg-7, dll.) untuk membagi layar menjadi susunan yang rapi dan responsif.
Penggunaan Class dan ID dengan tepat: Pengelompokan elemen menggunakan ID untuk navigasi (contoh: about, experience) dan Class untuk styling berulang (contoh: bg-main, edu-overlay, org-card). Minimal terdapat lebih dari 15 class CSS kustom yang dibuat sendiri.
Implementasi Hover Effect dan Transition:
Efek zoom dan transisi bayangan (shadow) pada foto profil dan kartu-kartu proyek atau pendidikan.
Transisi warna halus pada tombol Navbar dan tombol sosial media.
Efek interaktif Accordion menggunakan murni CSS (hover untuk memperluas kotak) pada seksi Jejak Organisasi.
Responsivitas: Sepenuhnya responsif menggunakan Media Query (terintegrasi dengan Bootstrap) sehingga tata letak akan menyesuaikan secara otomatis saat dibuka di perangkat Mobile maupun Desktop.
Bonus Framework: Menggunakan Bootstrap 5 untuk bantuan struktur tata letak awal dan interaktivitas bawaan (Navbar Collapse).