<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-Learning%20Resources-1e3a8a?style=for-the-badge" alt="cybersecurity learning resources">
</p>

<h1 align="center">Cybersecurity Learning Resources</h1>

<p align="center">
  A curated, beginner-to-advanced collection of free cybersecurity learning material —<br>
  official docs, free PDFs, and hands-on labs, sourced only from reputable publishers.
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/CyberChef-Aidoo/cybersecurity-learning-resources?style=for-the-badge" alt="stars">
  <img src="https://img.shields.io/github/forks/CyberChef-Aidoo/cybersecurity-learning-resources?style=for-the-badge" alt="forks">
  <img src="https://img.shields.io/github/license/CyberChef-Aidoo/cybersecurity-learning-resources?style=for-the-badge" alt="license">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-blue?style=for-the-badge" alt="level">
  <img src="https://img.shields.io/badge/Sources-NIST%20%7C%20OWASP%20%7C%20MITRE-darkred?style=for-the-badge" alt="sources">
</p>

---

## About

This repo exists to solve one problem: **most "free cybersecurity resources" lists point to pirated PDF reuploads or dead links.** Everything linked here traces back to the original publisher — NIST, OWASP, MITRE, or the platform itself (PortSwigger, TryHackMe, Cryptopals) — so links stay current and content stays legitimate.

Resources are organized by skill level, not just topic, so you can follow this roughly top-to-bottom as a self-paced curriculum, or jump straight to whichever tier matches where you're at.

## Table of Contents

- [🟢 Beginner](#-beginner)
  - [Networking Fundamentals](#networking-fundamentals)
  - [Operating Systems](#operating-systems-linux--windows)
  - [Security Fundamentals](#security-fundamentals)
  - [Beginner Certifications](#beginner-certifications-worth-knowing-about)
- [🟡 Intermediate](#-intermediate)
  - [Web Application Security](#web-application-security)
  - [Cryptography](#cryptography)
  - [Penetration Testing Basics](#penetration-testing-basics)
  - [Incident Response Basics](#incident-response-basics)
- [🔴 Advanced](#-advanced)
  - [Offensive Security / Red Team](#offensive-security--red-team)
  - [Defensive Security / Blue Team](#defensive-security--blue-team)
  - [Cloud & Modern Infrastructure Security](#cloud--modern-infrastructure-security)
  - [Research-Level / Deep Technical](#research-level--deep-technical)
- [How to Use This List](#how-to-use-this-list)
- [A Note on PDFs](#a-note-on-pdfs)
- [Contributing](#contributing)

---

## 🟢 Beginner

### Networking Fundamentals
- [Professor Messer's Free Network+ Course](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/) — full video course, no cost
- [Cisco Networking Academy](https://www.netacad.com/) — free intro networking courses
- Concepts to nail down first: OSI Model, TCP/IP, DNS, DHCP, subnetting, routing basics

### Operating Systems (Linux & Windows)
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — learn the Linux command line through a hands-on wargame, completely free
- [Linux Journey](https://linuxjourney.com/) — free, structured Linux fundamentals
- [Microsoft Learn](https://learn.microsoft.com/en-us/training/) — free training on Active Directory, Registry, PowerShell

### Security Fundamentals
- [NIST SP 800-12 — An Introduction to Computer Security: The NIST Handbook](https://csrc.nist.gov/pubs/sp/800/12/r1/final) — free official PDF covering the CIA Triad, risk management, and access control
- [TryHackMe: Pre-Security Path](https://tryhackme.com/path/outline/presecurity) — free/freemium guided intro path

### Beginner Certifications Worth Knowing About
- **CompTIA Security+** — paid exam, but Professor Messer's full Security+ course is free
- **Google Cybersecurity Certificate** (Coursera) — free to audit

---

## 🟡 Intermediate

### Web Application Security
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — free, widely regarded as the gold standard for hands-on web security training (SQLi, XSS, SSRF, IDOR, and more)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — official free PDF, the definitive list of critical web application security risks
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) — short, practical, topic-by-topic guidance
- [OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/) — free, comprehensive PDF on how to actually test for vulnerabilities

### Cryptography
- [Cryptopals Crypto Challenges](https://cryptopals.com/) — free, hands-on cryptography puzzles that build real understanding, not just theory
- [NIST Cryptographic Standards & Guidelines](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines) — official specs for AES, RSA, hashing standards

### Penetration Testing Basics
- [TryHackMe: Jr Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester) — free tier covers a solid chunk of this
- [HackTheBox Academy](https://academy.hackthebox.com/) — some modules free, others paid
- Tools to get comfortable with: Nmap, Burp Suite (Community Edition), Wireshark

### Incident Response Basics
- [NIST SP 800-61 — Computer Security Incident Handling Guide](https://csrc.nist.gov/pubs/sp/800/61/r2/final) — free official PDF, the standard reference for IR processes

---

## 🔴 Advanced

### Offensive Security / Red Team
- [MITRE ATT&CK Framework](https://attack.mitre.org/) — the industry-standard knowledge base of real-world adversary tactics and techniques
- Active Directory attack paths (Kerberoasting, LLMNR poisoning, BloodHound) — best learned via TryHackMe/HackTheBox advanced paths
- [PTES — Penetration Testing Execution Standard](http://www.pentest-standard.org/) — free, defines a professional pentest methodology end to end

### Defensive Security / Blue Team
- [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) — free official PDF, the framework most organizations structure their security programs around
- [MITRE D3FEND](https://d3fend.mitre.org/) — the defensive counterpart to ATT&CK, mapping countermeasures to techniques

### Cloud & Modern Infrastructure Security
- [NIST SP 800-207 — Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final) — free official PDF
- [Kubernetes Official Security Docs](https://kubernetes.io/docs/concepts/security/) — free, authoritative

### Research-Level / Deep Technical
- [freecomputerbooks.com — Security Section](https://freecomputerbooks.com/compscspecialSecurityBooks.html) — curated list of legitimately open-access security books
- [USENIX Security Symposium — Free Proceedings](https://www.usenix.org/conferences/byname/108) — cutting-edge published security research, free to read

---

## How to Use This List

1. Don't try to read everything front-to-back — pick the tier matching your current level and work through it alongside hands-on practice.
2. Treat the **official PDFs (NIST, OWASP)** as reference material to revisit, not one-time reads — they're dense and meant to be looked up as needed.
3. Pair each theory resource with something hands-on where possible — e.g. read the OWASP Top 10 entry on SQL injection, then immediately try the matching PortSwigger Academy lab.

## A Note on PDFs

The safest, always-current PDFs are the official government/standards-body ones (NIST, OWASP) linked throughout — free to download directly from the source, no login or paywall. For books, the `freecomputerbooks.com` link points to genuinely open-access/author-released titles rather than pirated reuploads — worth checking each book's own license page before relying on it for anything formal.

## Contributing

Found a dead link, or a resource that belongs here? Open an issue or a pull request. Please only submit resources that are **free and legitimately sourced** — no pirated PDF reuploads or paywalled content disguised as free.

---

<p align="center">
  Part of my broader cybersecurity learning journey — see <a href="https://github.com/CyberChef-Aidoo/CyberSecurity-Projects">100 Days of Building Cybersecurity Projects</a>.
</p>
