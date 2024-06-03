## ✨ Laravel Point of Sale


## 🚀 Database

    navicat and xampp install
    creat new database in navicat mysql

    database name: sale_main
    character set: utf8
    collation: utf8_general_ci

    run mysql using xampp

## 🚀 How to Use

1.  **Clone Repository or Download**

    ```bash
    $ git clone https://github.com/putrairawan992/laravel-sales-v2.git
    ```
1. **Setup**
    ```bash
    # Go into the repository
    $ cd laravel_sales

    # Install dependencies
    $ composer install
    $ composer update

    # Open with your text editor
    $ code .
    ```
1. **.ENV**

    Rename or copy the `.env.example` file to `.env`
    ```bash
    # Generate app key
    $ cp .env.example .env
    $ php artisan key:generate
    ```

1. **Setup Database**

    Setup your database credentials in your `.env` file.

1. **Seed Database**
    ```bash
    $ php artisan:migrate:fresh --seed

    # Note: If showing an error, please try to rerun this command.
    ```
1. **Create Storage Link**

    ```bash
    $ php artisan storage:link
    ```
1. **Run Server**

    ```bash
    $ php artisan serve
    ```
1. **Login**

    Try login with username: `admin` and password: `password`

## 🚀 Config

1. **Create Storage Link**

    ```bash
    $ php artisan storage:link
    ```
1. **Run Server**

    ```bash
    $ php artisan serve
    ```
1. **Login**

    Try login with username: `admin` and password: `password`


    or username: `user` and password: `password`