
# Laravel Single Sign On Demo
This is one way of learning Laravel, that is coding it. Make it works as you want. I want this application to act as central authentication provider. Like you use social login to log user in your application. This application will behave like that authenticate user and notify calling application of the result.

- Provides local email/password for this application itself, this done by the framework out of the box.
- Provide mobile (frontend) authentication using token based.
- Acts as single sign on server for other applications, may be made by Laravel itself or others.

# Requirements
 - PHP 7.4 | 8.0
 - Laravel 8.0
 - MySQL or MariaDB Database Server (tested)
 - Composer 2.0
 
# Packages Used
- [Laravel Breeze](https://github.com/laravel/breeze) as authentication scaffolding.
- [Laravel Passport](https://github.com/laravel/passport), the main package here.
- Cors handling using [CORS Middleware for Laravel](https://github.com/fruitcake/laravel-cors).
- Made consistent API response using [REST API Response Builder for Laravel](https://github.com/MarcinOrlowski/laravel-api-response-builder).


## License

The Application is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
