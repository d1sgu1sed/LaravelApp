# Для запуска на Ubuntu надо запустить
## 1
``` composer install ```
## 2
``` npm install ```
## 3 
При возникновении ошибок при **npm install** - ``` npm audit fix ```
## 4
``` cp .env.example .env ```
## 5
Указать название своей базы данных, пользователя и пароль в **.env**
## 6 
``` php artisan key:generate ```
## 7
``` php artisan migrate ```
## 8
``` npm run dev ``` - не выключать для запуска приложения
## 9
``` php artisan serve ```