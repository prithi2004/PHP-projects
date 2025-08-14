# 🏥 Doctor Appointment Booking System

A web-based Doctor Appointment Booking System developed using **PHP** and **MySQL**, allowing patients to book appointments, doctors to manage schedules, and admins to handle system settings.

---
## ✅ Features

### 👤 Patient Panel
- Register/Login
- Book appointments
- View booking history
- Cancel or reschedule appointments

### 👨‍⚕️ Doctor Panel
- Login to dashboard
- View upcoming appointments
- Update appointment status
- Manage availability

### 🛠️ Admin Panel
- Manage doctors and patients
- View all bookings
- Manage specializations
- System reports and controls

---

<img width="488" height="200" alt="image" src="https://github.com/user-attachments/assets/35b37272-9748-40c6-b6aa-37a8500493ce" />


## 🔧 Technologies Used

- 🧱 **Frontend**: HTML, CSS, Bootstrap
- ⚙️ **Backend**: PHP
- 🗃️ **Database**: MySQL
- 🔐 Session-based authentication

---

## ⚙️ How to Set Up Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/doctor-appointment-system.git
cd doctor-appointment-system

2. Import the Database
Open phpMyAdmin or any MySQL client.

Create a new database:

sql
Copy
Edit
CREATE DATABASE doctor_appointment;
Import the doctor_appointment.sql file from the project.

3. Configure Database Connection
Open the config.php or db.php file and update the following:

php
Copy
Edit
$host = "localhost";
$user = "root";
$password = "";
$database = "doctor_appointment";
4. Start the Server
Place the project folder inside htdocs (if using XAMPP).

Start Apache and MySQL from the XAMPP control panel.

Open browser and go to:

perl
Copy
Edit
http://localhost/doctor-appointment-system/
🗂️ Folder Structure
bash
Copy
Edit
/admin
/doctor
/patient
/includes
/css
/js
config.php
index.php
🙋‍♀️ Author
Prithi B
GitHub
LinkedIn
⭐ Show Your Support
If this project helped you, please ⭐ the repo and share it with others!
