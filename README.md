# Wireshark
# Task 5: Network Packet Capture and Analysis using Wireshark

##  Project Overview

This project demonstrates basic network traffic capture and protocol analysis using Wireshark. The goal was to identify at least 3 different protocols from live network traffic and summarize the key findings.

---

##  Files Included

- `task5capture.pcapng` – Packet capture file recorded using Wireshark.
- `README.md` – This report summarizing the findings.

---

## Protocols Identified

1. **DNS** – Used to resolve domain names to IP addresses.
2. **TCP** – Transmission Control Protocol for reliable data transmission.
3. **TLS** – Used for encrypted communication (e.g., HTTPS).

---

##Packet Analysis

###  Packet 1
- **Protocol:** DNS  
- **Source IP:** 192.168.X.X  
- **Destination IP:** 8.8.8.8  
- **Info:** Standard query for `www.google.com`

###  Packet 2
- **Protocol:** TCP  
- **Source IP:** 192.168.X.X  
- **Destination IP:** 142.250.XXX.XXX  
- **Info:** TCP three-way handshake (SYN)

###  Packet 3
- **Protocol:** TLS  
- **Source IP:** 192.168.X.X  
- **Destination IP:** 142.250.XXX.XXX  
- **Info:** TLS Client Hello

---

##  Summary

- Used Wireshark to capture live packets from an active network interface.
- Successfully identified and filtered DNS, TCP, and TLS protocols.
- Analyzed packet-level details to understand communication flow.
- Gained hands-on experience with protocol analysis and packet structures.

---

## 🛠 Tools Used

- Wireshark (GUI)
- Linux OS for capture
