# ​🧾​​ SPP Online SMK Jambi IX Lurah 2

[![Laravel](https://img.shields.io/badge/Laravel-11.x-orange.svg)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.0+-purple.svg)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue.svg)](https://mysql.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Instalasi

### Prasyarat
- PHP 8.1+
- Composer 2.2+
- MySQL 8.0+

### Langkah 1: Clone Repositori
```bash
git clone https://github.com/rickyylaa/spp-online-smk-jambi-ix-lurah-2.git
cd spp-online-smk-jambi-ix-lurah-2
```

### Langkah 2: Install Dependensi
```bash
composer install
```

### Langkah 3: Konfigurasi Environment
```bash
cp .env.example .env
php artisan key:generate

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=spp-online-smk-jambi-ix-lurah-2
DB_USERNAME=root
DB_PASSWORD=
```

### Langkah 4: Database Setup
```bash
php artisan migrate
php artisan db:seed
```

### Langkah 5: Optimasi 2x
```bash
php artisan optimize
php artisan optimize
```

### Langkah 6: Storage Link
```bash
php artisan storage:link
```

### Langkah 7: Jalankan Aplikasi
```bash
php artisan serve
```
