---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-01  12:02:01
modification date: 2022-08-01  12:01:47

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/unit_2-3-1
cards-deck: C836 - Fundamentals of security
Anki: 1

---

# The Bell-LaPadula Model
- A type of Access [[Access Control Lists|Control Model]].
- combines [[Discretionary Access Control (DAC)]] and [[Mandatory Access Control (MAC)]].
- Primarily concerned with the confidentiality of the resource in question.
- Generally, MAC takes precedence over DAC.
- Uses the *Simple Security Property* and *the `*` property*.
![[Pasted image 20220801120526.png]]
- When handling classified information, you can't read any higher than your clearance level, or write data at any lower level.

# cards
>[!info] card
>The {1:Bell-LaPdula} access control model is mostly concerned with the confidentiality of the resource. It uses a mix of {2:DAC and MAC} methods. It uses rules like {3:"No read up, No write down"}.
^1659489236347
