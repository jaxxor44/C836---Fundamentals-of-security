---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-04  11:44:07
modification date: 2022-08-04  11:44:00

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_6-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Web Security
- can be considered part of the [[Attack Surface Analysis#Application Surface|application]] attack surface.
- Can be compromised user data, or server data.
## Client-Side Attacks
- Takes advantage of weaknesses in the software loaded on the user's clients or rely on social engineering to fool the user ([[Attack Surface Analysis#User Surface|user attack surface]]).
- Examples include 
	- Cross-Site scripting (XSS)
	- Click jacking
## Server-Side Attacks
- Threats and vulnerabilities vary wildly based on software & hardware combinations.
- Directory traversal relies on [[Software Development Vulnerabilities#Input Validation attacks|input validation]] failures.
- [[Software Development Vulnerabilities#Authentication attacks|improper permissions]] or [[Software Development Vulnerabilities#Authorization attacks|inadequate permissions]] are also examples of server side attacks.
- Extraneous files are an example of [[Attack Surface Analysis#User Surface|user attack surface]] failure. Such as leaving a production key file in a production machine.