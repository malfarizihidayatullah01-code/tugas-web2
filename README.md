📚 Book Management System (Laravel CRUD)

Aplikasi web sederhana berbasis Laravel untuk mengelola data buku, kategori, dan penerbit.
Project ini dibuat sebagai tugas mata kuliah sekaligus latihan memahami konsep CRUD dan MVC di Laravel.

✨ Fitur Utama
📖 CRUD Data Buku (Tambah, Edit, Hapus, Lihat)
🏷️ CRUD Kategori
🏢 CRUD Penerbit
🔗 Relasi:
Buku → Kategori
Buku → Penerbit
✅ Validasi input form
🎨 Tampilan sederhana & user-friendly
🛠️ Teknologi yang Digunakan
Laravel 8
PHP
MySQL
Blade Template Engine
🚀 Cara Menjalankan Project
# Clone repository
git clone https://github.com/malfarizihidayatullah01-code/tugas-web2.git

# Masuk ke folder project
cd tugas-web2

# Install dependency
composer install

# Copy file environment
cp .env.example .env

# Generate application key
php artisan key:generate
⚙️ Konfigurasi Database

Buka file .env, lalu sesuaikan:

DB_DATABASE=nama_database_kamu
DB_USERNAME=root
DB_PASSWORD=

Lanjut jalankan:

php artisan migrate
▶️ Menjalankan Aplikasi
php artisan serve

Akses di browser:

http://127.0.0.1:8000
📂 Struktur Folder Penting
app/
 ├── Models/
 ├── Http/Controllers/

resources/views/

routes/web.php

database/migrations/
🔗 Fitur Endpoint (CRUD)
Method	URL	Keterangan
GET	/buku	Tampilkan data
GET	/buku/create	Form tambah
POST	/buku	Simpan data
GET	/buku/{id}/edit	Form edit
PUT	/buku/{id}	Update data
DELETE	/buku/{id}	Hapus data
🧠 Tujuan Project

Project ini dibuat untuk:

Memahami konsep CRUD di Laravel
Belajar struktur MVC
Mengelola relasi database
Latihan membuat aplikasi web sederhana
⚠️ Troubleshooting

Error: vendor/autoload.php tidak ditemukan

composer install

Error: Application key

php artisan key:generate

Error database

Pastikan database sudah dibuat
Cek konfigurasi .env
👨‍💻 Author

Malfarizi Hidayatullah
GitHub: https://github.com/malfarizihidayatullah01-code
