# 🛡️ Full Ethical Hacking Guide & Course (CEH Notes)

![CEH](https://img.shields.io/badge/Course-CEH_v12-blue) ![Modules](https://img.shields.io/badge/Modules-20-green) ![Pages](https://img.shields.io/badge/Pages-859-orange) ![License](https://img.shields.io/badge/Use-Educational-red)

> A complete **Certified Ethical Hacker (CEH)** study guide — the full 859-page PDF plus the same content **split into 20 focused modules** so you can study topic-by-topic.

---

## 🚀 Start Here — Learning Path

**Beginner (Weeks 1–4):** Modules 01 → 05 — ethics, recon, scanning, enumeration, vulnerability analysis.
**Intermediate (Weeks 5–8):** Modules 06 → 12 — system hacking, malware, sniffing, social engineering, DoS, session hijacking, IDS evasion.
**Advanced (Weeks 9–12):** Modules 13 → 20 — web servers, web apps, SQLi, wireless, mobile, IoT/OT, cloud, cryptography.

**How to study each module:** 1) read the PDF → 2) build the lab below → 3) run the listed tools → 4) write your own notes.

## 📕 Full Guide

| File | Pages | Notes |
|------|-------|-------|
| [`CEH-Full-Guide.pdf`](./CEH-Full-Guide.pdf) | 859 | Complete guide (Git LFS) — download via the repo page, not raw preview |

## 📚 Modules (20)

| # | Module | File | Key Tools |
|---|--------|------|-----------|
| 01 | Introduction to Ethical Hacking | [`Module-01`](./modules/Module-01-Introduction-to-Ethical-Hacking.pdf) | Kali Linux, VirtualBox |
| 02 | Footprinting and Reconnaissance | [`Module-02`](./modules/Module-02-Footprinting-and-Reconnaissance.pdf) | whois, nslookup, Maltego, Shodan, Google Dorks |
| 03 | Scanning Networks | [`Module-03`](./modules/Module-03-Scanning-Networks.pdf) | Nmap, Hping3, NetScanTools |
| 04 | Enumeration | [`Module-04`](./modules/Module-04-Enumeration.pdf) | NetBIOS, SNMP, LDAP enum, SMBclient |
| 05 | Vulnerability Analysis | [`Module-05`](./modules/Module-05-Vulnerability-Analysis.pdf) | Nessus, OpenVAS, Nikto |
| 06 | System Hacking | [`Module-06`](./modules/Module-06-System-Hacking.pdf) | Metasploit, Mimikatz, John the Ripper |
| 07 | Malware Threats | [`Module-07`](./modules/Module-07-Malware-Threats.pdf) | Any.Run sandbox, VirusTotal, YARA |
| 08 | Sniffing | [`Module-08`](./modules/Module-08-Sniffing.pdf) | Wireshark, Ettercap, tcpdump |
| 09 | Social Engineering | [`Module-09`](./modules/Module-09-Social-Engineering.pdf) | SET, Gophish (lab only) |
| 10 | Denial of Service | [`Module-10`](./modules/Module-10-Denial-of-Service.pdf) | Hping3, LOIC (lab only) |
| 11 | Session Hijacking | [`Module-11`](./modules/Module-11-Session-Hijacking.pdf) | Burp Suite, Ettercap |
| 12 | Evading IDS, Firewalls & Honeypots | [`Module-12`](./modules/Module-12-Evading-IDS-Firewalls-and-Honeypots.pdf) | Nmap evasion, proxychains |
| 13 | Hacking Web Servers | [`Module-13`](./modules/Module-13-Hacking-Web-Servers.pdf) | Nikto, DirBuster, Metasploit |
| 14 | Hacking Web Applications | [`Module-14`](./modules/Module-14-Hacking-Web-Applications.pdf) | Burp Suite, OWASP ZAP, DVWA |
| 15 | SQL Injection | [`Module-15`](./modules/Module-15-SQL-Injection.pdf) | sqlmap, DVWA, bWAPP |
| 16 | Hacking Wireless Networks | [`Module-16`](./modules/Module-16-Hacking-Wireless-Networks.pdf) | Aircrack-ng, Reaver, Wifite |
| 17 | Hacking Mobile Platforms | [`Module-17`](./modules/Module-17-Hacking-Mobile-Platforms.pdf) | MobSF, ADB, Frida |
| 18 | IoT and OT Hacking | [`Module-18`](./modules/Module-18-IoT-and-OT-Hacking.pdf) | Shodan, Firmwalker, Binwalk |
| 19 | Cloud Computing | [`Module-19`](./modules/Module-19-Cloud-Computing.pdf) | ScoutSuite, Prowler, Pacu |
| 20 | Cryptography | [`Module-20`](./modules/Module-20-Cryptography.pdf) | OpenSSL, Hashcat, CyberChef |

## 🧪 Practice Labs (free & legal)

- **Web:** DVWA, bWAPP, OWASP Juice Shop, PortSwigger Web Security Academy
- **General:** TryHackMe (Pre-Security → SOC1 / Jr Pentester paths), HackTheBox Starting Point, VulnHub VMs
- **Network:** Metasploitable 2/3 in VirtualBox (host-only network)

## 🛠️ Setup

1. Install **VirtualBox/VMware** + **Kali Linux** VM.
2. Keep a **host-only / NAT lab network** — never scan networks you do not own.
3. `git lfs install` then clone this repo (PDFs use Git LFS).

## 🎯 CEH Exam Tips

- Focus on **methodology + tool flags** (especially Nmap, sqlmap, Burp, Aircrack).
- Memorize **attack phases**: Recon → Scanning → Gaining Access → Maintaining Access → Covering Tracks.
- Practice **100+ MCQs per module** before moving on.

## ⚠️ Disclaimer

**Educational purposes only.** Test only systems you own or have explicit written permission to assess. Unauthorized access is illegal.

## 🤝 Contributing

PRs welcome — fix typos, add labs, cheatsheets, or mind-maps per module.
