# landingpage
#landingpage >> README.md
# Prasyarat
*Akses ke mesin lokal Ubuntu 20.04 atau server pengembangan sebagai pengguna non-root dengan privilese sudo.
* Docker yang sudah terinstall
* Docker Compose

1 Buka terminal dan arahkan ke folder yang sudah di mengambil dari repositori
2 ketik docker-compose build app
3 setelah selesai ketik docker-compose up -d
4. ketik docker-compose ps untuk melihat hasil layanan yang berisi 3 kontainer app,database dan ngixnn
5. ketik docker-compose exec app ls -l untuk mengeksekusi perintal dalam kontainer
6. ketik docker-compose exec app composer install untuk menginstal composer laravel
7. ketik docker-compose exec app php artisan migrate untuk membuat table price_list
7. ketik docker-compose exec app php artisan db:seed untuk mengisi data table price_list
8. ketik docker-compose exec app php artisan key:generate
9. buka localhost:8000 untuk mengakses 
exit;

echo #landingpage
