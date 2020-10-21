## Hacktoberfest 2020

Hacktoberfest is open to everyone in our global community! Four quality pull requests must be submitted to public GitHub repositories. You can sign up anytime between October 1 and October 31. [Read more](https://hacktoberfest.digitalocean.com/)

### How to Contribute / Cara mengikuti Hacktoberfest atau berkontribusi:

- Register your github account [here](https://hacktoberfest.digitalocean.com/)
- Fork this Repository (Fork Repositori ini. Ada di pojok kanan atas)
- Clone your Repository (Clone Repositori kamu yang berasal dari fork repositori ini)
- Add your name in contributor.md (Tambahkan namamu pada file contributor.md)
- Push (Push. bisa gunakan git push atau langung dari github.com)
- Pull Request (Lakukan pull request ke repositori asli)
- Done (Selesai)

We'll approve your pull request as soon as we don't run into any problems.

![Admin](https://shareku.net/admin.png)
![Login](https://shareku.net/screencapture-apiq-host-mobile_login-php-1602340283880.png)

## Tentang OnyetCBT

OnyetCBT adalah Aplikasi opensource yang diperuntukan untuk instansi seperti sekolah, madrasah, ataupun yang lain, OnyetCBT ini biasa digunakan untuk PTS/PAS/USBN/SIMULASI UNBK. Aplikasi ini bersumber dari [CandyCBT](https://cbtcandy.com) yang dikembangkan kembali guna keperluan lebih lanjut. Aplikasi ini masih bersifat Open Source dengan lisensi MIT atau harap jangan menghilangkan nama yang sudah berkontribusi dalam pembuatan dan pengembangan aplikasi ini.

Fitur OnyetCBT:

- [Responsive - Bootstrap 3](https://getbootstrap.com/docs/3.3).
- [Pengelolaan Mudah](https://shareku.net).
- [3 Jenjang Pendidikan](https://shareku.net).
- [Role : Admin, Guru, Pengawas, Proktor, Siswa](https://shareku.net).
- [Pengumuman](https://shareku.net)
- [E-Learning, Tugas dan Komentar](https://shareku.net)
- [Absen Harian](https://shareku.net)
- [Meeting Room](https://jitsi.github.io/handbook/docs/devops-guide/devops-guide-start)
- [Aplikasi Android - Harap kontak kami](mailto:onyet@shareku.net)

## 🥳 Demo Aplikasi

- [Web Aplikasi](https://demo.shareku.net/cbt)
- [Aplikasi Android](https://demo.shareku.net/cbt/aplikasi_demo.apk)

<p align="left">Username dan Password Administrator :</p>
<p align="left">Username : admin, Password: adminpassword</p><br>
Note : <b>Kalian masuk dulu sebagai Admin, da buat siswa atau guru atau pengawas dan baru login di aplikasi.</b>

## Requirement

- PHP Version : PHP 7.x, Rekomendasi PHP 7.4
- PHP Imagick
- Jitsi Server: Optional
- MariaDB Version : 10.x

## Admin Login

```bash
http://yourdomainroot/mobile_login.php

user		: admin
password	: adminpassword
```

## Kerentanan Keamanan

Jika anda menemui kendala dan lainnya silahkan buat issue dan saya akan segera meresponnya.

## Proses Pemasangan

### XAMPP

- Unduh [XAMPP](https://www.apachefriends.org/download.html)
- Lakukan [pemasangan XAMPP](https://www.wikihow.com/Install-the-Apache-Web-Server-on-a-Windows-PC)
- Unduh ZIP file atau Clone Repositori ini
- Masuk pada direktori/ folder XAMPP yang telah terpasang dan letakan semua file dalam repositori ini ke dalam folder ``htdocs``
- Jalankan XAMPP dan akse alamat XAMPP, biasanya ``http://localhost/_install.php``

### LARAGON

- Unduh [Laragon](https://laragon.org/download/index.html)
- Pasang atau ekstrak Laragon
- Unduh ZIP file atau Clone Repositori ini
- Masuk pada direktori/ folder Laragon yang telah terpasang dan letakan semua file dalam repositori ini ke dalam folder ``www``
- Jalankan Laragon dan akse alamat Laragon, biasanya ``http://localhost/_install.php``

### Apache Linux Server

- Siapkan semua package yang dibutuhkan : Apache/Apache2, MariaDB/MySQL, PHP 7.X, PHP7.X-FPM, PHP-Imagick dan kebutuhan webserver lainnya.
- Masuk ke Linux server menggunakan ssh/tls/filezilla
- Unduh ZIP file atau Clone Repositori ini
- Masuk pada dan unggah hasil clone repositori ini ke direktori/ folder ``/var/www/html``
- Mulai ulang / restart Apache/Apache2 dan akses melalui alamat web yang terhubung ke server tersebut.

Akses halaman instalasi atau pemasangan.
```bash
http://yourdomainroot/_install.php
```

## Aplikasi Android atau IOS

Untuk anda yang menginginkan aplikasi Android atau IOS build manual bisa hubungi kami langsung :
- Email : onyet@shareku.net
- Whatsapp : +6282221874400
- Telegram : +6282221874400

Pada vesi android ada beberapa fitur tambahan seperti :
- Melihat Dokumen MS.office, PDF, Gambar secara langsung
- Mencegah perekaman atau penangkapan layar

## Kontribusi

Semua kontribusi perbaikan atau ide yang anda ingin tuangkan atau kembangkan silahkan lakukan pullrequest.

## Lisensi

OnyetCBT adalah perangkat lunak bersumber terbuka yang dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).
