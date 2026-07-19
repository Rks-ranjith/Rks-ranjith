# Ranjith Kumar S - GitHub Profile

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,35:0d1f12,70:1a0b2e,100:2d0b5e&height=280&section=header&text=RANJITH%20KUMAR%20S&fontSize=52&fontColor=39FF88&fontAlignY=36&desc=Offensive%20Security%20%E2%80%A2%20AI%2FLLM%20Security%20%E2%80%A2%20Detection%20Engineering&descAlignY=54&descSize=16&animation=fadeIn&fontName=Fira+Code" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=700&color=39FF88&center=true&vCenter=true&width=750&lines=root%40kali%3A~%23+building+AWAP-AI+...;root%40kali%3A~%23+red-teaming+Active+Directory...;root%40kali%3A~%23+attacking+LLMs+%7C+prompt+injection+%7C+RAG;root%40kali%3A~%23+status%3A+top+10%25+TryHackMe" alt="typing"/>

<br/>

Bengaluru, India &nbsp;·&nbsp; Open to Internships &nbsp;·&nbsp; Offensive Security & AI/LLM Security

**[ GitHub ](https://github.com/Rks-ranjith)**&nbsp; · &nbsp;**[ LinkedIn ](https://linkedin.com/in/ranjith-kumar-0117d)**&nbsp; · &nbsp;**[ Email ](mailto:ranjithk0117@gmail.com)**

<br/>

<img src="https://komarev.com/ghpvc/?username=Rks-ranjith&style=for-the-badge&color=39FF88&labelColor=0d0d0d&label=PROFILE+VIEWS"/>

</div>

<br/>

<!-- DYNAMIC THEME-AWARE HERO BANNER -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark.svg?v=6">
  <source media="(prefers-color-scheme: light)" srcset="light.svg?v=6">
  <img alt="Ranjith Kumar S Banner" src="dark.svg?v=6" width="100%">
</picture>

<br>

### 0x00 WHOAMI

Final-year Cybersecurity engineer who'd rather break things than read about them breaking. I build offensive tooling that proves a vulnerability exists instead of just flagging it, from an autonomous AI-driven pentest platform to a self-built Active Directory red-team lab wired into a live SIEM, with a growing focus on attacking the AI systems everyone's racing to ship. Currently chasing internships in offensive security and AI/LLM security.

| | |
|---|---|
| **role** | Offensive Security / AI-LLM Security / Detection Eng. Intern |
| **building** | AWAP-AI :: autonomous pentest platform, 7-stage AI pipeline |
| **hardening** | 5-VM Active Directory red-team & SOC detection lab |
| **studying** | CompTIA Security+ (SY0-701) :: exam Aug 2026 |
| **certified** | LLM Security Expert (CLLMSE) :: prompt injection, RAG, MCP |
| **verified** | TryHackMe Top 10% (65+ rooms) · HackerOne researcher since 2024 |

<br/>

### 0x01 ARSENAL

<div align="center">
<img src="https://skillicons.dev/icons?i=python,ts,js,bash,html,css,react,nodejs,postgres,redis,docker,git,linux,windows&theme=dark"/>
</div>

<br/>

```
┌─ security_toolkit ───────────────────────────────────────────────────┐
│  recon / exploit  : Burp Suite · Nmap · Metasploit · Wireshark       │
│  ad attack        : Impacket · CrackMapExec                          │
│  automation       : Playwright (headless browser attack automation)  │
│  detection / siem : Wazuh SIEM · Sysmon · Sigma Rules                │
│  frameworks       : MITRE ATT&CK · OWASP Top 10 · OWASP LLM Top 10   │
└──────────────────────────────────────────────────────────────────────┘
```

<br/>

### 0x02 AI / LLM SECURITY MATRIX

| Domain | Proficiency | Details |
|---|---|---|
| `prompt_injection` | 80% | Direct & indirect vector ID + mitigation (CLLMSE) |
| `rag_security` | 80% | Retrieval pipeline hardening vs poisoning attacks |
| `ai_agent_security` | 60% | Threat modeling autonomous tool-use chains |
| `mcp_security` | 60% | Model Context Protocol attack-surface analysis |
| `owasp_llm_top10` | 80% | Applied coverage, 2025 risk categories |
| `ai_driven_triage` | 100% | Shipped inside AWAP-AI live verification pipeline |

<br/>

### 0x03 OPERATIONS LOG // FEATURED PROJECTS

<details open>
<summary><b>[>] AWAP-AI :: Autonomous Web Application Penetration Testing System</b></summary>
<br/>

```
$ ./awap-ai --target <spa/api> --mode autonomous
[+] initializing 7-stage FSM attack pipeline...
[+] launching headless playwright crawler for SPA/API discovery...
[+] loading 19 modular vulnerability-verification plugins...
[+] AI triage engine online, prioritizing and verifying findings...
[+] streaming live telemetry -> react/ts dashboard (websocket)...
```

Autonomous AI-assisted pentesting platform orchestrating a 7-stage attack pipeline via a finite-state-machine architecture. AI-driven analysis prioritizes and verifies findings before they hit the dashboard.

| | |
|---|---|
| **stack** | Python · React · TypeScript · Playwright · WebSockets |
| **scale** | 7-stage FSM pipeline · 19 verification plugins |
| **performance** | real-time WebSocket telemetry, live attack-graph rendering |
| **detects** | SQLi · XSS · IDOR · Broken Authentication |
| **validated on** | OWASP Juice Shop · DVWA |
| **repo** | [github.com/Rks-ranjith/AWAP-AI](https://github.com/Rks-ranjith/AWAP-AI) |

</details>

<details>
<summary><b>[>] Active Directory Threat Detection &amp; SIEM Monitoring Lab</b></summary>
<br/>

```
$ nmap -sV 192.168.100.0/24
$ GetUserSPNs.py CORP.LOCAL/user -request        # kerberoasting sim
$ crackmapexec smb 192.168.100.0/24 -u users.txt # password spray sim
[wazuh] alert: Event ID 4769, RC4 downgrade detected
[wazuh] alert: Event ID 4625 x5, multi-account correlation
[+] detection coverage: 3/3 scenarios, 100%
```

Self-built 5-VM enterprise-simulation environment (Windows Server 2022 DC, 2x Win11 endpoints, Kali, Ubuntu SIEM) on an isolated /24 subnet, built for offensive AD research paired with defensive detection engineering.

| | |
|---|---|
| **stack** | Windows Server / AD · Wazuh SIEM 4.7.5 · Sysmon · Sigma · Impacket · CrackMapExec · Nmap |
| **scale** | 5-VM isolated /24 subnet · 100% agent coverage |
| **attacks simulated** | Kerberoasting (T1558.003) · Password Spraying (T1110.003) · Recon (T1046) |
| **detection** | custom Sigma rules: Event ID 4769 RC4 downgrade, multi-account 4625 correlation |
| **deliverable** | full incident-response report: timeline, evidence, root cause, remediation |
| **repo** | [github.com/Rks-ranjith/active-directory-soc-lab](https://github.com/Rks-ranjith/active-directory-soc-lab) |

</details>

<details>
<summary><b>[>] Malicious URL Scanner using Machine Learning</b></summary>
<br/>

```
$ python train.py --dataset urls_650k.csv --model random_forest
[+] training on 650,000+ labeled URLs...
[+] accuracy: 97.12%
[+] enrichment: shodan + virustotal + google-safe-browsing [online]
```

| | |
|---|---|
| **stack** | Python · Scikit-learn · Random Forest |
| **scale** | 650,000+ labeled training URLs |
| **performance** | 97.12% classification accuracy |
| **enrichment** | Shodan · VirusTotal · Google Safe Browsing (real-time) |
| **repo** | [github.com/Rks-ranjith/malicious-url-scanner](https://github.com/Rks-ranjith/malicious-url-scanner) |

</details>

<br/>

### 0x04 FIELD EXPERIENCE

**Independent Security Researcher**
`HackerOne :: Sep 2024 - Present`
Bug-bounty & vulnerability research on modern SPA / API architectures.

**CTF Player**
`TryHackMe :: Nov 2023 - Present`
65+ rooms across web exploitation, network attacks, Linux privesc, and OSINT.

**Cybersecurity Analyst (Virtual Internship)**
`Tata Group :: 2024`
Simulated real-world SOC analyst workflows.

<br/>

### 0x05 ACHIEVEMENTS

| Recognition | Details |
|---|---|
| **TryHackMe** | Top 10% global rank · 65+ rooms · active since Nov 2023 |
| **HackerOne** | Independent researcher · active since Sep 2024 |
| **CLLMSE** | 150 assessment questions + 10 hands-on labs, AI app attacks |
| **AD Lab** | 100% detection coverage across all 3 simulated ATT&CK scenarios |
| **AWAP-AI** | SQLi / XSS / IDOR / Broken Auth confirmed on Juice Shop + DVWA |

<br/>

### 0x06 CERTIFICATIONS & TRAINING

| Status | Certification | Provider |
|---|---|---|
| In Progress | CompTIA Security+ (SY0-701) | CompTIA :: expected Aug 2026 |
| Certified | LLM Security Expert (CLLMSE) | Red Team Leaders :: Jul 2026 |
| Completed | Pre Security | TryHackMe :: 2025 |
| Completed | Cybersecurity Analyst Virtual Internship | Tata Group :: 2024 |
| Completed | Monitor & Log with GCP Observability | Google :: 2024 |

<br/>

### 0x07 GITHUB TELEMETRY

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Rks-ranjith&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=39FF88&icon_color=A78BFA&text_color=E9D5FF&ring_color=8B5CF6" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Rks-ranjith&theme=dark&hide_border=true&background=0d0d0d&ring=39FF88&fire=A78BFA&currStreakLabel=39FF88" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rks-ranjith&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=39FF88&text_color=E9D5FF" width="49%"/>

</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Rks-ranjith&theme=algolia&no-frame=true&no-bg=true&row=1&column=6&margin-w=8"/>
</div>

<br>

<div align="center">
<!-- GitHub Profile Summary Cards (from last image) -->
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Rks-ranjith&theme=tokyonight" alt="Profile Summary Details" width="100%">
<br><br>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Rks-ranjith&theme=tokyonight" alt="Repos Per Language" height="180em">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Rks-ranjith&theme=tokyonight" alt="Most Commit Language" height="180em">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Rks-ranjith&theme=tokyonight" alt="Stats Summary" height="180em">
</div>

<br><br>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Rks-ranjith&theme=react-dark&bg_color=0d0d0d&color=39FF88&line=8B5CF6&point=E9D5FF&hide_border=true" width="100%"/>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/Rks-ranjith/Rks-ranjith/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<br/>

### 0x08 CURRENT PROCESS

```yaml
learning:
  - Advanced AI agent security & MCP threat modeling
  - Exploit development for AI application attack surfaces
  - CompTIA Security+ exam prep

building:
  - AWAP-AI v2 : expanding AI-driven vulnerability triage engine
  - New Sigma detection rulesets for the AD SOC lab

open_to:
  - Offensive Security / Red Team internships
  - AI & LLM Security research roles
```

<br/>

<div align="center">

```
"Security without engineering discipline is theater.
 I build systems that prove the vulnerability, not just claim it."
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2d0b5e,50:1a0b2e,100:050505&height=150&section=footer"/>

</div>
