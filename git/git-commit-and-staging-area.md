# Git Commit and Staging Area

## Question

What problem does Git Commit and Staging Area solve?

## Short Answer

The Git staging area—also known as the index—acts as a preparation surface where you selectively organize changes before saving them. A commit is a permanent snapshot of staged files containing a unique SHA-1 hash, author details, timestamp, and descriptive log message. Staging lets you group related modifications into atomic commits rather than committing everything at once.

## Simple Example

```bash
git add server.py        # Move changes to staging area
git commit -m 'Add port validation' # Create permanent commit snapshot
```

## Key Point

Staging lets you curate exact changes into clean, atomic commits that record project progress.

<!-- date: 2026-09-27 -->
