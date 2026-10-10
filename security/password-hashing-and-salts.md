# Password Hashing and Salts

## Question

What problem do Password Hashing and Salts solve in Security?

## Short Answer

Password hashing transforms plain-text passwords into irreversible fixed-length cryptographic hashes so that database breaches do not expose user credentials. A salt is a unique, cryptographically secure random value generated per user and appended to the password before hashing. Salts guarantee that two users with identical passwords will produce completely different hashes, neutralizing rainbow table dictionary attacks.

## Simple Example

Instead of storing `secret123`, the database stores `bcrypt(secret123 + salt)`, producing `$2b$12$e8uq...` which cannot be reversed back to plain text.

## Key Point

Salts ensure identical passwords generate distinct hashes, protecting stored credentials against precomputed dictionary attacks.

<!-- date: 2026-10-10 -->
