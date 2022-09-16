---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-07-26  11:24:49
modification date: 2022-07-26  11:24:15

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836
cards-deck: C836 - Fundamentals of security
Anki: 3

---
#C836/unit_2-2-1 #C836/unit_2-1-1
# Chapter 1 exercises
1. Explain the difference between a vulnerability and a threat?
	- A [[2.1 - What is Information Security#Vulnerabilities|vulnerability]] is a weakness in the given system, physical, or otherwise.
	-  A [[2.1 - What is Information Security#threats|threat]] is an attacker who may take advantage o f a vulnerability.
2. What are six items that might be considered logical controls?
	- [[Risk mitigation, controls#Logical or technical|logical controls]]
		- Intrusion Prevention system (IPS)
		- Intrusion Detection system (IDS)
		- Multifactor authentication (MFA)
		- Firewalls
		- [[Least Privilege Principle#Least Privilege|least privilage principle]]
		- [[Least Privilege Principle#Implicit Deny|implicit deny]]
3. What term might you use to describe the usefulness of data?
	- The [[Parkerian Hexad#Utility|utility]] of the data.
4. Which category of attack is an attack against confidentiality?
	- [[Types of attacks#Interception|interception]]
5. How do you know at what point you can consider your environment to be secure?
>[!quote] Eugine Spaford
>The only truly secure computer is one that is powered off, cast in a block of concrete inside a lead lined room with armed guards - And even then I have my doubts.
6. Using the concept of defense in depth, what layers might you use to secure yourself against someone removing confidential data from your environment on a USB flash drive.
	- Data, with encryption
	- Application, with access control
	- Host, with access control
7. Based on the Parkerian hexad, what principles are affected if you lose a shipment of encrypted backup tapes that contain personal and payment information for your customers?
	- [[Parkerian Hexad#Possession|Possession]]
8. If the web servers in your environment are based on Microsoft's Internet Information Services (IIS) and a new worm is discovered that attacks Apache web servers, what do you not have?
	- A vulnerability
9. If you develop a new policy for your environment that requires you to use complex and automatically generated passwords that are unique to each system and are a minimum of 30 chars in length, such as `!Qa4(j0nO$&xn1%2AL34ca#!Ps321$,` what will be adversely impacted?
	- Availability, or more accurately, the usability of the system.
10. Considering the CIA triad and the Parkerian hexad, what are the advantages and disadvantages of each model?
	- The CIA triad is a simpler guideline, but doesn't consider several things the parkerian hexad does.
	- The CIA triad is also more restrictive than the parkerian hexad.


## Cards

>[!info] card
>A ==vulnerability== is a weakness in the given system that can be exploited.
^1658860877741

>[!info] card
>A ==threat== is an attacker who will take advantage of a vulnerability.
^1658860877753

# Chapter 2 exercises
1. What is the difference between verification and authentication of an identity?
	- [[Identification]] just asks who you are.
	- [[Verification]] asks the user to provide proof they are who they say.
	- [[Authentication]] takes the proof from verification, and compares it to a known database or repository for truth.
2. How do you measure the rate at which you fail to authenticate legitimate users in a biometric system?
	- [[Biometrics#Biometrics Performance|False Rejection Rate (FRR)]].
3. What do you call the process in which the client authenticates to the server and the server authenticates to the client?
	- [[Mutual Authentication]]
4. A key would be described as which type of authentication factor?
	- [[Factors#Something you have|Something you have]].
5. What biometric factor describes how well a characteristic resists change over time?
	- [[Biometrics#Characteristics of Biometric Factors|permanance]].
6. If you're using an identity card as the basis for your authentication scheme, what steps might you add to the process to allow you to move to multifactor authentication?
	- Including a different factor, such as [[Factors#Something you know|something you know]].
7. If you're using an eight-character password that contains only lowercase characters, would increasing the length to ten characters represent any significant increase in strength?
	- Not really, adding numbers, upper-case letters and symbols will add to the strength.
8. Name three reasons why an identity card alone might not make an ideal method of authentication.
	- An identity card can be forged/stolen
	- An identity card without back-end verification is just a piece of plastic
	- An identity card does not provide an easy input method.
9. What factors might you use when implementing a multifactor authentication scheme for users who are logging onto workstations that are in a secure environment and are used by more than one person?
	- [[Factors#Something you know|something you know]] and [[Factors#Something you have|something you have]].
10. If you're developing a multifactor authentication system for an environment where you might find a larger than average number of disabled or injured users, such as a hospital, which authentication factors might you want to use or avoid? Why?
	- Avoiding [[Biometrics]]/[[Factors#something you are|something you are]] due to some users not possessing the same physical ability to authenticate.
	- I'd also avoid factors that fall under [[Factors#somethin you do|something you do]] because some users may lack the ability to authenticate, such as handwriting or gait.
## Cards

>[!info] card
>In order of least to most secure, {1:Identification}, {2:Verification}, {3:Authentication}.
^1659027450157
