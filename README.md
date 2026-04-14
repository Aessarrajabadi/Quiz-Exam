# 🧠 Online Quiz Exam System

An advanced **Online Quiz Exam System** built using **HTML, CSS, JavaScript, PHP, and MySQL**.
This project allows students to take quizzes online and admins to manage questions, users, and results efficiently.

---

## 🚀 Features

### 👨‍🎓 Student Panel

* User Registration & Login
* Attempt quizzes
* Timer-based exams
* Instant result display

### 🛠️ Admin Panel

* Secure Admin Login
* Add/Edit/Delete Questions
* Manage Users
* View Results & Reports
* Control Quiz Time & Settings

---

## 💻 Technologies Used

* Frontend: HTML, CSS, JavaScript
* Backend: PHP
* Database: MySQL
* Hosting: InfinityFree / XAMPP / cPanel

---

## 📂 Project Structure

```
online-quiz-exam/
│
├── admin/
├── student/
├── database/
├── assets/
├── css/
├── js/
├── index.php
├── login.php
├── register.php
└── README.md
```

---

## ⚙️ Installation Guide

1. Clone the repository:

```
git clone https://github.com/Aessarrajabadi/online-quiz-exam.git
```

2. Move project to server:

* XAMPP → `htdocs`
* InfinityFree → `htdocs`

3. Import database:

* Open phpMyAdmin
* Create database (e.g. `quiz_db`)
* Import `.sql` file

4. Update DB connection:

```
$conn = mysqli_connect("localhost", "root", "", "quiz_db");
```

5. Run project:

```
http://localhost/online-quiz-exam
```

---

## 🔐 Admin Login (Default)

```
Username: admin
Password: admin123
```

---

## 📸 Screenshots

* Login Page
* Dashboard
* Quiz Interface
* Result Page

(Add images here)

---

## 🌐 Live Demo
 https://quiz-exam.infinityfreeapp.com/

---

## 📜 License

This project is open-source and free to use for educational purposes.

---

## ⭐ Support

If you like this project:

* ⭐ Star this repository
* 🍴 Fork it
* 📢 Share with others

---
