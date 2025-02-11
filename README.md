# Data Technician Workbook: SQL Language 🚀📊

**Author:** Sergios Vasileiou  
**Course Date:** 13/01/25  

This repository documents my practical exercises in SQL, covering database fundamentals, join types, real-world SQL query scenarios, and a detailed essay on designing a retail database. Explore the tasks below to learn about the essential concepts of SQL through hands-on examples and best practices. 🔍

## Table of Contents
- [Day 1: Database Concepts & Fundamentals 📚](#day-1-database-concepts--fundamentals-)
  - [Task 1: Key Database Concepts 🔑](#task-1-key-database-concepts-)
  - [Task 2: Relational vs Non-relational Databases 💻](#task-2-relational-vs-non-relational-databases-)
- [Day 3: SQL Joins & Query Techniques 🔗](#day-3-sql-joins--query-techniques-)
- [Day 4: Database Design & Practical SQL Tasks 🛠](#day-4-database-design--practical-sql-tasks-)
  - [Task 1: SQL Essay on Retail Database Design 📝](#task-1-sql-essay-on-retail-database-design-)
  - [Task 2: SQL Practical Exercises 🎯](#task-2-sql-practical-exercises-)
- [Course Notes & Additional Resources 📖](#course-notes--additional-resources-)

## Day 1: Database Concepts & Fundamentals 📚

### Task 1: Key Database Concepts 🔑
In this task I explored essential SQL and database definitions:
- **Primary Key:** A unique identifier for each record in a table; cannot be null. 🔒
- **Secondary Key:** May contain duplicate values and can include nulls.
- **Foreign Key:** A reference that links records in one table to a primary key in another, enforcing referential integrity.
- **Relationship Examples:**  
  - *One-to-One:* A trackID and its corresponding track name in a music dataset.  
  - *One-to-Many:* A single doctor serving multiple patients in a hospital dataset.  
  - *Many-to-Many:* Patients visiting various doctors where each doctor treats many patients.

These foundational concepts are crucial for designing efficient databases and ensuring data integrity.

### Task 2: Relational vs Non-relational Databases 💻
This task compares the two major database models:
- **Relational Databases:**  
  - Organize data into tables with rows and columns and enforce a strict schema.  
  - Support ACID properties for reliable transactions (e.g., MySQL, Oracle).  
  - Ideal for applications requiring complex queries and data consistency.
- **Non-relational Databases (NoSQL):**  
  - Allow flexible data formats such as documents, key-value pairs, or graphs.  
  - Emphasize scalability and high availability over strict consistency (e.g., MongoDB, Cassandra).  
  - Suitable for unstructured, semi-structured, or big data scenarios.

This section describes which data types benefit from non-relational models, such as unstructured social media posts or big data from real-time sensors.

## Day 3: SQL Joins & Query Techniques 🔗

### Task 1: SQL Join Types and Examples
Using the Sakila dataset, I explored various join types:
- **Self-Join:** Join a table to itself to compare rows.  
- **Right Join:** Returns all rows from the right table with matching left table rows (or NULL when unmatched).  
- **Full Join:** Combines left and right joins to return all records when there is a match in either table.  
- **Inner Join:** Retrieves only the rows where there are matching values in both tables.  
- **Cross Join:** Produces a Cartesian product of two tables by combining every row of one table with every row of the other.  
- **Left Join:** Returns all rows from the left table and matched rows from the right table (with NULLs for non-matches).

Each join is explained with syntax examples and real-world scenarios, reinforcing practical knowledge of data retrieval.

## Day 4: Database Design & Practical SQL Tasks 🛠

### Task 1: SQL Essay on Retail Database Design 📝
For this task, I wrote a detailed 500-word essay describing the process for designing a database for a small retail business. Key highlights include:
- **Understanding Business Requirements:**  
  - Identification of data elements like inventory, sales, and customer details.  
  - Consideration of the needs of store managers, workers, and IT staff.
- **Designing the Database Schema:**  
  - Creating three tables: Products, Customers, and Sales.  
  - Defining primary keys for uniqueness and foreign keys to establish relationships.
- **Database Implementation:**  
  - Using SQL commands such as `CREATE DATABASE`, `CREATE TABLE`, and specifying data types.  
  - Providing code examples for table creation and enforcing relationships.
- **Populating the Database:**  
  - Demonstrating how to insert initial data with `INSERT INTO` statements.
- **Maintaining the Database:**  
  - Strategies for updating records, scheduling backups, and ensuring data quality with queries to detect duplicates or missing values.
  
This essay integrates theoretical knowledge with hands-on examples of SQL commands, illustrating a complete workflow from design to maintenance.

### Task 2: SQL Practical Exercises 🎯
This section consists of multiple SQL exercises based on real-world scenarios, including:
- **Demographics and Geography:**  
  - Count the number of cities in the USA, list cities starting with specific prefixes, and sort cities alphabetically.
- **Health and Economic Analyses:**  
  - Identify the country with the highest life expectancy and the country with the largest population.
- **Population and Data Analysis:**  
  - Retrieve cities with populations above a given threshold or within a specific range.
- **Data Reporting:**  
  - Display limited sets of rows and perform city name frequency analysis.
- **Comparative Insights:**  
  - Determine the most and least populated cities, and compare capital city populations.

Each exercise includes both SQL syntax examples and sample output screenshots to illustrate the query outcomes.

## Course Notes & Additional Resources 📖
- **Comprehensive Course Notes:** Detailed outlines and revision guides summarizing key SQL concepts and exercises.  
- **Supplementary Materials:** Additional links and references recommended in the revision guide for further learning.  
- **Practice Screenshots:** Visual documentation of query execution and results for in-depth review.

---

This README offers a detailed and visually engaging overview of my SQL workbook. It bridges theoretical concepts with hands-on SQL tasks—from database fundamentals and join techniques to real-world query scenarios—providing a solid foundation in SQL for data management. Enjoy exploring the work! 🚀
