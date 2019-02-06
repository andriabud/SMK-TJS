TUTORIAL PEMBUATAN APLIKASI SMK TUNAS JAKASAMPURNA DENGAN MENGGUNAKAN LARAVEL
 
<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## DOWNLOAD & INSTALL LARAVEL

Langkah pertama yang harus disiapkan yaitu : 

- [Download XAMPP Versi terbaru](https://www.apachefriends.org/download.html).
- [Download Composser](https://getcomposer.org/Composer-Setup.exe).
- [Template AdminLTE 2.3.11.](https://codeload.github.com/almasaeed2010/AdminLTE/zip/v2.3.11).

Langkah kedua setelah sudah melakukan isntalasi, kemudian membuat folder baru didalam htdocs dengan nama "belajarLaravel" (C:\xampp\htdocs). Lalu klik kanan disembarang tempat didalam folder "belajarLaravel".
pilih menu gitbash here, kemudian ketik didalam cpmmand : composer create-project --prefer-dist laravel/laravel belajarLaravel"5.7"


## Membuat CRUD dengan Template AdminLTE

Langkah Selanjutnya untuk pembuatan aplikasi ini saya mengikuti turorial berikut : 

- **[Tutorial Laravel 5.7-Integrete AdminLTE & Make Simple CRUD](https://drive.google.com/file/d/1AmexPu9OEQEz1cHfvVOHHIx3-47ml-Jm/view)**
- **[Tighten Co.](https://tighten.co)**
- **[Turorial Laravel - Eloquent Relationship](https://drive.google.com/file/d/1WpHAgdv4zVrgA-nV1u64Mbl31C65LyVC/view)**
- **[Tutorial - Login](https://drive.google.com/file/d/1WpHAgdv4zVrgA-nV1u64Mbl31C65LyVC/view)**
- **[Tutorial Laravel - UploadFile](https://drive.google.com/file/d/1-qb34ta4QJFzmekmiUAK84CzW6Cy7IXR/view)**

## Tutorial Push Folder dengan mengunakan GIT
- [Download GITHUB](https://git-scm.com/)
- [Membuat Akun GITHUB](https://github.com/)
- Membuat Repositories pada akun yang sudah dibuat

Setelah sudah melakukan instalasi masuk kedalam folder "belajarLaravel" lalu klik kanan pada folder yang akan di push, pilih gitbashhere.

1. Lakukan konfigurasi :
git config --global user.name "masukkan username github anda" [enter]
git config --global user.email "masukkan email github anda" [enter]

2. Inisialisasi direktori local sebagai Repository Git.
git init [enter]

3. Menambahkan semua isi dari project yang telah dibuat (belajarLaravel).
git add .

4. git commit -m "isi", digunakan sebagai penanda jika ada file yang baru di ubah, contohnya
git commit -m "first commit"

5. Menambahkan remote didalam repository lokal
git remote add origin remote repository URL [enter]
Note: remote repository URL didapatkan di repository kita,
dibagian Clone or download maka akan muncul alamat url kemudian copy-paste ke git.

6. Push dari lokal ke github
git push origin master --force [enter]
