# SQL_ASSIGMENT_2 - Employee Database Management

## 📌 Project Overview

This project demonstrates the use of **MySQL** to manage and analyze employee information using SQL queries. It includes operations on employee, department, and location tables, along with data retrieval, filtering, sorting, aggregation, and table joins.

The assignment focuses on developing practical SQL skills for database management and data analysis.

## 🎯 Objectives

- Retrieve and filter employee records using `SELECT` and `WHERE`.
- Insert employee, department, and location data.
- Modify table structures using `ALTER TABLE`.
- Update employee designations using `UPDATE`.
- Perform aggregations using `SUM()`, `MIN()`, `AVG()`, `MAX()`, and `COUNT()`.
- Group and filter grouped results using `GROUP BY` and `HAVING`.
- Combine tables using `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN`.
- Sort and limit query results using `ORDER BY` and `LIMIT`.

## 🗂️ Database Structure

The project uses three main tables:

| Table | Description |
|---|---|
| `employees` | Stores employee details, including name, gender, age, hire date, designation, department, location, and salary. |
| `departments` | Stores department IDs and department names. |
| `location` | Stores location IDs and location names. |

## 🛠️ Technologies Used

- **Database:** MySQL
- **Language:** SQL
- **Concepts:** DDL, DML, DQL, aggregate functions, grouping, filtering, and joins.

## 📊 SQL Concepts Practiced

### 1. Data Definition and Manipulation
- `ALTER TABLE` to add and modify columns.
- `INSERT INTO` to add records.
- `UPDATE` to modify employee designations.

### 2. Data Retrieval and Filtering
- `SELECT DISTINCT` to retrieve unique salary values.
- `WHERE` with multiple conditions.
- `LIKE` to filter designations containing specific keywords.
- `ORDER BY` to sort employee records.
- `LIMIT` to restrict the number of results.

### 3. Aggregate Functions
- `SUM()` to calculate the total salary of the Finance department.
- `MIN()` to find the minimum employee age.
- `MAX()` to find the maximum salary by location.
- `AVG()` to calculate average salary and age.
- `COUNT()` to count employees by department.

### 4. Grouping and Filtering Groups
- `GROUP BY` to summarize data by department, location, and designation.
- `HAVING` to filter groups based on aggregate conditions.

### 5. SQL Joins
- `INNER JOIN` to display employees with their department names.
- `LEFT JOIN` to display all departments and their employee counts.
- `RIGHT JOIN` to display all locations, including locations without assigned employees.

## 📁 Repository Contents

- `SQL ASSIGMENT 2.sql` – SQL script containing table alterations, sample data insertion, employee data manipulation, and analytical queries.

## 🚀 How to Run the Project

1. Install MySQL Server and open MySQL Workbench.
2. Create or select the database containing the required tables.
3. Open `SQL ASSIGMENT 2.sql`.
4. Ensure the `employees`, `departments`, and `location` tables exist with the required columns.
5. Execute the SQL statements in the appropriate order.
6. Review the query results in MySQL Workbench.

**Note:** The script uses `USE employee;`, so the database must be named `employee`, or that statement must be changed to match your database name.

## 📚 Learning Outcomes

Through this assignment, I practiced writing SQL queries to retrieve, transform, summarize, and analyze relational data. I also gained practical experience working with aggregate functions, conditional filtering, grouping, and joins across multiple tables.

## 👨‍💻 Author

**T S MUHAMMED NABEEL**

B.Com Taxation Graduate | Aspiring Data Analyst

---

⭐ If you find this project useful, feel free to explore the SQL queries and practice the concepts.
