# FUTURE_CS_01 - Web Application Security Testing (Internship Task 1)

## 🛡️ About the Project

This repository contains the deliverables and analysis from Task 1 of the Cybersecurity Internship under **Future Interns**.  
The goal of this task was to conduct a thorough web application vulnerability assessment using ethical hacking tools and simulate real-world testing scenarios.

Target Application: **OWASP Juice Shop (Docker-based setup on Kali Linux)**

---

## 🔧 Tools & Technologies Used

- **OWASP ZAP** – Web application vulnerability scanner
- **Nikto** – Web server scanner
- **SQLMap** – Automated SQL injection tool
- **Burp Suite (Community Edition)** – Manual testing & proxy-based exploitation
- **Kali Linux** – Main penetration testing OS (VirtualBox)

---

## 🔍 Vulnerabilities Identified

| S.No | Vulnerability                | OWASP Mapping        | Risk Level |
|------|------------------------------|----------------------|------------|
| 1    | SQL Injection                | A01: Broken Access Control | High       |
| 2    | Cross-Site Scripting (XSS)   | A03: Injection        | Medium     |
| 3    | Broken Authentication        | A07: Identification & Auth Failures | High |
| 4    | Sensitive Data Exposure      | A02: Cryptographic Failures | Medium     |
| 5    | Broken Access Control        | A01: Broken Access Control | High       |

---

## 📁 Project Structure

```bash
FUTURE_CS_01/
├── README.md
├── WebApp_Security_Report.pdf
├── scans/
│   ├── zap_scan.html
│   ├── nikto_scan.txt

