# Students Database: Part 1

This project is part of the **freeCodeCamp Relational Database Certification**.

It contains a PostgreSQL database that models computer science students, including first_name, last_name, major, and gpa.

## Project Files

- `students.sql` — A PostgreSQL dump of the database, including:
  - Database creation
  - Table definitions
  - Primary and foreign keys
  - Data inserts

## Database Structure

The database includes the following tables:

- **students**
- **courses**
- **majors**
- **majors_courses**

Each table uses appropriate data types and constraints, and relationships are implemented using foreign keys.

## How to Use

To recreate the database locally:

```bash
psql -U postgres < students.sql
