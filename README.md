# 🎓 Student Management System – SQL Database

This project contains a PostgreSQL SQL script that creates a **Student Management System** database schema. It supports managing student, parent, teacher, class, and subject-related information in a school environment.

---

## 🛠️ Key Features

- ✅ Structured schema using `student_management` namespace
- ✅ User login table for system access control
- ✅ Full relational design connecting students, parents, teachers, classes, and subjects
- ✅ Support for subject allocation and tutor assignments
- ✅ Constraints and foreign keys to maintain data integrity

---

## 🗂️ Schema Overview

This SQL script creates the following tables:

| Table Name | Description |
|------------|-------------|
| `user_login` | Stores user login credentials and signup details |
| `parent_details` | Records father and mother details linked to students |
| `teachers` | Holds teacher information including contact and registration |
| `class_details` | Stores class info and assigns a class teacher |
| `student_details` | Contains student personal and academic details |
| `subject` | Stores subject name, year, and subject head |
| `subject_tutors` | Maps subjects to teachers and classes |

---

## 🧾 How to Use

1. **Open** a PostgreSQL client (e.g., pgAdmin, DBeaver, or terminal).
2. **Create a new database** (e.g., `student_db`).
3. **Run the SQL script** `student_management.sql`.
4. The `
