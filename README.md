laravel 6.x
configurar la base de datos, el nombre de usuario y la contraseña de la base de datos en el archivo .env

busque "extension = pdo_mysql" en el archivo php.ini y elimine el comentario

## comandos:
composer install
php artisan migrate
php artisan serve

## rutas
/ - crear registro en la base de datos
/all - ver registros de la base de datos
