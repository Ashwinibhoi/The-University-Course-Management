# 🎓 University Course Management System

A MySQL-based database management project designed to organize and manage university departments, students, courses, instructors, and student enrollments.

---

## 📌 Project Overview

The **University Course Management System** is a relational database project developed using **MySQL 8.0** and **MySQL Workbench**.

The project demonstrates how SQL can be used to create and manage a university database, maintain relationships between tables, retrieve information, and perform data analysis using basic and advanced SQL queries.

It covers essential database operations, including CRUD operations, joins, subqueries, aggregate functions, date functions, string functions, and window functions.

## 🎯 Project Objectives

- Design a structured relational database for a university.
- Manage student, course, department, and instructor records.
- Establish relationships using primary keys and foreign keys.
- Perform Create, Read, Update, and Delete operations.
- Retrieve specific information using SQL queries.
- Analyze course enrollments and department-wise student counts.
- Practice advanced SQL concepts for database analysis.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| MySQL 8.0 | Database management |
| MySQL Workbench | SQL development and execution |
| SQL | Database creation, manipulation, and querying |

## 🗂️ Database Details

**Database Name:** `UniversityCourseManagement`

The project contains five interconnected tables.

| Table | Description |
|---|---|
| `Departments` | Stores university department information. |
| `Students` | Stores student details and enrollment dates. |
| `Courses` | Stores course names, department IDs, and credits. |
| `Instructors` | Stores instructor details, departments, and salaries. |
| `Enrollments` | Connects students with their enrolled courses. |

## 🔗 Database Relationships

The database uses primary keys, foreign keys, and unique constraints to maintain data integrity.

- **Departments → Courses:** One department can offer multiple courses.
- **Departments → Instructors:** One department can have multiple instructors.
- **Students → Enrollments:** A student can have multiple enrollment records.
- **Courses → Enrollments:** A course can have multiple enrolled students.
- **Students ↔ Courses:** Students and courses have a many-to-many relationship through the `Enrollments` table.

## 📊 Sample Dataset

The SQL script inserts sample data into all five tables.

| Table | Number of Records |
|---|---:|
| Departments | 4 |
| Students | 12 |
| Courses | 8 |
| Instructors | 5 |
| Enrollments | 20 |
| **Total** | **49** |

Sample departments include Computer Science, Mathematics, Business Administration, and Physics.

Sample courses include Introduction to SQL, Data Structures, Database Management, Calculus I, Statistics, and Advanced SQL.

## 💻 SQL Concepts Covered

This project implements 16 SQL query tasks.

| No. | Query / Operation | SQL Concepts |
|---:|---|---|
| 1 | CRUD operations and data retrieval | INSERT, SELECT, UPDATE, DELETE |
| 2 | Find students enrolled after 2022 | WHERE |
| 3 | Retrieve Mathematics courses, limited to five | JOIN, ORDER BY, LIMIT |
| 4 | Find courses with more than five enrolled students | COUNT, GROUP BY, HAVING |
| 5 | Find students taking both specified courses | JOIN, GROUP BY, HAVING |
| 6 | Find students taking either specified course | DISTINCT, IN |
| 7 | Calculate average course credits | AVG |
| 8 | Find maximum Computer Science instructor salary | MAX, JOIN |
| 9 | Count students in each department | LEFT JOIN, COUNT |
| 10 | Retrieve students with their corresponding courses | INNER JOIN |
| 11 | Retrieve all students and their available courses | LEFT JOIN |
| 12 | Find students enrolled in courses with more than ten students | Subquery |
| 13 | Extract the student enrollment year | YEAR |
| 14 | Combine instructor first and last names | CONCAT |
| 15 | Calculate running enrollment totals | Window Functions |
| 16 | Classify students as Senior or Junior | CASE, DATE_SUB, CURDATE |

## ✨ Key Features

- Structured relational database design.
- Primary keys and foreign key relationships.
- Unique email addresses and department names.
- Course credit validation using a CHECK constraint.
- CRUD operations and record management.
- Filtering, sorting, and limiting query results.
- Aggregate functions for statistical calculations.
- INNER JOIN and LEFT JOIN for related data.
- Subqueries for advanced filtering.
- Date and string manipulation functions.
- Running totals using window functions.
- Conditional classification using CASE expressions.

## ⚙️ How to Run the Project

Follow these steps to execute the project in MySQL Workbench.

**Step 1:** Install MySQL Server 8.0 and MySQL Workbench.

**Step 2:** Open MySQL Workbench and connect to your database server.

**Step 3:** Create a new SQL query tab.

**Step 4:** Copy and paste the complete SQL project code into the editor.

**Step 5:** Click the lightning bolt **Execute** button to run the script.

**Step 6:** Refresh the Schemas panel and open `UniversityCourseManagement`.

**Step 7:** Expand the Tables section to view the five tables.

**Step 8:** Execute individual SELECT queries and inspect their results in the output grid.

> **Important:** The script drops and recreates the project tables when rerun. Existing records in those tables will be deleted and replaced by the sample data. Back up any data you want to keep before executing it again.

## 📈 Expected Outcomes

After successful execution, you can:

- View student and instructor information.
- Retrieve courses offered by specific departments.
- Analyze enrollment patterns.
- Calculate average course credits and maximum instructor salary.
- Count students across departments and courses.
- Identify students enrolled in multiple courses.
- Generate running totals of enrollments.
- Categorize students based on their enrollment dates.

## 🎓 Learning Outcomes

Through this project, learners gain practical experience in:

- Relational database design and normalization concepts.
- SQL data definition and manipulation.
- Primary keys, foreign keys, and constraints.
- Aggregate functions and grouping.
- Joins and nested queries.
- Date and string functions.
- Window functions and conditional logic.
- Database development using MySQL Workbench.

## 🚀 Future Enhancements

The project can be extended with the following features:

- Complete CRUD operations for every table.
- Student grades and examination management.
- Course prerequisites and semester management.
- Views for frequently used reports.
- Stored procedures and triggers.
- Transaction management.
- A web-based interface for students and administrators.

## 🏁 Conclusion

The **University Course Management System** is a practical SQL project that demonstrates how relational databases can be designed and used to manage university information efficiently.

By implementing 16 SQL query tasks, the project provides hands-on experience with essential and advanced SQL concepts and builds a strong foundation for future database management projects.

---

### 📁 Project Information

- **Project Name:** University Course Management System
- **Database:** MySQL 8.0
- **SQL Editor:** MySQL Workbench
- **Language:** SQL
- **Tables:** 5
- **Query Tasks:** 16
- **Project Type:** Database Management System
- **Status:** Completed

