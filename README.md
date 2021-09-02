# laravel-api
laravel api

Для использования Laravel API не нужно команда (php artisan server) у него есть (.htaccess) настройка. Можно узнать URL адресы двумя способами.  
1. Console с командой php artisan route:list.    
2. API можно использования у routes api файла следующий адреса 
GET запрос для index (/posts)       
POST запрос для store (/post)       
GET запрос для show (/posts/{id})       
PUT запрос для update (/posts/{id})       
DELETE запрос для destroy (/posts/{id})       
