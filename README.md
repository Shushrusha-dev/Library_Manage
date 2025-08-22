# 📚 Library Management System

A robust desktop application built with **Java (NetBeans IDE)** and **MySQL**, designed to simplify and automate library operations such as book issuance, returns, and student record management.



## ✨ Key Features

- 🔐 Secure Login – Authenticated access for system users  
- 👨‍🎓 Student Registration – Add and manage student profiles  
- 📘 Book Entry – Catalog new books with detailed metadata  
- 📕 Issue Book – Assign books to students with due dates  
- 📗 Return Book – Process and track returned books  
- 📊 Issue/Return Records – View transaction history in tabular format  
- 🖥️ User-Friendly GUI – Built with Java Swing for smooth interaction  
- 🗃️ MySQL Integration – Reliable backend for data storage  



## 🛠️ Tech Stack

- **Frontend**: Java Swing  
- **Backend**: Java (NetBeans IDE)  
- **Database**: MySQL  
- **Connectivity**: JDBC  



## 🖼️ Module Overview

### 🔐 Login Interface  
Secure login screen with username/password fields and a padlock icon.  
![Login Interface](screenshots/login.jpeg)

### 🏠 Main Dashboard  
Six core modules: New Student, New Book, Statistics, Issue Book, Return Book, Exit.  
![Main Dashboard](screenshots/dashboard.jpeg)

### 🧑‍🎓 New Student Registration  
Fields: Student ID, Name, Father's Name  
Dropdowns: Course, Branch  
Buttons: Save, Close  
![New Student](screenshots/new_student.png)

### 📚 New Book Entry  
Fields: Book ID, Name, Publisher, Price, Year  
Buttons: Save, Close  
![New Book](screenshots/new_book.png)

### 📕 Issue Book  
Fields: Book ID, Student ID, Issue Date, Due Date  
Buttons: Issue, Close  
![Issue Book](screenshots/issue_book.png)

### 📗 Return Book  
Search by Book ID and Student ID  
Buttons: Return, Close  
![Return Book](screenshots/return_book.png)

### 📊 Issue & Return Details  
Tabular display of issued and returned books  
Sortable columns and Close button  
![Issue & Return Details](screenshots/issue_return_details.png)


## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Shushrusha-dev/Library_Manage.git
   ```

2. Open the project in **NetBeans IDE**

3. Create a MySQL database:
   ```sql
   CREATE DATABASE library_db;
   ```

4. Import the required tables (SQL file not included—create manually or request from the author)

5. Update `DBConnection.java` with your MySQL credentials

6. Build and run the project from NetBeans



## 📌 Notes

This project is extendable with features like:
- Admin authentication  
- Fine calculation for overdue books  
- Book availability tracking  
- Email notifications  

## 🧠 Conclusion: Where This System Excels

This Library Management System is most beneficial for:

- **Schools & Colleges** – Streamlines book circulation and student tracking  
- **Community Libraries** – Offers a low-cost, easy-to-use digital solution  
- **Internship & Academic Projects** – Demonstrates full-stack Java development  
- **Skill Building** – Reinforces concepts in GUI design, database integration, and modular programming  

Its clean architecture and intuitive interface make it an ideal foundation for more advanced systems. Whether you're showcasing your skills or managing a real-world library, this project delivers practical value and learning.
