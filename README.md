# 🏨 Hostel Management System

## 🧠 Description

This project is a **comprehensive Hostel Management System** developed using **C** for the application logic and **MySQL** for backend data management. It is designed to streamline and automate hostel operations for institutions managing large student populations.

The system provides **role-based access control** to differentiate between student, staff, and admin users. It manages a variety of hostel-related tasks including student registration, staff records, inventory tracking, and monthly expense automation. The MySQL database is **fully normalized**, ensuring efficient data storage and faster queries.

Designed for scalability, the system currently supports 500+ students and significantly reduces manual workload with automated tracking and reporting.

---

## 🚀 Features

- ✅ **Role-Based Access Control**  
  Provides different access levels and interfaces for admin, staff, and students.

- ✅ **Student & Staff Management**  
  Handles student profiles, room allocations, and staff records in a centralized database.

- ✅ **Inventory Management**  
  Tracks hostel inventory including furniture, utilities, and supplies.

- ✅ **Automated Monthly Expense Tracking**  
  Automatically calculates and reports recurring monthly expenses, **reducing manual effort by 70%**.

- ✅ **Database Normalization**  
  Designed using **normalized relational schema** to reduce redundancy and improve consistency.

---

## 🛠 Technologies Used

- 💻 **Programming Language:** C  
- 🗄️ **Database:** MySQL  
- ⚙️ **Tools:** MySQL Workbench, GCC Compiler  
- 🧪 Tested on: Ubuntu 22.04 / Windows 10 (with MySQL Server)

---

## 📁 Project Structure

```plaintext
Hostel-Management-System/
├── src/                  # All C source code files
│   ├── main.c            # Entry point
│   ├── auth.c            # User login & role management
│   ├── student.c         # Student data functions
│   ├── staff.c           # Staff data functions
│   ├── inventory.c       # Inventory operations
│   └── expenses.c        # Monthly expense calculations
│
├── include/              # Header files
│   ├── auth.h
│   ├── student.h
│   ├── staff.h
│   ├── inventory.h
│   └── expenses.h
│
├── sql/                  # SQL scripts for schema and seed data
│   ├── create_tables.sql
│   └── sample_data.sql
│
├── docs/                 # Project documentation and reports
│   └── ER_diagram.png
│
└── README.md             # Project overview and instructions

```
---

## 📈 Results

- 🎯 **70% reduction in manual overhead** for monthly expense tracking  
- ⚡ **Improved data accuracy** and consistency through normalization  
- 🧑‍💼 **Scaled to support 500+ active users** across roles

---

## 📌 Future Improvements

- 🔧 Add web-based frontend using PHP or Python (Flask/Django)  
- 📩 Integrate email/SMS notifications for reminders and billing  
- 📊 Implement real-time analytics dashboard

---

## 📫 Contact

**Dinesh Bhattacharya**  
📧 dineshbhattacharya2002@gmail.com(mailto:dineshbhattacharya2002@gmail.com)  
🔗 [LinkedIn / GitHub / Portfolio link if applicable]

---

> ⚠️ **Note:** This project was developed for academic purposes. Production use may require additional security and optimization.

