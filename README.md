# Task 4: Data Analyst Internship - SQL for Student Database Management

## Objective
Utilize SQL to design, implement, and query a student database system using MySQL.

## What I Did
- **Created a comprehensive student database (`students_db`)**:
  - Tables: `students`, `subjects`, `enrollments`, `enrollment_items`
- **Populated the database with sample data** for students, subjects, enrollments, and enrollment items.
- **Developed SQL queries** for data retrieval and analysis, including:
  - Basic Queries: `SELECT`, `WHERE`, `ORDER BY`
  - Aggregations: `GROUP BY`, `SUM`, `AVG`, `COUNT`
  - Joins: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
  - Subqueries: Nested queries for dynamic filtering
  - Views: Simplified query management using `CREATE VIEW`
  - Null Handling: Used `COALESCE` to manage missing values

## Key Features of the Database
1. **Students Table**:
   - Stores student details such as `student_id`, `student_name`, and `email`.

2. **Subjects Table**:
   - Stores subject details like `subject_id`, `subject_name`, and `credits`.

3. **Enrollments Table**:
   - Tracks student enrollments with fields like `enrollment_id`, `student_id`, `enrollment_date`, and `total_credits`.

4. **Enrollment Items Table**:
   - Tracks subjects taken in each enrollment along with grades.

## Examples of Queries
- Retrieve all students sorted by name:
  ```sql
  SELECT * FROM students ORDER BY student_name;
