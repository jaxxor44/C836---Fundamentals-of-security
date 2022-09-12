---
aliases: [Operating System Hardening]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-05  13:08:25
modification date: 2022-08-05  13:04:20

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_6-1-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Operating System Hardening
- Aims to reduce the number of possible connection avenues for entry.
- Also known as reducing your attack surface.
![[Pasted image 20220805131059.png]]
## Remove unnecessary software
- Servers should have only the software that is absolutely critical to operation.
- Client machines should only have applications that are permitted by their [[Access Control Lists]].
- Unpatched or updated software can eventually cause a serious security problem.
## Remove all Unessential services
- The services installed that start in the background at boot.
- Sometimes takes some trial and error or research to determine what each service does.
- Use `Nmap` or `netstat` to look for services listening on open ports.
- conducting regular connection checks on regular systems is just good paranoia.
## Alter Default Accounts
- Guest accounts and admin accounts should be changed in favor of more verbose or [[Access Control Lists|ACL]] compliant name.
- Admin accounts should have their name changed if they cant be removed.
- Change default passwords on *EVERY* piece of equipment and account.
- Outright remove guest accounts or accounts that serve no purpose.
## Use Principles of least privilege
- Actively apply [[Least Privilege Principle]] to accounts.
- A cheap and easy security measure.
- simple to setup, difficult to put in place after the fact.
## Preform Updates
- Delays in updates leave you open to know or evolving security flaws.
- Imminently after installing a new system *UPDATE IT*.
	- Best practice is to have the newest update/patches pre-downloaded and confirmed offline.
	- Once the application is done installing, and before its connected to the internet, UPDATE.
## Turn on Logging and Auditing
- Enable failed login logging and other alerts
- If your collecting logs, *REVIEW THEM*.
- backup the logs regularly, or send them to cold storage.