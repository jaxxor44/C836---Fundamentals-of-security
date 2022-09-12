---
aliases: [IoT device, IoT]
banner: "![[Security shield background.jpg]]"
banner_lock: True
created: 2022-08-07  10:31:37
modification date: 2022-08-07  10:31:27

Class: C836 - Fundamentals of security
Source: Foundations of Information Security A Straightforward Introduction
tags: C836/Unit_7-1-1
cards-deck: C836 - Fundamentals of security
Anki: None

---

# IoT device
- basically an [[Embedded systems|embedded system]], with an internet connection.
	- More commonly defined as "Any device with an internet connection that doesn't run a full desktop operating system."
- Now spans to include almost every appliance you own and more.
	- Printers
- Generally runs an RTOS based on Linux.
- If you have the ability, its best to force IoT devices onto individual virtual private network.
	- This creates a virtual choke point to monitor the extent of the data traffic.
	- This can be done with tools like [mitmproxy](https://mitmproxy.org/).
## Printers
- often overlooked, but still an IoT device.
- reasonable amount of memory
- implicitly trusted by workers.
- most recently breached by the `KRACK` vulnerability, allowing WIFI eavesdropping and sensitive document access.
## Surveillance Cameras
- Some manufacturers do quality and security testing.
- Aside from the top several manufacturers, manufacturers rely on security through obscurity.
- Misconfigurations can easily leave the camera feeds vulnerable.
## Smart Devices
- prolific and growing, smart locks for example.
- Largest security vulnerability is users never change the default password.
- Updating devices that have lifespans in the decades, mean updates and maintenance are nearly impossible.
- The best method to secure these devices is [[Defense in depth]].