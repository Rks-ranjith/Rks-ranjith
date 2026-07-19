# Ranjith Kumar S - GitHub Profile

<div align="center">

<!-- DYNAMIC THEME-AWARE HERO BANNER -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="light.svg">
  <img alt="Ranjith Kumar S Banner" src="dark.svg" width="100%">
</picture>

<br>

<!-- METRICS BADGES (NO EMOJIS TO PREVENT ? ERRORS) -->
<img src="https://komarev.com/ghpvc/?username=Rks-ranjith&style=for-the-badge&color=00ff9f&label=PROFILE+VIEWS&labelColor=0d1117" alt="Views">
&nbsp;
<img src="https://img.shields.io/github/followers/Rks-ranjith?style=for-the-badge&color=7aa2f7&labelColor=0d1117&label=FOLLOWERS" alt="Followers">
&nbsp;
<img src="https://img.shields.io/badge/Status-Open%20to%20Internships-00ff9f?style=for-the-badge&labelColor=0d1117" alt="Status">

<br><br>

<!-- SOCIAL Badges -->
<a href="mailto:ranjithk0117@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-ranjithk0117-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Gmail">
</a>
&nbsp;
<a href="https://linkedin.com/in/ranjith-kumar-0117d">
  <img src="https://img.shields.io/badge/LinkedIn-ranjith--kumar--0117d-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn">
</a>
&nbsp;
<a href="https://github.com/Rks-ranjith">
  <img src="https://img.shields.io/badge/GitHub-Rks--ranjith-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="GitHub">
</a>
&nbsp;
<a href="https://tryhackme.com">
  <img src="https://img.shields.io/badge/TryHackMe-Top%2010%25-212C42?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117" alt="TryHackMe">
</a>
&nbsp;
<a href="https://hackerone.com">
  <img src="https://img.shields.io/badge/HackerOne-Bug%20Researcher-494649?style=for-the-badge&logo=hackerone&logoColor=white&labelColor=0d1117" alt="HackerOne">
</a>

</div>

---

```bash
[root@ranjith-kumar:~]# whoami

[+] Name          : Ranjith Kumar S
[+] Specialization: Offensive Security Researcher & AI Security Engineer
[+] Education     : B.Tech CS - Cybersecurity Engineering (CGPA: 8.18/10)
[+] Institution   : GM University, Davanagere, Karnataka, India
[+] Certification : Certified LLM Security Expert (CLLMSE)
[+] Status        : Seeking Offensive Security / AI Security Internship
[+] Location      : Bengaluru, Karnataka, India
[+] Contact       : ranjithk0117@gmail.com | +91 6361602812
```

---

## 0x01 ABOUT ME

```python
class RanjithKumarS:
    def __init__(self):
        self.username = "Rks-ranjith"
        self.focus = ["Offensive Security", "AI / LLM Security Research", "Red Team Operations"]
        self.academic = {
            "degree": "B.Tech in Computer Science (Cybersecurity Engineering)",
            "cgpa": 8.18,
            "status": "Final Year undergraduate"
        }
        self.research_areas = [
            "Autonomous pentesting pipelines (AWAP-AI)",
            "Prompt Injection, RAG and MCP protocol attacks",
            "Active Directory simulation and detection engineering"
        ]

    def get_philosophy(self):
        return "Building autonomous agents to scale adversarial intelligence and secure AI pipelines."
```

- **Offensive Focus**: Actively mapping MITRE ATT&CK techniques in Windows/Active Directory labs and auditing SPA/API vulnerabilities.
- **AI Security Focus**: Specializing in prompt injection chains, indirect prompt injection, and RAG/Agent system security.
- **Bug Bounty**: Independent vulnerability researcher on HackerOne since Sep 2024.

---

## 0x02 TECHNICAL EXPERTISE

```bash
[root@ranjith-kumar:~]# ./list_skills.sh
```

### Languages & Scripts
`Python` `TypeScript` `JavaScript` `SQL` `Bash` `HTML5` `CSS3`

### Offensive Tooling
`Burp Suite` `Nmap` `Metasploit` `Wireshark` `Impacket` `CrackMapExec` `Playwright`

### AI & LLM Security
`Prompt Injection Defense` `RAG Security Auditing` `AI Agent Trust Boundaries` `MCP Protocol Security` `OWASP LLM Top 10`

### Systems & Detection
`Wazuh SIEM` `Sysmon` `Sigma Detection Rules` `MITRE ATT&CK Mapping` `Windows Server (Active Directory)` `Kali Linux` `Ubuntu`

### Infrastructure & Databases
`Docker` `PostgreSQL` `Redis` `Git` `GCP Observability`

---

## 0x03 PRODUCTION PROJECTS

### 0. AWAP-AI: Autonomous Web Application Penetration Testing System
*Autonomous pentesting engine combining finite state machine (FSM) choreography with AI analysis.*
- **Core Architecture**: Engineered a 7-stage automated pentest execution pipeline: Discovery -> Crawling -> Fingerprinting -> Attack Dispatch -> Exploitation -> Verification -> Reporting.
- **Test Engine**: Developed a headless Playwright crawler for SPA path mapping alongside 19 vulnerability-verification modules (SQLi, XSS, IDOR, SSRF, SSTI, Cmd Injection).
- **Control Dashboard**: React + TypeScript frontend displaying real-time telemetry over WebSockets and dynamic target attack graphs.
- **Validation**: Verified against OWASP Juice Shop and DVWA target applications.
- **Tech Stack**: Python, FastAPI, Playwright, React, WebSockets, Redis, PostgreSQL, Docker.

### 1. Active Directory Threat Detection & SIEM Monitoring Lab
*Enterprise simulation lab simulating red team tactics and monitoring with Wazuh SIEM.*
- **Subnet Infrastructure**: Provisioned an isolated 5-VM subnet containing Windows Server 2022 DC, Windows 11 Endpoints, Kali Attacker, and Ubuntu SIEM.
- **Adversary Emulation**: Simulated Kerberoasting, Password Spraying, and Network Reconnaissance via Impacket and CrackMapExec.
- **SIEM / Logging**: Deployed Wazuh 4.7.5 and Windows Sysmon configured with SwiftOnSecurity rules to achieve full coverage.
- **Rule Design**: Authored custom Sigma rules mapping to MITRE ATT&CK for Event ID 4769 (RC4 downgrade) and Event ID 4625 (account lockout correlation).

### 2. Malicious URL Scanner using Machine Learning
*Supervised machine learning pipeline for real-time threat intelligence.*
- **Model Training**: Trained a Random Forest classifier on 650,000+ labeled URLs using structural, lexical, entropy, and domain indicators to achieve 97.12% accuracy.
- **API Integration**: Integrated real-time reputation analysis querying Shodan, VirusTotal, and Google Safe Browsing.

---

## 0x04 CERTIFICATIONS & BENCHMARKS

```
+------------------------------------------------------------+
|  [+] CLLMSE - Certified LLM Security Expert (Jul 2026)      |
|      Red Team Leaders: Prompt Injection, RAG, MCP Security  |
+------------------------------------------------------------+
|  [+] CompTIA Security+ (SY0-701)                            |
|      In Progress - Target: Aug 2026                        |
+------------------------------------------------------------+
|  [+] TryHackMe Profile                                     |
|      Top 10% Global Rank | 65+ Challenge Rooms Completed   |
+------------------------------------------------------------+
|  [+] Tata Group Internship                                 |
|      Cybersecurity Analyst Virtual Program (2024)          |
+------------------------------------------------------------+
```

---

## 0x05 GITHUB METRICS

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Rks-ranjith&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00ff9f&icon_color=7aa2f7&text_color=c0caf5&ring_color=00ff9f" alt="Stats">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rks-ranjith&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00ff9f&text_color=c0caf5" alt="Languages">

<br><br>

<img src="https://streak-stats.demolab.com?user=Rks-ranjith&theme=tokyonight-duo&hide_border=true&background=0d1117&stroke=00ff9f&ring=00ff9f&fire=f7768e&currStreakLabel=7aa2f7&sideLabels=c0caf5&dates=565f89&sideNums=00ff9f&currStreakNum=00ff9f" alt="Streak">

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Rks-ranjith&bg_color=0d1117&color=00ff9f&line=7aa2f7&point=f7768e&area=true&area_color=00ff9f&hide_border=true&custom_title=Contribution%20Activity%20Graph" alt="Activity Graph" width="100%">

</div>

---

## 0x06 CONNECT

```bash
[root@ranjith-kumar:~]# ./get_connect_links.py
```
- **Email**: [ranjithk0117@gmail.com](mailto:ranjithk0117@gmail.com)
- **LinkedIn**: [linkedin.com/in/ranjith-kumar-0117d](https://linkedin.com/in/ranjith-kumar-0117d)
- **GitHub**: [github.com/Rks-ranjith](https://github.com/Rks-ranjith)
- **TryHackMe**: [tryhackme.com/p/Rks.0117](https://tryhackme.com)
- **HackerOne**: [hackerone.com/ranjithk0117](https://hackerone.com)

---

```
+--------------------------------------------------------------------------+
|  "The best offense is understanding defense from the inside out.         |
|   I don't just find vulnerabilities - I build machines that think        |
|   like attackers, so defenders can finally think faster than them."      |
|                                                      - Ranjith Kumar S   |
+--------------------------------------------------------------------------+
```
