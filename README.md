# Red Team Operator Roadmap

## Phase 1 - Getting Comfortable with Linux & Windows Pen Testing Concepts

### Certifications
- (ISC)² Certified in Cybersecurity (CC)
- CompTIA Cybersecurity Analyst (CySA+)

### Tools to Learn
- Nmap
- Gobuster
- SQLmap
- LinPEAS & WinPEAS

### Goals
- Linux & Windows privilege escalation using kernel exploits, misconfigurations, and automated scripts
- Networking & Security Fundamentals:
  - OSI Model
  - TCP/IP
  - Firewalls
  - SIEMs

### TryHackMe Paths
- Pre-security path
- Jr. Penetration Tester path

### Hack The Box (HTB) (Tier 1 & 2 Machines)
- Basic Enumeration
  - Network Enumeration with Nmap
  - DNS Enumeration Using Python
- Active Directory Enumeration & Attacks
- Privilege Escalation
  - Linux Privilege Escalation
  - Windows Privilege Escalation

### Recommended Machines
- **Easy:** Archetype, Lame, Buff, Active
- **Medium:** Legacy, Sauna, Nest

### Helpful Resources
- HTB Writeups on Medium, 0xdf’s blogs, or IppSec’s YouTube Channel
- OverTheWire (Linux command-line & privilege escalation):
  - Bandit lab
  - Narnia lab

---

## Phase 2 - Performing Basic Penetration Tests on Networks, AD, and Web Apps

### Certifications
- CompTIA PenTest+
- eCPPT or PNPT (Pick one, better than CEH)
  - At the moment, 02/15/2025, I think PNPT is the better option
  - **eCPPT**
    - Covers real-world penetration testing: web apps, networks, and privilege escalation
    - AD Attacks
    - Pivoting & Tunneling
    - Requires report writing
  - **PNPT**
    - OSINT & Initial Access
    - AD Attacks
    - Lateral Movement & Pivoting
    - Bypassing Firewalls & EDR (Endpoint Detection Response)
    - Comprehensive reporting

### Hack The Box (Tier 2 & 3 Machines)
#### AD Labs (Active Directory)
- Enumeration
- Password Spraying
- Kerberoasting

### Web Application Pentesting
- **Local File Inclusion (LFI):** Exploit vulnerable web applications to read arbitrary files on the server, leading to potential credential leaks or code execution.
- **SQL Injection (SQLi):** Manipulate SQL queries to gain unauthorized access, extract sensitive information, or escalate privileges.
- **Server-Side Request Forgery (SSRF):** Exploit web applications to make unauthorized requests to internal resources, often leading to internal network enumeration or metadata exposure.

### Recommended Machines
#### Active Directory Focus
- Forest, Resolute, Reel, Sauna
- Start HTB Active Directory Challenges

#### Web App Focus
- Help, Ophiuchi, Cache

### Helpful Resources
- BloodHound to map AD environments
- PowerView, CrackMapExec, and Impacket for lateral movement

### TryHackMe Paths
- Offensive Pentesting
- Red Team

---

## Phase 3 - Executing Full Red Team Engagements

### Certifications
- **OSCP** (Good for hands-on penetration testing jobs)
- **CRTP** (Certified Red Team Professional) - Active Directory exploitation
- **CRTO** (Certified Red Team Operator) - Real-world red teaming

### Hack The Box (Tier 3+ Machines)
- Introduction to Windows Evasion Techniques
- Windows Lateral Movement
- Intro to C2 Operations with Sliver

### Hack The Box Pro Labs
- **Dante** - Red Team engagements with stealth, persistence, and evasion tactics
- **RastaLabs** - AD attack & persistence scenarios
- **Offshore** - Realistic corporate network pentesting with multi-layer pivoting

### Helpful Resources
- Sysmon & Sigma rules to understand detection and evasion
- Follow Pentester Academy’s Red Team Lab

### TryHackMe Paths
- Windows Privilege Escalation

### Construct a Home Lab
- Active Directory, Kali Linux, and C2 Frameworks (Cobalt Strike, Sliver, Empire, etc.)

---

## Phase 4 - Building a Strong Portfolio & Job Readiness

### Certifications
- OSCE3 (Advanced Exploit Development)
- AWS Security Specialty / Azure Security (AZ-500)

### Hack The Box
- Attempt CTF-style machines under time constraints
- Create write-ups for completed boxes and challenges to showcase knowledge
- Join HTB CTFs & challenges
- Contribute to HTB forums & Discord

### Final Recommendations
- **Master Evasion Tactics** - Bypass AV & EDR while staying stealthy
- **Document and Publish** techniques and methodologies
- **Prepare for Red Team job interviews**

### Bug Bounties (Optional)
- HackerOne
- Bugcrowd

### Contribute to Open Source Red Team Tools (Optional)
- Metasploit
- BloodHound

### Network & Attend Conferences (Optional)
- Defcon
- Black Hat
- Red Team Village
- Wild West Hackin’ Fest
