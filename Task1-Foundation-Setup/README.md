# Task 1: Foundation & Environment Setup

**Timeline:** Days 1–12
**Objective:** Build cybersecurity fundamentals and set up an isolated penetration testing lab.

## What was done
- Installed VirtualBox and set up two VMs:
  - **Kali Linux 2026.2** — attacker machine (2048 MB RAM, 2 vCPUs)
  - **Metasploitable2** — deliberately vulnerable target machine (1024 MB RAM)
- Configured both VMs on a **Host-only Adapter** to isolate the lab from the real network
- Verified connectivity between Kali and Metasploitable2 using `ping`
- Captured and analyzed ICMP traffic using **Wireshark**
- Studied core concepts: CIA Triad, threat types, Linux fundamentals, networking (OSI/TCP-IP/subnetting), and cryptography basics

## Lab network details
| Machine | IP Address | Role |
|---|---|---|
| Kali Linux | 192.168.56.101 | Attacker |
| Metasploitable2 | 192.168.56.102 | Target |

## Deliverables
- [Lab Setup Report (PDF)](./Task1_Lab_Setup_Report.docx)
- [Linux Command Cheat-Sheet](./linux-cheatsheet.md)
- [Networking Notes](./networking-notes.md)

## Key screenshots
- Kali Linux desktop running
- Metasploitable2 login confirmed
- Successful ping test (0% packet loss)
- Wireshark ICMP packet capture
