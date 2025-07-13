# Portofolio Pemrograman Web

**Mata Kuliah**: Pemrograman Web
**NIM**: 202312074
**Nama**: Nur Hikma
**Institusi**: STITEK Bontang

---

## 📋 Deskripsi Project

Repositori ini merupakan kumpulan tugas praktikum dari mata kuliah Pemrograman Web yang dikembangkan dari Modul 1 hingga Modul 6. Tujuannya adalah untuk membangun portofolio digital mahasiswa yang menunjukkan perkembangan keterampilan dalam pengembangan web, mulai dari dasar HTML, CSS, JavaScript, hingga pemrograman backend menggunakan PHP dan MySQL.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi  | Versi   | Deskripsi                           |
| ---------- | ------- | ----------------------------------- |
| HTML5      | Terbaru | Membuat struktur halaman web        |
| CSS3       | Terbaru | Menata tampilan dan layout web      |
| JavaScript | ES6+    | Interaktivitas pada halaman         |
| Bootstrap  | 5.3.3   | Framework responsif untuk desain UI |
| PHP        | 7.4+    | Bahasa backend untuk logika server  |
| MySQL      | 8.0+    | Sistem manajemen basis data         |

---

## 📁 Struktur Project

```
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

## 🔢 Detail Modul

### 📅 Modul 1: HTML Dasar

**File**: `Modul-1/tugas_modul1.html`

Formulir pendaftaran yang mencakup elemen-elemen seperti input teks, radio, checkbox, dan penggunaan atribut form secara lengkap. Dilengkapi juga dengan logo kampus.

### 🖌️ Modul 2: CSS dan Responsive Design

**File**: `Modul-2/tugas_modul2.html`, `tugas_modul2.css`

Mendesain layout grid yang responsif menggunakan CSS3, dengan gaya yang konsisten untuk berbagai perangkat (desktop, tablet, mobile).

### 🚀 Modul 3: Framework Bootstrap

**File**: `Modul-3/tugas3.html`

Situs profil perusahaan berbasis Bootstrap. Menggunakan card, tabel, dan elemen UI Bootstrap lainnya. Gambar produk ditampilkan dalam folder ini.

### ⚡ Modul 4: JavaScript Interaktif

**File**: `Modul-4/tugas.html`

Membuat toko elektronik sederhana. Fitur seperti kalkulasi total harga, promo, jam real-time, dan slideshow gambar produk dijalankan menggunakan JavaScript.

### 🔧 Modul 5: Dasar PHP

**File**: `Modul-5/tugas.php`

Implementasi buku tamu digital yang dapat menyimpan dan menampilkan data input pengguna dengan validasi server-side sederhana.

### 📂 Modul 6: CRUD dengan PHP & MySQL

**Folder**: `Modul-6/Crud Toko Online/`

Aplikasi CRUD (Create, Read, Update, Delete) untuk mengelola data produk toko online menggunakan database MySQL dan koneksi PHP. Mendukung tambah, edit, hapus, dan tampilan tabel data.

---

## 🚪 Cara Menjalankan Project

1. **Clone Repository**

```bash
git clone https://github.com/hikma26/Portofolio-Pemrograman_Web__202312074.git
```

2. **Buka di XAMPP**

* Tempatkan folder ke dalam `htdocs`
* Jalankan Apache & MySQL via XAMPP

3. **Import Database** (untuk Modul 6)

```sql
CREATE DATABASE db_toko;
USE db_toko;

CREATE TABLE produk (
  id_produk INT AUTO_INCREMENT PRIMARY KEY,
  nama_produk VARCHAR(100) NOT NULL,
  harga DECIMAL(10,2) NOT NULL,
  stok INT NOT NULL
);
```

---

## 🔗 Link Modul dan Video

### Modul 1

* Repository: [https://github.com/hikma26/Tugas-Modul-1-Praktikum-Pemrograman-Web.git](https://github.com/hikma26/Tugas-Modul-1-Praktikum-Pemrograman-Web.git)
* Video: [https://youtu.be/-NnTQF4CWHQ](https://youtu.be/-NnTQF4CWHQ)

### Modul 2

* Repository: [https://github.com/hikma26/tugas-modul-2-pemrograman-web.git](https://github.com/hikma26/tugas-modul-2-pemrograman-web.git)
* Video: [https://youtu.be/mfV1TGTCtZE?si=VxjW6DvTm80AYmoF](https://youtu.be/mfV1TGTCtZE?si=VxjW6DvTm80AYmoF)

### Modul 3

* Repository: [https://github.com/hikma26/Tugas-modul-3.git](https://github.com/hikma26/Tugas-modul-3.git)
* Video: [https://youtu.be/OrmCHsjEaa8](https://youtu.be/OrmCHsjEaa8)

### Modul 4

* Repository: [https://github.com/hikma26/tugasmodul4.git](https://github.com/hikma26/tugasmodul4.git)
* Video: [https://youtu.be/fO2z0llPxk4](https://youtu.be/fO2z0llPxk4)

### Modul 5

* Repository: *menyusul*
* Video: *menyusul*

### Modul 6

* Repository: [https://github.com/hikma26/tugas\_modul6.git](https://github.com/hikma26/tugas_modul6.git)
* Video: [https://youtu.be/fhhvjxIFiaE](https://youtu.be/fhhvjxIFiaE)

---

## 🛍️ Akses URL Lokal

| Modul   | URL                                                                                                                                                                      |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Modul 1 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-1/tugas\_modul1.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-1/tugas_modul1.html) |
| Modul 2 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-2/tugas\_modul2.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-2/tugas_modul2.html) |
| Modul 3 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-3/tugas3.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-3/tugas3.html)              |
| Modul 4 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-4/tugas.html](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-4/tugas.html)                |
| Modul 5 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-5/tugas.php](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-5/tugas.php)                  |
| Modul 6 | [http://localhost/Portofolio-Pemrograman\_Web\_\_202312074/Modul-6/Crud](http://localhost/Portofolio-Pemrograman_Web__202312074/Modul-6/Crud) Toko Online/               |

---

## 📑 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan dokumentasi tugas akhir mata kuliah Pemrograman Web STITEK Bontang oleh Nur Hikma (202312074).
