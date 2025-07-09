# Nexa Reach V2

Tingkatkan bisnis sosial media anda secara mudah dan efektif.

## Fitur Unggulan

| Manajemen Sosial Media                                                                           | Pembuatan Konten Instagram                                                                                  | Pembuatan Konten TikTok                                                          |
| --------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Kelola semua akun media sosial kamu tanpa ribet. Dari penjadwalan kampanye hingga posting otomatis. | Buat konten Instagram yang menarik, kreatif, dan jago promosi. Tingkatkan visibilitas dan penjualan! | Buat konten TikTok yang fun, cepat viral, dan bikin audiens betah scroll! |

## Preview Aplikasi

<img width="1154" alt="one" src="https://github.com/user-attachments/assets/c1f6bd21-c540-4a8a-beee-d7a42a7e544a" />

<img width="1063" alt="two" src="https://github.com/user-attachments/assets/f4cb3c9c-f0a9-49eb-8b43-1d200bf2ff92" />

<img width="1080" alt="three" src="https://github.com/user-attachments/assets/25352b4c-0381-4728-b9e2-cb23944e85dd" />

## Cara Menjalankan (Local Setup)

Ikuti langkah-langkah berikut untuk menjalankan Nexa Reach secara lokal:

### 1. Clone Repository

```bash
git clone https://github.com/username/nexa-reach.git
cd nexa-reach
```

### 2. Install Dependencies

```bash
composer install
npm install
```

### 3. Konfigurasi Environment

```bash
cp .env.example .env
```

> Sesuaikan konfigurasi database di file `.env` sesuai dengan database lokal Anda.

### 4. Generate Application Key

```bash
php artisan key:generate
```

### 5. Migrasi dan Storage

```bash
php artisan migrate
php artisan storage:link
```

### 6. Clear Cache (Optional but Recommended)

```bash
php artisan cache:clear
```

### 7. Jalankan Aplikasi

```bash
php artisan serve
npm run dev
```

## Kontak

Untuk pertanyaan, hubungi kami melalui:

- Email: nexareach@gmail.com