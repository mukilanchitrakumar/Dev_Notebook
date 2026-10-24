# Python Generators

## Question

Why would you use Python Generators and how does it work?

## Short Answer

A Python generator is a special type of iterator that yields values one at a time using the `yield` keyword instead of returning a complete collection at once. Because generators compute values lazily on-demand, they consume minimal memory even when processing millions of items or continuous data streams. When a generator encounters `yield`, its local execution state is paused and preserved until the next iteration.

## Simple Example

```python
def count_up(limit):
    num = 1
    while num <= limit:
        yield num
        num += 1
```
Consumes O(1) memory regardless of how large `limit` is.

## Key Point

Generators provide lazy on-demand evaluation, keeping memory usage constant across massive data processing pipelines.

<!-- date: 2026-10-24 -->
