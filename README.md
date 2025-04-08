# 🎓 Attendance Management System

A simple C++ console-based application to efficiently manage student attendance. This system provides separate functionalities for students and administrators, allowing for attendance tracking, record management, and student registration.

---

## 🚀 Features

### 👨‍🎓 Student Panel
- 🔐 **Secure Login** using username and password.
- ✅ **Mark Attendance** for the current date.
- 📊 **View Attendance Count** to track personal attendance.

### 🛠️ Admin Panel
- 🔐 **Admin Login** with secure credentials.
- ➕ **Register New Students** to the system.
- 🗑️ **Delete Students** by roll number or remove all records.
- 📋 **View Registered Students** with roll numbers and names.
- 🔍 **Check Attendance Count** by individual roll number.
- 📈 **View All Attendance Records** in a summarized format.

---

## ⚙️ Dependencies

This project is developed using standard C++ libraries:
- `<iostream>`
- `<fstream>`
- `<string>`
- `<cstring>`

🔧 **Requirements:**
- A C++ compiler (e.g., g++, clang++)
- A terminal or command-line environment

---

## 📂 Project Structure

```
📁 AttendanceManagementSystem
├── main.cpp              // Main application file
├── students.txt          // Stores student login info and records
└── attendance_log.txt    // Stores attendance records
```

---

## 💡 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pmritunjay1/Attendance-Management-System.git
   ```

2. **Compile the Code**:
   ```bash
   g++ main.cpp -o attendance
   ```

3. **Run the Application**:
   ```bash
   ./attendance
   ```

---

## 🤝 Contributing

Contributions are welcome! 🚀  
Feel free to:
- Report issues
- Suggest new features
- Submit pull requests with improvements
