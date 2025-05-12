# SPP Online SMK Jambi IX Lurah 2

Aplikasi web berbasis Laravel untuk mengelola sistem pembayaran SPP online di SMK Jambi IX Lurah 2. Proyek ini dirancang untuk membantu siswa, orang tua, dan staf sekolah dalam mencatat, memantau, dan melakukan transaksi pembayaran SPP secara efisien.

> ⚠️ Proyek ini masih dalam tahap pengembangan.

---

## ⚙️ Instalasi

Ikuti langkah-langkah berikut untuk menjalankan aplikasi ini di komputer lokal Anda:

### 1. Clone Repositori

Pertama, clone repositori ini ke mesin lokal Anda:

```bash
git clone https://github.com/rickyylaa/spp-online-smk-jambi-ix-lurah-2.git
cd spp-online-smk-jambi-ix-lurah-2
```

### 2. Install Dependensi

Install semua dependensi PHP dan JavaScript yang diperlukan:

```bash
composer install
npm install && npm run dev
```

### 3. Salin File .env

Salin file konfigurasi .env.example ke .env:

```bash
cp .env.example .env
```

### 4. Generate App Key

Generate aplikasi key untuk keamanan:

```bash
php artisan key:generate
```

### 5. Konfigurasi .env

Buka file .env dan sesuaikan konfigurasi database dan lainnya sesuai lingkungan Anda, misalnya:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=spp_sekolah
DB_USERNAME=root
DB_PASSWORD=
```

### 6. Migrate dan Seeder

Jalankan perintah berikut untuk melakukan migrasi ulang dan langsung mengeksekusi seeder:

```bash
php artisan migrate
php artisan migrate:fresh --seed
```

### 7. Jalankan Server

Jalankan server lokal Laravel:

```bash
php artisan serve
```

Aplikasi akan berjalan di http://localhost:8000.
