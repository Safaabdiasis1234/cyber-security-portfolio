#  Web Application Penetration Test – Maisie Platform  
### University of Roehampton – Cyber Security  
### Performed by: Safa Abiasis Bashir Yusuf  
### Date: 01.04.2025  

This folder contains a full penetration test report for the **Maisie web application (172.16.252.239)**.  
The assessment was completed as part of my Cyber Security course at the University of Roehampton.

📄 **Full Report:** *Penetration_Test_Report_Safa.pdf*

---

## 📝 Overview

This project simulates a real-world client penetration test.  
A manual **black-box** web application assessment was performed using ethical hacking methodologies and aligned with the **OWASP Top 10**.

The web application was developed using **PHP** and **MySQL**, hosted in the Cyber Lab environment (DB117).  
Testing involved identifying vulnerabilities without backend access, admin rights, or automated tools.

---

## 🎯 Objectives

- Identify security weaknesses in the Maisie application  
- Demonstrate realistic attack scenarios  
- Document findings using CVSS 3.1 scoring  
- Provide remediation advice to developers  
- Improve overall security posture before deployment

---

## 🧪 Methodology

- **Black-box manual testing**  
- SQL Injection payload crafting  
- XSS injection via SVG payload  
- Brute forcing using a custom script  
- Cookie analysis and session hijacking  
- Header inspection & HTTP security review  
- OWASP-aligned vulnerability assessment

---

## ⚠️ Key Vulnerabilities Found

### 🔴 Critical Severity
- **SQL Injection** – Extracted user data including admin credentials  
- **Cross-Site Scripting (XSS)** – Executed malicious JS via SVG payload  

### 🟠 High Severity
- **Brute-force login attack**  
- **HTTP Weak Protocol** – No HTTPS  
- **Cookie Poisoning / Session Hijacking**  
- **Unlimited Login Attempts**  

### 🟡 Medium Severity
- Weak password policy  
- No 2FA  
- Server error leakage  
- No ability for users to change credentials  

### 🔵 Info Severity
- Missing Terms & Conditions  

---

## 🔧 Skills Demonstrated

- Manual penetration testing  
- SQLi exploitation  
- XSS payload design  
- Session hijacking  
- Security scripting  
- Risk assessment (CVSS 3.1)  
- Technical reporting  

---
