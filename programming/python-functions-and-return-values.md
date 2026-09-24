# Python Functions and Return Values

## Question

What problem do Python Functions and Return Values solve in Programming?

## Short Answer

A function in Python is a reusable block of organized code created with the `def` keyword that executes only when called. Functions accept input values called arguments and return computed results to the caller using the `return` statement. If a function reaches its end without an explicit return statement, it implicitly returns `None`.

## Simple Example

```python
def calculate_total(subtotal, tax_rate):
    return subtotal * (1 + tax_rate)

final_price = calculate_total(100, 0.08)  # Returns 108.0
```

## Key Point

Functions encapsulate reusable logic, take input arguments, and explicitly pass results back via `return`.

<!-- date: 2026-09-24 -->
