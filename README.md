# KIET Student Academic Management System (Spring Boot REST API)

A lightweight Spring Boot RESTful API developed for **KIET Deemed to be University** to manage student academic records, search student profiles, filter toppers, and execute CRUD operations using an in-memory storage model.

---

## 🚀 Features

- **Full CRUD Operations**: Create, Read, Update, and Delete student records.
- **Search & Filter**: Search students by specific branch and academic year.
- **Academic Analytics**: Filter topper students based on a minimum CGPA threshold.
- **In-Memory Storage**: Uses Java collections (`List<Student>`) for quick, database-free execution.
- **Startup Diagnostics**: Custom `CommandLineRunner` with SLF4J logging for application initialization.

---

## 📁 Project Structure

```text
com.kiet.student
│
├── StudentApplication.java      # Main entry point & CommandLineRunner Logger
│
├── model
│   └── Student.java             # Student entity blueprint
│
└── controller
    └── StudentController.java   # REST API Endpoints mapping
