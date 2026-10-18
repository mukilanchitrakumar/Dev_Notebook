# Error Handling and Exceptions

## Question

How do Error Handling and Exceptions work at a basic level?

## Short Answer

Exception handling allows programs to detect, catch, and handle unexpected runtime errors gracefully without terminating abruptly. In Python, potentially failing operations are placed inside a `try` block, while corresponding error-handling logic is written in an `except` block. This separation prevents unhandled crashes and allows applications to release resources safely via `finally` blocks.

## Simple Example

```python
try:
    port = int('invalid_port')
except ValueError:
    port = 8080  # Safe fallback default
```

## Key Point

Exceptions decouple error detection from recovery, ensuring applications recover cleanly rather than crashing.

<!-- date: 2026-10-18 -->
