### Requirements

1. PHP 7.2
2. Laravel 7.0

### Getting Started

Clone the project repository by running the command below

`git@github.com:dnezle94/Laravel_vue.git`

`cd` into the project directory and run:

`composer install`

Duplicate `.env.example` and rename it `.env`

Import database provided

`db/test.sql`

Then run

`php artisan migrate --seed`

Then run

`npm install`

Then run

`php artisan serve`

### Usage

Register a user or login using admin@argon.com and secret and start testing the preset (make sure to run the migrations and seeders for these credentials to be available).
