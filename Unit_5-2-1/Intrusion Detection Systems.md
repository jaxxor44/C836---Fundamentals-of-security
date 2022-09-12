---
aliases: [Intrusion Detection Systems, IDS]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-05  11:57:16
modification date: 2022-08-05  11:57:07

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_5-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Intrusion Detection Systems
- Hardware or software based tools to monitor networks, hosts or applications for unauthorized entry.
- Common practice to 'Pre-filter' traffic with a firewall to save IDS resources.
- Its possible to use [[Intrusion Detection Systems#Signature-based IDS|signature based]] and [[Intrusion Detection Systems#Anomaly-based IDS|anomaly based]] filters, but can slow networks or be resource intensive.
- Attacks can be crafted specifically to avoid detection by any IDS.
## Signature-based IDS
- Works similar to antivirus systems.
- Maintains an updated database of signatures that signal an attack.
- Compares incoming traffic to the signatures.
- Works well except on new attacks or those designed to avoid this kind of system.
## Anomaly-based IDS
- Works by measuring traffic against a known normal baseline.
- Can catch new or emerging attacks.
- Creates a higher number of false positives. (see Biometrics: FRR)
