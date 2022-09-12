---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-07-23  23:21:06
modification date: 2022-07-23  23:20:33

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/unit_2-1-1
cards-deck: C836 - Fundamentals of security
Anki: 1

---

# Incident Response Process
## Preparation
- All the things you do before an incident occurs.
- Conduct regular [[Qualitative Risk Assessment#Qualitative Risk Assessment|Risk Assessments]]. (or [[Quantitative Risk Analysis|quantitative analysis]])
- Reduce your [[Attack Surface Analysis|attack surface]] as much as possible.

## Detection and Analysis
- Intrusion Detection System (IDS)
- Antivirus (AV)
- Firewall logs
- proxy logs
- Security information and event monitoring (SIEM) alerts
- Managed security service provider (MSSP)
- Detection tools mixed with human judgement decides what is an incident and what isn't.

## Containment
- This step begins the majority of the actual work when an incident occurs.
- To prevent more damage from happening
- Includes taking servers offline, updating firewall rules and Intrusion Prevention System (IPS) signatures.

## Eradication
- Attempt to remove the issue from your environment
- Start by tracing the propagation backwards and forwards through the system.

## Recovery
- Roll back to known good as needed
- re-image equipment as needed

## Post-Incident activity
- Preform a Postmortem report.
- to Gather the complete picture and details of the incident.
- Avoid finger-pointing or blame placing.
- Focus on improving the process.
- Compare the incident outcome to the historical [[Quantitative Risk Analysis|quantitative]]/[[Qualitative Risk Assessment|qualitative]] score.

# cards
>[!info] card
>The ==6== steps for incident response are ==Prep, Detect, Contain, Eradicate, Recover, and Post==.
^1658862356859

