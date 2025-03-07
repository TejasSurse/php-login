# PHP Login & Signup System

This is a simple login and signup system built using PHP, MySQL, HTML, CSS (Tailwind), and JavaScript. It allows users to register and log in securely.

## 📌 Features
- User Registration with hashed passwords
- Secure Login with password verification
- Tailwind CSS for modern styling
- Single PHP file (`auth.php`) to handle both login and signup
- Database integration using MySQLi

## 🛠️ Technologies Used
- PHP
- MySQL
- HTML, CSS (Tailwind)
- JavaScript

## 📂 Project Structure
/php-login/ │── login.html # Login Page │── signup.html # Signup Page │── auth.php # PHP Script for authentication │── style.css # Tailwind CSS Styles │── README.md # Project Documentation 


## 🚀 Setup Instructions

### 1️⃣ Install PHP & MySQL
Ensure you have PHP and MySQL installed on your system.

### 2️⃣ Database Setup
Run the following SQL commands to create the database and users table:

```sql
CREATE DATABASE login_db;
USE login_db;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL,
    password VARCHAR(255) NOT NULL
);


3️⃣ Configure PHP
Make sure the mysqli extension is enabled in php.ini.

4️⃣ Start the Server
Run the following command in the project directory:

sh
Copy
Edit
php -S localhost:8000
Now, open http://localhost:8000/signup.html to register and http://localhost:8000/login.html to log in.

📞 Support
For any issues, feel free to contact me.

Happy Coding! 🚀

vbnet
Copy
Edit

Let me know if you need any modifications! 😊






