
# 🛡️ OWASP ZAP – Web Application Vulnerability Scanning

<p align="center">
  <img src="https://img.shields.io/badge/Tool-OWASP%20ZAP-blue?style=for-the-badge&logo=owasp" />
  <img src="https://img.shields.io/badge/Version-2.17.0-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Windows%2011-blue?style=for-the-badge&logo=windows" />
  <img src="https://img.shields.io/badge/Project-Web%20Security-red?style=for-the-badge" />
</p>

## 📌 About The Project

This project demonstrates practical **Web Application Security Testing using OWASP ZAP (Zed Attack Proxy)**.

OWASP ZAP is a free and open-source security testing tool used to identify vulnerabilities and security weaknesses in web applications.

In this project, I performed an automated vulnerability scan on a deliberately vulnerable practice website, analyzed the detected security alerts, and generated a security assessment report.

## 🎯 Objectives

- Understand web application security testing.
- Install and configure OWASP ZAP.
- Perform automated vulnerability scanning.
- Identify common web application vulnerabilities.
- Analyze security alerts and risk levels.
- Understand vulnerability remediation techniques.
- Generate a professional security assessment report.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| OWASP ZAP 2.17.0 | Vulnerability scanning |
| Java (JDK) | Runtime environment |
| Google Chrome | Accessing the target website |
| Windows 11 | Operating system |
| Demo Testfire | Vulnerable practice website |

## 🌐 Target Website

**Target:** [http://demo.testfire.net](http://demo.testfire.net)

A deliberately vulnerable practice website used for learning and authorized security testing.

## ⚙️ Methodology / Workflow

1. **Installation:** Downloaded and installed OWASP ZAP and Java.
2. **Configuration:** Opened ZAP and configured the target website.
3. **Spider Scanning:** Used Traditional Spider and AJAX Spider to discover website pages.
4. **Active Scanning:** Tested discovered pages for potential security vulnerabilities.
5. **Passive Scanning:** Analyzed HTTP requests and responses for security weaknesses.
6. **Alert Analysis:** Reviewed detected vulnerabilities and their risk levels.
7. **Report Generation:** Generated and exported the security assessment report in PDF format.

## 📊 Vulnerability Scan Results

The automated scan identified **11 security alerts**.

| Severity | Alerts | Risk |
|---|---:|---|
| 🔴 High | 1 | Critical attention required |
| 🟠 Medium | 4 | Should be fixed |
| 🟡 Low | 4 | Security improvement recommended |
| 🔵 Informational | 2 | Informational findings |
| **Total** | **11** | |

## 📄 Project Documentation

The repository includes a step-by-step practical guide covering:

- OWASP ZAP installation and setup.
- Java installation and configuration.
- Target website configuration.
- Automated vulnerability scanning.
- Security alert analysis.
- PDF report generation.

## 👩‍💻 Author

**Nehal Sarode**

Cyber Security & Forensics Student

**Interests:** Web Application Security | Vulnerability Assessment | Penetration Testing

---


