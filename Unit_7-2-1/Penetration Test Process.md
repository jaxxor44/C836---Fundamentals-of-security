---
aliases: [Penetration Test Process]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-07  12:54:45
modification date: 2022-08-07  12:54:28

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_7-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# Penetration Testing Process
![[Pasted image 20220807125517.png]]
- Relatively standardized process.
- With some variation, the general process is the same.
- For someone hired to do an assessment, documentation is everything.

## Scoping
- Its important to discuss with the client ahead of time, what the scope (or Rules of engagement) of the test will be.
- The client may wish to include "all assets of the company" or only a specific IP range.
- The client may want to exclude all production servers, to prevent down time or excess traffic load.
- The client may stipulate other rules of engagement, like times of day, disclosure procedure or "knock it off" procedures.
- The scope should represent a realistic attack sector and not unrealistically remove capability, like chained attacks.
- this stage should clearly define the [[Penetration Test targets]].
## Reconnaissance
- The research you conduct before attempting any attacks against a target.
- Includes things like [[Open Source Intelligence|OSINT]]. 
- Mostly a passive activity, falls just short of directing tools against the target.
- This step may include many parts of a [[Vulnerability Assessment]].
## Discovery
- Direct specific tools against services of the target.
- Investigate leads, probe open ports for services.
- conduct recon on further collected information.
## Exploitation
- Exploit vulnerabilities that are detected in earlier stages.
- chain multiple vulnerabilities together.
- findings from exploitation may result in looping back to the recon phase.
## Reporting
- Carefully document what was discovered and what exact steps you need to reproduce the attacks that where successfully carried out.
