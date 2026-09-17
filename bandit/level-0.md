# OverTheWire: Bandit — Level 0

**Date:** 16/09/2026
**Platform:** OverTheWire — Bandit
**Level:** 0 → 1

## Objective
Connect to the Bandit server via SSH and find the password for the next level.

## What I did
1. Connected to the server with SSH using user `bandit0` on port `2220`.
2. Ran `ls` and saw a file called `readme`.
3. Read the file with `cat readme`. It contained the password for the next level.
4. Typed `exit` to log out, then connected as `bandit1` using the password I found.

### 1. Connected to the server
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
