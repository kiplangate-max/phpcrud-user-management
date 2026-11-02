# PHP CRUD User Management System

A web-based user management application developed using PHP and MySQL. It allows users to create, view, update, and delete user records.

## Application Preview

The application homepage displays registered users and provides options to view, edit, and delete records.

![PHP CRUD Application](screenshots/application-records.png)

## Database Preview

User information is stored in a MySQL database named `phpcrud`, using the `tblusers` table.

![Database Records](screenshots/database-records.png)

## Features

- Add new user records.
- View all registered users.
- View individual user details.
- Edit existing user information.
- Delete user records.
- Input validation and prepared SQL statements.

## Technologies Used

- PHP
- MySQL
- HTML
- CSS
- XAMPP

## Project Structure

```text
phpcrud/
├── screenshots/
│   ├── application-records.png
│   └── database-records.png
├── dbconnection.php
├── functions.php
├── index.php
├── insert.php
├── read.php
├── edit.php
├── delete.php
├── database.sql
├── style.css
└── README.md
```

## Installation and Setup

### Requirements

- XAMPP
- Web browser

### 1. Project Setup

Place the project folder inside:

`C:\xampp\htdocs\`

### 2. Start XAMPP

Start Apache and MySQL from the XAMPP Control Panel.

### 3. Database