# hyourinseta.github.io

hyourinseta.github.io adalah GitHub Pages dari akun github https://github.com/hyourinseta. GitHub Pages ini dibuat oleh saya sendiri, Gugi Gustaman (NPM : 1541811) dan merupakan salah satu tugas yang dibuat untuk memenuhi Ujian Tengah Semester (UTS) mata kuliah Pemrograman Web di Program Studi Sistem Informasi STMIK "AMIKBANDUNG".

Berikut adalah tampilan halaman "Home" dari https://hyourinseta.github.io.

![enter image description here](https://www.dropbox.com/s/l2hp8ppg20wm57z/Home.png?raw=1)


----------


## Daftar Isi

[TOC]

----------

## Bootstrap sebagai Framework Front-end


Framework front-end yang saya gunakan pada GitHub Pages ini adalah **Bootstrap**. Berikut langkah-langkah dalam mengimplementasikan Bootstrap pada halaman web.

1. Buka web browser kemudian tuju http://getbootstrap.com.
2. Klik tombol “Download” di sebelah kanan atas halaman seperti pada gambar berikut.
![enter image description here](https://www.dropbox.com/s/js0bhamyrnn4x47/1.png?raw=1)

3. Setelah download selesai, ekstrak arsip tersebut, maka akan terdapat dua direktori seperti pada gambar berikut.
![enter image description here](https://www.dropbox.com/s/rhsv9d60ye5lcdc/2.png?raw=1)

4. Salin kedua direktori tersebut ke dalam direktori halaman web yang akan dibuat.
5. Download JQuery dengan cara akses ke https://jquery.com/download/ menggunakan Web Browser kemudian download jQuery versi 3.2.1 (compressed) seperti pada gambar berikut.
![enter image description here](https://www.dropbox.com/s/rgniqclmpcbfbce/3.png?raw=1)

6. Salin file jquery-3.2.1.min.js tersebut ke direktori js di dalam direktori halaman web yang akan dibuat.
7. Unduh popper.js dengan akses menggunakan web browser ke https://unpkg.com/popper.js@1.12.6/dist/umd/popper.js kemudian Save halaman tersebut dengan nama popper.js seperti pada gambar berikut.
8. Salin file popper.js tersebut ke direktori js di dalam direktori halaman web yang akan dibuat.
9. Masukkan baris-baris kode berikut ke dalam tag HEAD di dokumen HTML yang akan dipasang bootstrap.
`<link rel="stylesheet" href="css/bootstrap.min.css" />`

10. Masukkan baris-baris kode berikut ke dalam tag BODY di dokumen HTML, tepat sebelum tag BODY ditutup.
    `<script src="js/jquery-3.2.1.min.js"></script>`
    `<script src="js/popper.js"></script>`
    `<script src="js/bootstrap.min.js"></script>`
    
11. Berikut contoh penggunaan bootstrap pada source code dokumen index.html.
![enter image description here](https://www.dropbox.com/s/klq10qfx71qs6ao/7.png?raw=1)
12. Ubahlah halaman seperti yang diinginkan menggunakan *style*, *component* dan *utilities* yang telah Bootstrap sediakan dengan panduan dokumentasi dari Bootstrap (https://getbootstrap.com/docs/4.0).
13. Buka index.html tersebut pada web browser dan hasilnya adalah sebagai berikut.
![enter image description here](https://www.dropbox.com/s/l2hp8ppg20wm57z/Home.png?raw=1)
