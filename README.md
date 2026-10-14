# DBMS Practical Experiments (MySQL)

## Student Details
- **Student Name:** Aryan Kushwaha
- **Student ID / Roll Number:** 25LBCS3339
- **Semester:** 03
- **Course Name:** Database Management System
- **Course Code:** 25CSH-210
- **Program:** B.Tech – CSE (AI & ML)

---

## Objectives
The primary objectives of these lab experiments are:
- Designing conceptual and logical database models using Entity-Relationship (ER) modeling and relational schemas.
- Applying schema constraints and domain integrity rules (Primary Key, Foreign Key, Unique, Check, Not Null, Default).
- Writing complex SQL queries involving aggregations, group filtering, joins, nested subqueries, and set operations.
- Constructing database views and recursive Common Table Expressions (CTEs) for hierarchical organizational data.
- Automating business logic and data auditing using stored procedures and event-driven triggers.
- Evaluating query execution paths and performance using the `EXPLAIN` analytical statement.

---

## Repository Description
This repository contains SQL implementation scripts for Experiments 1 through 6 of the Database Management System practical curriculum. Each `.sql` script includes structured DDL/DML statements along with inline comments detailing expected query execution results and sample output formats.

---

## Requirements
- **Database Engine:** MySQL Server 8.0+ (Required for CTEs and advanced window functions)
- **Client Interface:** MySQL Workbench 8.0+, MySQL CLI, or compatible SQL IDE

---

## Repository Files

| File Name | Description |
| :--- | :--- |
| `Experiment_01.sql` | E-commerce ER model design and relational table implementations. |
| `ER_Diagram.png` | Entity-Relationship diagram visual reference for Experiment 1. |
| `Experiment_02.sql` | Relational schema definitions with integrity and key constraints. |
| `Experiment_03.sql` | Employee–Department–Project relational database schema and basic queries. |
| `Experiment_04.sql` | Advanced joins, correlated/nested subqueries, set-style operations, and `EXPLAIN` query analysis. |
| `Experiment_05.sql` | Standard database views and recursive Common Table Expressions (CTEs) for hierarchy traversal. |
| `Experiment_06.sql` | Custom stored procedures, validation triggers, and automated logging routines. |

---

## Recommended Execution Order

To maintain relational integrity and satisfy foreign key dependencies, execute the scripts sequentially:

1. **`Experiment_01.sql`**: Execute independently to create and populate the initial E-commerce schema.
2. **`Experiment_02.sql`**: Run to implement constraint validation models.
3. **`Experiment_03.sql`**: **Required dependency.** Builds the foundational `Employee`, `Department`, and `Project` schemas required by subsequent scripts.
4. **`Experiment_04.sql`**: Depends on tables populated in Experiment 3.
5. **`Experiment_05.sql`**: Extends the schema from Experiment 3 with organizational views and recursive employee hierarchy CTEs.
   > **Note:** If rerunning `Experiment_05.sql`, ensure dependent views are dropped first (`DROP VIEW IF EXISTS ...`) to prevent object definition conflicts.
6. **`Experiment_06.sql`**: Implements stored routines and trigger-based business rules on the base tables.

---

## Conclusion
These experiments cover core relational database concepts—ranging from early entity design and integrity enforcement to procedural database programming and query optimization using modern MySQL 8.0+ constructs.

---

DBMS-Practical-Experiments
