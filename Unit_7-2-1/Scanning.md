---
aliases: [Scanning]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-07  12:10:46
modification date: 2022-08-07  12:10:37

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_7-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Scanning
- In a [[Vulnerability Assessment]] the previous step is [[Mapping and Discovery]].

## Unauthenticated Scans
- requires no credentials to interrogate the host network.
- merely requires network access.
- The most common type of scan, will check for things like open ports, and guess at different applications and operating systems.
## Authenticated Scans
- conducted with a valid set of credentials, generally Admin.
- Will let you login to the host and scan more deeply for applications installed, system configs, patching status.
- Gives you a much more detailed picture of the host.
## Agented Scans
- Gets around some of the problems that come with Authenticated scans.
- Uses a piece of software on the host to provide data (or send data) to a scanning service.
- Runs the scan with the permissions of a user on the system, and therefore doesnt require the high level credentials of an Authenticated scan.
## Application Scanning
- A specialized type of scanner, that goes into significant more depth than system level scanners.
- Smaller focus, more detailed picture.
- [Burp Suite](https://portswigger.net/burp). An automated web application scanner and tester.
