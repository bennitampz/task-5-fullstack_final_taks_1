# Final_Project_first

Final project Pada pelaksanaan program Virtual Internship Experience ini, teman-teman akan diberikan gambaran tentang bagaimana seorang Fullstack Developer bekerja di Investree.

## Daftar Isi

- [Tentang Proyek](#tentang-proyek)
- [Persyaratan Sistem](#persyaratan-sistem)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Fitur](#fitur)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)
- [Kontak](#kontak)

## Tentang Proyek

Recipe Hub yang dibuat menggunakan laravel dilengkapi dengan fitur-fitur baru seperti akun pengguna, pembuatan resep, dan detail resep yang mencakup daftar bahan dan instruksi. Antarmuka pengguna telah diperbaiki dengan desain yang lebih menarik, sehingga pengalaman pengguna menjadi lebih baik berkat penggunaan Javascript untuk pembaruan konten yang dinamis. Bagian belakang sistem juga telah ditingkatkan dengan menggunakan RESTful API dari Laravel untuk pengelolaan data yang lebih efisien. Selain itu, Laravel UI terus dikembangkan untuk mendukung otentikasi pengguna dan komponen antarmuka pengguna yang dasar.

## Persyaratan Sistem

- PHP versi 8.2 atau lebih tinggi
- Composer
- NPM atau Yarn
- Database Mysql
- Web Server XAMPP

## Instalasi

1. **Clone repositori**

    ```bash
    git clone https://github.com/bennitampz/final_taks_1
    ```

2. **Masuk ke direktori proyek**

    ```bash
    cd Final_Project_first
    ```

3. **Install dependensi Composer**

    ```bash
    composer install
    ```

4. **Install dependensi Node.js**

    ```bash
    npm install
    ```

    atau jika menggunakan Yarn:

    ```bash
    yarn
    ```

5. **Salin file konfigurasi**

    Salin file `.env.example` menjadi `.env` dan sesuaikan pengaturannya.

    ```bash
    cp .env.example .env
    ```

6. **Generate key aplikasi**

    ```bash
    php artisan key:generate
    ```

7. **Konfigurasi database**

    Sesuaikan pengaturan database di file `.env` Anda.

8. **Migrasi database**

   Atau import dari database yang telah disediakan di final_taks_1 dengan nama restapi_laravel_passport_benni.sql
    
    ```bash
    php artisan migrate
    ```

10. **Build aset frontend**

    Untuk environment pengembangan:

    ```bash
    npm run dev
    ```

    atau untuk production:

    ```bash
    npm run build
    ```

## Penggunaan

    Jalankan server pengembangan:

```bash
php artisan serve
```

    Buka http://localhost:8000 di browser Anda.


## Fitur
### jwt authentication menggunakan laravel passport
