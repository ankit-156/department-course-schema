# -department-course-schema

This repository contains SQL scripts to design and interact with a normalized academic database involving departments and courses.

## 📂 Files

- `department_course.sql` - Complete SQL script containing:
  - Table creation normalized to 3NF
  - Sample data insertion
  - Subquery to retrieve departments offering more than 2 courses
  - DCL command to grant SELECT permission

## 🧩 Problem Breakdown

### ✅ Part A - Create Tables (3NF)
- `Departments(dept_id, dept_name)`
- `Courses(course_id, course_name, dept_id)` with FK referencing `Departments`

### ✅ Part B - Insert Data
- 5 Departments
- 15 Courses (3 per department)

### ✅ Part C - Subquery
- Retrieves departments offering more than 2 courses

### ✅ Part D - Access Control
- Grants `SELECT` access on `Courses` to `viewer_user`

## 📜 Sample Query Output


