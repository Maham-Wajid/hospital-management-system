# 🏥 Hospital Management System (C# Desktop)

A Windows-based hospital management system built with C# (WinForms). It streamlines hospital operations by managing patients, doctors, nurses, lab staff, pharmacists, and receptionists in a single desktop application.

---

## 🎯 Purpose

This project provides a unified solution for hospital administration, allowing staff to manage medical records, staff accounts, and operational workflows efficiently.

---

## ✅ Key Features

- **Admin Dashboard** for complete system control
- **Patient Management** (add, update, view)
- **Doctor Management** (add, update, view)
- **Nurse Management** (add, update, view)
- **Laboratory Management** (add, update, view)
- **Pharmacy Management** (add, update, view)
- **Receptionist Management** (add, update, view)
- **Role-based modules** for different staff types
- **Password reset** for users
- **SQL Database integration** (via HMS_System.sql)

---

## 🛠️ Technologies Used

- C# (WinForms)
- .NET Framework
- SQL Server (database schema in HMS_System.sql)

---

## 📂 Project Structure

```
hospital-management-system/
├── HMS Interface.sln
├── HMS_System.sql
├── HMS Interface/
│   ├── *.cs (Forms and logic)
│   ├── *.Designer.cs
│   └── *.resx
└── packages/
```

---

## ▶️ How to Run

### 1. Open the Solution
- Open `HMS Interface.sln` in **Visual Studio**.

### 2. Setup the Database
- Open SQL Server Management Studio (SSMS).
- Run `HMS_System.sql` to create the database and tables.

### 3. Configure Connection String
- In the project, update the SQL connection string (usually in `App.config` or the code-behind file).
- Ensure it matches your SQL Server instance.

### 4. Build & Run
- Build the solution.
- Run the application using Visual Studio.

---

## 🧩 Problem It Solves

Hospitals often manage data across multiple departments with separate tools. This system centralizes management for:

- **Patient records**
- **Staff records**
- **Department coordination**
- **Operational efficiency**

---

## 📌 Notes

- This is a **Windows-only** desktop application.
- Database setup is required before first run.
- The project is intended for academic and learning purposes.

---

## 📝 License

This project is provided for learning and demonstration purposes.
