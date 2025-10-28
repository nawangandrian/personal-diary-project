<p align="center">
  <a href="https://flask.palletsprojects.com" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg" width="200" alt="Flask Logo">
  </a>
</p>

<p align="center">
  <a href="https://pypi.org/project/Flask/"><img src="https://img.shields.io/pypi/dm/Flask" alt="Total Downloads"></a>
  <a href="https://pypi.org/project/Flask/"><img src="https://img.shields.io/pypi/v/Flask" alt="Latest Version"></a>
  <a href="https://opensource.org/licenses/BSD-3-Clause"><img src="https://img.shields.io/badge/license-BSD-blue.svg" alt="License"></a>
</p>

# Dictionary App – Flask + MongoDB

Aplikasi **Dictionary (Kamus Online)** berbasis **Flask** dan **MongoDB**, yang memungkinkan pengguna untuk mencari arti kata dari API eksternal, menyimpan kata ke database pribadi, serta menambahkan contoh penggunaan kata tersebut.

---

## Fitur Utama

**Cari Arti Kata**
- Aplikasi akan mengambil data definisi kata dari [Merriam-Webster API](https://dictionaryapi.com/).  
- Jika kata tidak ditemukan, aplikasi akan memberikan **saran kata yang mirip**.

**Simpan Kata Favorit**
- Pengguna dapat menyimpan kata dan definisinya ke database MongoDB.

**Tambah & Hapus Contoh Kalimat**
- Setiap kata dapat diberi **contoh kalimat penggunaan (example sentence)**.
- Pengguna dapat menambahkan atau menghapus contoh secara dinamis.

**Manajemen Data MongoDB**
- Semua data kata dan contoh disimpan di koleksi `words` dan `examples` pada database MongoDB.

---

## Teknologi yang Digunakan

| Komponen | Teknologi |
|-----------|------------|
| Backend | Flask (Python) |
| Database | MongoDB Atlas |
| API | Merriam-Webster Dictionary API |
| Template Engine | Jinja2 (HTML) |
| Environment | python-dotenv |
| Frontend | HTML, CSS, JavaScript |

---

## Cara Menjalankan Aplikasi (Localhost)

1. **Clone repository**
   ```bash
   git clone https://github.com/nawangandrian/personal-diary-project.git
