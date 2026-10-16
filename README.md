# PRACTICAL 09 — Laravel Forms, Validation and Database

Student: Samuel Fernando Chuma
Register Number: 19
Practical: 09

## Runtime
- PHP 8.0.30 (C:\xampp\php\php.exe)
- Laravel 9.52.22
- SQLite

## Run in VS Code
```cmd
cd /d "D:\Samuel Chuma\PRACTICAL_09"
composer install
copy .env.example .env
C:\xampp\php\php.exe artisan key:generate
C:\xampp\php\php.exe artisan migrate:fresh --seed
C:\xampp\php\php.exe artisan route:list
C:\xampp\php\php.exe artisan serve
```
Open http://127.0.0.1:8000

No XAMPP Apache or MySQL is required because the practical uses SQLite.
