<div align="center">

# Abdelrahman El-Maghraby

### Offensive Security · Penetration Testing · Cloud & Kubernetes Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelrahman-el-maghraby/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdelrahman-El-Maghraby)
[![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://profile.hackthebox.com/profile/019e1eae-dc09-7174-9efb-4309ba61f873)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/maghraby6271)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/b_X51kkBIq4)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abdelrahmanfekrymaghrby@gmail.com)

</div>

---

## whoami

Cybersecurity professional pairing hands-on **offensive security** and **OSINT** with a strong network and systems foundation. Recently chained web, container, and Kubernetes flaws to reach a live Amazon EKS cluster's data plane, and built an AI-assisted ransomware detector. B.Sc. in Computer Science (Networking & Cybersecurity); **CEH** certified.

I work the full attack chain — web exploitation → RCE → container foothold → **Kubernetes RBAC abuse, lateral movement, and privilege escalation** — and build the defensive tooling to match.

## 🎯 Core Focus & Technical Skills

- **Offensive Security & Pentesting:** Web Application Penetration Testing, SQL Injection, OS Command Injection / RCE, Privilege Escalation, Lateral Movement, Vulnerability Assessment, Burp Suite, Metasploit, Nmap, Wireshark
- **Cloud & Kubernetes Security:** Amazon EKS, Kubernetes RBAC, Service Accounts & Tokens, Pod Exec (SPDY/WebSocket), Secrets & ConfigMaps, NetworkPolicies, Admission Control, Container Security
- **OSINT & Reconnaissance:** Open-Source Intelligence (OSINT), Sherlock, Shodan, FOCA, Footprinting & Reconnaissance
- **Threat Detection & Analysis:** Threat Detection, Incident Analysis, Threat Intelligence, Static & Behavioural Malware Analysis
- **Systems & Networking:** Linux Administration (CLI), Windows Server, Active Directory, Group Policy (GPO), VMware, Routing & Switching (CCNA), VLANs, Subnetting
- **Programming & Automation:** Python (Security Automation), Bash Scripting, REST API Interaction, JSON

## 🧰 Arsenal

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
&nbsp;
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
&nbsp;
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2B2B2B?style=flat-square&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![YARA](https://img.shields.io/badge/YARA-00599C?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 🚀 Featured Projects

### [Thndr Security CTF — Internship Security Assessment](https://github.com/zzddf656666/Thndr-Security-CTF-Writeup)

- Solo cloud-native penetration test against a live Amazon EKS environment (eu-central-1) — captured 4 of 5 flags.
- Bypassed authentication via SQL injection and achieved RCE as root via OS command injection.
- Escalated into the Kubernetes API by abusing auto-mounted SA tokens and over-permissive RBAC; enumerated rights with `SelfSubjectRulesReview` and read protected cluster Secrets.
- Moved laterally between pods via the K8s exec API (SPDY/WebSocket) and escalated by deploying a custom PodSpec under a target identity; every finding mapped to concrete remediations (CWE/CVSS + MITRE ATT&CK).

### [Hybrid Ransomware Detection System](https://github.com/zzddf656666/hybrid-ransomware-detector)

- Seven-layer scanner for PDF and Word documents fusing cryptographic + fuzzy/structural hashing (TLSH/ssdeep), VBA-macro triage, a YARA engine, VirusTotal, and a local-first LLM into an explainable 0–100 risk score.
- Hardened the LLM layer against prompt injection (system/user role isolation, temperature 0) and kept all API keys in a local `.env`, never in code.
- OCR fallback (Tesseract + Poppler) for scanned/image-only PDFs, scheduled background scans, and cross-platform autostart — Windows registry, macOS launchd, Linux systemd — on x86_64 and ARM64.
- Desktop GUI (CustomTkinter dark dashboard: live scan progress, per-layer results, report browser) alongside a fully independent CLI; detailed JSON + TXT report per scan.

### [Linux System Maintenance Tool](https://github.com/zzddf656666/linux-maintain)

- Safe, idempotent Bash maintenance & security-audit tool for Debian, Ubuntu, and Kali: apt updates/upgrades, package repair, hardware-detected firmware/GPU drivers/microcode, and SSD TRIM.
- Safe-by-default design with strict error handling (`set -Eeuo pipefail`); high-risk repairs are strictly opt-in, previewable with `--dry-run`, and back up every file they touch.
- Pre-upgrade snapshots, SUID/world-writable and SSH-posture audits, an attack-surface summary, and failure alerting; detects bare-metal vs VM vs WSL and is multi-arch (amd64/arm64/i386) with systemd-timer automation.

## 💼 Professional Experience

- **IT Support Specialist — Egyptian European Co.** *(Jan 2023 – Jun 2026)* — Provided company-wide IT support, maintained the office network (routing, switching, Wi-Fi), administered Windows systems and user accounts, and maintained CCTV/surveillance systems.
- **Technical Member — Cyber Security Club, Arab Open University (AOU)** *(Feb 2023 – Oct 2023)* — Researched emerging threats and delivered a [recorded technical session on OSINT methodology and tooling](https://youtu.be/b_X51kkBIq4) (Sherlock, Shodan, FOCA).

## 🎓 Education

- **B.Sc. in Computer Science — Networking & Cybersecurity** — Dual Degree: Arab Open University & The Open University (UK) (2021–2026)

## 📜 Certifications

- **CEH** — Certified Ethical Hacker (EC-Council)
- **Network Security** — Cisco
- **CCNA** — National Telecommunication Institute (NTI)
- **NDE** — Network Defense Essentials (EC-Council)
- **Linux 100: Fundamentals** — TCM Security (2026)
- **Introduction to Cybersecurity** — Cisco

## 📫 Connect

- **LinkedIn:** [Abdelrahman El-Maghraby](https://www.linkedin.com/in/abdelrahman-el-maghraby/)
- **Hack The Box:** [Profile](https://profile.hackthebox.com/profile/019e1eae-dc09-7174-9efb-4309ba61f873)
- **TryHackMe:** [Profile](https://tryhackme.com/p/maghraby6271)
- **YouTube:** [OSINT Introduction Session](https://youtu.be/b_X51kkBIq4)
- **CyLab Academy:** [Profile](https://learn.cylabacademy.org/users/zzddf656666)
- **Email:** <abdelrahmanfekrymaghrby@gmail.com>
