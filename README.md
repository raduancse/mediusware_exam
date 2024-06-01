# Banking System

This is a Laravel-based Mediusware banking system that supports deposit and withdrawal operations for two types of users: Individual and Business.

## Features

- User registration and login
- Deposit and withdrawal transactions
- Different fee structures for Individual and Business accounts
- Free withdrawal conditions for Individual accounts
- Adjustable fee rates for Business accounts based on withdrawal amounts

## Requirements

- PHP >= 8.1.0
- Composer
- MySQL

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/raduancse/mediusware_exam.git
   cd mediusware_exam


composer install
npm install
npm run dev

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan serve


API Endpoints
User Management
Create a new user:

POST /users
Request body:

json data
{
  "name": "Raduan Islam",
  "email": "raduan@gmail.com",
  "password": "secret123",
  "account_type": "Individual"
}
Login user:

POST /login
Request body:

json data

{
  "email": "raduan@gmail.com",
  "password": "secret123"
}
