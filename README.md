<h1 align="center" color:"#3498DB" >SUBUR.IN</h1>



## Cara Menggunakan

1.pastiin udah install xampp. kalo bisa yang terbaru biar phpnya yg terbaru juga
2.install composer juga. cari di google bisa cara install composer, ga begitu ruwet kok
3.download file zipnya di github
4.extract file, terus extract lagi pokok sampe kebuka folder laravel
5.folder laravel taruh di D biar enak nnti ngaksesnya
6.buka cmd
7.terus buka filenya dari cmd (kan tadi foldenya ditaruh di D tinggal ketik di cmd:  cd /d d:\laravel))
8.buka xampp hidupin apache sama mySQL
9.buat baru database, kasih nama "subur.in" tanpa tanda petik
10buka cmd lagi
11.ketik composer install terus enter (tunggu lama)
12.ketik php artisan key:generate terus enter
13.ketik php artisan route:clear terus enter
14.ketik php artisan config:clear terus enter
15.ketik php artisan cache:clear terus enter
16k.etik php artisan migrate terus enter
17.ketik php artisan db:seed --class=RoleSeeder terus enter
18.ketik php artisan db:seed --class=UserSeeder terus enter
19.ketik php artisan serve terus enter
20.buka chrome (bebas pake firefox, explorer juga bisa) terus buka http://127.0.0.1:8000/

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).


<p align="center"><img src="https://media1.tenor.com/images/e98a5d3d8a924d685e88361e93c5172a/tenor.gif?itemid=15792714" width="400"></p>
<p align="center">

