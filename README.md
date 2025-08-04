# Task 1 - Local Network Port Scanning

## 🔧 Tools Used:
- Nmap (TCP SYN scan)
- Wireshark (optional)

## 🛰 My IP Range:
- 192.168.139.0/24

## 🔍 Findings:
- Device 1: 192.168.139.67 → Ports open: 135 (msrpc), 139 (netbios-ssn), 445 (microsoft-ds), 6646 (unknown), 7070 (realserver)
- Device 2: 192.168.139.96 → Ports open: 0
- Device 3: 192.168.139.158 → Ports open: 0, only filtered ports shown: 2077/tcp, 5060/tcp, 25734/tcp
- Device 4: 192.168.139.221 → Ports open: 0
- Device 5: 192.168.139.138 → Ports open: 0

## 📚 What I Learned:
- How to discover devices and open ports in a network.
- Meaning of common ports.
- Importance of securing unused or vulnerable ports.
- TCP SYN scan sends half-open connections (stealthy method).
- Firewall blocks unauthorized access to sensitive ports.

## 📂 Files in this Repo:

| File Name          | Description                          |
|--------------------|--------------------------------------|
| [README.md](README.md)             | This file (task explanation)       |
| [scan_results.txt](scan_results.txt) | Nmap scan output in text format    |
| [scan.xml](scan.xml)               | Nmap scan output in XML format     |
| ![Scan Screenshot](scan.png)       | Screenshot of terminal Nmap scan   
