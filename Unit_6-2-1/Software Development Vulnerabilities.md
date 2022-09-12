---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-04  09:59:03
modification date: 2022-08-04  09:58:43

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_6-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Software Development Vulnerabilities
- CMU offers several [secure operations guides](https://www.cmu.edu/iso/governance/guidelines/index.html) and [programming guides](https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards/) and policy.
- [PEP8](https://pep8.org/) offers a programing standard for python that covers the most common security practices as well as clean coding.
![[Pasted image 20220804105622.png]]
- within the [[Attack Surface Analysis#Application Surface|application attack surface]] there are several types of attack:
## Buffer Overflows
- aka buffer overruns
![[Pasted image 20220805143614.png]]
- when you don't properly account for the size of the data input into your application.
- The 'overrun' data, will bleed over into other memory spaces, possible leaving gaps open for exploitation or corruption.
## Race Conditions
- Happens when multiple threads/processes control or share access to a resource
- data integrity relies on the proper timing of data arriving into that resource.
## Input Validation attacks
- Happens when an application fails to constrain the data input by the user.
- The user can input malicious commands that can be executed by a remote server.
- In Format string attacks, particular print functions from the language can allow for manipulation or access to internal server data.
	- from `C` the chars `%f`, `%n` and `%p` apply formatting to the data your printing.
## Authentication attacks
- Attempts to gain access to resources without the proper credentials to do so.
- Avoid client side authentication
- Remove controls from the client/attacker as much as possible.
- Enforce strong passwords.
- Don't allow hard coded passwords.
## Authorization attacks
- attempts to gain access to resources without the proper authorization to do so.
- Implement measures to limit broken access, and actively identify breaches.
- Re-verify privileges whenever a user preforms an action in a restricted application.
## Cryptographic attacks
- Dont "Roll your own" cryptographic scheme.
- Use standards such as AES or RSA
- Plan ahead, what happens WHEN your crypto mechanism becomes obsolete?