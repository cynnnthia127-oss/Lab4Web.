# Laporan Praktikum 4 - Pemrograman Web: CSS Layout

---

## 1. Pendahuluan

### 1.1 Latar Belakang
CSS (Cascading Style Sheets) merupakan bahasa yang digunakan untuk mengatur tampilan halaman web. Dengan CSS, elemen HTML dapat disusun dan ditata agar halaman web terlihat lebih terstruktur, rapi, dan mudah digunakan.

Pada praktikum ini, dipelajari mengenai **CSS Layout**, yaitu teknik untuk mengatur posisi dan susunan elemen pada halaman web. Materi mencakup penggunaan elemen `div`, properti `float`, teknik `clearfix`, serta penerapan elemen semantik HTML5 seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, dan `<footer>`.

### 1.2 Tujuan Praktikum
1. Memahami konsep dasar layout pada halaman web.
2. Memahami penggunaan elemen box dan properti CSS `float`.
3. Memahami penggunaan teknik `clearfix` untuk mengatasi masalah tata letak.
4. Mengenal dan menerapkan elemen semantik HTML5.
5. Membuat layout halaman web sederhana menggunakan HTML dan CSS.

---

## 2. Langkah-Langkah Praktikum

### Langkah 1: Pembuatan Dokumen HTML Dasar (`lab4_box.html`)
* Membuat file HTML baru bernama `lab4_box.html`.
* Mendeklarasikan `<!DOCTYPE html>`, tag `<html>`, `<head>`, dan `<body>`.
* Menambahkan pengaturan `charset`, `viewport`, `<title>Box Element</title>`, serta elemen `<header>` bertuliskan `<h1>Box Element</h1>`.

### Langkah 2: Membuat Box Element (`div`)
* Menambahkan 4 elemen `<div>` di dalam elemen `<section>` dengan class `div1`, `div2`, `div3`, dan `div4`.
* Menggunakan elemen `<div>` sebagai kotak dasar untuk mempelajari pengaturan posisi halaman.

### Langkah 3: Mengatur CSS Float Property & Clearfix Element
* Menambahkan tag `<style>` di dalam bagian `<head>`.
* Mengatur elemen `div` menggunakan properti `float: left` dan `padding: 10px` agar kotak tersusun berdampingan ke arah kiri.
* Memberikan latar belakang warna berbeda (`red`, `yellow`, `green`) pada setiap kotak.
* Menerapkan teknik `clearfix` pada `.div4` menggunakan properti `clear: left; float: none;` dengan latar belakang warna `blue` untuk menghentikan efek float dari elemen sebelumnya.

### Langkah 4: Membuat Layout Sederhana (`home.html` & `style.css`)
* Membuat struktur kerangka layout utama pada file `home.html`:
  * **Header & Navigasi:** Menambahkan judul halaman dan menu navigasi (Home, Artikel, About, Kontak).
  * **Hero Panel:** Area banner utama di bawah navigasi bertuliskan "Hello World!" dan tombol CTA.
  * **Main Content & Sidebar:** Membagi tata letak dua kolom menggunakan `float: left` (`#main` lebar 640px dan `#sidebar` lebar 300px).
  * **Widget Sidebar & Content Box:** Menambahkan widget teks/link pada sidebar serta 3 kotak konten berbentuk lingkaran (`image-circle`) di area main.
  * **Artikel:** Menambahkan artikel fitur lengkap dengan gambar pendukung rata kiri dan rata kanan.
  * **Footer:** Bagian bawah halaman yang berisi teks hak cipta (`&copy; 2026 - Universitas Pelita Bangsa`).

### Langkah 5: Pengembangan Halaman About (`about.html` & `styleabout.css`)
* Buat file `about.html` dengan tata letak single page.
* Berisi informasi **Deskripsi** tentang mahasiswa, **Portfolio** (Illustrator, Beginner Data Analyst, Pemrograman Web Dasar), serta bagian **Tujuan Pembelajaran**.

### Langkah 6: Pengembangan Halaman Contact (`contact.html` & `stylecont.css`)
* Buat file `contact.html` dengan formulir isian kontak.
* Komponen form terdiri dari: Nama Lengkap, Email, Subjek, dan Pesan.
* Dilengkapi dengan sidebar informasi kontak di sebelah kanannya.

---

## 3. Kesimpulan

Berdasarkan praktikum CSS Layout yang telah dilakukan, dapat disimpulkan bahwa HTML dan CSS memiliki peran penting dalam pembuatan tata letak halaman web. Melalui praktikum ini, telah dipelajari penggunaan elemen box, properti `float`, teknik `clearfix`, serta elemen semantik HTML5 untuk menyusun struktur halaman web yang rapi dan teratur.

Selain itu, pengaturan bagian-bagian halaman seperti header, navigasi, hero panel, konten utama, sidebar, dan footer dapat diimplementasikan dengan baik menggunakan CSS. Pembuatan halaman tambahan seperti `about.html` dan `contact.html` memberikan pemahaman mendalam mengenai pengembangan halaman web multi-halaman yang saling terhubung melalui menu navigasi.