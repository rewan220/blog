# Laravel Blog
A simple blog for demonstration purpose. Based on Laravel 7.

# Installation
Clone the repository-
Then cd into the folder with this command-
```sh
cd blog
```
Then do a composer install
```sh
composer install
```
Then create a environment file using this command-
```sh
cp .env.example .env
```
Then edit .env file with appropriate credential for your database server. Just edit these two parameter(DB_USERNAME, DB_PASSWORD).

Then create a database named "blog" and then do a database migration using this command-
```sh
php artisan migrate
```
generate application key, which will be used for password hashing, session and cookie encryption etc.
```sh
php artisan key:generate
```
Run ``` npm install ``` to install all front end dependencies
Run ``` php artisan storage:link ``` to link storage to public file


