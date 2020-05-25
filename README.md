# bagisto-
assignment work for webkul.

## Tools use 
* composer 
* wampservar (mysql, php)
* bagisto
## Setps
1. Download wampserver.
2. Download bagisto ( paste in "wamp64/www").
3. Download composer.
4. Open CMD.
5. Move to bagisto directory.
6. ```composer install```
7. ``` copy .env.example .env ```
8. edit .env ( set env varaibles)
```
APP_ENV = Bagisto
APP_URL = http://localhost:8000
DB_HOST = 127.0.0.1
DB_DATEBASE = bagisto
DB_PASSWORD = 
BD_PORT = 3306
```
9. ```php atrisan key:generate```
10. ``` php artisan migrate ```
11. ``` php artisan db:seed```
12. ``` php artisan vendor:publish --all```
13. ```php artisan storage:link ```
14. ```composer dump_autoload ```
15. ```php artisan serve``` <br />
  http://127.0.0.1

