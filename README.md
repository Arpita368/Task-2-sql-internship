# 📊 Task 2: Data Insertion and Handling Nulls

## 🎯 Objective
Practice inserting, updating, and deleting data in a SQL database while handling missing values (`NULL`) and using default values.

## 🧰 Tools
Oracle SQL

---

## 📁 Deliverables
- A file containing:
  -  Table creation
  - `INSERT INTO` statements with/without nulls
  - `UPDATE` statements with `WHERE` conditions
  - `DELETE` statements with `WHERE` conditions
  - `SELECT` query for verification

---

## 🗃️ Table Schema

```sql
CREATE TABLE Students (
    studentID NUMBER PRIMARY KEY,
    name VARCHAR2(30) NOT NULL,
    age NUMBER,
    email VARCHAR2(30),
    course VARCHAR2(15) DEFAULT 'Undeclared'
);
```

---

## INSERT Statement
INSERT INTO statement is used to insert data into the table. It is used as a DML query.
**Syntax:** INSERT INTO table_name(column1_name, column2_name, ...) VALUES (value1, value2, ...);

## Update Statement
UPDATE statement is used to modify existing data in the table. It is used with WHERE clause which is used to specify which data needs to be modified. It can be used to modify multiple rows.
**Syntax:** UPDATE table_name SET column1_name=value1, column2_name=value2, ... WHERE condition;

## DELETE Statement
DELETE statement is used to remove records from the table. It is used as a DML query. It is used with WHERE clause to specify the data that needs to be deleted. It can be used without WHERE clause. It can delete single record as well as multiple records.
**Syntax:** DELETE FROM table_name WHERE condition;

## SELECT Statement
SELECT statement is used to display records from a table. It can be used with or without WHERE clause.
**Syntax:** SELECT column1_name, column2_name, ... FROM table_name;
