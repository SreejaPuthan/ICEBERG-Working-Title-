# 🧊 ICEBERG – Automated CVE, Exploit & Risk Intelligence

ICEBERG is an automated threat intelligence pipeline that continuously tracks
new and updated CVEs, correlates exploit availability, and produces Threat Intel space to work on security advisories.

## 🔍 What ICEBERG Does
- Pulls **new & updated CVEs** from NVD
- Identifies **actively exploited vulnerabilities** (CISA KEV)
- Detects **public exploit availability** (Exploit-DB, GitHub)
- Classifies CVEs by **risk & exploitability**
- Generates **advisory-style comprised reports**
- Auto-updates every **6 hours via GitHub Actions**

## 📄 Live Advisory Output
➡️ **[Latest ICEBERG Threat Advisory](README_ICEBERG.md)**  
(Automatically updated every 6 hours)

## 🧠 Use Cases
- Vulnerability Management
- Threat Intelligence
- Security Advisory Automation
- GRC & Risk Prioritization

## ⚙️ Tech Stack
- Python 3.10
- NVD CVE API
- CISA KEV Catalog
- Exploit-DB (local cache)
- GitHub Search API
- GitHub Actions (Automation)

## 🔐 Security & API Keys
All API keys are handled securely using GitHub Secrets.  
No credentials are hardcoded.

## 📜 License
MIT License

## 👤 Author
Built by **Puthan Sreeja**  
(Security & Vulnerability Management Professional)
