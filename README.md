```
             ████████               █████                ████      █████ ████     █████     █████   
            ███░░░░███            ███░░░███             ░░███     ░░███ ░░███   ███░░░███  ░░███    
  █████████░░░    ░███ ████████  ███   ░░███ █████ █████ ░███   ███████  ░███  ███   ░░███ ███████  
 ░█░░░░███    ██████░ ░░███░░███░███    ░███░░███ ░░███  ░███  ███░░███  ░███ ░███    ░███░░░███░   
 ░   ███░    ░░░░░░███ ░███ ░░░ ░███    ░███ ░░░█████░   ░███ ░███ ░███  ░███ ░███    ░███  ░███    
   ███░   █ ███   ░███ ░███     ░░███   ███   ███░░░███  ░███ ░███ ░███  ░███ ░░███   ███   ░███ ███
  █████████░░████████  █████     ░░░█████░   █████ █████ █████░░████████ █████ ░░░█████░    ░░█████ 
 ░░░░░░░░░  ░░░░░░░░  ░░░░░        ░░░░░░   ░░░░░ ░░░░░ ░░░░░  ░░░░░░░░ ░░░░░    ░░░░░░      ░░░░░  
                                                                                                    
                                                                                                    
                                                                                                    
                                                                                                    
```

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF41&background=00000000&center=true&vCenter=true&width=600&lines=Cybersecurity+Engineer+%26+Full-Stack+Dev;TryHackMe+Top+1%25+%7C+Rank+%233515;PortSwigger+Practitioner+Level;Breaking+things+to+understand+them...;XCloak+%E2%80%94+AI+Pentest+SaaS+%40+xcloak.tech)

[![](https://visitcount.itsvg.in/api?id=The-Abhishek1&label=Profile%20Views&color=12&icon=5&pretty=true)](https://visitcount.itsvg.in)
&nbsp;
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%201%25%20%7C%20%233515-00ff41?style=flat-square&logo=tryhackme&logoColor=white&labelColor=000000)](https://tryhackme.com/p/0xIdiot)
&nbsp;
[![PortSwigger](https://img.shields.io/badge/PortSwigger-Practitioner-ff6633?style=flat-square&logo=burpsuite&logoColor=white&labelColor=000000)](https://portswigger.net/web-security)

</div>

---

## `$ whoami`

```bash
┌──(0xIdiot㉿kali)-[~]
└─$ cat about.conf

  [identity]
  name         = Abhishek N
  alias        = 0xIdiot
  location     = Bangalore, Karnataka, IN
  education    = MCA in Cybersecurity, Ethical Hacking and Cyber Forensics
  university   = S-VYASA University
  cgpa         = 9.0

  [skills]
  primary      = Penetration Testing, Web App Security, VAPT, Digital Forensics
  secondary    = Full-Stack Development, AI/LLM Integration, DevSecOps
  targets      = CEH (EC-Council) | OSCP (OffSec)

  [status]
  current      = Building XCloak — AI-powered cybersecurity SaaS
  thm_rank     = #3515 | Top 1% globally | 413 rooms completed
  portswigger  = Practitioner Level | 46+ labs completed
  ctf          = picoCTF 95 challenges | Active HTB/THM player
```

---

## `$ nmap --scan-stats 0xIdiot`

<div align="center">

| `[*]` Target | `[+]` Result |
|:---|:---|
| TryHackMe | **Rank #3515 — Top 1% globally** · 413 rooms completed |
| PortSwigger | **Practitioner Level** · Auth, WebSockets, NoSQL, SQLi |
| picoCTF | **95 Easy challenges** · Web · Binary · Forensics · Crypto |
| HTB | Active — machines in progress |
| CGPA | **9.8** · MCA Cybersecurity |

</div>

<div align="center">
  <img src="https://tryhackme-badges.s3.amazonaws.com/0xIdiot.png" alt="0xIdiot TryHackMe Badge"/>
</div>

---

## `$ ls -la ~/projects/`

```
drwxr-xr-x  [LIVE]        XCloak-ESO/       AI-powered cybersecurity SaaS @ xcloak.tech
drwxr-xr-x  [OPEN-SOURCE] ForenX/           Linux digital forensics CLI toolkit
drwxr-xr-x  [SHIPPED]     AI-Placement/     AI student-company matching platform
drwxr-xr-x  [SHIPPED]     CRMSX/            Real-time CRM system
drwxr-xr-x  [SHIPPED]     PropertyNexus/    Full CRUD property platform
drwxr-xr-x  [WIP]         Aethr/            Discord-inspired social platform
```

### [LIVE] [XCloak / ESO](https://xcloak.tech) — AI Pentest SaaS

```python
# xcloak.py — what it does

target = input("Describe what you want to pentest: ")
# "scan this target for SQLi and open ports"

ai.plan(target)           # GPT-4 creates execution plan
ai.validate(plan)         # human-in-the-loop approval
eso.execute([             # ESO orchestrates 7 Docker tools
    nmap, nuclei,         # recon + vuln scan
    gobuster, sqlmap,     # enum + exploitation
    nikto, ffuf, whatweb  # web scanning + fingerprinting
], stream=websocket)      # real-time output

report.export(format="PDF", scoring="CVSS")
# Paid SaaS @ xcloak.tech
```

> `Next.js 15` `FastAPI` `Supabase` `Docker` `Redis` `RabbitMQ` `PostgreSQL`

---

### [OSS] [ForenX](https://github.com/The-Abhishek1/ForenX) — Linux Forensics Toolkit

```bash
┌──(0xIdiot㉿kali)-[~/ForenX]
└─$ python forenx.py --help

  Modules:
    --auth-log    Analyze auth.log for SSH brute-force and login patterns
    --memory      Extract credentials and IPs from memory dumps (Volatility)
    --pcap        Parse PCAP captures for HTTP requests and credential leakage
    --artifacts   File analysis: hashes, EXIF metadata, hidden files

└─$ python forenx.py --auth-log /var/log/auth.log
  [+] 47 failed SSH attempts from 192.168.1.105
  [+] Brute-force pattern detected — top attacker: 45.33.32.156
```

> `Python 3` `Scapy` `Volatility` `ExifTool`

---

### [SHIPPED] Other Projects

```
[*] AI Student Placement System   Gemini + OpenAI matching | JWT + TOTP 2FA
    github.com/The-Abhishek1/AI-Student-Placement-System
    Stack: Next.js 14 | MongoDB | Socket.io | Gemini API | OpenAI

[*] CRMSX                         Real-time CRM with live updates
    github.com/The-Abhishek1/CRMSX
    Stack: React.js | Node.js | Express.js | MySQL

[*] PropertyNexus                 Full CRUD property management platform
    github.com/The-Abhishek1/Property-Manager
    Stack: Next.js 14 | Firebase | Tailwind | Recharts

[*] Aethr (WIP)                   Discord-inspired social platform
    Stack: Next.js | TypeScript | Supabase | Reputation Economy
```

---

## `$ cat /etc/skills.conf`

**Offensive Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white&labelColor=000)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white&labelColor=000)
![Nmap](https://img.shields.io/badge/Nmap-00457C?style=flat-square&logoColor=white&labelColor=000)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white&labelColor=000)
![SQLMap](https://img.shields.io/badge/SQLMap-CC0000?style=flat-square&logoColor=white&labelColor=000)
![Gobuster](https://img.shields.io/badge/Gobuster-00ff41?style=flat-square&logoColor=black&labelColor=000)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white&labelColor=000)
![Nuclei](https://img.shields.io/badge/Nuclei-00C6C6?style=flat-square&logoColor=white&labelColor=000)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white&labelColor=000)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=000)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white&labelColor=000)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white&labelColor=000)

**Backend and Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&labelColor=000)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white&labelColor=000)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=000)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white&labelColor=000)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white&labelColor=000)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white&labelColor=000)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white&labelColor=000)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB&labelColor=000)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white&labelColor=000)

**AI and LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white&labelColor=000)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=google&logoColor=white&labelColor=000)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat-square&logo=anthropic&logoColor=white&labelColor=000)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

---

## `$ cat certifications.txt`

```
[COMPLETED]
  [+] Jr. Penetration Tester Path        TryHackMe          Apr 2025
  [+] Android Bug Bounty                 EC-Council         2024
  [+] SQL Injection Attacks              EC-Council         2024
  [+] Dark Web and Cryptocurrency        EC-Council         2023
  [+] Endpoint Security                  Cisco              2023
  [+] Intro to Cybersecurity             Cisco              2023
  [+] Networking Basics                  Cisco              2023
  [+] Cybersecurity Job Simulation       Forage / Tata      2023

[IN PROGRESS]
  [-] PortSwigger Web Security Academy   Practitioner Level  Active

[TARGETING]
  [ ] CEH v13                            EC-Council          Q3 2025
  [ ] OSCP                               OffSec              2026
```

---

## `$ github-stats --user The-Abhishek1`

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=The-Abhishek1&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=The-Abhishek1&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0D1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=The-Abhishek1&theme=chartreuse-dark&hide_border=true&background=0D1117"/>
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=The-Abhishek1&theme=matrix&no-frame=true&column=7&margin-w=8&no-bg=true"/>
</div>

---

## `$ netstat -connect 0xIdiot`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white&labelColor=000)](https://www.linkedin.com/in/abhishek-gowda17)
[![GitHub](https://img.shields.io/badge/GitHub-ffffff?style=flat-square&logo=github&logoColor=white&labelColor=000)](https://github.com/The-Abhishek1)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white&labelColor=000)](https://twitter.com/justAbhi0)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white&labelColor=000)](https://instagram.com/abhishekg0wda_02)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white&labelColor=000)](mailto:abhishekn1003@gmail.com)
[![XCloak](https://img.shields.io/badge/XCloak.tech-00ff41?style=flat-square&logoColor=black&labelColor=000)](https://xcloak.tech)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white&labelColor=000)](https://tryhackme.com/p/0xIdiot)

</div>

---

<div align="center">

```
┌──(0xIdiot㉿kali)-[~]
└─$ echo "hack the planet"

hack the planet

└─$ █
```

*"An idiotic ethical hacker who builds things to break them"*

</div>
