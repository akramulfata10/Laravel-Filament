## laravel filament
filament ini sangat asik digunakan dengan semua kemudahan yang di berikan oleh filament , filament mempercepat pengerjaan projek yang kita bangun atau pun yang kita buat, tapi ada beberapa kendala juga pada saat saya gunakan filament ini , yaa itu tidak terlepas dari kebiasaan kita pada saat kita ngoding , tapii saya menemukan error/bug yang sangat unik hanya permasalahannya hanya di extension yang saya pakai di visual studio code itu penyebab terjadi nya error/bug .


## Install fillament
Sebelum menggunakan filament admin, tentunya kita harus persiapkan terlebih dahulu project laravel kita.

kalau sudah selesai install projek lanjut tulisan perintah di bawah 

```md
composer require filament/filament:"^2.0"
```


Membuat filament user:
```md
php artisan make:filament-user
```

Setelah menjalankan perintah tersebut kamu akan diminta untuk memasukkan nama, email, dan password untuk akun yang dibuat.
```md
 Name:
 > Ruang Developer

 Email address:
 > mail@ruangdeveloper.com

 Password:
 >

Success! mail@ruangdeveloper.com may now log in at http://localhost/admin/login.
```
