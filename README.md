# 📊 Task 2: Data Insertion and Handling Nulls

## 🎯 Objective
Practice inserting, updating, and deleting data in a SQL database while handling missing values (`NULL`) and using default values.

## 🧰 Tools
Oracle SQL

---

## 📁 Deliverables
- A `.sql` file containing:
  - `INSERT INTO` statements with/without nulls
  - `UPDATE` statements with `WHERE` conditions
  - `DELETE` statements with `WHERE` conditions
  - Table creation and optional `SELECT` query for verification

---

## 🗃️ Table Schema

```sql
CREATE TABLE Students (
    studentID NUMBER PRIMARY KEY,
    name VARCHAR2(100) NOT NULL,
    age NUMBER,
    email VARCHAR2(100),
    course VARCHAR2(100) DEFAULT 'Undeclared'
);
