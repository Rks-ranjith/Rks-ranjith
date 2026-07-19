<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,35:0d1f12,70:1a0b2e,100:2d0b5e&height=280&section=header&text=RANJITH%20KUMAR%20S&fontSize=52&fontColor=39FF88&fontAlignY=36&desc=Offensive%20Security%20%E2%80%A2%20AI%2FLLM%20Security%20%E2%80%A2%20Detection%20Engineering&descAlignY=54&descSize=16&animation=fadeIn&fontName=Fira+Code" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=700&color=39FF88&center=true&vCenter=true&width=750&lines=root%40kali%3A~%23+building+AWAP-AI+...;root%40kali%3A~%23+red-teaming+Active+Directory...;root%40kali%3A~%23+attacking+LLMs+%7C+prompt+injection+%7C+RAG;root%40kali%3A~%23+status%3A+top+10%25+TryHackMe" alt="typing"/>

<br/>

<img src="https://img.shields.io/badge/Bengaluru-India-0d0d0d?style=for-the-badge&labelColor=0d0d0d&color=8B5CF6"/>&nbsp;
<img src="https://img.shields.io/badge/Status-Open_to_Internships-0d0d0d?style=for-the-badge&labelColor=0d0d0d&color=39FF88"/>

<br/><br/>

[![GitHub](https://img.shields.io/badge/GitHub-Rks--ranjith-0d0d0d?style=for-the-badge&logo=github&logoColor=39FF88)](https://github.com/Rks-ranjith)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0d0d0d?style=for-the-badge&logo=linkedin&logoColor=A78BFA)](https://linkedin.com/in/ranjith-kumar-0117d)
[![Email](https://img.shields.io/badge/Email-Contact-0d0d0d?style=for-the-badge&logo=gmail&logoColor=E9D5FF)](mailto:ranjithk0117@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=Rks-ranjith&style=for-the-badge&color=39FF88&labelColor=0d0d0d&label=PROFILE+VIEWS"/>&nbsp;
<img src="https://img.shields.io/github/followers/Rks-ranjith?style=for-the-badge&logo=github&labelColor=0d0d0d&color=8B5CF6&label=FOLLOWERS"/>&nbsp;
<img src="https://img.shields.io/github/stars/Rks-ranjith/AWAP-AI?style=for-the-badge&logo=github&labelColor=0d0d0d&color=A78BFA&label=STARS"/>

</div>

<br/>

<div align="center">
<img src="assets/mission-dossier.svg" width="100%"/>
</div>

<br/>

### `0x01` ARSENAL

<div align="center">
<img src="https://skillicons.dev/icons?i=python,ts,js,bash,html,css,react,nodejs,postgres,redis,docker,git,linux,windows&theme=dark"/>
</div>

<br/>

```
┌─ security_toolkit ──────────────────────────────────────────────────┐
│  recon / exploit  : Burp Suite · Nmap · Metasploit · Wireshark       │
│  ad attack        : Impacket · CrackMapExec                          │
│  automation       : Playwright (headless browser attack automation)  │
│  detection / siem : Wazuh SIEM · Sysmon · Sigma Rules                │
│  frameworks       : MITRE ATT&CK · OWASP Top 10 · OWASP LLM Top 10   │
└────────────────────────────────────────────────────────────────────┘
```

<br/>

<div align="center">
<img src="assets/ai-security-matrix.svg" width="100%"/>
</div>

<br/>

### `0x03` OPERATIONS LOG // FEATURED PROJECTS

<details open>
<summary><b>▸ AWAP-AI :: Autonomous Web Application Penetration Testing System</b></summary>
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
<summary><b>▸ Active Directory Threat Detection & SIEM Monitoring Lab</b></summary>
<br/>

```
$ nmap -sV 192.168.100.0/24
$ GetUserSPNs.py CORP.LOCAL/user -request        # kerberoasting sim
$ crackmapexec smb 192.168.100.0/24 -u users.txt # password spray sim
[wazuh] alert: Event ID 4769, RC4 downgrade detected
[wazuh] alert: Event ID 4625 x5, multi-account correlation
[+] detection coverage: 3/3 scenarios, 100%
```

Self-built 5-VM enterprise-simulation environment (Windows Server 2022 DC, 2× Win11 endpoints, Kali, Ubuntu SIEM) on an isolated /24 subnet, built for offensive AD research paired with defensive detection engineering.

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
<summary><b>▸ Malicious URL Scanner using Machine Learning</b></summary>
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

<div align="center">
<img src="assets/field-experience.svg" width="100%"/>
</div>

<br/>

<div align="center">
<img src="assets/achievements.svg" width="100%"/>
</div>

<br/>

<div align="center">
<img src="assets/certifications.svg" width="100%"/>
</div>

<br/>

### `0x07` GITHUB TELEMETRY

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Rks-ranjith&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=39FF88&icon_color=A78BFA&text_color=E9D5FF&ring_color=8B5CF6" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Rks-ranjith&theme=dark&hide_border=true&background=0d0d0d&ring=39FF88&fire=A78BFA&currStreakLabel=39FF88" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rks-ranjith&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=39FF88&text_color=E9D5FF" width="49%"/>

</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Rks-ranjith&theme=algolia&no-frame=true&no-bg=true&row=1&column=6&margin-w=8"/>
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Rks-ranjith&theme=react-dark&bg_color=0d0d0d&color=39FF88&line=8B5CF6&point=E9D5FF&hide_border=true" width="100%"/>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/Rks-ranjith/Rks-ranjith/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<br/>

<div align="center">
<img src="assets/current-process.svg" width="100%"/>
</div>

<br/>

<div align="center">

```
"Security without engineering discipline is theater.
 I build systems that prove the vulnerability, not just claim it."
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2d0b5e,50:1a0b2e,100:050505&height=150&section=footer"/>

</div>
