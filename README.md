# Contoh Aplikasi CRUD Laravel dengan Eloquent ORM

Proyek ini merupakan contoh sederhana aplikasi **CRUD (Create, Read, Update, Delete)** menggunakan **Laravel** dan **Eloquent ORM**.

## 🔧 Fitur

- Tambah data post (judul & konten)
- Lihat daftar semua post
- Lihat detail post
- Edit post
- Hapus post

## 📦 Instalasi

Pastikan Anda sudah menginstal:
- PHP >= 8.1
- Composer
- MySQL / SQLite
- Laravel CLI (opsional)

### Langkah-langkah:

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/laravel-eloquent-crud.git
   cd laravel-eloquent-crud
2. install dependnsi
   composer install
3. Salin file konfigurasi environment
   cp .env.example .env
4. Generate application key
   php artisan key:generate
5. Atur koneksi database pada file .env sesuai konfigurasi lokal Anda
   DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=nama_database
  DB_USERNAME=root
  DB_PASSWORD=

6. Jalankan migrasi database
   php artisan serve
7. Jalankan server Laravel
   php artisan serve
8. buka browser dan akses
  http://localhost:8000/posts

