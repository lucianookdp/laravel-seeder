# Laravel Seeder Playground

A small Laravel project for testing database seeders that populate fake
data for simulations and tests.

## Requirements

- PHP 8.1+
- Composer

## Setup

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

## License

All rights reserved.
