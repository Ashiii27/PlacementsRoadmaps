# 🔐 Cyber Security Roadmap

> Primary Focus: SOC Analyst / Blue Team
> Secondary Focus: Bug Bounty
> Long Term: Penetration Testing + Malware Analysis
> Current Level: Top 4% on TryHackMe

---

## 📌 Career Target

```
FRESHER (0-2 yrs)    → SOC Analyst L1 | ₹3-6 LPA
MID LEVEL (2-4 yrs)  → SOC L2/L3 + Bug Bounty on side | ₹8-15 LPA  
SENIOR (5+ yrs)      → Threat Hunter / Pentester / Consultant | ₹25-50 LPA
ABROAD (5+ yrs)      → $100k-$180k (USA) | £60k-£100k (UK)
```

---

## 🗺️ The Roadmap

### ✅ Phase 1 — Foundation (COMPLETED)
Strong foundation already in place:
- Networking — TCP/IP, DNS, HTTP/S, OSI Model, DHCP
- Linux command line
- Windows internals — registry, event logs, processes
- Security concepts — CIA Triad, types of attacks
- Phishing analysis
- SOC concepts — SIEM, IDS/IPS, firewalls, threat intel
- TryHackMe — Top 4% globally

---

### 🔵 Phase 2 — SOC Hands-On (Current Focus)

#### TCM Security — SOC Level 1 Course
- [ ] Introduction to Security Operations
- [ ] Networking for SOC Analysts
- [ ] Linux & Windows for Security Analysts
- [ ] Log Analysis & SIEM — Splunk
- [ ] Phishing Analysis (deep dive)
- [ ] Threat Intelligence
- [ ] Incident Response Process
- [ ] Malware Analysis Basics
- [ ] Digital Forensics Basics
- [ ] Capstone — Full SOC Investigation ⭐

#### LetsDefend.io Practice
- [ ] SOC Analyst learning path
- [ ] Alert investigation simulations
- [ ] Incident response exercises
- [ ] 10+ alerts investigated

#### CyberDefenders Challenges
- [ ] Bruteforce challenge
- [ ] Phishing challenge
- [ ] Network forensics challenge
- [ ] 5+ challenges completed with writeups

#### Splunk
- [ ] Splunk Fundamentals 1 (free — official)
- [ ] Basic SPL queries
- [ ] Dashboard creation
- [ ] Alert investigation using Splunk

#### Key Windows Event IDs to Master
- [ ] 4624 — Successful logon
- [ ] 4625 — Failed logon
- [ ] 4648 — Explicit credential logon
- [ ] 4688 — Process creation
- [ ] 4698 — Scheduled task created
- [ ] 4778 — RDP session reconnect
- [ ] 4779 — RDP session disconnect
- [ ] 7045 — New service installed

---

### 🟡 Phase 3 — Bug Bounty Foundation (May–June)

#### PortSwigger Web Security Academy (Free — Gold Standard)
- [ ] SQL Injection — all labs
- [ ] Cross-Site Scripting (XSS) — all labs
- [ ] CSRF — all labs
- [ ] IDOR — all labs
- [ ] SSRF — all labs
- [ ] Authentication vulnerabilities
- [ ] Access control vulnerabilities
- [ ] Business logic vulnerabilities
- [ ] OWASP Top 10 — all covered

#### Burp Suite
- [ ] Burp Suite Community setup
- [ ] Proxy and intercept
- [ ] Repeater and Intruder basics
- [ ] Scanning basics
- [ ] Using Burp with PortSwigger labs

#### Platforms
- [ ] HackerOne account created — read 10 disclosed reports
- [ ] Bugcrowd account created
- [ ] Hacker101 CTF — first 5 challenges

---

### 🔴 Phase 4 — Penetration Testing (Post Placement)

#### Resources (for later)
- TCM Security — Practical Ethical Hacking
- TryHackMe — Jr Penetration Tester path
- HackTheBox — Easy retired machines
- "The Web Application Hacker's Handbook"

---

## 🎓 Certifications Roadmap

| Priority | Certification | Cost | Timeline |
|----------|--------------|------|----------|
| 1st | Google Cybersecurity Certificate (Coursera) | Free audit | March |
| 2nd | TryHackMe SOC L1 Certificate | ~$14 | May |
| 3rd | CompTIA Security+ | ~$350 | Final year or 1st job |
| 4th | BTL1 — Blue Team Labs Level 1 | ~$200 | Post placement |
| 5th | CEH or OSCP | Expensive | 2-3 years experience |

> 💡 Honest advice: Google cert + TryHackMe profile + LetsDefend + CyberDefenders is more than enough for fresher placements. Don't spend on expensive certs yet.

---

## 🛠️ Tools to Master

| Tool | Purpose | Priority | Status |
|------|---------|----------|--------|
| Wireshark | Network traffic analysis | High | |
| Nmap | Network scanning & enumeration | High | |
| Splunk | SIEM platform | High | |
| Burp Suite | Web app security testing | High | |
| Autopsy | Digital forensics | High | (College project) |
| FTK Imager | Disk imaging & forensics | High | (College project) |
| Wazuh | Open source SIEM (home lab) | Medium | |
| ANY.RUN | Malware sandbox analysis | Medium | |
| Volatility | Memory forensics | Medium | |
| Metasploit | Exploitation framework | Low (later) | |

---

## 🏗️ College Project — Windows Remote Login Forensics

**Goal:** Forensic investigation of remote login activity in Windows

### Project Phases
- [x] Topic approved and synopsis ready
- [ ] Work split between team members
- [ ] Lab environment setup (Windows 10 VM)
- [ ] Sysmon installation and configuration
- [ ] Windows Event Log collection and baseline
- [ ] Attack simulation — RDP brute force
- [ ] Forensic artifact collection
- [ ] Tool integration — Autopsy / FTK Imager
- [ ] PPT presentation — April deadline
- [ ] Final report and documentation

### Key Artifacts to Investigate
- Windows Event Logs (Security, System, Application)
- RDP cache files
- Prefetch files
- Registry keys — `HKLM\SYSTEM\CurrentControlSet\Services\TermService`
- Network logs — captured with Wireshark
- Memory dumps (if in scope)

---

## 📁 Portfolio Building

Everything I do gets documented publicly:

- **TryHackMe profile** — keep ranking, complete paths
- **LetsDefend profile** — SOC simulations
- **CyberDefenders** — writeups for every challenge
- **GitHub** — all tool scripts, notes, writeups
- **PortSwigger** — lab completion screenshots
- **College project** — full documentation and report

---

## 🔗 Resources

### Platforms
| Platform | Purpose | Cost |
|----------|---------|------|
| [TryHackMe](https://tryhackme.com) | Guided learning + CTF | Free + paid |
| [LetsDefend.io](https://letsdefend.io) | SOC simulations | Free tier |
| [CyberDefenders](https://cyberdefenders.org) | Blue team CTF | Free |
| [PortSwigger Web Academy](https://portswigger.net/web-security) | Web security | Free |
| [HackerOne Hacker101](https://www.hacker101.com) | Bug bounty training | Free |
| [ANY.RUN](https://any.run) | Malware sandbox | Free tier |

### YouTube Channels
| Channel | Focus |
|---------|-------|
| John Hammond | Malware analysis, CTF, blue team |
| Simply Cyber (Gerald Auger) | SOC career, blue team |
| David Bombal | Networking + security |
| TCM Security | Pentesting, SOC |
| Nahamsec | Bug bounty |

### Free Courses
| Course | Platform | Link |
|--------|---------|------|
| Google Cybersecurity Certificate | Coursera (free audit) | [Link](https://coursera.org) |
| Security+ Prep | Professor Messer (YouTube) | Free |
| Splunk Fundamentals 1 | Splunk official | Free |
| CP-Algorithms | cp-algorithms.com | Free |

### Books (Optional but valuable)
- "The Practice of Network Security Monitoring" — Richard Bejtlich
- "Blue Team Handbook" — Don Murdoch
- "The Web Application Hacker's Handbook"

---

## 💼 Target Companies

### Cyber Security Focused
- Wipro CyberDefense
- Tata Elxsi (security division)
- Securonix
- Securly
- Local MSSPs (Managed Security Service Providers)
- Cyber security startups

### Product Companies (SOC/Security teams)
- Any company with internal security team
- Fintech companies (high security needs)
- Healthcare tech companies

---

## 💡 Interview Prep Topics

When placement season hits, be ready to explain:

1. What happens during a phishing incident response?
2. Walk me through investigating a suspicious login alert
3. What is the difference between IDS and IPS?
4. Explain the CIA Triad with a real example
5. What are common Windows Event IDs for login monitoring?
6. How does a SIEM work?
7. What is threat intelligence and how is it used in SOC?
8. Explain your college project — what did you find?
9. What is the difference between malware analysis static vs dynamic?
10. How would you detect lateral movement in a network?

---

## 🏆 Milestones

- [x] Top 4% on TryHackMe
- [ ] TCM SOC L1 course completed
- [ ] LetsDefend — 10+ alerts investigated
- [ ] CyberDefenders — 5+ challenges with writeups
- [ ] Splunk Fundamentals 1 certified
- [ ] Google Cybersecurity Certificate done
- [ ] PortSwigger — OWASP Top 10 labs complete
- [ ] College project completed
- [ ] First bug bounty report submitted
- [ ] First interview call from cyber sec company

---

*"The best defenders know how attackers think."*
