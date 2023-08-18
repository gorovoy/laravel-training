## Laravel training via Gorovoy


# run MySql
$ docker run --detach --name some-mariadb --env MARIADB_USER=example-user --env MARIADB_PASSWORD=my_cool_secret --env MARIADB_ROOT_PASSWORD=my-secret-pw  mariadb:latest

Get container ip for access

$ docker inspect some-mariadb

Find                     "IPAddress": "172.17.0.2",

php artisan serve
