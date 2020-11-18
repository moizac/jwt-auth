# Tugas Praktikum
## Moh. Izza Auladina L./185150707111009

## Dokumentasi Project JWT-Auth

>### 1. Membuat projek Lumen dengan nama “jwt-app” dan konfigurasi .env dengan database baru

>### 2. Instalasi package JWT dengan menjalankan perintah berikut untuk menginstal package JWT untuk laravel atau lumen.

>### 3. Buka bootstrap/app.php, lalu aktivasi fitur Eloquent, Facades, Middleware Auth, dan daftarkan package JWT. 

>### 4. Menjalankan perintah berikut untuk men-generate  secret key untuk JWT yang disimpan pada .env.

>### 5. Membuat migration dan model User

>### 6. Membuat folder baru pada root projek dengan nama “config”, lalu buat file dengan nama auth.php 

>### 7. Membuat file controller dengan nama UserController.php lalu membuat route untuk memanggil fungsi tersebut

>### 8. Memuka UserController dan menambahkan fungsi login dan logout dan menambahkan route pada group auth

>### 9. Membuka UserController dan tambahkan fungsi me untuk melihat pengguna yang sedang login dan fungsi index list pengguna dan juga menambahkan route pada group auth

>### 10. Menambahkan constructor pada UserController untuk membatasi akses pengguna yang belum login. Arti dari middleware tersebut adalah middleware akan dijalankan pada semua fungsi UserController kecuali fungsi login dan register.