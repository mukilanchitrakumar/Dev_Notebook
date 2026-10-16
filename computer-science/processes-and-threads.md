# Processes and Threads

## Question

What is a process and why do programs run inside processes?

## Short Answer

A process is an isolated running instance of a computer program that possesses its own dedicated address space, memory pages, and system resources. A thread is a lightweight execution path within that process that shares the same address space and open file descriptors with sibling threads. The operating system uses processes to maintain security boundaries so that a crashing program cannot corrupt other running applications.

## Simple Example

A web browser runs distinct browser tabs in isolated processes for fault tolerance, while each tab uses multiple threads to render HTML and handle user clicks simultaneously.

## Key Point

Processes provide isolated memory boundaries for safety; threads share memory within a process for efficient concurrency.

<!-- date: 2026-10-16 -->
