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

