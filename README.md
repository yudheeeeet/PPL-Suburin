
<h1 align="center" color:"#3498DB" >SUBUR.IN</h1>

<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Cara Menggunakan

1. pastiin udah install xampp. kalo bisa yang terbaru biar phpnya yg terbaru juga
2. install composer juga. cari di google bisa cara install composer, ga begitu ruwet kok
3. download file zipnya di github
4. extract file, terus extract lagi pokok sampe kebuka folder laravel
5. folder laravel taruh di D biar gampang nnti ngaksesnya
6. buka CMD
7. terus buka filenya dari cmd (kan tadi foldenya ditaruh di D tinggal ketik di cmd:  cd /d d:\laravel))
8. terus buka xampp hidupin apache sm mySQL
9. klik admin di mySQL
10. buat baru database, kasih nama "subur.in" tanpa tanda petik
11. buka cmd lagi
12. ketik composer install terus enter (tunggu lama)
13. ketik php artisan key:generate terus enter
14. ketik php artisan route:clear terus enter
15. ketik php artisan config:clear terus enter
16. ketik php artisan cache:clear terus enter
17. ketik php artisan migrate terus enter
18. ketik php artisan db:seed --class=RoleSeeder terus enter
19. ketik php artisan db:seed --class=UserSeeder terus enter
20. ketik php artisan serve terus enter
21. buka chrome (bebas pake firefox, explorer juga bisa) terus buka http://127.0.0.1:8000/

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).


<p align="center">

