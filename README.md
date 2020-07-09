# AJ Kasir
Aplikasi kasir online

## Technology Stack

- Laravel 7
- Laravel Livewire
- Bootstrap 4
- Tailwind CSS
- JQuery
- Alipine Js
- MySQL 5.7

# Installasi Aplikasi

## Installasi Shared Hosting

1. Siapkan database
2. Catat nama database, username, dan password untuk koneksi ke database
3. Upload source code ke directory utama hosting (public, public_html, dsb)
4. Pada folder aplikasi, masuk ke folder `laravel`
5. Edit file `.env`. Sesuaikan `APP_NAME` `APP_URL` `DB_CONNECTION` `DB_HOST` `DB_PORT` `DB_DATABASE` `DB_USERNAME` `DB_PASSWORD`
6. Import file `dump.sql` ke database
7. Aplikasi siap digunakan dengan membuka domain atau mengarahkan domain langsung ke folder aplikasi

# Modifkasi

Berikut adalah beberapa file yang dapat dimodifkasi sesuai kebutuhan.

### ./laravel/.env
File ini merupakan file untuk menyimpan konfigurasi environment aplikasi. Setelah melakukan perubahaan pada file ini, file `laravel/bootstrap/cache/config.php` harus direname atau dihapus. Hal ini agar pengaturan yang baru akan segera diload oleh server.

### ./laravel/config
File-file yang ada di dalam sini adalah file konfigurasi yang digunakan oleh aplikasi. Beberapa key di dalamnya sudah ada yang terhubung dengan file `./laravel/.env`. Setelah melakukan perubahaan pada file ini, file `laravel/bootstrap/cache/config.php` harus direname atau dihapus. Hal ini agar pengaturan yang baru akan segera diload oleh server.

### ./laravel/resources/views
File-file yang ada di dalam sini adalah file untuk UI aplikasi. Di dalamnya terdapat master layout yaitu pada file `layouts/app.blade.php`.
