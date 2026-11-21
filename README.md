<div align="center">

# Oludemi Joshua

**Cybersecurity Analyst · Cloud Security · IAM · Security Automation**

I build, break, and document practical security systems across cloud, identity, and security operations.

`AWS` `Azure` `Terraform` `Bicep` `PowerShell` `Python` `JavaScript`

**Learn → Build → Test → Document → Improve**

</div>

<!-- Add contact links here, e.g. LinkedIn and email -->

---

## Targeting

**SOC Analyst · Cloud Security Analyst · IAM / Security Automation**
Also open to Cloud Security Engineering and IT Security Support roles.

---

## Featured projects

### ☁️ [Azure Honeypot & SOC Lab (V2)](https://github.com/Bigsnack7/Honeypot-SOC_Lab.V2)
`Azure` `Microsoft Sentinel` `Bicep` `KQL` `Logic Apps` `GitHub Actions`

A SOC lab defined entirely as code. Three internet-facing decoys (Windows RDP, Cowrie SSH, web) feed Microsoft Sentinel, which runs MITRE-mapped detections, threat-intel enrichment, and an automated SOAR playbook.

- Isolated VNet with outbound internet denied, so a compromised decoy can't attack anything else.
- Pipeline-health rules, added after a real three-day silent outage went undetected.
- Sentinel workbook with a MITRE heat map and attack geo map.

### 🪟 [Active Directory Automation Toolkit](https://github.com/Bigsnack7/AD_PS-automation) 
`PowerShell` `Active Directory` `Audit logging`

Guarded automation for AD provisioning, user lifecycle, and security reporting, built as the `ADAutoX` module.

- Preflight, provision, verify, and report stages for bulk department provisioning.
- `-WhatIf` previews, destructive-operation gates, protected-account checks, and rollback.
- JSONL audit trail plus locked-out, inactive, and password-never-expires scans.
- Offline test suite and manual evidence from a Windows Server lab.

### 🛰️ [Terraform AWS Honeypot Lab](https://github.com/Bigsnack7/Terraform-Honeypot_Lab)
`AWS` `Terraform` `CloudWatch` `GitHub Actions (OIDC)`

Isolated Linux (Cowrie), web (Flask), and Windows RDP honeypots deployed with Terraform, with CloudWatch and CloudTrail logging, Sysmon telemetry, and nine version-controlled Logs Insights investigation queries. Separate plan, apply, and destroy workflows with remote state protection.

**Status:** deployed dev environment with runtime evidence for Linux, web, and Windows telemetry. Detection-query and Windows event validation is ongoing.

### 🔐 [HEX WATCH CIPHER](https://github.com/Bigsnack7/hex-watch-cipher)
`JavaScript` `Web Crypto API`

Client-side file and message encryption in the browser: AES-256-GCM, RSA-OAEP hybrid encryption, PBKDF2 key derivation, and HMAC integrity checks, with no backend uploads.

<details>
<summary><b>🌐 Enterprise Network Security Lab</b> (Cisco Packet Tracer)</summary>

<br>

Enterprise network simulation covering VLANs and inter-VLAN routing, OSPF, HSRP redundancy, ACLs and segmentation, EtherChannel, Spanning Tree, DHCP relay, NAT, and wireless.

</details>

---

## Currently building

### HEX WATCH: AI-native SOC platform
**Ingestion → Detection → Correlation → Investigation → Automation → AI assistance**

A security operations platform covering the full investigation lifecycle: event ingestion, detection and alert correlation, incident management, investigation workflows, automation, and AI-assisted analysis.

`Python` `FastAPI` `React` `Redis` `Rust` `C++` `WebSockets` `LangGraph` `Redpanda`

**Status:** active development.

---

## Open-source contributions

| Project | Contribution |
|---|---|
| **HashGuard** (Python, file integrity monitoring) | Authentication hardening, scheduled integrity scans, event status tracking, automated tests, CI improvements |
| **SCOUT-X** (Python, FastAPI, authenticated telemetry) | Telemetry authentication, replay protection, input and GPS consistency validation, dashboard authentication, adversarial testing, CI improvements |

---

## Skills

| Domain | Tools & concepts |
|---|---|
| **Security operations** | Blue team, SOC operations, detection engineering, MITRE ATT&CK mapping |
| **Cloud security** | AWS, Azure, Microsoft Sentinel |
| **Detection & investigation** | KQL, CloudWatch Logs Insights |
| **Infrastructure as code** | Terraform, Bicep, GitHub Actions (OIDC) |
| **Identity & access** | Active Directory, IAM, PowerShell |
| **Networking** | TCP/IP, VLANs, OSPF, HSRP, ACLs, NAT |
| **Development** | Python, PowerShell, JavaScript, FastAPI |
| **Cryptography** | AES-GCM, RSA-OAEP, HMAC, PBKDF2 |

---

## Certifications & training

**Roadmap:** Microsoft SC-900 → SC-300 → HashiCorp Terraform Associate (004) → Microsoft SC-500

**Completed training:** Centri Blue Team Junior Analyst · Cisco Python Essentials 1 · Cisco Networking Basics · Ethical Hacking Essentials · Vulnerability Management · Threat Hunting · Digital Forensics · OSINT

---

<div align="center">

I demonstrate what works, document the limits, and keep improving.
Open to collaborating on practical security engineering and open-source security projects.

[![GitHub](https://img.shields.io/badge/GitHub-BigSnack7-181717?style=for-the-badge&logo=github)](https://github.com/Bigsnack7)

</div>
