> ⚠️ This repository is for educational and threat intelligence purposes only. No malicious functionality is hosted or executed here.

# 🛡️ The CAPTCHA Deception: From Individual Phishing to International Crackdown

## Overview

This report presents an in-depth investigation into a sophisticated phishing campaign leveraging fake Cloudflare CAPTCHA challenges combined with **pastejacking techniques** to deploy multi-stage malware payloads. The attack culminates in data exfiltration and communication with command-and-control infrastructure linked to the recently sanctioned **AEZA Group**, a known bulletproof hosting provider.

The campaign was initially spotted and shared by [Christoph Jans](https://www.linkedin.com/in/christoph-jans/), whose vigilance sparked this analysis.

## 🔍 Key Findings

- **Attack Vector**: Fake CAPTCHA ➝ Clipboard Injection ➝ PowerShell Execution
- **Malware Delivered**: Base64-encoded stealer (e.g., HijackLoader / DeerStealer)
- **Persistence Mechanisms**: Registry edits, memory injection, folder cloaking
- **Data Stolen**: Credentials, browser sessions, system information
- **C2 Communication**: Exfiltration to `anodes.pro` and `aeza.network` infrastructure
- **Attribution**: Russian-language code comments, link to OFAC-sanctioned AEZA

## 📎 Contents

- `index.html`: Full illustrated report with screenshots and technical breakdown
- `/assets`: Folder containing malware screenshots, deobfuscated code, and network traces
- `ioc_list.txt`: Indicators of Compromise (domains, IPs, hashes)

## 📢 Background

On **July 1, 2025**, the U.S. Department of the Treasury’s Office of Foreign Assets Control (OFAC) and the UK’s National Crime Agency (NCA) sanctioned **AEZA INTERNATIONAL LTD**, citing their critical role in supporting ransomware gangs and phishing operators.

This phishing campaign demonstrates direct infrastructure use of AEZA-hosted assets, providing real-time threat intelligence tied to sanctioned networks.

## 🔖 Tags

`#CyberSecurity` `#ThreatIntelligence` `#Phishing` `#Pastejacking` `#MalwareAnalysis` `#AEZAGroup` `#DeerStealer` `#BulletproofHosting` `#CTI` `#OFACSanctions`


---

## ✍️ Author

**Andrii Stepovyi**  
Security Consultant | Cyber Threat Intelligence Researcher | PenTester  
[LinkedIn Profile](https://www.linkedin.com/in/andrii-stepovyi/)  
