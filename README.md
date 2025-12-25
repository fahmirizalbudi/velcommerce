<div align="center">
<a href="https://github.com/fahmirizalbudi/velcommerce" target="blank">
<img src="https://raw.githubusercontent.com/JjagoKoding/icon/935739b7cbab876990e47eabbc9294f4306c81f0/velcommerce.svg" width="400" alt="Logo" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</a>

<br />
<br />

![](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br />

## 🛒 Velcommerce

Velcommerce is an online e-commerce created to make online stores easier. Built with Laravel as the web application and MySQL as relational database. Key features include:

## 🖼️ Preview

![](velcommerce.png)

## ✨ Features

- **🛍️ Product Management:** Complete CRUD for products, categories, and inventory.
- **🛒 Shopping Cart:** Dynamic cart system with session management.
- **🔐 Authentication:** Secure customer login, registration, and admin access.
- **💳 Order Processing:** Order tracking, history, and status management.
- **🔍 Search & Filter:** Easy product discovery features.

## 👩‍💻 Tech Stack

- **Laravel**: A PHP web application framework with expressive, elegant syntax.
- **MySQL**: Relational database management system for storing product and user data.
- **Blade Templates**: Laravel's powerful templating engine.

## 📦 Getting Started

To get a local copy of this project up and running, follow these steps.

### 🚀 Prerequisites

- **PHP** (v8.2 or higher) & **Composer**
- **MySQL** (or another supported SQL database).

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/fahmirizalbudi/velcommerce.git
   cd velcommerce
   ```

2. **Install dependencies:**

   ```bash
   composer install
   cp .env .env.example
   php artisan key:generate
   ```

3. **Run migration:**

   ```bash
   php artisan migrate
   ```

4. **Start the development server:**

   ```bash
   php artisan serve
   ```

## 📖 Usage

### ✔ Running the Application

- **Website development:** `php artisan serve`.

> Open [http://localhost:8000](http://localhost:8000) to view it in the browser.

## 📜 License

All rights reserved. This project is for educational purposes only and cannot be used or distributed without permission.
