# DBMS Practical Experiments (MySQL)

**Student Name:** Aryan Kushwaha
**Student ID / Roll Number:** 25LBCS3339
**Semester:** 03
**Course Name:** Database Management System  
**Course Code:** 25CSH-210  
**Program:** B.Tech – CSE (AI & ML)

## Objectives

- Understand database management system concepts and relational database design.
- Design ER diagrams and convert them into relational schemas.
- Implement tables with primary keys, foreign keys, and integrity constraints.
- Perform SQL operations using joins, subqueries, aggregate functions, and set-style queries.
- Create views and recursive Common Table Expressions (CTEs).
- Implement stored procedures, triggers, validation, and error handling.
- Understand query execution plans using EXPLAIN.

This repository contains Experiments 1–6 as individual SQL scripts and the Experiment 1 ER diagram. Each SQL file starts with its **Aim**, followed by the SQL statements and an **Output (expected)** note. Output notes are guidance, not screenshots or claims that the scripts were executed on your machine.

## Requirements

- MySQL 8.0+ (recommended) and MySQL Workbench or another MySQL client.
- Run scripts in a practice database/server, not a production database.

## Files

- `Experiment_01.sql` — E-commerce ER model and relational tables
- `ER_Diagram.png` — ER diagram for Experiment 1
- `Experiment_02.sql` — Relational schema and integrity constraints
- `Experiment_03.sql` — Employee–Department–Project schema and queries (30 employees, 5 departments, 8 projects)
- `Experiment_04.sql` — Joins, subqueries, set-style queries, and EXPLAIN
- `Experiment_05.sql` — Views and recursive CTE hierarchy
- `Experiment_06.sql` — Stored procedure, triggers, and validation

## Recommended Run Order

1. Run Experiments 1 and 2 independently.
2. Run Experiment 3 before Experiments 4, 5, and 6; these scripts share `EmployeeDB`.
3. Experiment 5 alters the Employee table and is intended to be run once on a fresh setup. If re-running it, recreate `EmployeeDB` first or carefully remove the already-added manager column and constraint.
4. In Experiment 2, invalid INSERT examples are commented out intentionally; uncomment one at a time to observe constraint errors.
5. Review each script before execution and use a practice database.

## Conclusion

These practical experiments provide hands-on experience with database design, relational schema implementation, SQL querying, and integrity constraints. They also introduce views, recursive CTEs, stored procedures, and triggers. Completing these experiments helps develop the skills required to design, manage, and query structured databases efficiently.
