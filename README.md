# Tugas 2: Pemrograman Web - Frontend Portofolio

Repositori ini berisi kode sumber untuk Tugas 2 mata kuliah Pemrograman Web, yaitu membuat halaman Frontend Web Portofolio Personal menggunakan HTML5, CSS3 murni (External CSS), dan bantuan framework Bootstrap 5.

## Informasi Mahasiswa
Nama: Jauda Avaro Zufaru  
NIM: F1D02410059  
Kelas C  
Teknik Informatika Universitas Mataram

## Konsep Desain
Website portofolio ini mengusung konsep "*Dark Header* UI". Bagian atas (*Navbar* dan *Hero Section*) menggunakan tema gelap (*Dark Mode*) dengan elemen abstrak untuk memberikan kesan elegan dan fokus pada profil awal. Ketika digulir ke bawah, website bertransisi dengan garis tegas menjadi tema terang (*Light Mode*) menggunakan palet warna Ivory dan Putih bersih untuk memastikan teks konten (Pendidikan, Keahlian, Hobi, Pengalaman) sangat nyaman dibaca.

## Implementasi Kriteria Tugas
Website ini telah memenuhi seluruh instruksi dan kriteria penilaian tugas:
1. Penggunaan External CSS: Seluruh gaya dan modifikasi visual dipisahkan secara rapi di dalam file style.css.
2. Implementasi Box Model: Penggunaan padding, margin, dan border diterapkan pada setiap kontainer, kartu (cards), dan tombol untuk menjaga ruang kosong yang proporsional (menggunakan class section-padding dan edu-card).
3. Penggunaan Flexbox dan Grid:
  * Flexbox: Digunakan secara ekstensif pada tata letak Navbar, Footer, dan penyejajaran ikon-ikon (alignment).
  * Grid System: Menggunakan sistem Grid bawaan Bootstrap (row, col-md-6, col-lg-7, dll.) untuk membagi layar menjadi susunan yang rapi dan responsif.
4. Penggunaan Class dan ID dengan tepat: Pengelompokan elemen menggunakan ID untuk navigasi (contoh: about, experience) dan Class untuk styling berulang (contoh: bg-main, edu-overlay, org-card). Minimal terdapat lebih dari 15 class CSS kustom yang dibuat sendiri.
5. Implementasi Hover Effect dan Transition:
  * Efek zoom dan transisi bayangan (shadow) pada foto profil dan kartu-kartu proyek atau pendidikan.
  * Transisi warna halus pada tombol Navbar dan tombol sosial media.
  * Efek interaktif Accordion menggunakan murni CSS (hover untuk memperluas kotak) pada seksi Jejak Organisasi.
6. Responsivitas: Sepenuhnya responsif menggunakan Media Query (terintegrasi dengan Bootstrap) sehingga tata letak akan menyesuaikan secara otomatis saat dibuka di perangkat Mobile maupun Desktop.
7. Bonus Framework: Menggunakan Bootstrap 5 untuk bantuan struktur tata letak awal dan interaktivitas bawaan (Navbar Collapse).

## Penjelasan Fitur Unggulan Tambahan
Selain memenuhi kriteria dasar, website ini juga dilengkapi beberapa interaksi khusus untuk meningkatkan pengalaman pengguna (UI/UX):
* **Integrasi Video Lokal:** Menggunakan background video berformat MP4 lokal (bukan iframe eksternal) secara *autoplay* dan *loop* pada kartu pendidikan Universitas Mataram. Ini memberikan efek visual yang hidup dan eksklusif tanpa harus bergantung pada koneksi server pihak ketiga.
* **Interactive Accordion CSS Murni:** Bagian "Jejak Organisasi" dirancang agar tertutup rapat di awal untuk menghemat ruang baca. Ketika kursor diarahkan (*hover*), kartu akan memanjang mulus ke bawah untuk menampilkan detail daftar kepanitiaan.
* **Layout Kombinasi (Split Layout):** Bagian "Keahlian" menggunakan pemisahan visual yang tegas antara foto personal di sisi kiri dan barisan kartu kemampuan teknis di sisi kanan, meniru tata letak website profesional.

## Struktur Direktori
Penyimpanan file diatur sedemikian rupa agar rapi dan terstruktur:
* `index.html` : Berisi kerangka dasar semantik HTML dan struktur elemen website.
* `style.css` : File *External CSS* untuk memanipulasi tata letak, warna, batas, dan animasi efek sentuh (*hover*).
* `KebutuhanGambar` : Folder yang menyimpan seluruh aset visual pendukung (foto profil, gambar hobi, video lokal, dan ikon-ikon keahlian berformat resolusi tinggi).
* `Screenshot Tampilan` : Dokumentasi/tampilan web yang sudah dibuat.
* `README.md` : Penjelasan repositori tugas 2 CSS.


