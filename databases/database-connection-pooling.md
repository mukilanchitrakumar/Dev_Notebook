# Database Connection Pooling

## Question

Why would you use Database Connection Pooling and how does it work?

## Short Answer

Database connection pooling maintains a cache of active database connections that can be reused across incoming requests instead of opening and closing a new socket connection each time. Establishing a new database connection involves expensive network round trips, process/thread allocation, and TLS/authentication handshakes. By leasing and returning connections from a pool, backend applications significantly decrease query latency and prevent database server overload.

## Simple Example

Instead of: `connect() -> query() -> close()` per request (50ms),
pool leases: `conn = pool.get() -> query() -> pool.release(conn)` (1ms).

## Key Point

Connection pooling eliminates connection setup latency and shields databases from being overwhelmed by spikes in traffic.

<!-- date: 2026-10-26 -->
