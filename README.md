# Apexplanet-task4-cybersecurity-internship
# Task 4 – Cybersecurity Internship

## Objective

The objective of Task 4 is to perform practical cybersecurity activities in a controlled lab environment using Kali Linux and Metasploitable2. The task demonstrates vulnerability assessment, exploitation, password auditing, password cracking, phishing awareness, and system hardening.

---

## Lab Environment

- Attacker Machine: Kali Linux
- Target Machine: Metasploitable2
- Virtualization: Oracle VirtualBox
- Network: Host-Only Network

---

## Tools Used

- Nmap
- Metasploit Framework
- Hydra
- John the Ripper
- OpenSSL
- SSH

---

# Activities Performed

## 1. Service Enumeration

Performed service discovery using Nmap to identify open ports and running services.

Example:

```bash
nmap -sV 192.168.56.102
```

---

## 2. Exploitation using Metasploit

Used the DistCC Remote Command Execution vulnerability.

Module:

```
exploit/unix/misc/distcc_exec
```

Payload:

```
cmd/unix/generic
```

Successfully executed remote Linux commands.

---

## 3. Password Auditing

Created username and password wordlists and demonstrated password auditing using Hydra against the SSH service.

---

## 4. Password Cracking

Generated a password hash using OpenSSL and cracked it using John the Ripper with a custom wordlist.

---

## 5. Phishing Awareness

Created a phishing awareness example to explain how phishing attacks work and discussed methods to identify and prevent phishing attempts.

---

## 6. System Hardening

Performed basic Linux security checks and discussed best practices including:

- Regular system updates
- Firewall usage
- Least privilege principle
- Strong password policies
- Disabling unnecessary services

---

# Learning Outcomes

- Service Enumeration
- Vulnerability Assessment
- Remote Command Execution
- Password Auditing
- Password Cracking
- Social Engineering Awareness
- Linux System Hardening

---

# Disclaimer

This project was performed in an isolated virtual lab environment using authorized systems strictly for educational purposes.

---

# Author

ANKALA VENKATA RAGHU

Cybersecurity Internship – Task 4
