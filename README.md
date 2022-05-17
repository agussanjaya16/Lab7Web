## TUGAS PEMOGRAMAN

| Nama    | Agus sanjaya  |
| ------  | ------------- |
| NIM     | 312010060     |
| Kelas   | TI.20.A1      |
| Matkul  | Pemograman Web|

## Langkah-langkah Praktikum 
# Persiapan <br>
Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP
terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7.
Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu
XAMPP.<br>
# Install XAMPP <br>
Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi
portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan
direktorinya (misal: d:\xampp). <br>
![Lab7Web](img/download%20xampp.png)<br>
# Konfigurasi Web Server <br>
• Konfigurasi Apache
Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul
yang diaktifkan, lokasi document root, dll.
Lokasi file: \xampp\apache\conf\httpd.conf
• Konfigrasi PHP
Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.
Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload, error
reporting, dll.
Lokasi file: \xampp\php\php.ini
• Konfigrasi MySql
Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.
Lokasi file: \xampp\mysql\bin\my.ini <br>
# Menjalankan Web Server <br>
Untuk menjalankan web server dari menu XAMPP Control.<br>
![Lab7Web](img/xampp%20awal.png) <br>
• Uji coba apakah server sudah berkerja dengan baik
http://127.0.0.1 atau http://localhost
Tampil halaman utama XAMPP jika server sudah berkerja dengan baik.
• Dokumen Website
Semua file website tempatkan di direktori: \xampp\htdocs\
• Database MySQL
Direktori: \xampp\mysql\
Manajemen database: http://localhost/phpmyadmin <br>
# Memulai PHP <br>
Buat folder lab7_php_dasar pada root directory web server (d:\xampp\htdocs) <br>
![Lab7Web](img/memulai%20php.png) <br>
Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: <br>
![Lab7Web](img/xampp.png) <br>
# PHP Dasar <br>
Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut. <br>
![Lab7Web](img/kode%20php%20dasar.png) <br>
Kemudian untuk mengakses hasilnya melalui URL:
http://localhost/LAB7_PHP_DASAR/php_dasar.php <br>
![Lab7Web](img/PHP%20DASAR.png) <br>
# Variable PHP 
Menambahkan variable pada program. <br>
![Lab7Web](img/kode%20variabel.png)<br>
dan ini hasilnya. <br>
![Lab7Web](img/menambahkan%20variabel.png) <br>
# Predefine Variable $_GET  <br>