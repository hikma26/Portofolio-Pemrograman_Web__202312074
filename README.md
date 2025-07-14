# 📘 Portofolio Pemrograman Web

**Mata Kuliah**: Pemrograman Web
**NIM**: 202312074
**Nama**: Nur Hikma
**Institusi**: STITEK Bontang

---

## 📋 Deskripsi Project

Repositori ini merupakan kumpulan tugas praktikum Pemrograman Web dari Modul 1 hingga Modul 6. Setiap modul menyajikan kemampuan berbeda dalam pengembangan web, mulai dari dasar HTML hingga integrasi database menggunakan PHP & MySQL. Tujuan utama proyek ini adalah membangun portofolio yang mencerminkan progres pemahaman teknologi web modern secara terstruktur.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi  | Versi   | Keterangan Penggunaan                  |
| ---------- | ------- | -------------------------------------- |
| HTML5      | Terbaru | Struktur dasar halaman web             |
| CSS3       | Terbaru | Styling tampilan dan layout            |
| JavaScript | ES6+    | Logika interaktif dan DOM Manipulation |
| Bootstrap  | 5.3.3   | Framework responsif berbasis komponen  |
| PHP        | 7.4+    | Bahasa backend dan server-side logic   |
| MySQL      | 8.0+    | Pengelolaan database relasional        |

---

## 📁 Struktur Project

```plaintext
Portofolio-Pemrograman-Web-202312074/
├── Modul-1/
│   ├── tugas_modul1.html
│   └── logo stitek.png
├── Modul-2/
│   ├── tugas_modul2.html
│   └── tugas_modul2.css
├── Modul-3/
│   ├── tugas3.html
│   ├── Nokia-C3-3.jpg
│   ├── maxresdefault.jpg
│   └── readmiA1.jpg
├── Modul-4/
│   ├── tugas.html
│   ├── asusvivobook.jpg
│   ├── iphone 16.jpg
│   ├── iphone14.jpg
│   ├── iphone15.jpg
│   ├── laptophp.jpg
│   ├── legion.jpg
│   ├── maxresdefault.jpg
│   ├── readmiA1.jpg
│   └── Nokia-C3-3.jpg
├── Modul-5/
│   └── tugas.php
├── Modul-6/
│   └── Crud Toko Online/
│       ├── index.php
│       ├── tambah.php
│       ├── edit.php
│       ├── hapus.php
│       ├── koneksi_toko.php
│       └── backup_koneksi.txt
└── README.md
```

---

## 🔍 Ringkasan Modul

### 📄 Modul 1: HTML Dasar

Membuat form pendaftaran mahasiswa dengan input lengkap (text, radio, select, dll). Struktur HTML disusun semantik.

### 🎨 Modul 2: CSS & Responsive Design

Menerapkan Grid CSS untuk tampilan layout halaman yang responsif. Desain menyesuaikan ukuran perangkat.

### 🧱 Modul 3: Bootstrap Framework

Profil perusahaan sederhana menggunakan Bootstrap. Dilengkapi gambar dan layout grid responsif.

### ⚙️ Modul 4: JavaScript Interaktif

Simulasi toko elektronik, fitur seperti kalkulasi harga otomatis, slideshow gambar produk, dan jam real-time.

### 📝 Modul 5: PHP Dasar

Membuat buku tamu digital dengan validasi server-side, menyimpan data input pengguna secara aman.

### 📃 Modul 6: CRUD Produk Toko Online

Aplikasi CRUD (Create, Read, Update, Delete) produk dengan PHP dan database MySQL. Dilengkapi form input dan koneksi database.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone Repository**:

   ```bash
   git clone https://github.com/hikma26/Portofolio-Pemrograman_Web__202312074.git
   cd Portofolio-Pemrograman_Web__202312074
   ```

2. **Setup Local Server** (XAMPP):

   * Letakkan folder ke `htdocs`
   * Jalankan Apache & MySQL

3. **Buat Database untuk Modul 6**:

   ```sql
   CREATE DATABASE db_toko;

   CREATE TABLE produk (
     id_produk INT AUTO_INCREMENT PRIMARY KEY,
     nama_produk VARCHAR(100) NOT NULL,
     harga DECIMAL(10,2) NOT NULL,
     stok INT NOT NULL
   );
   ```

---

## 🌿 Branch Pengembangan

| Branch          | Modul yang Dicakup                       |
| --------------- | ---------------------------------------- |
| tugas/modul-1-3 | Modul 1, 2, dan 3 (HTML, CSS, Bootstrap) |
| tugas/modul-4   | Modul 4 (JavaScript)                     |
| tugas/modul-5   | Modul 5 (Buku Tamu PHP)                  |
| tugas/modul-6   | Modul 6 (CRUD PHP & MySQL)               |

Contoh perintah git:

```bash
git checkout main
git pull origin main
git checkout -b tugas/modul-1-3
git add .
git commit -m "Menambahkan Modul 1–3"
git push origin tugas/modul-1-3
```

---

## 🔗 Link Repository & Video Per Modul

| Modul   | Repository                                                                                                                                       | Video                                                                                                |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Modul 1 | [https://github.com/hikma26/Tugas-Modul-1-Praktikum-Pemrograman-Web.git](https://github.com/hikma26/Tugas-Modul-1-Praktikum-Pemrograman-Web.git) | [https://youtu.be/-NnTQF4CWHQ](https://youtu.be/-NnTQF4CWHQ)                                         |
| Modul 2 | [https://github.com/hikma26/tugas-modul-2-pemrograman-web.git](https://github.com/hikma26/tugas-modul-2-pemrograman-web.git)                     | [https://youtu.be/mfV1TGTCtZE?si=VxjW6DvTm80AYmoF](https://youtu.be/mfV1TGTCtZE?si=VxjW6DvTm80AYmoF) |
| Modul 3 | [https://github.com/hikma26/Tugas-modul-3.git](https://github.com/hikma26/Tugas-modul-3.git)                                                     | [https://youtu.be/OrmCHsjEaa8](https://youtu.be/OrmCHsjEaa8)                                         |
| Modul 4 | [https://github.com/hikma26/tugasmodul4.git](https://github.com/hikma26/tugasmodul4.git)                                                         | [https://youtu.be/fO2z0llPxk4](https://youtu.be/fO2z0llPxk4)                                         |
| Modul 5 | *Menyusul*                                                                                                                                       | *Menyusul*                                                                                           |
| Modul 6 | [https://github.com/hikma26/tugas\_modul6.git](https://github.com/hikma26/tugas_modul6.git)                                                      | [https://youtu.be/fhhvjxIFiaE](https://youtu.be/fhhvjxIFiaE)                                         |

---

## 🌐 Akses Lokal

| Modul   | URL Lokal                                                                                                                                                                |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Modul 1 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-1/tugas\_modul1.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-1/tugas_modul1.html) |
| Modul 2 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-2/tugas\_modul2.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-2/tugas_modul2.html) |
| Modul 3 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-3/tugas3.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-3/tugas3.html)              |
| Modul 4 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-4/tugas.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-4/tugas.html)                |
| Modul 5 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-5/tugas.php](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-5/tugas.php)                  |
| Modul 6 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-6/Crud](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-6/Crud) Toko Online/               |

---

## 🔐 Keamanan & Validasi

* ✅ Validasi Input (Client & Server Side)
* ✅ Proteksi XSS (`htmlspecialchars()`)
* ⚠️ Peningkatan: SQL Injection → gunakan prepared statements
* 🛡️ (Opsional) CSRF token untuk proteksi form

---

## ✨ Catatan Akhir

Struktur repository dan branch telah dibuat dengan memperhatikan keteraturan versi, kolaborasi, dan penilaian per modul. Ini menunjukkan penguasaan praktik Git dan dokumentasi proyek secara profesional.

---

## 📄 Lisensi

Proyek ini disusun untuk dokumentasi akademik mata kuliah Pemrograman Web oleh **Nur Hikma (202312074)** di **STITEK Bontang**.
