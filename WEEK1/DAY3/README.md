# Week 1 - Day 3 : SQL JOINS Practice

This repository contains SQL JOIN practice exercises using a student-course enrollment database.  
The project demonstrates different types of SQL joins with practical examples and beginner-friendly queries.

---

# Files Included

## 1. data.sql
Contains:
- Table creation
- Relationships using foreign keys
- Sample data insertion

### Tables Used
- instructors
- students
- courses
- enrollments

---

## 2. queries-answers.sql
Contains SQL JOIN queries with comments and solutions.

Topics covered:
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- NULL handling
- Multi-table joins
- Reporting queries

---

# Database Schema Overview

## instructors
| Column Name | Data Type |
|---|---|
| instructor_id | INT |
| instructor_name | VARCHAR(100) |
| department | VARCHAR(100) |

---

## students
| Column Name | Data Type |
|---|---|
| student_id | INT |
| student_name | VARCHAR(100) |
| email | VARCHAR(100) |

---

## courses
| Column Name | Data Type |
|---|---|
| course_id | INT |
| course_name | VARCHAR(100) |
| instructor_id | INT |

---

## enrollments
| Column Name | Data Type |
|---|---|
| enrollment_id | INT |
| student_id | INT |
| course_id | INT |
| enrollment_date | DATE |

---

# SQL JOIN Concepts Practiced

## LEFT JOIN
Returns all rows from the left table and matched rows from the right table.

Example:
- Display all students even if they are not enrolled.

---

## RIGHT JOIN
Returns all rows from the right table and matched rows from the left table.

Example:
- Display all students with enrollment details.

---

## FULL OUTER JOIN
Returns all matched and unmatched rows from both tables.

Example:
- Show all students and enrollments together.

---

## CROSS JOIN
Creates every possible combination between two tables.

Example:
- Every student combined with every course.

---

# Practice Queries Included

- Students and enrolled courses
- Courses without enrollments
- Instructors and assigned courses
- Courses without instructors
- Students not enrolled in any course
- FULL OUTER JOIN examples
- Multi-table reporting query
- CROSS JOIN combinations

---

# Key Learning Outcomes

By completing this practice, you will learn:
- How table relationships work
- How foreign keys connect tables
- How different JOINs behave
- How to retrieve matched and unmatched records
- How to build real-world SQL reports

---

# JOIN Summary

| JOIN Type | Description |
|---|---|
| INNER JOIN | Returns only matching rows |
| LEFT JOIN | Returns all left table rows |
| RIGHT JOIN | Returns all right table rows |
| FULL OUTER JOIN | Returns all rows from both tables |
| CROSS JOIN | Returns all possible combinations |

---

# Beginner Notes

- `NULL` means missing or no matching data.
- JOINs are used to combine related tables.
- Foreign keys help connect tables together.

---

# Author
SQL Practice Repository  
Week 1 - Day 3 : JOINS
