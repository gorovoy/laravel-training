## Laravel training via Gorovoy
Run server: 




$ php -S localhost:8000 -t public

or

$ php artisan serve


# run MySql
$ docker run --detach --name some-mariadb --env MARIADB_USER=example-user --env MARIADB_PASSWORD=my_cool_secret --env MARIADB_ROOT_PASSWORD=my-secret-pw  mariadb:latest

Get container ip for access

$ docker inspect some-mariadb

Find                     "IPAddress": "172.17.0.2",

MARIADB_ROOT_PASSWORD=my-secret-pw


$ docker exec -it some-mariadb bash

$ mariadb -u root -p my-secret-pw
$ create database laravel;
$ php artisan migrate:install

$ http://127.0.0.1:8000/telescope/requests

create db laravel db

# Vite
****
https://laravel.com/docs/10.x/vite

#### Run the Vite development server...
npm run dev

#### Build and version the assets for production...
npm run build

### Production install composer:
composer install

### DEV Production install composer:
composer install --no-dev

