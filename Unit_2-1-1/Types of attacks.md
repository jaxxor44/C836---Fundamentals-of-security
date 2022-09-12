---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-07-22  14:38:45
modification date: 2022-07-22  14:37:51

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/unit_2-1-1
cards-deck: C836 - Fundamentals of security
Anki: 2

---

# Types of attacks
- Each type of attack occurs because of a [[Threats, Vulnerabilities and Risk#Vulnerabilities|vulnerability]] on an [[Attack Surface Analysis#Attack Surface Analysis|attack surface]].
- Each type of attack can be assessed with a [[Qualitative Risk Assessment]] or a [[Quantitative Risk Analysis]].
- Can be mitigated with the appropreate type of [[Risk mitigation, controls|control]].
![[CIA triad and categories of attacks.png]] ^e389f6
## Interception
- Allowing unauthorized users to view or collect data.
- Can include emails, phone calls or viewing files.
- Primarily, an attack of [[CIA triad#Confidentiality|confidentiality]]
- applies to data that is [[Data states#In Use|in use]] or [[Data states#In Motion|in motion]] (encrypted).

## Interruption
- Any significant disruption in service or operations.
- Includes DOS attacks and more direct attacks against active servers.
- The end result of all attacks is the same, the system is unavailable.
- This can be an attack of [[CIA triad#integrity|integrity]] or [[CIA triad#Availability|availability]].
- Applies to data that is [[Data states#In Motion|in motion]].

## Modification
- includes modifying database information or unsigned emails.
- Changing one configuration file can grant/deny access to an entire database.
- This can be an attack of [[CIA triad#integrity|integrity]] or [[CIA triad#Availability|availability]].
- Applies to data that is [[Data states#At Rest|at rest]], but can theoretically be all 3.

## Fabrication
- The creation of data, processes, communications, or other materials.
- Making fake web traffic, unsigned emails or database entries
- combatted best with digital signatures, and audit logs.
- This can be an attack of [[CIA triad#integrity|integrity]] or [[CIA triad#Availability|availability]].
- Applies to data that is [[Data states#At Rest|at rest]], but can theoretically be [[Data states#In Motion|in motion]] also.

# cards
>[!info] card
>An attack on {1:Confidentiality} (CIA) is called {2:Interception}.
^1658863648169

>[!info] card
>An attack on {1:Integrity/Availability} (CIA) is called {2:Interruption, Modification,Fabrication}(3).
^1658863648177

