# Artisan create database command

This is a way to create a Laravel application's data base using a command similar to how you would run `rails db:create` in Ruby on Rails.

# Usage (once-off in a project)
Run the following command:

```zsh
php artisan make:command DatabaseCreate
```

This will create a file in the following location: app/Console/Commands/DatabaseCreate.php

Edit the contents of this file with the contents of `DatabaseCreate.php` in this repository.

Run the following command to create the database:

```zsh
php artisan db:create
```
