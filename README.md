<h1 align="center">Hi there, I'm Abdelrahman Fekry El-Maghraby 👋</h1>
<h3 align="center">Cybersecurity Specialist | Penetration Testing | Cloud & Kubernetes Security</h3>

<p align="center">
  Cybersecurity professional combining hands-on offensive security and OSINT with a strong network and systems foundation. Recently chained web, container, and Kubernetes flaws to reach a live cloud cluster's data plane, and built an AI-assisted ransomware detector.
</p>

---

## 🎯 Core Focus & Technical Skills

- **Offensive Security & Pentesting:** Web Application Penetration Testing, SQL Injection, OS Command Injection / RCE, Privilege Escalation, Lateral Movement, Vulnerability Assessment, Burp Suite, Metasploit, Nmap, Wireshark
- **OSINT & Reconnaissance:** Open-Source Intelligence (OSINT), Sherlock, Shodan, FOCA, Footprinting & Reconnaissance
- **Cloud & Kubernetes Security:** Amazon EKS, Kubernetes RBAC, Service Accounts & Tokens, Pod Exec (SPDY/WebSocket), Secrets & ConfigMaps, NetworkPolicies, Admission Control, Container Security
- **Threat Detection & Analysis:** Threat Detection, Incident Analysis, Threat Intelligence, Static & Behavioural Malware Analysis
- **Systems & Networking:** Linux Administration (CLI), Windows Server, Active Directory, Group Policy (GPO), VMware, Routing & Switching (CCNA), VLANs, Subnetting
- **Programming & Automation:** Python (Security Automation), Bash Scripting, REST API Interaction, JSON

## 💼 Professional Experience & Activities

- **IT Support Specialist | Egyptian European Co.** *(Jan 2023 - Jun 2026)* Provided day-to-day IT support, maintained the office network (routers, switching, Wi-Fi), administered Windows systems and user accounts, and maintained CCTV/surveillance systems.
- **Technical Member | Cyber Security Club - Arab Open University (AOU)** *(Feb 2023 - Oct 2023)* Researched emerging cyber threats. Delivered a recorded technical session introducing OSINT methodology and tooling (Sherlock, Shodan, FOCA).

## 🚀 Security Projects, Assessments & Scripts

### [Thndr Security CTF - Internship Security Assessment](https://github.com/zzddf656666/Thndr-Security-CTF-Writeup)

- Solo cloud-native penetration test against a live Amazon EKS environment (eu-central-1) - captured 4 of 5 flags.
- Bypassed authentication via SQL injection and achieved RCE as root via OS command injection.
- Escalated into the Kubernetes API by abusing auto-mounted SA tokens and over-permissive RBAC.
- Moved laterally between pods via K8s exec API (SPDY/WebSocket).

### [Hybrid Ransomware Detection System](https://github.com/zzddf656666/hybrid-ransomware-detector)

- Multi-layered scanner for PDF and Word documents: fuses a local malware-hash dataset (chunked MD5/SHA-256 hashing), VirusTotal multi-engine reputation, and LLM semantic analysis into a single 0-10 severity score.
- Hardened the LLM layer against prompt injection (system/user role isolation, temperature 0) and kept all API keys in a local `.env`, never in code.
- OCR fallback (Tesseract + Poppler) for scanned/image-only PDFs, scheduled background scans, and cross-platform autostart at login - Windows registry, macOS launchd, Linux systemd - on x86_64 and ARM64.
- Detailed JSON report + human-readable TXT summary per scan.

### [Linux System Maintenance Script](https://github.com/zzddf656666/linux-maintain)

- Safe, idempotent Bash maintenance tool for Debian, Ubuntu, and Kali: apt updates/upgrades, package repair, hardware-detected firmware/GPU drivers/microcode, and SSD TRIM.
- Safe-by-default design with strict error handling (`set -Eeuo pipefail`); high-risk repairs (mirror repair, storage tuning, forced drivers) are strictly opt-in, previewable with `--dry-run`, and back up every file they touch.
- Detects bare-metal vs VM vs WSL and adapts; multi-arch (amd64/arm64/i386) with systemd-timer automation support.

## 🎓 Education

- **B.Sc. in Computer Science - Networking & Cybersecurity** | Dual Degree: Arab Open University & The Open University (UK) (2021-2026)

## 📜 Certifications

- **Certified Ethical Hacker (CEH)** - EC-Council
- **Network Defense Essentials (NDE)** - EC-Council
- **CCNA** - NTI (Switching, Routing & Wireless Essentials; Enterprise Networking, Security & Automation)
- **Linux 100: Fundamentals** - TCM Security (2026)
- **Introduction to Cybersecurity** - Cisco
- **Network Security** - Cisco

## 📫 Connect with me

- **LinkedIn:** [Abdelrahman El-Maghraby](https://www.linkedin.com/in/abdelrahman-el-maghraby-994a8b226/)
- **HackTheBox:** [Profile](https://profile.hackthebox.com/profile/019e1eae-dc09-7174-9efb-4309ba61f873)
- **TryHackMe:** [Profile](https://tryhackme.com/p/maghraby6271)
- **YouTube:** [OSINT Introduction Session](https://youtu.be/b_X51kkBIq4?si=dennIN9BeMU6vX-L)
- **Email:** <abdelrahmanfekrymaghrby@gmail.com>
- **CyLab Academy:** [Profile](https://learn.cylabacademy.org/users/zzddf656666)
