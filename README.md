# Mini URL Shortener

Mini URL Shortener build based on Lumen micro-framework using Eloquent, Caching and mysql database

## Getting Started

For start clone repository, install all dependenies:

```
composer install
```

Second rename .env.example file:

```
cp .env.example .env
```

Third create app key and jwt secret by running this command on terminal:

```
php artisan key:generate
php artisan jwt:secret
```

Fourth and last, create your database and change configuration in .env file

```
DB_DATABASE=YOUR_DB_NAME
DB_USERNAME=YOUR_DB_USERNAME
DB_PASSWORD=YOUR_DB_PASSWORD
```

Enjoy it on [http://localhost:8000](http://localhost:8000):

```
php -S localhost:8000 -t public
```

## License

The Lumen framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
