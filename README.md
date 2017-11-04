# hyourinseta.github.io

hyourinseta.github.io adalah GitHub Pages dari akun github https://github.com/hyourinseta. GitHub Pages ini dibuat oleh saya sendiri, **Gugi Gustaman (NPM: 1541811)** dan merupakan salah satu tugas yang dibuat untuk memenuhi Ujian Tengah Semester (UTS) mata kuliah Pemrograman Web di Program Studi Sistem Informasi STMIK "AMIKBANDUNG".

Berikut adalah tampilan halaman "Home" dari https://hyourinseta.github.io.

![enter image description here](https://www.dropbox.com/s/l2hp8ppg20wm57z/Home.png?raw=1)

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

## Animsition sebagai Plugin Transisi Halaman

Saya menggunakan animsition sebagai tool untuk menghadirkan transisi dalam setiap pergantian halaman. Berikut cara implementasi animsition pada halaman web.

1. Download terlebih dahulu animsition di https://github.com/blivesta/animsition/archive/master.zip. 
2. Ekstrak file hasil download dan salin direktori **dist/css** dan **dist/js** ke direktori *root* halaman web.
3. Masukkan baris kode berikut sebelum tag HEAD berakhir pada dokumen HTML.
`<link rel="stylesheet" href="css/animsition.min.css">`
4. Masukkan baris kode berikut sebelum tag BODY berakhir pada dokumen HTML.
`<script src="js/animsition.min.js"></script>`
`<script type="text/javascript" src="js/custom.js"></script>`
5. Buatlah sebuah file di dalam direktori js dengan nama **custom.js**. Masukkan baris-baris kode berikut ke dalam file tersebut.
![enter image description here](https://www.dropbox.com/s/qwqfu6p6f75hqy0/8.png?raw=1)

6. Simpan file tersebut. Baris-baris kode di atas dapat disesuaikan dengan referensi dokumentasi di http://git.blivesta.com/animsition/.

## Membuat GitHub Pages

Untuk dapat membuat GitHub Pages, berikut adalah langkah-langkah yang harus dilakukan.

1. Buat repository di akun GitHub dengan nama *username*.github.io. Misalnya untuk akun saya, repository yang saya buat bernama **hyourinseta.github.io**. Secara otomatis GitHub akan menjadikan repository tersebut sebagai direktori *root* dari halaman web **hyourinseta.github.io**.
2. Jalankan perintah **git init** pada direktori *root* halaman web untuk menginisialisasi repository.
`$ git init`
3. Jalankan perintah **git add .** untuk menambahkan semua file dan direktori yang ada pada direktori *root* halaman web.
`$ git add .`
4. Jalankan perintah **git commit -m "First commit"** untuk menambahkan pesan/deskripsi atas perubahan yang baru ditambahkan ke git.
`$ git commit -m "First commit"`
5. Tambahkan repository GitHub yang baru dibuat sebagai remote repository dengan perintah berikut.
`$ git remote add origin https://github.com/hyourinseta/hyourinseta.github.io.git`
6. Push semua file di direktori *root* ke GitHub sebagai branch **master**.
`$ git push -u origin master`

## Hasil Akhir

Halaman **Home**
![Halaman Home](https://www.dropbox.com/s/l2hp8ppg20wm57z/Home.png?raw=1)

Halaman **Profile**
![Halaman Profile](https://www.dropbox.com/s/gmgkt5jk33xl0v8/Profile.png?raw=1)

Halaman **Contact**
![enter image description here](https://www.dropbox.com/s/toz83v0tawdgt04/Contact.png?raw=1)

Halaman Validasi Form **Contact**
![enter image description here](https://www.dropbox.com/s/x0lb21brpcr2prt/FormValidation.png?raw=1)

## Credits

- Bootstrap (https://getbootstrap.com/)
- jQuery (https://jquery.com/)
- Font Awesome (http://fontawesome.io/)
- Animsition (http://git.blivesta.com/animsition/)