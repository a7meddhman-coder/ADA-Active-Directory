# 🛡️ ADA Active Directory Security Assessment - Final Project

A comprehensive security assessment and penetration testing report conducted against the `ada.htb` Active Directory domain environment (Target IP: `192.168.1.2`)[cite: 1].

---

## 📋 Executive Summary
This report documents the end-to-end security evaluation of the target AD infrastructure[cite: 1]. The assessment followed a structured methodology, starting from initial open-source intelligence (OSINT) and network reconnaissance, service enumeration, protocol-level analysis, to targeted authentication testing and vulnerability identification[cite: 1].

---

## 🛠️ Tools & Utilities Used
The following toolset and security utilities were utilized throughout the engagement:
* **Reconnaissance & Enumeration:** `Nmap`, `NetExec`, `Kerbrute`, `dig (AXFR)`
* **Vulnerability Analysis & Exploitation:** `Impacket` (GetNPUsers, GetUserSPNs), `ffuf`
* **Target OS:** Windows Server 2019 (Domain Controller - `DC.ada.htb`)[cite: 1]

---

## 📌 Key Assessment Phases
1. **Network Discovery & Port Scanning:** Identifying active services across ports such as LDAP (389/636), SMB (445), Kerberos (88), DNS (53), and HTTP/HTTPS[cite: 1].
2. **Domain Enumeration & User Profiling:** Utilizing tools like `kerbrute` and `netexec` for valid user identification and password policy analysis[cite: 1].
3. **Authentication & Protocol Testing:** Analyzing SMB signing requirements, LDAP bind configurations, and checking for potential AS-REP Roasting or Kerberoasting vectors[cite: 1].
4. **Web Application Assessment:** Performing directory brute-forcing (`ffuf`) against the target's IIS web service (`Ada Security`) to uncover hidden endpoints and resources[cite: 1].

---

## 📄 Final Report
You can access the full detailed PDF report here in the repository: 
[`Final Project (Ahmed Dahman Saleh) (1).pdf`](./Final Project%20(Ahmed Dahman Saleh)%20(1).pdf)

---
*Prepared by **Ahmed Dahman Saleh** — May 2026*[cite: 1]
