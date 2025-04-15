# Instalasi_Laravel
🚀 Dokumentasi Instalasi Laravel Menggunakan Laragon dan Shell di VS Code
Dokumentasi ini menjelaskan langkah-langkah menginstal Laravel menggunakan Laragon dan terminal di VS Code, mulai dari mengaktifkan Apache dan MySQL hingga menjalankan Laravel di browser lokal.

📌 Langkah 1: Menyalakan Apache dan MySQL di Laragon
Buka aplikasi Laragon.

Klik tombol Start pada modul Apache dan MySQL.

Pastikan statusnya berubah menjadi hijau yang menandakan sudah aktif.

📌 Langkah 2: Buka Terminal di VS Code
Pastikan VS Code sudah terpasang di komputer kamu.

Buka proyek Laravel kamu di VS Code.

Tekan Ctrl + Shift + ~ untuk membuka terminal bawaan VS Code.

📌 Langkah 3: Arahkan ke Direktori www di Laragon
Jika kamu belum berada di folder proyek kamu, arahkan terminal ke folder www di mana Laragon menyimpan proyek-proyeknya.

bash
Salin
Edit
cd C:\laragon\www
📌 Langkah 4: Cek Apakah Composer Sudah Terinstal
Ketik perintah berikut di terminal untuk mengecek versi Composer:

bash
Salin
Edit
composer --version
Jika Composer sudah terinstal, akan muncul versinya seperti:

yaml
Salin
Edit
Composer version 2.7.1 2024-03-15 10:00:00
Jika Composer belum terinstal, silakan download dan install Composer terlebih dahulu dari website resmi berikut:

🔗 https://getcomposer.org/download/

📌 Langkah 5: Install Laravel
Gunakan perintah berikut untuk mengunduh dan menginstal Laravel di dalam folder proyek kamu (gantilah levaral dengan nama folder yang kamu inginkan):

bash
Salin
Edit
composer create-project --prefer-dist laravel/laravel levaral
levaral adalah nama folder proyek Laravel kamu. Gantilah sesuai kebutuhan.

Tunggu hingga proses instalasi selesai. Ini akan memakan waktu tergantung kecepatan internet.

📌 Langkah 6: Masuk ke Folder Proyek Laravel
Setelah instalasi selesai, masuk ke folder Laravel:

bash
Salin
Edit
cd levaral
📌 Langkah 7: Jalankan Laravel
Jalankan perintah berikut untuk menjalankan Laravel:

bash
Salin
Edit
php artisan serve
Jika berhasil, akan muncul URL seperti:

nginx
Salin
Edit
Starting Laravel development server: http://127.0.0.1:8000
📌 Langkah 8: Buka Laravel di Browser
Buka browser dan akses URL berikut:

cpp
Salin
Edit
http://127.0.0.1:8000
Jika berhasil, akan tampil halaman default Laravel.

🎉 Instalasi Berhasil!
