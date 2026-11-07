# Bankly v2

Bankly v2 is a modern banking management web application built with PHP, MySQL, HTML, CSS, and JavaScript. It provides a clean dashboard experience for managing customers, accounts, transactions, and communication between users and the bank.

The project is designed to help users navigate a digital banking platform with sections such as login, registration, account management, client overview, and financial operations.

## Overview

This application aims to simulate a financial management system where bank staff or administrators can:

- manage customers and their profiles,
- track bank accounts,
- monitor financial transactions,
- communicate through a built-in chat interface,
- manage a dashboard and visual data overview,
- switch language and dark mode support in the interface.

## Features

- User login and registration flow
- Dashboard landing page
- Customer management area
- Account management pages
- Transaction overview and operations
- Chat module for communication
- Modern responsive design
- Dark mode UI toggle
- Multi-language interface support
- MySQL database integration

## Tech Stack

- PHP
- MySQL / MariaDB
- JavaScript
- CSS
- HTML
- Font Awesome and Boxicons for icons

## Project Structure

```text
Bankly-v2/
│
├── connect/
│   └── db_connexion.php
├── fichiers_B.D/
│   └── MySQL database files
├── imgs/
│   └── assets and images
├── js/
│   ├── filter.js
│   ├── language.js
│   ├── main.js
│   ├── menu&dark_mode.js
│   └── settings.js
├── accounts.php
├── chat.php
├── customers.php
├── deposit.php
├── details.php
├── home.php
├── index.php
├── login.php
├── main.css
├── modify.php
├── register.php
├── tran_direct.php
├── transactions.php
├── README.md
└── ...
```

## Database Configuration

The application connects to a MySQL database using the following configuration in `connect/db_connexion.php`:

```php
$connexion = mysqli_connect('localhost', 'root', '', 'bankly_v2');
```

Before running the project, make sure:

1. MySQL is installed and running.
2. A database named `bankly_v2` exists.
3. Your local credentials match your development environment.
4. The tables required by the application are present.

If your database is stored in the project folder under `fichiers_B.D`, you may need to import or restore it into your local MySQL instance.

## Installation

### 1. Clone the project

```bash
git clone <repository-url>
cd Bankly-v2
```

### 2. Set up a local server

Use a local PHP development environment such as:

- XAMPP
- WAMP
- MAMP
- Laragon

Place the project folder in your local server root, usually:

- `C:/xampp/htdocs/Bankly-v2`
- or the equivalent for your server setup

### 3. Start Apache and MySQL

Launch your local server environment and ensure Apache and MySQL are running.

### 4. Configure the database

Create the `bankly_v2` database in MySQL and import the project data if needed.

### 5. Run the app

Open your browser and visit:

```text
http://localhost/Bankly-v2/
```

## Usage

Once the app is running, users can:

- log in to access the bank dashboard,
- register new accounts,
- view customer and account information,
- handle transactions,
- switch the site language and theme,
- navigate between the application pages.

## Notes

This project is a front-end and back-end PHP banking prototype and is suitable for learning, demo, or academic use. The application structure is simple and intentionally easy to understand, making it a good project for improving PHP and MySQL skills.

## License

This project is for educational and demonstration purposes. Please check with the project owner before using it in production or commercial environments.

## Author

Bankly v2 project
