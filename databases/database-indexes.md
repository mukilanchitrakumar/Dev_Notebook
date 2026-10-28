# Database Indexes

## Question

What are Database Indexes and why are they used?

## Short Answer

A database index is an auxiliary data structure—most commonly a B-Tree—that accelerates data retrieval without scanning every row in a table. It works like the index of a book, pointing directly to the exact physical block containing the requested row. While indexes make read queries substantially faster, they introduce additional overhead for write operations such as INSERT, UPDATE, and DELETE.

## Simple Example

Querying `SELECT * FROM users WHERE email = 'dev@example.com';` scans all 1,000,000 rows without an index. With a B-Tree index on `email`, it resolves in ~3 disk page reads.

## Key Point

Indexes trade write speed and storage space for exponentially faster read lookups.

<!-- date: 2026-10-28 -->
