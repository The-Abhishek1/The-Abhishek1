<div align="center">

[![Header](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=42&duration=3000&pause=800&color=#f52d05&background=00000000&center=true&vCenter=true&width=900&height=80&lines=z3r0x1d10t)](https://github.com/The-Abhishek1)

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=14&duration=3000&pause=800&color=005500&background=00000000&center=true&vCenter=true&width=700&height=24&lines=%E2%94%8C%E2%94%80%E2%94%80(0xIdiot%E2%86%99kali)-[~]+-+Cybersecurity+Engineer+%26+Full-Stack+Dev" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=800&color=00FF41&background=00000000&center=true&vCenter=true&multiline=false&width=700&lines=%5B%2B%5D+Cybersecurity+Engineer+%26+Full-Stack+Dev;%5B%2B%5D+TryHackMe+Top+1%25+%7C+Global+Rank+%233515;%5B%2B%5D+PortSwigger+Web+Security+Practitioner;%5B*%5D+Creator+of+XCloak+AI+Pentest+SaaS;%5B%21%5D+Breaking+things+to+understand+them...)](https://git.io/typing-svg)

<br/>

[![TryHackMe](https://img.shields.io/badge/TryHackMe-%23212C42?style=for-the-badge&logo=tryhackme&logoColor=00FF41&label=TOP%201%25%20%7C%20%233515)](https://tryhackme.com/p/0xIdiot)
[![PortSwigger](https://img.shields.io/badge/PortSwigger-Practitioner-%23FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)](https://portswigger.net/web-security)
[![XCloak](https://img.shields.io/badge/XCloak-LIVE%20SaaS-%2300FF41?style=for-the-badge&logoColor=black)](https://xcloak.tech)
[![Profile Views](https://komarev.com/ghpvc/?username=The-Abhishek1&color=00ff41&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/The-Abhishek1)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=The-Abhishek1.The-Abhishek1&left_color=000000&right_color=00ff41&left_text=TOTAL+VISITORS)](https://github.com/The-Abhishek1)

<br/>

<img src="https://tryhackme-badges.s3.amazonaws.com/0xIdiot.png" alt="0xIdiot TryHackMe Badge"/>

</div>

<br/>

---

## 🖥️ `$ whoami`

```bash
┌──(0xIdiot㉿kali)-[~]
└─$ cat /proc/identity

╔══════════════════════════════════════════════════════════════╗
║  NAME     ›  Abhishek N                                      ║
║  ALIAS    ›  0xIdiot  [ an idiot who knows how to hack ]     ║
║  ROLE     ›  Cybersecurity Engineer & Full-Stack Developer   ║
║  BASE     ›  Bangalore, Karnataka, IN  🇮🇳                   ║
║  DEGREE   ›  MCA — Cybersecurity, Ethical Hacking & Forensics║
║  UNIV     ›  S-VYASA University  |  CGPA: 9.8                ║
╠══════════════════════════════════════════════════════════════╣
║  SKILLS   ›  Penetration Testing · VAPT · Web App Security   ║
║             Digital Forensics · Full-Stack Dev · AI/LLMs     ║
╠══════════════════════════════════════════════════════════════╣
║  STATUS   ›  [ ONLINE ]  Building XCloak — AI Pentest SaaS  ║
║  THM      ›  Rank #3515  |  Top 1% globally  |  413 rooms   ║
║  PSW      ›  Practitioner Level  |  46+ labs completed       ║
║  CTF      ›  picoCTF 95 solved   |  Active HTB/THM player    ║
╠══════════════════════════════════════════════════════════════╣
║  NEXT     ›  [ ] CEH v13 (EC-Council)  [ ] OSCP (OffSec)    ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 📡 `$ nmap -sV --open 0xIdiot`

<div align="center">

| PORT | SERVICE | STATE | VERSION |
|:----:|:--------|:-----:|:--------|
| 1337 | TryHackMe | `OPEN` | **Rank #3515 · Top 1% · 413 rooms** |
| 8080 | PortSwigger | `OPEN` | **Practitioner · Auth · SQLi · NoSQL · WebSockets** |
| 9001 | picoCTF | `OPEN` | **95 challenges · Web · Binary · Forensics · Crypto** |
| 4444 | HTB | `OPEN` | **Active — machines in progress** |
| 443  | XCloak SaaS | `OPEN` | **Live @ xcloak.tech — AI Pentest Engine** |

</div>

---

## 🚀 `$ ls -la ~/projects/ --sort=impact`

```
total 6 elite projects

drwxr-xr-x  [ LIVE  ]  XCloak-ESO/       AI-powered cybersecurity SaaS  →  xcloak.tech
drwxr-xr-x  [ OSS   ]  ForenX/           Linux digital forensics CLI toolkit
drwxr-xr-x  [ SHIP  ]  AI-Placement/     Gemini + OpenAI student matching platform
drwxr-xr-x  [ SHIP  ]  CRMSX/            Real-time CRM with live data sync
drwxr-xr-x  [ SHIP  ]  PropertyNexus/    Full CRUD property management platform
drwxr-xr-x  [ WIP   ]  Aethr/            Discord-inspired social platform (reputation economy)
```

<br/>

### ⚡ `[LIVE]` — [XCloak / ESO](https://xcloak.tech) · AI Pentest SaaS

> **The idea:** What if you could describe a pentest in plain English and have AI execute it?

```python
#!/usr/bin/env python3
# xcloak_engine.py — ESO core loop

target = input("[*] Describe your pentest goal: ")
# >>> "find SQL injection and open ports on this web app"

plan   = ai.plan(target)          # [+] GPT-4 generates execution strategy
_      = ai.human_approval(plan)  # [!] You review before anything fires
output = eso.execute(pipeline=[   # [*] ESO orchestrates 7 Docker-isolated tools:
    nmap,                         #     recon + port scanning
    nuclei,                       #     CVE + vulnerability scanning
    gobuster,                     #     directory + vhost enumeration
    sqlmap,                       #     SQL injection exploitation
    nikto,                        #     web server misconfiguration
    ffuf,                         #     parameter + endpoint fuzzing
    whatweb,                      #     tech fingerprinting
], realtime=WebSocket)            # [+] Live streaming output to browser

report = pdf.export(              # [+] Professional pentest report
    scoring="CVSS",               #     with CVSS scores
    format="PDF"                  #     ready to send to clients
)
# Deployed @ xcloak.tech  |  Rs.999/month  |  Razorpay billing
```

`Next.js 15` `FastAPI` `Python 3.12` `Supabase` `Docker` `Redis` `RabbitMQ` `PostgreSQL` `WebSockets`

[![Live Demo](https://img.shields.io/badge/LIVE-xcloak.tech-00FF41?style=for-the-badge&logoColor=black)](https://xcloak.tech)
[![Frontend](https://img.shields.io/badge/Frontend-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/The-Abhishek1/Xcl0ak-New)
[![Backend](https://img.shields.io/badge/Backend%20(ESO)-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/The-Abhishek1/Enterprise-Security-Orchestrator)

---

### 🔬 `[OSS]` — [ForenX](https://github.com/The-Abhishek1/ForenX) · Linux Forensics Toolkit

```bash
┌──(0xIdiot㉿kali)-[~/ForenX]
└─$ python forenx.py --help

  ███████╗ ██████╗ ██████╗ ███████╗███╗   ██╗██╗  ██╗
  ██╔════╝██╔═══██╗██╔══██╗██╔════╝████╗  ██║╚██╗██╔╝
  █████╗  ██║   ██║██████╔╝█████╗  ██╔██╗ ██║ ╚███╔╝ 
  ██╔══╝  ██║   ██║██╔══██╗██╔══╝  ██║╚██╗██║ ██╔██╗ 
  ██║     ╚██████╔╝██║  ██║███████╗██║ ╚████║██╔╝ ██╗
  ╚═╝      ╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝╚═╝  ╚═╝

  Linux Incident Response & Digital Forensics Toolkit

  MODULES:
    --auth-log   [*] Analyze auth.log → SSH brute-force IPs, login patterns
    --memory     [*] Volatility memory dumps → credential + IP extraction
    --pcap       [*] PCAP analysis → HTTP requests, credential leakage
    --artifacts  [*] File analysis → hashes, EXIF metadata, hidden files

└─$ python forenx.py --auth-log /var/log/auth.log

  [+] Scanning auth.log...
  [+] 47 failed SSH attempts detected from 192.168.1.105
  [+] BRUTE-FORCE PATTERN: top attacker → 45.33.32.156 (Shodan: Tor exit node)
  [+] Suspicious logins: root@03:47:22, admin@03:47:31
  [!] ALERT: Possible credential stuffing attack in progress
```

`Python 3` `Scapy` `Volatility` `ExifTool`

[![View on GitHub](https://img.shields.io/badge/ForenX-Open%20Source-00FF41?style=for-the-badge&logo=github&logoColor=white&labelColor=000)](https://github.com/The-Abhishek1/ForenX)

---

### 📦 `[SHIPPED]` — Other Projects

<div align="center">

| Project | Stack | What it does |
|:--------|:------|:-------------|
| [AI Student Placement](https://github.com/The-Abhishek1/AI-Student-Placement-System) | Next.js 14 · MongoDB · Gemini · OpenAI · TOTP 2FA | AI-driven student-company matching with real-time notifications |
| [CRMSX](https://github.com/The-Abhishek1/CRMSX) | React · Node.js · Express · MySQL | Real-time CRM with live data sync and user management |
| [PropertyNexus](https://github.com/The-Abhishek1/Property-Manager) | Next.js 14 · Firebase · Recharts | Full CRUD property platform with price history + analytics |
| Aethr *(WIP)* | Next.js · TypeScript · Supabase | Discord-inspired social platform with reputation economy |

</div>

---

## 🛠️ `$ cat /proc/skills`

<div align="center">

**`[ OFFENSIVE SECURITY ]`**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white&labelColor=000)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white&labelColor=000)
![Nmap](https://img.shields.io/badge/Nmap-00457C?style=for-the-badge&logoColor=white&labelColor=000)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white&labelColor=000)
![SQLMap](https://img.shields.io/badge/SQLMap-CC0000?style=for-the-badge&logoColor=white&labelColor=000)
![Nuclei](https://img.shields.io/badge/Nuclei-00C6C6?style=for-the-badge&logoColor=white&labelColor=000)
![Gobuster](https://img.shields.io/badge/Gobuster-00FF41?style=for-the-badge&logoColor=black&labelColor=000)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white&labelColor=000)

**`[ LANGUAGES ]`**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white&labelColor=000)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=000)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=000)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white&labelColor=000)

**`[ BACKEND & INFRA ]`**

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&labelColor=000)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=000)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=000)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=000)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white&labelColor=000)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white&labelColor=000)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white&labelColor=000)

**`[ FRONTEND ]`**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=000)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white&labelColor=000)

**`[ AI / LLMs ]`**

![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4-412991?style=for-the-badge&logo=openai&logoColor=white&labelColor=000)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white&labelColor=000)
![Claude](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white&labelColor=000)
![Ollama](https://img.shields.io/badge/Ollama_Local-000000?style=for-the-badge&logoColor=white)

</div>

---

## 📜 `$ cat certifications.txt`

```
╔═══════════════════════════════════════════════════════════════════╗
║                     CERTIFICATIONS & TRAINING                     ║
╠═══════════════════════════════════════════════════════════════════╣
║  [COMPLETED]                                                      ║
║  ✅  Jr. Penetration Tester Path    TryHackMe        Apr 2025    ║
║  ✅  Android Bug Bounty             EC-Council        2024       ║
║  ✅  SQL Injection Attacks          EC-Council        2024       ║
║  ✅  Dark Web & Cryptocurrency      EC-Council        2023       ║
║  ✅  Endpoint Security              Cisco             2023       ║
║  ✅  Intro to Cybersecurity         Cisco             2023       ║
║  ✅  Networking Basics              Cisco             2023       ║
║  ✅  Cybersecurity Job Simulation   Forage / Tata     2023       ║
╠═══════════════════════════════════════════════════════════════════╣
║  [IN PROGRESS]                                                    ║
║  🔄  PortSwigger Web Security Academy   Practitioner   Active    ║
╠═══════════════════════════════════════════════════════════════════╣
║  [TARGETING]                                                      ║
║  🎯  CEH v13                        EC-Council        Q3 2025    ║
║  🎯  OSCP                           OffSec            2026       ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## 📊 `$ github-stats --verbose The-Abhishek1`

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=The-Abhishek1&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00FF41&icon_color=00FF41"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=The-Abhishek1&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FF41"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=The-Abhishek1&theme=chartreuse-dark&hide_border=true&background=0D1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41"/>
</div>

<br/>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=The-Abhishek1&theme=matrix&no-frame=true&column=7&margin-w=6&no-bg=true"/>
</div>

<br/>

<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=The-Abhishek1&theme=2077"/>
</div>

---

## 🌐 `$ netstat -active --connect 0xIdiot`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000)](https://www.linkedin.com/in/abhishek-gowda17)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-ffffff?style=for-the-badge&logo=github&logoColor=white&labelColor=000)](https://github.com/The-Abhishek1)
[![XCloak](https://img.shields.io/badge/XCloak.tech-Visit-00FF41?style=for-the-badge&logoColor=black&labelColor=000)](https://xcloak.tech)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25-212C42?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=000)](https://tryhackme.com/p/0xIdiot)

[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white&labelColor=000)](https://twitter.com/justAbhi0)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=000)](https://instagram.com/abhishekg0wda_02)
[![Gmail](https://img.shields.io/badge/Gmail-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000)](mailto:abhishekn1003@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-z3r0x1d10t-00FF41?style=for-the-badge&logoColor=black&labelColor=000)](https://z3r0x1d10t.netlify.app)

</div>

---

<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║   ┌──(0xIdiot㉿kali)-[~]                                 ║
║   └─$ sudo rm -rf /limitations/*                         ║
║                                                           ║
║   [sudo] password for 0xIdiot: ************              ║
║                                                           ║
║   removing /limitations/fear_of_failure...   [ DONE ]    ║
║   removing /limitations/self_doubt...        [ DONE ]    ║
║   removing /limitations/comfort_zone...      [ DONE ]    ║
║                                                           ║
║   [+] All limitations removed successfully               ║
║   [+] System ready. Hack the planet.                     ║
║                                                           ║
║   └─$ █                                                   ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

**"An idiotic ethical hacker who builds things to break them"**

*— Abhishek N aka 0xIdiot*

</div>
