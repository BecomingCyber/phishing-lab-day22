# 🛡️ Day #22 – Phishing Email Analysis Lab

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Lab Status](https://img.shields.io/badge/status-completed-brightgreen)
![Security](https://img.shields.io/badge/focus-phishing_analysis-critical)
![Tool: EML Analyzer](https://img.shields.io/badge/tool-EML_Analyzer-blue)
![Tool: VirusTotal](https://img.shields.io/badge/tool-VirusTotal-red)
![VSCode Ready](https://img.shields.io/badge/IDE-VSCode-007ACC?logo=visualstudiocode&logoColor=white)
![SOC Challenge](https://img.shields.io/badge/SOC_Challenge-Day_22-blueviolet?style=flat-square&logo=github)


---

## 🎯 Objective

Analyze a real-world phishing email in `.eml` format using manual investigation techniques. Learn how to review email headers, validate sender identity, check IP/domain reputation, and identify indicators of compromise (IOCs).

---

## 🧪 Tools Used

- [EML Analyzer](https://eml-analyzer.herokuapp.com/#/)
- [MX Toolbox – Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [VirusTotal](https://www.virustotal.com/)
- [AbuseIPDB](https://abuseipdb.com/)
- [urlscan.io](https://urlscan.io/)
- VSCode (for .eml preview and extraction)

---

## 🔍 Investigation Summary

| Field                        | Value                                                |
|-----------------------------|------------------------------------------------------|
| **Sender Email**            | `banco.bradesco@atendimento.com.br`                 |
| **Sending Domain**          | `atendimento.com.br`                                |
| **Sender IP Address**       | `137.184.34.4`                                       |
| **SPF Result**              | `Temperror` – DNS timeout on SPF lookup             |
| **Blacklisted IP?**         | Likely **Yes** – flagged by multiple tools          |
| **Suspicious URL**          | `https://blog1seguimentmydomaine2bra.me/`           |

---

## 📸 Screenshots

All evidence images are located in the `/images` folder:

| Screenshot | Description |
|------------|-------------|
| `1_header_details.png` | Email header showing From, Return-Path, and sender IP |
| `2_ip_reputation.png`  | IP reputation check on VirusTotal or AbuseIPDB        |
| `3_suspicious_link.png`| Malicious link result from urlscan or VirusTotal      |
| `4_email_body_preview.png` | HTML body showing branding/spoofed urgency        |

---

## ✅ Key Takeaways

- Email headers can be manipulated to spoof legitimate senders
- SPF/DMARC failures are strong indicators of phishing
- Urgency and reward-based language are common phishing tactics
- Domain and IP reputation checks are essential for verifying authenticity

---

## 📂 Folder Structure

```
Day22_Phishing_Analysis/
├── BRADESCO LIVELO.eml
├── report.md
├── README.md
└── images/
├── 1_header_details.png
├── 2_ip_reputation.png
├── 3_suspicious_link.png
└── 4_email_body_preview.png
```