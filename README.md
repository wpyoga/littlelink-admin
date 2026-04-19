## _⚙️ LittleLink Admin_

LittleLink Admin is an admin panel for [littlelink] that provides you a website similar [linktree].

## 📑 Features

- creating a link page with more than 20 buttons
- raising important links on the page
- counting clicks
- managing users and pages and links
- and ...

## ✨ Demo

[home] / [panel]

## 🔨 Install

```sh
composer create-project khzg/littlelink-admin
```

- edit .env file

DB_DATABASE=YOUR_DATABASE_NAME

DB_USERNAME=YOUR_USERNAME

DB_PASSWORD=YOUR_PASSWORD

APP_NAME="Littlelink admin"

```sh
cd littlelink-admin
php artisan migrate
php artisan db:seed 
(or commands below)
php artisan db:seed --class="AdminSeeder"
php artisan db:seed --class="PageSeeder"
php artisan db:seed --class="ButtonSeeder"
php artisan serve
```

- login:

email: admin@admin.com

password: 12345678

## 💞 Partners

- [littlelink]
- [laravel]
- [panel template]

## Fork notes

- Reverted to last good commit, with AGPL license
- Removed bitcoin donate wallet, since it's not mine
- Feel free to build upon this fork

   [littlelink]: https://github.com/sethcottle/littlelink
   [linktree]: https://linktr.ee
   [home]: demo-home.png
   [panel]: demo-panel.png
   [laravel]: https://github.com/laravel/laravel
   [panel template]: https://colorlib.com/wp/bootstrap-sidebar
