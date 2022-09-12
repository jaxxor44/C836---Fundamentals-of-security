---
aliases: [Operating System Security Tools]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-05  15:07:20
modification date: 2022-08-05  15:07:09

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_6-1-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Operating System Security Tools
- Conducting audits with OS [[Operating System Hardening]].
- Port scanning tools like nmap.
	- `nmap -sS -sU -A -v <some IP>`
		- `-sS` Run a TCP SYN port scan
		- `-sU` to run a UDP port scan
		- `-A` Enable OS detect, Version detect and script scanning.
		- `-v` Enable verbose output as scan runs.
