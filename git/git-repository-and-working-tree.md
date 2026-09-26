# Git Repository and Working Tree

## Question

What is a Git repository and what does it contain?

## Short Answer

A Git repository is a database tracked within a hidden `.git` directory that stores the complete history and metadata of a project. The working tree consists of the actual local files currently extracted and visible on disk for you to edit. When you modify files in your editor, those changes exist solely in your working tree until staged and committed into repository history.

## Simple Example

```bash
# Initialize a fresh repository database in the current folder
git init
```

## Key Point

The repository stores immutable history in `.git`, while the working tree contains your active local files.

<!-- date: 2026-09-26 -->
