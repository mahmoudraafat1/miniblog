# Laravel Blog Assignment PHP Project

This project is an assignment for PHP and Laravel web framework. a basic blog with user authentication and CRUD functionality.

## Requirements
- PHP 7.4 or higher
- Laravel 8.x
- MySQL or MariaDB

## Installation


Navigate to the project directory

```bash
cd LaravelBlogAssignment
```

Install dependencies with Composer

```
composer install
```

Copy the `.env.example` file to `.env`

```bash
cp .env.example .env
```

Generate an application key

```
php artisan key:generate
```

Configure the database settings in the .env file:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_assignment
DB_USERNAME=root
DB_PASSWORD=
```

Run the migrations to create the necessary tables:

```
php artisan migrate
```

Start the built-in development server:

```
php artisan serve
```

## Features

- User authentication (register, login, and logout)
- **CRUD** functionality for blog posts
- Pagination for blog posts
- Search functionality for blog posts
- Admin panel to manage users and blog posts

## Conclusion

This project provides a basic foundation for a Laravel web application with user authentication and **CRUD** functionality. It can be used as a starting point for building a more complex web application.

