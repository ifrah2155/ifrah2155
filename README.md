<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,100:58a6ff&height=220&section=header&text=Ifrah%20Hasware&fontSize=45&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Cybersecurity%20%7C%20SOC%20%7C%20GRC%20%7C%20Threat%20Intelligence&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=39D353&center=true&vCenter=true&width=680&lines=Final-Year+B.Tech+CE+%7C+Cyber+%26+Digital+Forensics;SOC+%7C+GRC+%7C+Threat+Intelligence;Python+%7C+Flask+%7C+Streamlit+%7C+Scikit-learn;Building+security+tools+that+explain+themselves" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Open%20to%20SOC%20%2F%20GRC%20%2F%20Threat%20Intel%20Internships-39D353?style=for-the-badge&logo=hackthebox&logoColor=white" />
<img src="https://img.shields.io/badge/B.Tech%20Computer%20Engineering-2027-58a6ff?style=for-the-badge&logo=academia&logoColor=white" />
<img src="https://img.shields.io/badge/Navi%20Mumbai-India-0d1117?style=for-the-badge&logo=googlemaps&logoColor=39d353" />

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=ifrah2155&color=39d353&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/ifrah2155?style=for-the-badge&color=58a6ff&labelColor=black)

</div>

---

### 🧑‍💻 Who I Am

```typescript
const ifrah = {
  name: "Ifrah Mateen Hasware",
  location: "Navi Mumbai, Maharashtra, India",
  education: {
    degree: "B.Tech Computer Engineering",
    college: "Ramrao Adik Institute of Technology (RAIT), D.Y. Patil University",
    minor: "Cybersecurity & Digital Forensics",
    cgpa: "8.95 / 10",
    graduation: "June 2027 (expected)"
  },
  focus: [
    "SOC operations, alert triage & incident response",
    "Threat detection, log analysis & MITRE ATT&CK awareness",
    "GRC, ISO/IEC 27001, risk assessment & audit documentation",
    "Threat intelligence, OSINT & digital investigations",
    "VAPT fundamentals & application security",
    "Python automation & security dashboards"
  ],
  languages: ["Python", "SQL", "Bash", "Java", "C++", "HTML5", "CSS3"],
  securityTools: [
    "Wireshark", "Nmap", "Burp Suite", "Scapy",
    "Kali Linux", "Git & GitHub"
  ],
  buildStack: [
    "Flask", "Streamlit", "Pandas", "scikit-learn",
    "REST APIs", "Matplotlib", "ReportLab"
  ],
  research: "First-author manuscript — JanSetu (AI-driven civic issue resolution)",
  status: "Security-focused final-year student seeking SOC / GRC / Threat Intelligence internships",
  openTo: ["SOC Analyst", "GRC Analyst", "Threat Intelligence", "Cybersecurity internships"]
};
```

---

### ⚡ At a Glance

| | |
|---|---|
| 🎓 **Education** | B.Tech Computer Engineering — RAIT, D.Y. Patil University, Navi Mumbai |
| 🛡️ **Minor** | Cybersecurity & Digital Forensics |
| 📊 **CGPA** | 8.95 / 10 |
| 🎯 **Focus** | SOC · Threat Detection · GRC · Threat Intel · VAPT |
| 📝 **Research** | First-author manuscript on AI-driven civic issue resolution |
| 🚀 **Flagship build** | Explainable hybrid IDS — F1 **0.992**, recall **1.000** |
| 📍 **Location** | Navi Mumbai, Maharashtra, India |

---

### 🔬 Featured Security Projects

#### 🛡️ Hybrid Intrusion Detection System
A hybrid network IDS that combines **9 Snort-style signature rules** with **Random Forest** and **Isolation Forest**, then fuses both layers into **explainable incidents** — every alert states the rule that fired, the feature that deviated, and whether the ML layer agrees.

- Crafted **6 labelled PCAPs** with Scapy — **9,776 packets / 2,844 flows** — covering port scans, DoS variants, brute force, ARP poisoning and benign traffic
- Reconstructed bidirectional **5-tuple flows** and engineered **55 features** across volume, timing, TCP flags and host behaviour
- Results: **precision 0.984 · recall 1.000 · F1 0.992 · accuracy 0.986** (11/12 true positives, 1 justified false positive)
- **4-tab Streamlit dashboard**: Evidence · ML Attribution · Affected Flows · Raw Alerts

| Layer | Technology |
|---|---|
| Data | Scapy, labelled PCAPs, Pandas |
| Detection | 9 signature rules, Random Forest, Isolation Forest |
| Explainability | Rule evidence, feature attribution, cross-layer validation |
| Interface | Streamlit, JSON/CSV exports, technical report |

<img src="https://github-readme-stats.vercel.app/api/pin/?username=ifrah2155&repo=Intrusion-Detection-System&theme=nord&border_color=39d353&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" />

[🔗 Code](https://github.com/ifrah2155/Intrusion-Detection-System) · [📄 Technical report](https://github.com/ifrah2155/Intrusion-Detection-System/blob/main/docs/REPORT.md)

<br/>

#### 📊 Log File Analyzer & Security Dashboard
Python/Flask tool that parses SSH (`auth.log`) and Apache (`access.log`) files, processing **50,000+ log lines** to surface brute-force, DoS and web-scanning attacks.

- Severity classification, evidence collection and structured incident reporting
- **REST API** plus an interactive dashboard with **5 visualisations** — activity timeline, top attacker IPs, threat distribution, hourly heatmap and protocol breakdown
- CSV exports and PDF incident summaries with attacker attribution

| Layer | Technology |
|---|---|
| Backend | Python, Flask, Pandas, Regex, REST APIs |
| Reporting | Matplotlib, ReportLab |
| Output | CSV, PDF, live web dashboard |

<img src="https://github-readme-stats.vercel.app/api/pin/?username=ifrah2155&repo=log-analyzer&theme=nord&border_color=39d353&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" />

[🔗 Code](https://github.com/ifrah2155/log-analyzer)

<br/>

#### ⌨️ Virtual Keyboard Attack Suite
A controlled-lab offensive security project documenting **6 attack modules** against a virtual keyboard in a Flask demo app:

- Screenshot capture, click-coordinate reconstruction, clipboard hijacking
- DOM inspection, keystroke-timing analysis, process-memory scanning/keylogging
- Proposed mitigations: input randomisation, clipboard isolation, protected rendering and timing defences

| Layer | Technology |
|---|---|
| Environment | Python, Flask, controlled lab |
| Focus | Client-side attack surface, keylogging, timing side channels |
| Output | Documented attack modules + mitigation guidance |

<br/>

#### 🏙️ JanSetu — AI-Driven Civic Issue Resolution
**First-author research manuscript.** JanSetu detects coordinated fake civic reports using spatio-temporal analysis and **multi-signal corroboration**, then ranks issues by verified evidence rather than raw complaint volume.

- End-to-end web application with issue reporting, validation, prioritisation and **explainable outputs**
- Research prototype in **Python, Flask, HTML/CSS**
- Full-stack build with **FastAPI, PostgreSQL/PostGIS, DBSCAN, YOLOv8 + CLIP, React and Flutter**

<img src="https://github-readme-stats.vercel.app/api/pin/?username=ifrah2155&repo=JanSetu&theme=nord&border_color=39d353&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" />

[🔗 Code](https://github.com/ifrah2155/JanSetu)

---

### 📋 GRC & Threat Intelligence

#### 🏛️ ISMS Tracker — ISO/IEC 27001 Compliance Automation
Final-year project: an audit-readiness platform that follows the real GRC workflow — risk assessment → control implementation → evidence collection → gap analysis → Statement of Applicability → auditor pack.

- Full **ISO/IEC 27001:2022 Annex A** library — **93 controls** across 4 themes
- **FAIR-lite risk quantification** (SLE, ALE, residual risk) with Monte Carlo support
- Evidence lifecycle with expiry-based nonconformity flags
- Cross-mapping across **ISO 27001 ↔ NIST CSF 2.0 ↔ SOC 2**, plus SoA and audit-pack exports

| Layer | Technology |
|---|---|
| Backend | Python 3.12, Flask 3.1, SQLAlchemy 2.0 |
| Data | SQLite, Pandas |
| Reporting | Jinja2, CSV / HTML audit pack, LaTeX-ready PDF |
| Testing | pytest |

<sub>🔒 Repository in progress — happy to walk through the architecture on request.</sub>

<br/>

#### 🕵️ Threat Intelligence Briefing Portfolio
Four **TLP:AMBER** threat-intelligence assessments built with passive, read-only collection and explicit source tiering:

| Brief | Focus |
|---|---|
| **Underground Economy** | Ransomware-as-a-service tiers, initial-access pricing, stealer-log exposure and market disruption — 37 traceable sources |
| **Exploit & Zero-Day Credibility** | Separate a confirmed breach from an unproven zero-day claim; confidence language, CVE mapping and IOC annexes |
| **Threat Actor Profile: Handala** | Attribution to Iran's MOIS, MITRE ATT&CK **G1055** mapping, Diamond Model and IOC register |
| **Brand & Data Exposure** | Credential exposure, impersonation/phishing indicators, certificate-transparency checks and monitoring uplift |

- Evidence captured as numbered sources; every judgement traceable to a capture
- **MITRE ATT&CK** and **Diamond Model** annexes
- OSINT toolkit: Shodan, Amass, Google dorking, crt.sh, CertSpotter, urlscan.io, Hudson Rock, ransomware.live

---

### 🧪 Labs & Incident Response

| Lab | What I did |
|---|---|
| **Incident Response Capstone** | Detected reconnaissance with Nmap and Wireshark; investigated network evidence with CurrPorts, Windows Event Viewer and HashCalc; contained, blocked and recovered affected systems |
| **Ransomware Behaviour Analysis** | Simulated ransomware in an isolated Kali VM; static analysis (SHA-256, strings, YARA) and dynamic analysis (inotifywait, entropy tracking, ransom-note capture), plus a behaviour detector and incident report |
| **Malware Analysis** | VirusTotal triage, PEiD packing checks, Ghidra/strings static analysis, Process Explorer and Wireshark dynamic analysis in an isolated lab |
| **Network Security** | Nmap scanning, packet capture and ARP analysis; identified port scans, spoofing indicators and lateral-movement patterns |
| **OSINT & Digital Investigations** | Social-media and website investigations, WHOIS/DNS/certificate checks, evidence capture and structured report writing (CTRL. ALT. ACT. — CSI & MKITOS) |
| **Cryptography & Network Security** | Implemented Caesar, Playfair, Vigenère, Rail Fence and Hill ciphers, RSA, Diffie-Hellman, hashing and socket programming |

---

### 🧩 More Builds

| Project | What it does | Stack |
|---|---|---|
| **ResolveIt** | Virtual court & mediation platform with RBAC across three roles and a tamper-evident document lifecycle | TypeScript, React, Node |
| **Digital Wellbeing Guardian** | IBM SkillsBuild team project: screen-time tracker with Pomodoro cycles, notifications and local analytics | JavaScript, HTML5, Tailwind CSS |
| **Phishing Email Analysis** | Header forensics, SPF/DKIM/DMARC checks, URL/attachment inspection and user-awareness report | MxToolbox, VirusTotal, URLVoid |
| **Nmap Network Scan** | Scanned a /24 network, mapped live hosts, open ports and service-level risk | Nmap, Kali Linux |
| **Hotel Booking Website** | End-to-end booking flow with payments, PDF invoices and email confirmations | PHP, MySQL, Bootstrap |
| **DevOps lab** | Dockerised Express service, React Router + Tailwind app and Git branching workflows | Docker, Express, React, Vite |

---

### 🛠️ Tech Stack

**Languages**

![Skills](https://skillicons.dev/icons?i=python,java,cpp,php,typescript,javascript,bash)

**Frameworks & Data**

![Skills](https://skillicons.dev/icons?i=flask,fastapi,react,nodejs,tailwind,mysql,postgresql,sqlite)

**Platforms & Tools**

![Skills](https://skillicons.dev/icons?i=docker,git,github,linux,aws,vscode,postman)

**Security operations:** SOC workflows · alert triage · incident response · log analysis · threat detection · MITRE ATT&CK · IDS/IPS concepts

**GRC & compliance:** ISO/IEC 27001 · risk assessment · security controls · audit documentation · policy mapping · NIST CSF 2.0 · SOC 2 · FAIR

**Offensive & defensive:** OWASP Top 10 · VAPT fundamentals · vulnerability assessment · packet analysis · Wireshark · Nmap · Burp Suite · Scapy · Kali Linux

**Threat intelligence & OSINT:** Shodan · Amass · Google dorking · crt.sh · CertSpotter · urlscan.io · Hudson Rock · ransomware.live · Diamond Model

**Programming & automation:** Python · SQL · Bash · Flask · Streamlit · REST APIs · Pandas · scikit-learn · Matplotlib · ReportLab

---

### 🏅 Certifications

| Certification | Issuer | Year |
|---|---|---|
| ISO/IEC 27001 Information Security Associate | SkillFront | 2025 |
| AWS Academy Graduate — Cloud Foundations | AWS Academy | 2026 |
| Palo Alto Networks Fundamentals — Cybersecurity, Cloud, SOC & Network Security | Palo Alto Networks | 2024 |
| Microsoft Applied Skills — Power Automate | Microsoft Learning | 2025 |
| Deloitte Cyber Job Simulation | Deloitte / Forage | 2025 |
| Tata Group — Cybersecurity Analyst Job Simulation | Tata / Forage | 2025 |
| CTRL. ALT. ACT. — Open-Source Intelligence | Cyber Secured India | 2025 |
| CS50's Introduction to Programming with Python | HarvardX | 2025 |
| AI, LLM, Prompting & AI Agents | IBM SkillsBuild | 2025 |
| Cybersecurity, SOC, Network & Cloud Security Fundamentals | Beacon | — |
| PCCET — Certified Cybersecurity Entry-level Technician | Palo Alto Networks | — |
| Foundation Course on IR4.0 Technologies | Edunet Foundation | 2025 |

<sub>Also completed: NPTEL Design, Technology & Innovation, OOPs in Java (Great Learning), Mission GSoC and project-based learning programmes.</sub>

---

### 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ifrah2155&show_icons=true&theme=nord&border_color=39d353&title_color=58a6ff&icon_color=39d353&text_color=c9d1d9&bg_color=0d1117" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ifrah2155&layout=compact&theme=nord&border_color=39d353&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" width="39%" />

<img src="https://streak-stats.demolab.com?user=ifrah2155&theme=nord&border=39d353&background=0d1117&stroke=58a6ff&ring=39d353&fire=58a6ff&currStreakLabel=39d353" width="70%" />

</div>

### 🏆 Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=ifrah2155&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8" />

</div>

### 📊 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ifrah2155&theme=react-dark&color=39d353&line=58a6ff&point=ffffff&area=true&hide_border=true&bg_color=0d1117" width="100%" />

</div>

---

### 🌱 Beyond the Terminal

- 🎤 **Workshop Speaker** — designed and delivered a hands-on *Security & Workflow Tools* workshop for peers at RAIT (Nov 2025).
- 🗣️ **Languages** — English (advanced), Hindi, Marathi and Urdu (native).
- 🎨 **Outside tech** — arts & crafts, handmade design and poetry.
- 📚 **Currently learning** — deeper GRC, threat intelligence tradecraft, cloud security and AI-agent workflows for security operations.

---

### 🔗 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-58a6ff?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ifrah-hasware-502646286)
[![Email](https://img.shields.io/badge/Email-39d353?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ifrah.hasware21@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ifrah2155)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,100:39d353&height=120&section=footer" width="100%"/>
