# Oludemi Joshua

### 🛡️ Cybersecurity Analyst · IAM Analyst · Cloud Security · Security Automation

I'm a cybersecurity-focused builder who wants to understand how infrastructure works, how threats operate, and how technology can make systems more secure. My approach: **Learn, Build, Test, Document, Improve.**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

## ⚡ The Short Version

```text
> whoami
Oludemi Joshua, Cloud Security & Automation Engineer

> mission
Know the infrastructure.
Understand the threat.
Build the defense.
Automate the response.
Prove it with working code.

> method
Learn → Build → Test → Document → Improve
```

I don't just study security tools in isolation. I build them, test them, and document the results, including what I have and haven't verified yet.

## 🚀 Featured Projects

| Project | What It Does | Stack |
|---|---|---|
| ☁️ **[Terraform Honeypot Lab](https://github.com/Bigsnack7/Terraform-Honeypot_Lab)** | Opt-in AWS honeypots with centralized logging, audit trails, and investigation queries, all as code | AWS · Terraform · CloudWatch · GitHub Actions |
| 🪟 **AD_PS-automation** | Active Directory identity lifecycle automation with safety rails built in | PowerShell · AD · IAM |
| 🔐 **HEX WATCH CIPHER** | Client-side encryption in the browser; no server ever sees your data | JavaScript · Web Crypto API |
| 🌐 **Enterprise Network Security Lab** | Full enterprise topology with redundancy and segmentation | Cisco Packet Tracer |

### ☁️ Terraform Honeypot Lab: AWS decoys, built to be reviewed before they're run

My latest build, and a rebuild of my earlier Azure/Bicep/Sentinel honeypot lab on AWS and Terraform.

- **Three optional decoys:** Cowrie SSH, a Flask web app with honeytoken paths, and a Windows RDP host with Sysmon and PowerShell telemetry.
- **Safe by default:** everything is off until enabled, each decoy has its own VPC, and listeners open only to CIDRs I list. There are no public SSH or RDP admin ports, and Systems Manager is the admin path.
- **Logging and investigation:** CloudWatch Logs with 7-day retention, CloudTrail audit logging to a private S3 bucket, and 9 version-controlled Logs Insights queries for manual hunting.
- **Controlled delivery:** 5 GitHub Actions workflows using OIDC (no long-lived AWS keys), with separate plan, apply, and destroy flows and a Python plan guard against unintended deletions.
- **Cost-aware:** no NAT Gateway or load balancer, optional security services off by default, and a budget alert.

**Status:** build complete and statically validated (Terraform fmt/validate, plan-guard tests, workflow parsing). Not yet deployed. Next step is deploying it and validating the detections against real telemetry.

## 🤝 Open-Source Contributions

Security improvements I contributed to other people's projects.

| Project | My Contribution | Stack |
|---|---|---|
| 🧾 **HashGuard** | Authentication hardening, scheduled integrity scans, event status tracking, automated tests and CI improvements. Reviewed and merged upstream. | Python · SHA-256 · CI |
| 🛰️ **SCOUT-X** | Authenticated telemetry with replay protection, input and GPS consistency validation, dashboard authentication, adversarial testing and CI improvements. | Python · FastAPI · Crypto |

## 🔭 Currently Building

### 🧠 HEX WATCH: an AI-native SOC platform

My most ambitious project yet: a platform that takes a security event from raw log to investigated incident.

`Ingest → Detect → Correlate → Investigate → Automate → AI-assist`

- Security event ingestion
- Threat detection and alert correlation
- Incident management and investigation workflows
- Security automation
- AI-assisted analysis

**Stack:** Python · WebSockets · React · Rust · C++ · TailwindCSS · LangGraph · Redpanda · Redis · HTTPX | 🚧 Actively in development

## 🧰 Toolbox

| Area | Technologies |
|---|---|
| 🛡️ Security Operations | Blue Team, SOC, Security Monitoring, Threat Analysis, Detection Engineering |
| ☁️ Cloud & IaC | AWS (EC2, VPC, CloudWatch, CloudTrail, IAM, Systems Manager), Terraform, Azure, Microsoft Sentinel, KQL, Bicep |
| ⚙️ CI/CD | GitHub Actions, OIDC |
| 🪟 Windows & IAM | Windows Server, Active Directory, PowerShell |
| 🌐 Networking | TCP/IP, VLANs, OSPF, HSRP, ACLs, NAT |
| 💻 Development | Python, JavaScript, FastAPI |
| 🔑 Cryptography | AES-GCM, RSA-OAEP, HMAC, PBKDF2 |

## 📚 Certifications & Training

**🎯 Certification path (in progress)**

| Step | Certification | Level |
|---|---|---|
| 1 | Microsoft SC-900: Security, Compliance, and Identity Fundamentals | Fundamentals |
| 2 | Microsoft SC-300: Identity and Access Administrator | Associate |
| 3 | HashiCorp Terraform Associate (004) | Associate |
| 4 | Microsoft SC-500: Cloud and AI Security Engineer Associate | Associate |

**✅ Completed:** Cisco Python Essentials 1 · Cisco Networking Basics · Blue Team Junior Analyst · Ethical Hacking Essentials · Vulnerability Management · Threat Hunting · Digital Forensics and OSINT

## 🎯 Open To

SOC Analyst · Cybersecurity Analyst · Blue Team · Cloud Security · IAM · Security Engineering · Security Automation

🟢 **Open to work:** cybersecurity roles, IT security support, freelance projects and collaborations. Send a project, role or question and I'll reply within 24 hours.

**LEARN. BUILD. SECURE. IMPROVE.**

💻 [GitHub](https://github.com/Bigsnack7)

<!-- Add your links here: 🌐 [Portfolio](URL) • 💼 [LinkedIn](URL) -->
