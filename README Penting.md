Ekstrak file Final Project
Masuk Ke file Final Project
Pindahkan File ecommerce-youtube-master ke htdocs
selanjutnya buka cmd didalam folder diatas

lalu ketikkan perintah dibawah ini
composer install
php artisan key:generate
php artisan migrate:fresh --seed (noted : pastikan sudah membuat database)
php artisan storage:link

rubah localhost di .env menjadi localhost anda

Login akun
email = admin@example.com
password = 123
