# SQL SELECT and WHERE Clause

## Question

What is SQL SELECT and WHERE Clause in Databases?

## Short Answer

The SQL `SELECT` statement queries data from database tables, allowing developers to retrieve specific columns or computed expressions. Appending a `WHERE` clause filters rows based on boolean conditions, ensuring only records matching specified criteria are returned. Filtering rows at the database level minimizes network transfer and speeds up application performance.

## Simple Example

```sql
SELECT email, created_at 
FROM users 
WHERE is_active = true AND created_at >= '2026-01-01';
```

## Key Point

`SELECT` retrieves columns, while `WHERE` filters rows at the database server before transmission.

<!-- date: 2026-10-12 -->
