<link rel="stylesheet" href="./assets/style.css">

# 🛡️ SOC Challenge: Day #22 – Phishing Email Analysis

Welcome to my phishing email analysis lab for **Day #22** of the SOC Challenge.

## 🔍 Investigation Highlights

- **Sender:** banco.bradesco@atendimento.com.br
- **Domain:** atendimento.com.br
- **IP Address:** 137.184.34.4
- **SPF Result:** Temperror
- **Suspicious URL:** [blog1seguimentmydomaine2bra.me](https://blog1seguimentmydomaine2bra.me)

## 📸 Screenshots

| Evidence | Description |
|---------|-------------|
| ![](./images/1_header_details.png) | Header showing From, Return-Path, IP |
| ![](./images/2_ip_reputation.png)  | IP reputation scan |
| ![](./images/3_suspicious_link.png)| Phishing URL scan |
| ![](./images/4_email_body_preview.png) | HTML email content spoofing |

## 🔧 Tools Used

- [EML Analyzer](https://eml-analyzer.herokuapp.com/#/)
- [VirusTotal](https://www.virustotal.com/)
- [AbuseIPDB](https://abuseipdb.com/)
- [urlscan.io](https://urlscan.io/)
- MXToolbox (Email Header Analyzer)

## 📁 Download Report

[📄 View full report (report.md)](./report.md)

---

_This GitHub Pages site was built for educational and portfolio use as part of my cybersecurity journey._  
🎓 **@BecomingCyber**

[![GitHub](https://img.shields.io/badge/github-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BecomingCyber/phishing-lab-day22.git) [![LinkedIn](https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mozella-mccoy-flowers/)