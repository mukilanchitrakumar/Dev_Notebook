# Linux Standard Streams and Pipes

## Question

What problem do Linux Standard Streams and Pipes solve in Linux?

## Short Answer

Every standard Linux process is launched with three default I/O streams: standard input (stdin, fd 0), standard output (stdout, fd 1), and standard error (stderr, fd 2). Pipes, represented by the vertical bar `|`, connect the standard output of one command directly into the standard input of another in memory. This composition model allows engineers to build complex data processing workflows from small, single-purpose command line tools.

## Simple Example

```bash
# Filter active system processes by name using a pipe
ps aux | grep python
```

## Key Point

Pipes connect the stdout of one process directly to the stdin of another, enabling powerful command composition.

<!-- date: 2026-10-21 -->
