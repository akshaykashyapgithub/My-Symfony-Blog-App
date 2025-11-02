Simple Symfony Blog Project CRUD

A simple blog application built with Symfony.
Allows users to register, login, create, edit, and delete posts. Designed with a modern, responsive UI.

## Features
  - User registration and login (with CSRF protection)
  - Logout functionality
  - Create, edit, delete posts (only by the author)
  - Posts display latest first
  - Responsive blog post design with clean card layout
  - External CSS for consistent styling
  - Only logged-in users can create posts

## Tech Stack
  - Backend: PHP, Symfony
  - Frontend: Twig templates, CSS (external stylesheet)
  - Database: MySQL / Doctrine ORM
    
## Installation
1.Clone the repository:
```
git clone https://github.com/akshaykashyapgithub/My-Symfony-Blog-App.git
cd symfony-blog
```
2.Install dependencies:
```
composer install
```
3.Configure database in .env:
```
DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"
```
4.Create database and run migrations:
```
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```
5. Run the Symfony server:
   ```
   symfony serve:start
```
6.Open your browser:
```http://127.0.0.1:8000
```

## Usage

- Register a new account
- Login
- Create posts
- Edit/Delete your own posts
- View all posts in a clean, responsive blog layout

## Screenshots
Login Page
![Login](Images/Login.png)
Register Page
![Register](Images/Register.png)
Dashboard
![Dashboard/All Posts](Images/Dashboard.png)
Show Post
![Show Post](Images/ShowPost.png)
Edit Post
![Edit Post](Images/EditPost.png)

