# Database Transactions and Atomicity

## Question

What is Database Transactions and Atomicity and why is it used?

## Short Answer

A database transaction bundles multiple SQL statements into an all-or-nothing unit of work that guarantees atomicity. If every statement inside the transaction succeeds, the database issues a `COMMIT` and persists all changes permanently. If any statement fails or an error occurs, a `ROLLBACK` executes, restoring database state to precisely where it was before the transaction began.

## Simple Example

```sql
BEGIN;
UPDATE accounts SET balance = balance - 100 WHERE id = 1;
UPDATE accounts SET balance = balance + 100 WHERE id = 2;
COMMIT;
```

## Key Point

Transactions guarantee atomicity: all operations succeed together, or all fail together with zero partial state.

<!-- date: 2026-10-20 -->
