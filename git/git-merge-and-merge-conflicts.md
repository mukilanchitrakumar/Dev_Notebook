# Git Merge and Merge Conflicts

## Question

How do Git Merge and Merge Conflicts work at a basic level?

## Short Answer

Merging incorporates changes from one branch into another, combining separate lines of development into a unified commit history. If the branches modified completely different files or lines, Git automatically creates a merge commit. When both branches modify the same line in conflicting ways, Git halts the merge and marks the conflict markers for manual developer resolution.

## Simple Example

```bash
git switch main
git merge feature-auth  # Merges feature-auth into main
```

## Key Point

Merging integrates divergent branch lines, either automatically or through conflict resolution when edits overlap.

<!-- date: 2026-10-19 -->
