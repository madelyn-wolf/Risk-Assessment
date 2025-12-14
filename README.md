# Open-Source Intelligence & Penetration Testing Project

## Overview
This repository contains a comprehensive **Open-Source Intelligence (OSINT) and Penetration Testing assessment** conducted as part of **IFT 475: Security Analysis** at **Arizona State University**. The project evaluates the security posture of a simulated enterprise environment by combining public-facing intelligence gathering with hands-on penetration testing in a controlled lab setting.

The assessment focuses on identifying organizational, technical, and human-centered security risks and provides actionable recommendations to improve overall security resilience.

---

## Project Scope
The project covers two primary components:

### 1. Open-Source Intelligence (OSINT)
- Company profiling and organizational structure analysis  
- Executive leadership exposure and data broker risk  
- Financial disclosure visibility and search engine indexing risks  
- Social media footprint and reconnaissance opportunities  
- Network footprint analysis using publicly available tools  

### 2. Penetration Testing (Simulated Environment)
- Assessment of three simulated servers within the Apporto Modular Cyberlab  
- Network scanning, enumeration, vulnerability identification, and exploitation validation  
- Tools used include:
  - **Nmap**
  - **Enum4Linux**
  - **Nessus**
  - **Metasploit**
  - **Nikto**

---

## My Role & Contributions
I was responsible for **leading the group, documentation effort, and compiling all team contributions into a single, cohesive report**. My specific responsibilities included:

- Compiling and organizing all team members’ technical findings into the final document  
- Writing the following major sections:
  - **Introduction**
  - **Scope**
  - **Company Profile**
  - **Executive Leadership Analysis**
  - **Financial Exposure Analysis**
  - **Recommendations**
  - **Conclusion**
- Integrating penetration testing findings into the recommendations section
- Writing and formatting **all three annexes**:
  - Annex A – References  
  - Annex B – Acronyms  
  - Annex C – Additional Images, Screenshots, and Tables  
- Ensuring consistency in tone, formatting, and technical clarity across the entire report  

This role required strong technical writing skills, attention to detail, and the ability to translate complex security findings into clear, professional documentation.

---

## Key Findings
- Significant exposure of executive personal data through third-party data broker websites  
- Publicly indexed internal financial documents discoverable through advanced search queries  
- One well-secured Windows Active Directory Domain Controller with strong authentication controls  
- Two severely vulnerable servers running outdated operating systems and end-of-life software  
- Multiple critical vulnerabilities including:
  - Exposed NFS shares
  - Weak cryptographic implementations
  - Unsupported web servers and application frameworks
  - Misconfigured services increasing attack surface  

---

## Recommendations Summary
- Remove executive personal data from third-party data brokers  
- Restrict public access to internal financial and HR documents  
- Implement least-privilege and zero-trust authentication models  
- Upgrade and patch all end-of-life systems immediately  
- Harden exposed services and disable unnecessary ports  
- Enforce strong password policies and multi-factor authentication  

---

## Academic Context
- **Course:** IFT 475 – Security Analysis  
- **Institution:** Arizona State University  
- **Environment:** Apporto Modular Cyberlab  
- **Methodology:** OSINT analysis paired with simulated penetration testing  

---

## Disclaimer
This project was conducted **strictly for educational purposes** in a controlled academic environment. All penetration testing activities were performed on **authorized, simulated systems only**. No real-world systems were targeted.

---

## Author
Madelyn Wolf
- Bachelor's of Information Technology, Focus Area: Security
- Expected Graduation: May 2026, Summa Cum Laude
