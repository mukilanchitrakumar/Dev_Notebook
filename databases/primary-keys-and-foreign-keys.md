# Primary Keys and Foreign Keys

## Question

What is a primary key and why is it important in a database?

## Short Answer

A primary key is a column or set of columns in a relational table that uniquely identifies each individual row and strictly prohibits null values. A foreign key is a column in one table that references the primary key of another table, creating a formal relationship between them. Relational database engines enforce foreign key constraints to maintain referential integrity, preventing orphaned rows.

## Simple Example

```sql
-- orders references users table via user_id foreign key
CREATE TABLE orders (
    order_id INT PRIMARY KEY,
    user_id INT REFERENCES users(id)
);
```

## Key Point

Primary keys guarantee row uniqueness; foreign keys preserve relationships and referential integrity between tables.

<!-- date: 2026-09-29 -->
