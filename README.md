# 🔐 My Cybersecurity Journey

Documenting my path from cybersecurity student to penetration tester — daily notes, lab write-ups, cheat sheets, and scripts, updated as I go.

## 🎯 Current focus
I'am doing a 30-day plan (3–4 hrs/day, ~100 hrs total)

Realistic framing: in 30 days at this pace you won't be "elite," but you can absolutely reach solid CTF-competent status — comfortable with web exploitation, basic privesc, and box methodology, with a real portfolio of solved machines and write-ups. That's a legitimate foundation the 1% built on too; they just kept going past day 30.

Week 1 — Compress the fundamentals, get your hands dirty immediately

Day 1–2: Set up Kali (VM or WSL), get comfortable with tmux/CLI workflow, skim TCP/IP refresher only where rusty. Do your first guided room (TryHackMe "Pre Security"/"Jr Penetration Tester" intro rooms — this path was rebuilt for 2026 with 89 rooms including a full nine-room Active Directory module). 
tryhackme
Day 3–4: Learn Nmap properly (not just -sV -sC) — scan types, timing, scripts. Start your methodology doc today.
Day 5–7: Do 3–4 "Easy" rated boxes end-to-end solo, using the stuck-then-peek method. Write a mini-report for each.

Week 2 — Web exploitation immersion

Daily split: ~2 hrs PortSwigger Web Security Academy labs (free, gold standard for web — XSS, SQLi, auth bypass, SSRF, IDOR), ~1–2 hrs applying it on HTB/THM web-focused boxes.
Goal by end of week: comfortable manually finding and exploiting the OWASP Top 10 without relying on automated scanners.

Week 3 — Privilege escalation + intro Active Directory

Learn Linux privesc (GTFOBins, misconfigured cron/SUID, kernel exploits) and Windows privesc (services, tokens, unquoted paths).
Start the AD module from the Jr Penetration Tester path — it tests the full kill chain in unguided format via capstone challenges, which is exactly the pressure-test you want at this stage. 
tryhackme
Mix in 3–5 "Medium" boxes.

Week 4 — CTF speed and specialization

Join 1–2 live CTF events off CTFtime.org (even mid-tier ones). Play the full window, then upsolve — go back after and solve what you missed using write-ups, which is where a huge amount of learning happens.
Pick your strongest category from weeks 1–3 (likely web) and go deeper on it specifically.
Finish by publishing 2–3 of your best write-ups publicly (GitHub/blog) — this is your proof of work and doubles as review.
## 📁 What's in here

| Folder | What goes here |
|---|---|
| `notes/` | Daily/weekly study notes as I learn |
| `writeups/` | Solved lab & CTF write-ups (retired/closed challenges only) |
| `cheat-sheets/` | Commands and references I've compiled myself |
| `scripts/` | Small tools and automation I've built |
| `home-lab/` | My practice lab setup, configs, and build notes |

## ✅ Progress checklist
- [ ] Linux & networking fundamentals
- [ ] Practical Ethical Hacking course (TCM Security)
- [ ] Web application pentesting (PortSwigger Academy)
- [ ] Active Directory & privilege escalation
- [ ] First certification

---
*Started: [26/09]. Updated (almost) daily — check the commit history.*
