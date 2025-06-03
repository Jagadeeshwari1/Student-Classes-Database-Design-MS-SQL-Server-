# Student-Classes-Database-Design-MS-SQL-Server-

This repository contains the database design, SQL scripts, ER diagram, and presentation materials for a normalized student-classroom information system.

## Project Overview

This project involves the design and implementation of a relational database in **3rd Normal Form (3NF)** to capture and manage student information, dorm assignments, class schedules, and grades. All SQL code is written for **MS SQL Server**.

### Key Features

- Normalized table structure (3NF) for students, dorms, classes, enrollments, and majors.
- ER diagram illustrating table relationships and keys.
- DDL and DML SQL scripts:
  - Table creation (`CREATE TABLE`)
  - Primary and foreign key constraints
  - Data insertion (`INSERT INTO`) with at least 15 records per table
  - Views for common queries (students list, class enrollments, students by dorm)
- Sample queries and database views as per assignment requirements

---

## Repository Structure

```
├── README.md
├── student_classes_db.sql       # All DDL, DML, and view creation statements
├── ERD.png                     # Entity-Relationship Diagram (embed in Word doc)

```

---

## How to Use

1. **Clone the repository**
   ```
   git clone https://github.com/<Jagadeeshwari1>/Student-Classes-Database-Design-SQLServer.git
   ```

2. **Open SQL file**
   - Open `student_classes_db.sql` in SQL Server Management Studio (SSMS) or Azure Data Studio.

3. **Run all scripts**
   - Execute the entire file to create tables, relationships, insert data, and create views.

4. **Review ER Diagram**
   - See `ERD.png` for the visual database schema.

---
