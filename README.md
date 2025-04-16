# VAPT - Infrastructural Penetration Testing on Public IPs

> **Project type:** Security Assessment Report    
> **Batch Number:** G10 CS 
> **Course Name:** CyberSecurity-and-Ethical-Hacking
> **Mentor:** Nishchay Gaba 
> **Organisation:** SURE-Trust

This repository contains the final documentation and details of the Vulnerability Assessment and Penetration Testing (VAPT) project conducted as part of my 6-month Cybersecurity & Ethical Hacking Internship under the mentorship of **Nishchay Gaba (OSCP Certified)**.

---

## Project Overview

**Title:** VAPT – Infrastructural Penetration Testing on Public IPs  
**Duration:** January 2025 – February 2025   
**Role:** VAPT Analyst (Intern)

The objective of this project was to identify vulnerabilities across a range of externally exposed infrastructure components (public IPs) using standard VAPT methodologies and tools. The approach simulated how an attacker would discover, analyze, and potentially exploit vulnerable services.

---

## 🎯 Scope of Work

- **Target Assets:** 31 Public IPs
- **Diversity:** Each IP represented a different infrastructure — servers, services, or domain-specific applications.
- **Project Focus:** Infrastructure-level security assessment with real-time vulnerability analysis and reporting.

---

## 🔧 Tools & Technologies Used

The following tools and platforms were used extensively throughout the assessment:

- **Network Scanning:** `Nmap`, `Shodan`
- **Vulnerability Scanning:** `Nessus`, `Nikto`
- **Web Security Testing:** `Burp Suite`, `SQLMap`
- **Service Enumeration:** `Netcat`, `CrackMapExec`, `Hydra`
- **Exploitation:** `Metasploit`
- **Packet Analysis:** `Wireshark`
- **Operating Environment:** `Kali Linux`

---

## 🔄 Methodology Followed

1. **Reconnaissance:** Identifying live hosts and services via public IPs.
2. **Scanning & Enumeration:** Using automated and manual tools to fingerprint services and gather version info.
3. **Vulnerability Assessment:** Detecting known vulnerabilities using CVE databases and scanner tools.
4. **Risk Evaluation:** Categorizing each finding based on CVSS scoring (Critical, High, Medium, Low).
5. **Reporting:** Documenting all findings in a professional format with mitigation strategies.

> While exploitation and post-exploitation were not the focus, basic exploit checks were conducted on a few targets for proof of concept.

---

## Project Outcomes

- **Vulnerabilities Identified:** Distinct vulnerabilities across the 31 IPs.
- **Severity Breakdown:**
  - 🔴 Critical
  - 🟠 High
  - 🟡 Medium
  - 🟢 Low

Each finding was mapped to its corresponding CVSS score and included:
- Description
- Affected IP
- Affected port
- CVSS Score
- CVSS Vector
- Technical Impact
- Mitigations
- Proof of Concept (POC)
- References

---

## 📁 Report Details

- **Format:** `.docx` (Microsoft Word)
- **Contents:**
  - Executive Summary
  - Methodology
  - Vulnerability Breakdown (with CVSS scores)
  - Technical Findings
  - Mitigation & Recommendations
  - Appendix (Screenshots, References)

---

## ⚠️ Challenges Faced

Some key challenges during the assessment process included:

- Limited or no access to service-side internals — had to rely purely on external data (black-box testing).
- Some IPs hosted multiple services, requiring multi-angle testing approaches.
- Identifying valid vulnerabilities while filtering false positives from automated tools.
- Crafting concise and impactful reports suitable for professional review.

---

## Acknowledgments

Special thanks to:
- **Nishchay Gaba** – for mentorship and expert guidance throughout the project.
- My fellow trainees and the training organization for enabling this hands-on experience.

---

## Note

This was an individual project conducted as part of a cybersecurity internship. No custom tools or scripts were developed, but detailed personal notes and testing documentation were created for reference.

---

## Timeline

- **Training Period:** Sept 2024 – Dec 2024  
- **Real-Time Project:** Jan 2025 – Feb 2025  
- **Final Report Submission:** Feb 2025

---

> 🔐 This repository does not include sensitive IP addresses or client-specific data due to privacy and NDA restrictions. The report and details shared are anonymized and generalized for educational and documentation purposes.

