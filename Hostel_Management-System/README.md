# 🏨 Hostel Management System
A web-based Hostel Management System built with **PHP** and **MySQL**. It helps manage room allocations, student registrations, payments, and admin tasks in an organized way.
---

## 🎯 Features
### 👨‍🎓 Student Panel
- Register/Login  
- Apply for hostel rooms
- View allocated room details
- Check payment status
### 🧑‍💼 Admin Panel
- Admin login dashboard
- Manage rooms (add/update/delete)
- View and approve student applications
- Allocate rooms
- Manage payment and billing
---
<img width="460" height="380" alt="image" src="https://github.com/user-attachments/assets/08f738f8-1263-4d12-a0ab-83f53f431243" />
## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP
- **Database**: MySQL
- **Authentication**: Session-based login system

---
## 📂 Folder Structure

---
## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/hostel-management-system.git
cd hostel-management-system
/admin
/student
/includes
/css
/js
/db.php
index.php
---
## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/hostel-management-system.git
cd hostel-management-system
2. Import the Database
Open phpMyAdmin or MySQL CLI.

Create a new database:

sql
Copy
Edit
CREATE DATABASE hostel_db;
Import the hostel_db.sql file from the repo.

3. Configure Database Connection
Update your database config file (db.php or config.php):

php
Copy
Edit
$host = "localhost";
$user = "root";
$password = "";
$db = "hostel_db";
4. Run the Project
Place the project folder in your web server's root directory (htdocs if using XAMPP).

Start Apache and MySQL using XAMPP.
Open your browser and go to:
perl
Copy
Edit
http://localhost/hostel-management-system/
🧑‍💻 Author
Prithi B
GitHub
LinkedIn
💡 Suggestions or Contributions?
Feel free to open an issue or submit a pull request to improve the system.

⭐ Show Your Support
If you found this project helpful, please ⭐ the repository and share it with your friends!
