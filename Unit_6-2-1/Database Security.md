---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-04  12:50:32
modification date: 2022-08-04  12:50:22

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_6-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Database Security
![[Pasted image 20220804130141.png]]
## Protocol Issues
- Gaps, flaws or other unknown issues in protocols.
- mitigation and prevention for these issues include
	- constant patching of the OS and software
	- sanitize for [[Software Development Vulnerabilities#Buffer Overflows|buffer overflows]].
	- follow the [[Least Privilege Principle]].
## Unauthenticated Access
- When you give a user or process the opportunity to interact with your data-base without credentials.
- Prevented by forcing a user to send credentials in order to begin a transaction.
## Arbitrary Code Execution
- aka _remote code execution_, when conducted over the network.
- Any ability to execute code on a remote system without restriction.
- defenses include
	- patching all software
	- internal reviews to ensure that patching practices are being followed.
## Privilege Escalation
- Any time a user elevates their level of access above what you have authorized them to have for that system or application.
- Can be completed by *SQL injection* of a username that allows an `always true` condition.
- escalation can also happen when the underlying OS is not patched or maintained correctly.