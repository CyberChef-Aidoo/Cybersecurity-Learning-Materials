# Cybersecurity Learning Resources — Beginner to Advanced

A curated set of free, legitimate learning material — official docs, free PDFs, and hands-on labs — organized by level. Everything here links to the original publisher.


## 🟢 Beginner

### Networking Fundamentals
- [Professor Messer's Free Network+ Course](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/) — full video course, no cost
- [Cisco Networking Basics (Cisco Networking Academy)](https://www.netacad.com/) — free intro networking courses
- Concepts to nail down first: OSI Model, TCP/IP, DNS, DHCP, subnetting, routing basics

### Operating Systems (Linux & Windows)
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — learn Linux command line through a hands-on wargame, completely free
- [Linux Journey](https://linuxjourney.com/) — free, structured Linux fundamentals
- Windows: Active Directory basics, Registry, PowerShell — [Microsoft Learn (free)](https://learn.microsoft.com/en-us/training/)

### Security Fundamentals
- [NIST — An Introduction to Computer Security: The NIST Handbook (SP 800-12)](https://csrc.nist.gov/pubs/sp/800/12/r1/final) — free official PDF, foundational read on CIA Triad, risk management, access control
- [TryHackMe: Pre-Security Path](https://tryhackme.com/path/outline/presecurity) — free/freemium guided intro path

### Beginner Certifications Worth Knowing About
- CompTIA Security+ (paid exam, but many free study resources exist — Professor Messer's Security+ course is free)
- Google Cybersecurity Certificate (Coursera — free to audit)

---

## 🟡 Intermediate

### Web Application Security
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — completely free, widely regarded as the gold standard for hands-on web security training (SQLi, XSS, SSRF, IDOR, and more)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — official free PDF, the definitive list of the most critical web application security risks
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) — short, practical, topic-by-topic security guidance
- [OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/) — free, comprehensive PDF on how to actually test for vulnerabilities

### Cryptography
- [Cryptopals Crypto Challenges](https://cryptopals.com/) — free, hands-on cryptography puzzles that build real understanding (not just theory)
- [NIST Cryptographic Standards & Guidelines](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines) — official specs for AES, RSA, hashing standards, etc.

### Penetration Testing Basics
- [TryHackMe: Jr Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester) — free tier covers a solid chunk of this
- [HackTheBox Academy — free modules](https://academy.hackthebox.com/) — some modules free, others paid
- Tools to get comfortable with: Nmap, Burp Suite (Community Edition), Wireshark

### Incident Response Basics
- [NIST SP 800-61: Computer Security Incident Handling Guide](https://csrc.nist.gov/pubs/sp/800/61/r2/final) — free official PDF, the standard reference for IR processes

---

## 🔴 Advanced

### Offensive Security / Red Team
- [MITRE ATT&CK Framework](https://attack.mitre.org/) — the industry-standard knowledge base of real-world adversary tactics and techniques
- Active Directory attack paths: Kerberoasting, LLMNR poisoning, BloodHound — best learned via TryHackMe/HackTheBox advanced paths
- [PTES — Penetration Testing Execution Standard](http://www.pentest-standard.org/) — free, defines a professional pentest methodology end to end

### Defensive Security / Blue Team
- [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) — free official PDF, the framework most organizations structure their security programs around
- [MITRE D3FEND](https://d3fend.mitre.org/) — the defensive counterpart to ATT&CK, mapping countermeasures to techniques

### Cloud & Modern Infrastructure Security
- [NIST SP 800-207: Zero Trust Architecture](https://csrc.nist.gov/pubs/sp/800/207/final) — free official PDF
- Container/Kubernetes security: [Kubernetes official security docs](https://kubernetes.io/docs/concepts/security/) — free, authoritative

### Research-Level / Deep Technical
- [freecomputerbooks.com — Security section](https://freecomputerbooks.com/compscspecialSecurityBooks.html) — curated list of legitimately open-access security books (TPM, secure systems design, applied cryptography)
- Academic papers: [USENIX Security Symposium (free proceedings)](https://www.usenix.org/conferences/byname/108) — cutting-edge published security research, free to read

---

## How to use this list

1. Don't try to read everything front-to-back — pick the tier matching your current level and work through it alongside hands-on practice (TryHackMe/OverTheWire rooms, or your own 100-days projects).
2. Treat the **official PDFs (NIST, OWASP)** as reference material to revisit, not one-time reads — they're dense and meant to be looked up as needed.
3. Pair each theory resource with something hands-on where possible — e.g. read the OWASP Top 10 entry on SQL injection, then immediately try the matching PortSwigger Academy lab.
