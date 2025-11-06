# FUTURE_CS_01
# Rohit Pawar's Cybersecurity Portfolio

This repository documents the tasks, labs, and projects I complete, demonstrating my skills in vulnerability assessment, penetration testing, and digital forensics.

---

## Project 1: Vulnerability Assessment of OWASP Juice Shop

* **Date:** November 6, 2025
* **Objective:** To identify and document common web vulnerabilities by setting up a test environment and performing a manual and automated assessment.

### Summary of Tasks

1.  **Environment Setup:** Deployed the OWASP Juice Shop application in a secure, local environment using Docker on Kali Linux.
2.  **Automated Scanning:** Used `Nikto` for initial server-side scanning and `OWASP ZAP` for automated spidering and vulnerability discovery.
3.  **Manual Penetration Testing:** Used `Burp Suite` to manually proxy traffic and identify vulnerabilities that automated scanners missed.

### Key Findings Documented

* **Critical:** SQL Injection (Authentication Bypass)
* **High:** Cross-Site Request Forgery (CSRF)
* **High:** Sensitive Data Exposure (via GET request)
* **Medium:** Reflected Cross-Site Scripting (XSS)

### Final Deliverables

You can view the complete findings and remediation steps in the final report.

* **View the Full Report:** [**Security_Report.pdf**](VA-OWASP-JuICE-Shop/Security_Report.pdf)
* **Scanner Logs:**
    * [Nikto Scan Report](VA-OWASP-Juice-Shop/Nikto_Report.html)
    * [OWASP ZAP Scan Report](VA-OWASP-Juice-Shop/ZAP_Scan_Report.html)
