# module-web

Repository ini berisi modul pembelajaran komprehensif untuk pengembangan web. Modul ini dirancang untuk membantu pemula hingga pengembang tingkat lanjut memahami konsep dasar hingga lanjutan dalam pengembangan web. Setiap bab mencakup penjelasan teori, contoh kode, dan latihan praktis untuk memperkuat pemahaman.

## Daftar Isi

- [Praktikum 1](#praktikum-1)
  - [1.1 Teori Pendukung](#11-teori-pendukung)
  - [Pre-Test](#12-pre-test)
  - [Langkah Praktikum](#13-langkah-praktikum)
  - [Post Test](#14post-test)

# PRAKTIKUM 1

## 1.1 Teori Pendukung

### Apa itu Pengembangan Web?

Pengembangan web adalah proses pembuatan dan pemeliharaan situs web. Ini mencakup berbagai aspek seperti desain web, pengembangan konten, scripting client-side/server-side, dan konfigurasi keamanan jaringan. Pengembangan web dibagi menjadi dua bagian utama: front-end (client-side) dan back-end (server-side).

### Sejarah dan Evolusi Web

Sejarah web dimulai pada tahun 1990 ketika Tim Berners-Lee menciptakan World Wide Web (WWW). Pada awalnya, web hanya terdiri dari dokumen teks statis. Seiring waktu, teknologi web berkembang pesat:

- `Web 1.0`: Era situs web statis dengan konten yang hampir tidak berubah
- `Web 2.0`: Pengguna bisa berinteraksi dengan web, yang meliputi situs jejaring sosial, blog, dan wiki.
- `Web 3.0`: Fokus pada AI dan data yang lebih semantik untuk memberikan pengalaman pengguna yang lebih cerdas dan personal.

### Arsitektur Web dan Komponen Utama

Pengembangan web modern terdiri dari beberapa komponen penting yang bekerja bersama untuk memberikan pengalaman pengguna yang mulus:

- `HTML (Hypertext Markup Language)`: Bahasa standar untuk membuat struktur halaman web.
- `CSS (Cascading Style Sheets)`: Digunakan untuk mengatur tampilan dan tata letak halaman web.
- `JavaScript`: Bahasa pemrograman yang membuat halaman web menjadi interaktif dan dinamis.
- `Server-Side Scripting`: Bahasa seperti PHP, Node.js, dan Python digunakan untuk membangun logika di sisi server.
- `Database`: Sistem manajemen basis data seperti MySQL, PostgreSQL, dan MongoDB digunakan untuk menyimpan dan mengelola data.

## 1.2 Pre-Test

1. Apa itu HTML dan apa fungsinya dalam pengembangan web?
2. Sebutkan tiga komponen utama dari pengembangan web.
3. Apa perbedaan antara Web 1.0, Web 2.0, dan Web 3.0?
4. Sebutkan satu bahasa pemrograman yang digunakan untuk server-side scripting.

## 1.3 Langkah Praktikum

### Langkah 1: Membuat halaman web sederhana

Persiapan Alat dan Lingkungan:

- Instal Visual Studio Code atau editor teks lain yang kamu sukai.
- Siapkan browser modern seperti Google Chrome atau Firefox.

### Langkah 2: Menulis HTML Dasar

- Buat file baru bernama `index.html`.
- Tambahkan struktur HTML dasar:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Halaman Web Sederhana</title>
  </head>
  <body>
    <h1>Selamat Datang di Pengembangan Web</h1>
    <p>Ini adalah contoh halaman web sederhana.</p>
  </body>
</html>
```

### Langkah 3: Menambahkan CSS untuk Styling

- Tambahkan tag `<style>` dalam `<head>`:

```html
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background-color: #f4f4f4;
  }
  h1 {
    color: #333;
  }
  p {
    color: #666;
  }
</style>
```

### Langkah 4: Melihat Hasil di Browser

- Buka file `index.html` di browser dan lihat hasilnya.

## 1.4 Post-Test

- Apa saja komponen utama dalam struktur HTML dasar?
- Bagaimana cara menambahkan styling CSS dalam halaman HTML?
- Sebutkan tiga perbedaan antara HTML, CSS, dan JavaScript.
- Mengapa penting untuk menggunakan database dalam pengembangan web?
