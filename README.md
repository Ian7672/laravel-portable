
## 🕒 Carbon CLI

Versi ini juga menyertakan **carbon-cli** untuk manipulasi waktu/tanggal melalui command line.

- Version: `1.3.0`
- Library utama:
  - `nesbot/carbon` v3.9.1
  - `carbonphp/carbon-doctrine-types` v3.2.0
  - `symfony/clock`, `translation`, dll.

## 📦 Dependency yang Sudah Terpasang

- `carbon-cli/carbon-cli` (v1.3.0)
- `nesbot/carbon` (v3.9.1)
- `symfony/translation` (v7.2.6)
- `symfony/clock` (v7.2.0)
- `simple-cli/simple-cli` (v1.6.0)
- `composer` (terpasang di dalam folder `Composer/`)

# Laravel Windows Portable 5.14.2 – Stable Version

Versi ini adalah **Laravel Installer 5.14.2** yang telah dikemas secara portabel untuk sistem operasi Windows. Cocok bagi Anda yang ingin menjalankan Laravel tanpa instalasi tambahan atau pengaturan lingkungan yang kompleks. Semua sudah dipaketkan dalam satu file arsip `.7z`, tinggal ekstrak dan jalankan.

## 📦 Distribusi

File distribusi tersedia dalam format `laravel_windows_5.14.2-portable-stable.7z`.

### 📥 Cara Install

1. Ekstrak file `.7z` menggunakan aplikasi seperti **7-Zip** atau **WinRAR**.
2. Setelah ekstraksi, jalankan file:

```bash
LARAVEL-INSTALL.exe

## 🔧 Cara Membuat Proyek

Buka terminal (CMD/PowerShell) lalu arahkan ke direktori ini:

```bash
cd D:\upload-github\portable\fix\laravel_windows_5.14.2-portable-stable\Composer\Composer\vendor\bin

# Untuk cek versi Laravel
laravel -v

# Untuk buat project baru
laravel new nama_project
