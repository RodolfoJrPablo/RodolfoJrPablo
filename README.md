# 👾 Rodolfo Jr Pablo - SOC Analyst Portfolio

> Cybersecurity student focused on threat detection, incident response, and security operations.

---

## 🧑‍💻 About Me

Hi, I'm Rodolfo, a cybersecurity student passionate about Blue Team operations and Security Operations Centre (SOC) analysis. I'm building hands-on experience through lab projects that simulate real-world threats, log analysis, and detection engineering.

- 🎓 Studying: Bachelor of Cybersecurity at University of Technology, Sydney
- 🏅 Certifications: Expected completion 2026
- 📍 Location: Sydney, Australia
- 📧 Contact: RodolfoJr.Pablo@student.uts.edu.au
- 🔗 LinkedIn: https://www.linkedin.com/in/rodolfo-jr-pablo/

---

## 🛡️ Skills & Tools

| Category              | Tools & Technologies                                      |
|-----------------------|-----------------------------------------------------------|
| SIEM                  | Splunk, Elastic Stack (ELK), Microsoft Sentinel           |
| Network Analysis      | Wireshark, Zeek, Suricata                                 |
| Threat Intelligence   | MITRE ATT&CK, VirusTotal, AlienVault OTX, MISP            |
| Scripting             | Python, Bash                                              |
| Frameworks            | NIST CSF, Cyber Kill Chain, MITRE ATT&CK                  |
| Operating Systems     | Kali Linux, Ubuntu, Windows Server                        |
| Virtualisation        | VirtualBox, VMware                                        |

---

## 📁 Projects

### 🟢 ### 🟢 Easy — [Home Lab SIEM with Splunk](https://github.com/RodolfoJrPablo/Home-Lab-SIEM-with-Splunk)

**Goal:** Ingest logs from your own machine (Windows Event Logs, syslog), and create basic dashboards to visualize login attempts, process creation, and network connections. Great intro to log ingestion and querying.

**What I did:**
- Set up [tool/environment]
- Ingested logs from [source]
- Built dashboards to visualise [what]

**Skills demonstrated:** Log ingestion, SIEM querying, dashboard creation  
**Tools used:** Splunk Free, Windows Event Logs  
**Write-up:** [View project README](https://github.com/yourusername/home-lab-siem/blob/main/README.md)

---

### 🟡 Medium - Detection Rule Library with Sigma

**Goal:** Write custom Sigma rules for common attack techniques from the MITRE ATT&CK framework and test them against log samples using sigma-cli and document true/false positive rates.

**What I did:**
- Mapped attack techniques to MITRE ATT&CK
- Wrote Sigma rules for [techniques]
- Tested rules against sample logs and documented FP/TP rates

**Skills demonstrated:** Detection engineering, ATT&CK mapping, log analysis  
**Tools used:** Sigma CLI, Atomic Red Team, ELK Stack  
**Write-up:** [Link to report]

---

### 🔴 Hard - SOC Automation Pipeline

**Goal:** Design a mini SOAR workflow using open-source tools (n8n or Shuffle) that automatically ingests an alert, enriches it via VirusTotal/Shodan APIs, assigns a severity score, and fires a Slack/email notification. Mirrors real enterprise SOC automation.

**What I did:**
- Designed an automated alert triage workflow
- Integrated VirusTotal and Shodan APIs for IOC enrichment
- Triggered notifications via Slack/email based on severity scoring

**Skills demonstrated:** SOAR concepts, API integration, alert triage automation  
**Tools used:** n8n / Shuffle, Python, VirusTotal API  
**Write-up:** [Link to report]

---

## 📊 Lab Environment

```
┌─────────────────────────────────────────────┐
│              Home Lab Setup                 │
│                                             │
│  [Attacker VM]        [Victim VM]           │
│   Kali Linux    ───►  Windows 10 / Ubuntu   │
│                                             │
│          ▼ Logs forwarded to ▼              │
│                                             │
│         [SIEM] Splunk / Elastic             │
│                                             │
│         [Threat Intel] OTX / MISP           │
└─────────────────────────────────────────────┘
```

---

## 📝 Incident Response Reports

| # | Scenario | Type | Date |
|---|----------|------|------|
| 1 | [Phishing Email Analysis] | Threat Intel | [Month Year] |
| 2 | [Lateral Movement Detection] | IR Report | [Month Year] |
| 3 | [Ransomware Simulation Response] | IR Report | [Month Year] |

> Reports are written in analyst format: executive summary, timeline, IOCs, containment, and lessons learned.

---

## 📚 Learning Path

- [ ] CompTIA Security+
- [ ] Blue Team Labs Online — SOC Level 1
- [ ] TryHackMe — SOC Analyst Learning Path
- [ ] Splunk Core Certified User
- [ ] MITRE ATT&CK Defender (MAD)

---

## 🗂️ Repository Structure

```
📦 soc-portfolio
 ┣ 📂 projects
 ┃ ┣ 📂 01-home-lab-siem
 ┃ ┣ 📂 02-detection-rules
 ┃ ┗ 📂 03-soc-automation
 ┣ 📂 ir-reports
 ┣ 📂 scripts
 ┗ 📄 README.md
```

---

## 📌 References & Resources

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)
- [Sigma Rules](https://github.com/SigmaHQ/sigma)
- [Blue Team Labs Online](https://blueteamlabs.online/)
- [TryHackMe](https://tryhackme.com/)

---

*Last updated: April 2026*
