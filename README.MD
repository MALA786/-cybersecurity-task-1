Objective
Learn to discover open ports on devices in the local network using Nmap, understand network exposure, and perform basic reconnaissance.

---

Tools Used
Nmap— Port scanning and network mapping.
Wireshark— Packet analysis.
Operating System-[Kali Linux]

---
Steps Performed

1. Installed Nmap
Downloaded Nmap from: https://nmap.org/download.html
Installed it on my system successfully.

2. Found Local IP Range
Command used:
On Linux: `ifconfig` or `ip a`
Identified my network IP range as: `192.168.1.0/24`

3. Performed TCP SYN Scan using Nmap
 Command executed:
