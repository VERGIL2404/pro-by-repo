# 📋 Task Management System

A simple yet functional Task Management System built using **PHP**, **MySQL**, and **XAMPP**. This system supports Admin and Employee roles, enabling easy task assignment, tracking, and progress monitoring with built-in notifications.

---

## 🚀 Features

- **User Role Management**
  - Two types of users: **Admin** and **Employee**
  - Role-based access control for actions and pages

- **Task Management**
  - Admin can create, update, delete, and assign tasks
  - Employees can view and update the status of their tasks

- **Authentication & Authorization**
  - Secure login and session management
  - Access restrictions based on user roles

- **Notifications**
  - Users are notified of new task assignments or status changes

- **Task Categorization & Filtering**
  - Filter tasks by:
    - Status (Pending, In Progress, Completed)
    - Priority (Low, Medium, High)
    - Due Date

- **Deadline Tracking**
  - View upcoming and overdue tasks
  - Highlight tasks based on their urgency

---

## 🛠 Requirements

Before you begin, ensure you have the following installed:

- [XAMPP](https://www.apachefriends.org/)
  - Apache
  - MySQL
  - PHP (7.4 or higher)
- MySQL 5.7 or higher
- Web browser (for accessing the UI)

---

## 📦 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task-management-system.git
   ```

2. **Start XAMPP**
   - Run Apache and MySQL from the XAMPP Control Panel

3. **Import the Database**
   - Open `phpMyAdmin` at `http://localhost/phpmyadmin`
   - Create a new database named: `task_management_db`
   - Import the SQL file (`/database/task_management_db.sql`)

4. **Configure Database Connection**
   - Open `DB_connection.php` and update your DB credentials if necessary:
     ```php
     $db = new PDO("mysql:host=localhost;dbname=task_management_db", "root", "");
     ```

5. **Access the Application**
   - Visit `http://localhost/Employee-Task-Management-System` in your browser

---

