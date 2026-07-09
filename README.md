# MySQL & Ruby on Rails (Puma Server) Learning

## Topics Covered

### MySQL
- Created a database
- Created Employees table
- Inserted records
- Retrieved records using SELECT
- Modified table using ALTER TABLE
- Renamed column
- Changed column datatype
- Reordered columns using AFTER

### SQL Queries Practiced

```sql
SELECT * FROM employees;

ALTER TABLE employees
ADD phone_number VARCHAR(15);

ALTER TABLE employees
RENAME COLUMN phone_number TO email;

ALTER TABLE employees
MODIFY email VARCHAR(100);

ALTER TABLE employees
MODIFY email VARCHAR(100)
AFTER last_name;
```

---

## Ruby on Rails - Puma Server

### What is Puma?

Puma is the default web server used by Ruby on Rails.

### Features

- Fast web server
- Multi-threaded
- Multi-process support
- Handles multiple users simultaneously
- Lightweight and efficient

### Commands

Start Rails Server

```bash
rails server
```

or

```bash
rails s
```

Runs on

```
http://localhost:3000
```

Stop Server

```
Ctrl + C
```

---

## Learning Outcome

- Understood SQL basics
- Practiced ALTER TABLE commands
- Learned how to modify table structure
- Learned how the Puma server runs Rails applications

---

## Screenshots

### MySQL Workbench

(Add your screenshots here)

---

## Tech Stack

- MySQL Workbench
- MySQL 8.0
- Ruby
- Ruby on Rails
- Puma Server
