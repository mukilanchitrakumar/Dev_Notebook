# Database Tables and Columns

## Question

What is a database table and how are columns defined?

## Short Answer

In relational database management systems, a table organizes structured data into a two-dimensional grid of rows and columns. Each column represents a specific attribute with a defined data type such as text, integer, or timestamp, while each row represents a distinct data record. Tables enforce schemas to ensure data consistency and validity across all stored records.

## Simple Example

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    email VARCHAR(255) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

## Key Point

Tables structure data into strictly typed columns and populated rows, ensuring data uniformity.

<!-- date: 2026-09-28 -->
