---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-05  10:55:23
modification date: 2022-08-05  10:55:02

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_5-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Firewalls
## History
- First discussed in *Simple and Flexible Datagram Access Controls* written in 1989 by Jeffery Mogul.
- First created in 1992 by Digital Equipment Corporation, called *DEC SEAL*.

## Usage
- Typically placed at points of trust change, or boarders.
## Packet Filtering
- The firewall looks at the contents of each packet in the traffic individually and allows/blocks based on:
	- source/destination IP
	- port number
	- protocol
- Can sometimes be bypassed by using an attack over multiple packets.
## stateful Packet Inspection
- Have all the same functions and features of a [[Firewalls#Packet Filtering|packet filtering]] firewall.
- Also tracks the state of each connection.
	- If a connection is closed from a website, the firewall no longer allows any additional traffic from that connection.
## Deep Packet Inspection
- questionable in privacy circles
- Does all the functions of a [[Firewalls#Stateful Packet Inspection|Stateful firewall]] but also looks at the packet contents.
- Can reassemble over multiple packets and determine if the contents are malicious or not.