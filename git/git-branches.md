# Git Branches

## Question

Why are Git Branches important in software engineering?

## Short Answer

A Git branch is a lightweight, movable pointer to a specific commit in your repository history. Creating and switching branches allows developers to develop isolated features or bug fixes without affecting the stable `main` codebase. Because branches are simply small reference files storing commit hashes, creating and deleting them is instantaneous and requires almost zero disk space.

## Simple Example

```bash
git switch -c feature-auth  # Create and switch to a new branch
# Work safely without touching main branch
```

## Key Point

Branches are lightweight movable pointers that isolate parallel feature work safely.

<!-- date: 2026-10-11 -->
