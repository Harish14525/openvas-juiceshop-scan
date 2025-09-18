# OpenVAS Vulnerability Scan – OWASP Juice Shop

## Overview
This repository documents a vulnerability scanning project using **OpenVAS (Greenbone Vulnerability Manager)** on the deliberately insecure web application **OWASP Juice Shop**.  
The goal of this task was to configure OpenVAS, perform a full system scan, identify vulnerabilities (CVEs), and prepare a professional risk assessment.

---

## Repository Structure
- **screenshots/** → Setup, scan configuration, and results screenshots.  
- **report/** → Exported PDF vulnerability scan report.  
- **summary.md** → Risk assessment summary of identified CVEs and recommendations.  
- **setup.md** → Step-by-step guide to install, configure, and run OpenVAS with Juice Shop.  
- **README.md** → Main documentation (this file).  

---

## 🛠️ Tools & Environment
- **Operating System:** Kali Linux  
- **Scanner:** OpenVAS (Greenbone Vulnerability Manager)  
- **Target Application:** OWASP Juice Shop (Dockerized)  
- **Ports:** 9390 / 9392 (for Greenbone services), 3000 (Juice Shop)  

---

## Project Workflow
1. Installed and configured OpenVAS on Kali Linux.  
2. Deployed Juice Shop using Docker.  
3. Added Juice Shop as a scan target in Greenbone Security Assistant.  
4. Ran a **Full and Fast Scan** to detect vulnerabilities.  
5. Exported the scan report in PDF format.  
6. Created a risk assessment summary based on discovered CVEs.  

---

## Deliverables
- **PDF Scan Report** → `Report.PDF`  
- **Screenshots** → Setup and results in `Screenshots/`  
- **Risk Assessment Summary** → `Report summary.md`  

---

## Disclaimer
This project was conducted in a controlled lab environment for **educational and research purposes only**.  
Do **not** use these techniques against systems without explicit authorization.  

---

## License
This repository is released under the **MIT License**.  
