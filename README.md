# fbsaler

## Installation
- Clone repository
```
$ git clone https://github.com/sourcecde/fbsaler.git
```
- Run in your terminal
```
$ composer install
$ php artisan key:generate
```
- Setup database connection in .env file
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=fbsaler
DB_USERNAME=root
DB_PASSWORD=
```

- Migrate tables and seed with demo data
```
$ php artisan migrate --seed
```
- Run the server
```
$ php artisan serve
```

- Access URL
```
http://localhost:8000/admin/login

