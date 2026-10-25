# Git Rebase

## Question

Why would you use Git Rebase and how does it work?

## Short Answer

Git rebase rewrites project history by taking all the new commits from the current branch and reapplying them sequentially on top of another base branch. Unlike `git merge`, which creates a non-linear history with a dedicated merge commit, rebase produces a clean, perfectly linear project history. However, rebasing commits that have already been pushed to a shared public branch can cause synchronization issues for collaborators.

## Simple Example

```bash
# Move feature branch commits on top of current main branch
git checkout feature
git rebase main
```

## Key Point

Rebasing creates a clean, linear commit history, but should never be used on shared public branches.

<!-- date: 2026-10-25 -->
