# 📧 Day #22 – Phishing Analysis Report

## 🔍 Analysis Summary

**1. Full Sender Email Address:**  
`banco.bradesco@atendimento.com.br`

**2. Sending Domain:**  
`atendimento.com.br`

**3. Sender IP Address:**  
`137.184.34.4`

**4. Is Sender IP Blacklisted?:**  
Check required via [AbuseIPDB](https://abuseipdb.com/check/137.184.34.4) or [VirusTotal](https://www.virustotal.com/gui/ip-address/137.184.34.4)  
_(📝 The domain was flagged in DNSBL lookups by SpamAssassin and may indicate abuse or spam)_  
→ _**Likely Yes**_

**5. SPF Authentication Result:**  
`Temperror`  
_(This means the sender’s domain failed to respond to SPF DNS checks — a red flag)_

**6. Suspicious URL Found in Email Body:**  
`https://blog1seguimentmydomaine2bra.me/`  
_(Appears in CTA buttons like “Resgatar Agora” and anchor tags — a phishing site)_

---

## 📸 images

1. **Email Header (From, Return-Path, IP)**  
   ![Header Info](./images/1_header_details.png)

2. **IP Reputation Lookup**  
   ![IP Reputation](./images/2_ip_reputation.png)

3. **Suspicious URL Scan**  
   ![Suspicious Link](./images/3_suspicious_link.png)

4. **Email HTML Preview (Urgency, Branding, Spoof)**  
   ![Email Body](./images/4_email_body_preview.png)

---

## ✅ Learning Outcome

By completing this lab, I was able to:
- Extract and review email headers for spoofing and IP trace
- Detect suspicious sending domains and malformed headers
- Identify spoofed branding and urgency in email body
- Use online tools to validate IP/domain reputation and catch phishing attempts
