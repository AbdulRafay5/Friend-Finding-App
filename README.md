Introduction

A very Simple Social media web application built with laravel Jetstream and livewire.

The application is designed and tested to use conveniently without any issues.

Features

Built with Laravel 8
Jetstream (Livewire + blade stack)
Create posts
Like posts
Comment on posts
Delete posts
Delete Comments
On-time image uploads
Dynamic and Responsive Design
Compile and minify assets (200 kb resources)
Many more features....
Installation

Clone this repo using any method (https, ssh, gh cli)

Set the configuration file using the command cp .env.example .env

Install all required packages via composer. composer install

Set up Database configuration inside .env file.

Run the migration and seeder

php artisan setup
or

php artisan migrate --seed
Install all dependencies via npm or yarn and Compile all assets based on your deployment environment.
Yarn (recommended)

#Install all dependencies
yarn

#Development
yarn dev

#Production
yarn prod
Npm

#Install all dependencies
npm install

#Development
npm dev

#Production
npm prod
Create symbolic link
php artisan storage:link
Start the local server using the command
php artisan serve
Current Admin Credentials

You may use these credentials to log into your website. you can change these credentials shortly after logging in.

Email : admin@gmail.com
Password : password

Generating Dummy Data

Creates dummy data using faker library.

php artisan setup:dummy
or

php artisan db:seed --class="DummyDataSeeder"
Clear Temporary Files

All files uploaded from Create Post form is stored on storage/app/livewire-tmp folder. The following command cleana all Temporary Files from server.

php artisan clean:temp
Tests

php artisan test
Credits

@albinvar
License

MIT © Albin Varghese
