# 🐧 Linux Fundamentals — OverTheWire Bandit

Working through [OverTheWire's Bandit wargame](https://overthewire.org/wargames/bandit/) to build real command-line fluency — the foundation everything else in pentesting sits on.

**Goal:** solve every level, and write each one up clearly enough that someone else could follow my steps and understand *why* they worked, not just copy the commands.

---

## 📊 Progress (33 levels)

- [ ] Level 0 → 1
- [ ] Level 1 → 2
- [ ] Level 2 → 3
- [ ] Level 3 → 4
- [ ] Level 4 → 5
- [ ] Level 5 → 6
- [ ] Level 6 → 7
- [ ] Level 7 → 8
- [ ] Level 8 → 9
- [ ] Level 9 → 10
- [ ] Level 10 → 11
- [ ] Level 11 → 12
- [ ] Level 12 → 13
- [ ] Level 13 → 14
- [ ] Level 14 → 15
- [ ] Level 15 → 16
- [ ] Level 16 → 17
- [ ] Level 17 → 18
- [ ] Level 18 → 19
- [ ] Level 19 → 20
- [ ] Level 20 → 21
- [ ] Level 21 → 22
- [ ] Level 22 → 23
- [ ] Level 23 → 24
- [ ] Level 24 → 25
- [ ] Level 25 → 26
- [ ] Level 26 → 27
- [ ] Level 27 → 28
- [ ] Level 28 → 29
- [ ] Level 29 → 30
- [ ] Level 30 → 31
- [ ] Level 31 → 32
- [ ] Level 32 → 33

---
## 🧠 Concepts & commands I've picked up
 
> Running list — add to this every time a new command or idea clicks, even something small.
 
-
---

## 📝 Level walkthroughs
 
<details>
<summary><b>Level 0 → 1</b> — SSH basics & reading a file</summary>
**Goal:** log in with SSH, find the password for the next level stored in a file called `readme`.
 
**Commands used:**
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
 
**What I learned:**
- ssh: The core command that launches the secure client.
- SSH, which stands for Secure Shell, is a cryptographic network protocol that allows you to securely connect to and manage a remote computer over an unsecured network
- bandit0: my username for the level 0
- @bandit.labs.overthewire.org: The remote server address hosting the game
- -p 2220: SSH defaults to port 22, but Bandit hosts its service on port 2220. If you omit this flag, the connection will fail
**Screenshot:**
![Level 0 terminal output](images/linux-fundamentals/bandit-0.png)
 
</details>
