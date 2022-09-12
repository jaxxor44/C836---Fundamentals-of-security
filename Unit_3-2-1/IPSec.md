---
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-01  20:33:39
modification date: 2022-08-01  20:33:06

Class: C836 - Fundamentals of security
Source: Udemy
tags: C836/Unit_3-2-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# IPSec
- Authenticates and encrypts packets sent over an IP network.
### Authentication Header (AH)
- provides a mechanism for authentication
- does __NOT__ provide a way to encrypt.
### Encapsulating Security Payload (ESP)
- Provides a mechanism for authentication
- Provides a mechanism for encryption

## Modes
### Tunnel mode
- protects the data and internal routing data
- commonly used for site-to-site [[VPN#VPNs|VPNs]].
- NAT is supported with tunnel mode.

### Transport mode
- only encrypts the payload (data) and ESP trailer.
- Header of the original packet is NOT encrypted
- used for Client-to-site connections
- NAT not supported.

