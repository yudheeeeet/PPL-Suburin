pastiin udah install xampp. kalo bisa yang terbaru biar phpnya yg terbaru juga
install composer juga. cari di google bisa cara install composer, ga begitu ruwet kok
download file zipnya di github
extract file, terus extract lagi pokok sampe kebuka folder laravel
folder laravel taruh di D biar enak nnti ngaksesnya
buka cmd
terus buka filenya dari cmd (kan tadi foldenya ditaruh di D tinggal ketik di cmd:  cd /d d:\laravel))
buka xampp hidupin apache sama mySQL
buat baru database, kasih nama "subur.in" tanpa tanda petik
buka cmd lagi
ketik composer install terus enter (tunggu lama)
ketik php artisan key:generate terus enter
ketik php artisan route:clear terus enter
ketik php artisan config:clear terus enter
ketik php artisan cache:clear terus enter
ketik php artisan migrate terus enter
ketik php artisan db:seed --class=RoleSeeder terus enter
ketik php artisan db:seed --class=UserSeeder terus enter
ketik php artisan serve terus enter
buka chrome (bebas pake firefox, explorer juga bisa) terus buka http://127.0.0.1:8000/
