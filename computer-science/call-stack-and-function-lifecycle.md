# Call Stack and Function Lifecycle

## Question

What is the Call Stack and Function Lifecycle and how does it function?

## Short Answer

The call stack is an internal LIFO data structure that tracks active function invocations throughout program execution. Every time a function is called, a stack frame containing its arguments, local variables, and return instruction address is pushed onto the stack. When the function returns, its stack frame is popped off, restoring execution back to the caller's exact previous state.

## Simple Example

Calling `calculate_tax()` from `main()` pushes a new stack frame for `calculate_tax()`. When it returns, that frame is removed and execution resumes in `main()`.

## Key Point

The call stack tracks nested function calls and automatically cleans up local variables upon function return.

<!-- date: 2026-10-23 -->
