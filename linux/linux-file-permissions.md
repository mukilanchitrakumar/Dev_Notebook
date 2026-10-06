# Linux File Permissions

## Question

Why are Linux File Permissions important in software engineering?

## Short Answer

Linux secures files and directories using a permission model divided into three categories of users: user (owner), group, and others. For each category, Linux controls three fundamental permissions: read (`r`), write (`w`), and execute (`x`). These permissions are represented in terminal listings as a 10-character string (such as `-rwxr-xr--`) or as an octal number (such as `754`).

## Simple Example

```bash
# Grant read and write to owner, read to group and others
chmod 644 config.yml
```

## Key Point

File permissions regulate read, write, and execute capabilities across owner, group, and other users.

<!-- date: 2026-10-06 -->
