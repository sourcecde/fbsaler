# fbsaler

## Installation
- Clone repository
```
$ git clone https://github.com/updivision/estarter-ecommerce-for-laravel.git
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

- Access it on
```
http://localhost:8000/admin/login
```

## Setup
In order to use the shop and be able to add products, you must have a minimum configuration:
- Create at least one category;
- Create at least one attribute for at least one of these types: text, textarea, date, dropdown, multiple select, media;
- Create at least one attribute set;
- Create a tax (eg. VAT).
