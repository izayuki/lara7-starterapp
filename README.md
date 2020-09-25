## About Laravel 7 Starter APP

Laravel 7 Starter App & admin LTE 3
Starter app sederhana menggunakan Laravel 7 dan Admin LTE 3

Fitur :
- Login
- Roles and permission
- Cetak PDF
- Export Excel
- Import dari excel ke database
- Contoh CRUD sederhana

Cara Install :
1. Buat database dengan nama lara7_start
2. Masuk ke direktori aplikasi dan jalankan composer
composer install
3. Migrate table
php artisan migrate
4. Seed table
php artisan db:seed
5. jalankan lokal develompent server
php artisan serve

Server Requirements :
1. PHP 7.2+
2. MySQL
3. Composer 1.10.8+

## Demo

- <a href="http://demo.isengoding.my.id" target="blank">Demo</a>

## Installasi
- Download repository dan ekstrak atau clone repository
	```sh
	$ git clone https://github.com/sainstech/lara7-starterapp.git
	```
- Masuk ke direktori aplikasi dan jalankan composer
	```sh
	$ cd lara7-starterapp
	$ composer install
	```
 - Copy file .env.example menjadi .env
	```sh
	$ cp .env.example .env
	```
- Generate key application
	```sh
	$ php artisan key:generate
	```
- Buat Database
- Edit database name, database username dan database password di file .env
    ```sh
	DB_DATABASE=your_db.
    DB_USERNAME=your_mysql_username.
    DB_PASSWORD=your_mysql_password.
	```
- Migrate table
	```sh
	$ php artisan migrate
	```
- Seed table
	```sh
	$ php artisan db:seed
	```
- Jalankan lokal development server
    ```sh
	$ php artisan serve
	```
- Buka di browser http://localhost:8000
- Login
    ```sh
	Username :  admin@admin.com
    Password :  password
	```
 ## Author
Sains Technology – oviyanto@gmail.com

[https://github.com/sainstech/](https://github.com/sainstech/)

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- <a href="https://www.sainstech.com" target="_blank">sainstech.com</a>.

## Sample Aplikasi
![alt tag](https://i.ibb.co/GPVPFnv/demo-lara7-lte.jpg)
