##Instalation instructions:

composer install
cp .env.example .env

configure database in .env -> 
DB_DATABASE={your database name}
DB_USERNAME={your database username}
DB_PASSWORD={your database password}

php artisan key:generate

php artisan migrate --seed
php artisan serve