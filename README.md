# Nmap Scanning Lab (Kali → Ubuntu)

This project is part of my cybersecurity home lab, where I scan an Ubuntu target machine using Kali Linux.  
It covers basic and detailed Nmap scans, results, screenshots, and notes.

---

## Purpose of This Lab
- Learn and practice penetration testing safely  
- Understand how network scanning works  
- Create documentation for a cybersecurity portfolio  
- Build workflow using Git, GitHub, Kali, and VirtualBox  

---

## Lab Setup

| Component | Details |
|----------|---------|
| Host OS  | Windows |
| Attacker Machine | Kali Linux (VirtualBox) |
| Target Machine | Ubuntu Linux (VirtualBox) |
| Network Type | NAT + Host-Only Adapter |
| Tools Used | Nmap, Git, GitHub |

---

## Repository Structure
```plaintext
Nmap-Scanning-Lab/
│
├── README.md                # Main documentation of the project
│
├── Commands-Used/           # All Nmap commands used during the scans
│   └── basic-scans.txt
│
├── Scan-Results/            # Raw scan outputs
│   └── ubuntu-basic-scan.txt
    └──   ubuntu-aggressive-scan.txt 
│
├── Screenshots/             # Screenshots of terminal outputs
│   └── <images go here>
│
└── Notes/                   # Personal notes, observations, learnings
    └── nmap-notes.md

