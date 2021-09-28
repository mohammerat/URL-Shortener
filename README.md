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

Third create app key by running this command on terminal:

```
php artisan key:generate
```

Fourth and last, create your database and change configuration in .env file

```
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret
```

Enjoy it on [http://localhost:8000](http://localhost:8000):

```
php -S localhost:8000 -t public
```

## API Documentation

Documentation for API can be found on this url: [Postman API](https://google.com).

## License

The Lumen framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
