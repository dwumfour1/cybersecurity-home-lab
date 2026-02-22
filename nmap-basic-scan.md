# Nmap Basic Network Scan

## Objective
To identify open ports and running services on a target machine within my local lab environment.

## Lab Environment
- Host OS: Windows 10
- Virtualization: VMware Workstation Pro
- Attacker Machine: Kali Linux
- Target: Local network device (lab only)

## Command Used
nmap -sS 192.168.1.1

## Explanation of Command
- -sS : TCP SYN (Stealth) Scan
- 192.168.1.1 : Target IP address within local network

## Results
The scan identified:
- Port 80 (HTTP) – Open
- Port 443 (HTTPS) – Open

## Key Learnings
- How to identify open ports on a system
- Understanding common service ports
- Difference between open, closed, and filtered ports

## Reflection
This lab improved my understanding of reconnaissance techniques used in cybersecurity and strengthened my ability to analyze network exposure in a controlled environment.
