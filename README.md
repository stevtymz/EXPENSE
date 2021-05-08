# Laravel 8 project for managing expenses and income

It was deveolped using  laravel quickadmin panel tool.

Features:
- CRUDs for income/expenses and their categories
- Monthly reports by income/expenses and their categories
- Multi-tenancy: Ability to register new user who sees only their categories/entries (admin sees all).
- Based on [CoreUI Free Theme](https://coreui.io) (Bootstrap 4)


## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL and login with default credentials __admin@admin.com__ - __password__


