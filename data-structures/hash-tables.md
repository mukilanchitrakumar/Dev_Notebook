# Hash Tables

## Question

What is a hash table and why is lookup usually fast?

## Short Answer

A hash table is an associative data structure that maps keys to values by passing each key through a hash function to compute an integer bucket index. Because computing a hash and indexing an array are constant-time operations, hash tables provide average O(1) time complexity for insertions, deletions, and lookups. When two distinct keys produce the same bucket index, the table resolves the collision using chaining with linked lists or open addressing.

## Simple Example

```python
# Hash table lookup by key in average O(1) time
cache = {'user_101': 'Alice', 'user_102': 'Bob'}
print(cache['user_101'])  # Instantly resolves bucket index
```

## Key Point

Hash tables achieve average constant-time lookups by mapping keys directly to array memory indices via hash functions.

<!-- date: 2026-10-22 -->
