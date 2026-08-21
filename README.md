networkwalks-B082-🔐 WEEK 2 | CYBERSECURITY PROJECTS
# FOOTPRINTING &amp; RECONNAISSANCE ATTACKS  WITH MULTIPLE KALI TOOLS

<p align="center">
  <img src="https://www.kali.org/images/kali-logo.svg" alt="Kali Linux Logo" width="120"/>
</p>

<p align="center">

<p align="center">
![Cybersecurity](https://img.shields.io/badge/Focus-Cybersecurity-blue?style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Platform-Kali%20Linux-success?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Week%202-orange?style=for-the-badge)

</p>
<p align="center">
## 📌 Project Overview

This repository contains my **Week 2 Cybersecurity Projects**, focusing on two important areas of cybersecurity assessment:

* 🌐 **W2-PM1: Footprinting & Reconnaissance with Multiple Kali Linux Tools**
* 🛰️ **W2-PM5: Zenmap-Based Network Scanning**
* 📄 **W2-PM-FINAL: Comprehensive Final Project Report**

The purpose of these projects is to develop practical skills in **information gathering, reconnaissance, network discovery, port scanning, service identification, and cybersecurity reporting**.

The project demonstrates how cybersecurity professionals gather and analyze information about authorized targets before conducting further security assessments. The findings collected throughout the project were documented and analyzed as part of the final report.

---

# 📑 Repository Contents

* 🎯 **Project Overview and Objectives**
* 🔧 **Tools and Technologies Used**
* 🌐 **Footprinting & Reconnaissance**
* 🛰️ **Zenmap-Based Network Scanning**
* 📊 **Findings and Analysis**
* ⚠️ **Challenges and Difficulties Faced**
* 💡 **Key Lessons Learned**
* 📝 **Conclusion and Recommendations**
* 🛠️ **Technologies & Tools**

---

# 🎯 Project Overview and Objectives

The main objective of this project is to gain practical experience with cybersecurity reconnaissance and network scanning tools within an authorized educational environment.

Through this project, I explored how different tools can be used to gather information about a target's publicly accessible infrastructure and analyze network services.

### Objectives

* Understand the importance of footprinting and reconnaissance.
* Gather publicly available information about an authorized target.
* Identify domain and DNS information.
* Fingerprint web technologies.
* Analyze HTTP response headers.
* Detect potential Web Application Firewall protection.
* Perform DNS enumeration.
* Conduct network scanning using Zenmap.
* Identify hosts, ports, and available services.
* Analyze and interpret scan results.
* Document findings in a structured cybersecurity report.

---

# 🔧 Tools and Technologies Used

## 🐉 Kali Linux

<p align="center">
  <img src="https://www.kali.org/images/kali-logo.svg" alt="Kali Linux" width="100"/>
</p>

Kali Linux was used as the primary cybersecurity environment for performing reconnaissance and security assessment activities.

---

## 🔍 WHOIS

**Purpose:** Domain registration and ownership information lookup.

WHOIS was used to examine publicly available domain registration information and other related domain details.

---

## 🌐 WhatWeb

**Purpose:** Web technology fingerprinting.

WhatWeb was used to identify technologies, frameworks, servers, and other information exposed by a website.

---

## 📡 NSLookup

**Purpose:** DNS and domain resolution.

NSLookup was used to query DNS information and resolve domain names to associated IP addresses.

---

## 📥 cURL

**Purpose:** HTTP response and header analysis.

cURL was used to inspect HTTP response headers and identify information exposed by the web server.

---

## 🛡️ WAFW00F

**Purpose:** Web Application Firewall detection.

WAFW00F was used to determine whether the target website appeared to be protected by a Web Application Firewall.

---

## 🧭 DNSRecon

**Purpose:** DNS enumeration.

DNSRecon was used to collect and analyze available DNS records associated with the authorized target.

---

## 🛰️ Zenmap / Nmap

<p align="center">
  <img src="https://nmap.org/images/nmap-logo-256x256.png" alt="Nmap Logo" width="100"/>
</p>

Zenmap, the graphical interface for Nmap, was used to perform and analyze network scanning activities in an authorized environment.

---

# 🌐 W2-PM1: Footprinting & Reconnaissance

## 📖 Overview

Footprinting and reconnaissance are important phases of a cybersecurity assessment. Before conducting further testing, cybersecurity professionals need to understand the target environment.

This module focused on gathering and analyzing publicly available information about an authorized target using multiple Kali Linux tools.

The designated lab target was:

```text
networkwalks.com
```

The tools used included:

<p align="center">

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-Security-blue?style=for-the-badge\&logo=kalilinux)
![WHOIS](https://img.shields.io/badge/WHOIS-Domain%20Lookup-success?style=for-the-badge)
![WhatWeb](https://img.shields.io/badge/WhatWeb-Web%20Fingerprinting-orange?style=for-the-badge)
![NSLookup](https://img.shields.io/badge/NSLookup-DNS%20Lookup-blueviolet?style=for-the-badge)
![cURL](https://img.shields.io/badge/cURL-HTTP%20Analysis-brightgreen?style=for-the-badge)
![WAFW00F](https://img.shields.io/badge/WAFW00F-WAF%20Detection-red?style=for-the-badge)
![DNSRecon](https://img.shields.io/badge/DNSRecon-DNS%20Enumeration-yellow?style=for-the-badge)

</p>
<p align="center">

Each tool provided a different piece of information that contributed to building a broader profile of the target's publicly exposed infrastructure.

---

## 🔎 Reconnaissance Activities

| Tool              | Primary Function                                  |
| ----------------- | ------------------------------------------------- |
| 🐉 **Kali Linux** | Cybersecurity and penetration testing environment |
| 🔍 **WHOIS**      | Domain registration lookup                        |
| 🌐 **WhatWeb**    | Web technology fingerprinting                     |
| 📡 **NSLookup**   | DNS lookup and domain resolution                  |
| 📥 **cURL**       | HTTP header inspection                            |
| 🛡️ **WAFW00F**   | Web Application Firewall detection                |
| 🧭 **DNSRecon**   | DNS record enumeration                            |

### Key Information Gathered

The reconnaissance process focused on identifying publicly accessible information such as:

* Domain registration details
* Domain resolution information
* IP address information
* DNS records
* Web server information
* HTTP response headers
* Web technologies
* Hosting and infrastructure indicators
* Potential Web Application Firewall protection

The collected information provides a clearer understanding of the target's publicly exposed infrastructure and supports the planning of later stages of an **authorized security assessment**.

---

# 🛰️ W2-PM5: Zenmap-Based Network Scanning

## 📖 Overview

<p align="center">
  <img src="https://nmap.org/images/zenmap.png" alt="Zenmap Logo" width="200"/>
</p>

This module focuses on using **Zenmap**, the graphical user interface for Nmap, to perform and analyze network scanning activities in an authorized environment.

Zenmap provides a visual interface for conducting and interpreting Nmap scans. The project explored how network scanning can help identify active hosts, open ports, available services, and other information relevant to understanding network infrastructure.

---

## 🔍 Key Areas Explored

* 🔎 **Host Discovery**
  Identifying active devices within an authorized network environment.

* 🔌 **Port Scanning**
  Identifying open, closed, or filtered ports.

* 🖥️ **Service Identification**
  Examining services associated with discovered ports.

* 📊 **Scan Result Analysis**
  Reviewing and interpreting scan results generated by Zenmap.

* 🛡️ **Network Security Assessment**
  Understanding how exposed services and network configurations may contribute to the overall security posture.

---

# 📊 Findings and Analysis

The project demonstrated that different reconnaissance and scanning tools provide different perspectives on a target environment.

Reconnaissance tools can reveal information related to:

* Domain infrastructure
* DNS configuration
* Public IP addresses
* Web technologies
* HTTP server information
* Security controls

Network scanning tools can provide additional information about:

* Active hosts
* Open ports
* Available services
* Network accessibility
* Potentially exposed services

By combining reconnaissance findings with authorized network scanning results, it becomes easier to develop a broader understanding of the target environment.

> **Note:** Specific findings and screenshots can be added to the appropriate project folders as evidence of the practical exercises.

---

# ⚠️ Challenges and Difficulties Faced

During the completion of this project, several challenges were encountered.

### 🔹 Understanding Tool Output

Some tools generated large amounts of information. Learning how to identify relevant data and distinguish important findings from general output was an important part of the project.

### 🔹 DNS Interpretation

Understanding different DNS record types and their relevance required additional research and practice.

### 🔹 Web Technology Identification

Interpreting technology fingerprinting results required an understanding of web servers, frameworks, and other technologies commonly used in web environments.

### 🔹 Scan Result Analysis

Network scanning results required careful interpretation to understand the difference between open, closed, and filtered ports.

### 🔹 Connecting Findings

Another challenge was understanding how information collected from different tools could be combined to build a more complete profile of the target environment.

### 🔹 Documentation

Recording commands, outputs, observations, screenshots, and findings in an organized manner was essential for preparing the final report.

---

# 💡 Key Lessons Learned

This project provided several important cybersecurity lessons:

* ✅ Reconnaissance is a critical foundation for security assessments.
* ✅ Different tools provide different types of intelligence.
* ✅ Publicly accessible information can reveal details about an organization's infrastructure.
* ✅ DNS records can provide valuable information about a domain and its services.
* ✅ HTTP headers may expose information about web servers and technologies.
* ✅ Web technology fingerprinting helps improve understanding of a target environment.
* ✅ Web Application Firewalls can provide an additional layer of protection.
* ✅ Network scanning helps identify hosts, ports, and available services.
* ✅ Proper interpretation of scan results is as important as running the scan itself.
* ✅ Documentation and reporting are essential cybersecurity skills.
* ✅ Security testing must always be conducted ethically and with proper authorization.

---

# 📄 W2-PM-FINAL: Detailed Project Report

The final project report combines the selected Week 2 cybersecurity modules into a comprehensive documentation of the practical exercises completed.

The report includes:

* 🎯 Project background and objectives
* 🔧 Tools and technologies used
* 🌐 Footprinting and reconnaissance methodology
* 🛰️ Zenmap-based network scanning activities
* 📊 Findings and analysis
* ⚠️ Challenges encountered
* 💡 Key lessons learned
* 📝 Conclusion and recommendations

The purpose of the final report is to demonstrate both the practical and theoretical knowledge gained throughout the project.

---

# 📝 Conclusion and Recommendations

## Conclusion

This Week 2 cybersecurity project provided practical exposure to important phases of a security assessment, including **footprinting, reconnaissance, and network scanning**.

Using multiple tools in Kali Linux and Zenmap, the project demonstrated how cybersecurity professionals gather and analyze information to better understand an authorized target environment.

The project also highlighted the importance of careful analysis, proper documentation, ethical responsibility, and authorization when conducting cybersecurity activities.

Overall, the experience strengthened my understanding of **cybersecurity reconnaissance, web technology fingerprinting, DNS enumeration, network discovery, port scanning, service identification, and security reporting**.

## Recommendations

Based on the lessons learned from this project, the following recommendations are made:

1. 🔐 Always obtain proper authorization before conducting security testing.
2. 📋 Clearly define the scope of every cybersecurity assessment.
3. 📝 Document commands, outputs, findings, and observations throughout the project.
4. 🔄 Use multiple tools to validate and compare findings.
5. 📚 Continue practicing in legal lab environments to strengthen technical skills.
6. 🛡️ Apply appropriate security controls to reduce unnecessary exposure of infrastructure information.
7. 📊 Regularly review network services and publicly exposed systems.
8. 🎓 Continue developing practical skills in vulnerability assessment, network security, and ethical penetration testing.

---

# 🛠️ Technologies & Tools

<p align="center">

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-Cybersecurity-blue?style=for-the-badge\&logo=kalilinux)
![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanning-success?style=for-the-badge)
![Zenmap](https://img.shields.io/badge/Zenmap-GUI%20Network%20Scanner-orange?style=for-the-badge)
![WHOIS](https://img.shields.io/badge/WHOIS-Domain%20Information-blueviolet?style=for-the-badge)
![WhatWeb](https://img.shields.io/badge/WhatWeb-Web%20Fingerprinting-red?style=for-the-badge)
![DNSRecon](https://img.shields.io/badge/DNSRecon-DNS%20Enumeration-yellow?style=for-the-badge)
![WAFW00F](https://img.shields.io/badge/WAFW00F-WAF%20Detection-critical?style=for-the-badge)
![cURL](https://img.shields.io/badge/cURL-HTTP%20Analysis-brightgreen?style=for-the-badge)

</p>

---

# 📂 Suggested Repository Structure

```text
WEEK-2-CYBERSECURITY-PROJECTS/
│
├── README.md
│
├── W2-PM1-Footprinting-Reconnaissance/
│   ├── README.md
│   ├── screenshots/
│   └── findings/
│
├── W2-PM5-Zenmap-Network-Scanning/
│   ├── README.md
│   ├── screenshots/
│   └── scan-results/
│
└── W2-PM-FINAL/
    ├── Final-Project-Report.pdf
    └── README.md
```
👨‍💻 Author

<p align="center">

Andrew Maneply Tokpah

Data Analyts | Emerging Cybersecurity Professional

🔐 Learning, practicing, documenting, and growing in cybersecurity.

</p>
---

### ⚠️ Disclaimer

All footprinting, reconnaissance, and network scanning activities documented in this repository were conducted strictly for **educational purposes** and within an **authorized environment or designated project scope**. No unauthorized systems, networks, or services were intentionally targeted.

The reconnaissance process helps provide a clearer understanding of a target's **publicly exposed infrastructure**, including domain information, DNS records, web technologies, HTTP response headers, and potential security controls. These findings serve as a foundation for planning and conducting subsequent stages of an **authorized security assessment**.

All findings, observations, and tool outputs were carefully documented and analyzed for educational purposes and inclusion in the **final project report**.

---

<p align="center">
  <b>🔐 Learning • Practicing • Documenting • Growing in Cybersecurity 🛡️</b>
</p>
