# **Tools for Identifying Malicious Activity**

This project demonstrates the use of multiple security analysis tools to identify, investigate, and validate potentially malicious activity. The lab focuses on monitoring network traffic, analyzing suspicious files in a sandboxed environment, and validating domains and IP addresses using threat-intelligence platforms commonly used in SOC environments.

**Skills Highlighted:** Network Traffic Analysis · Wireshark · Tcpdump · Malware Analysis · Threat Intelligence · SOC Tools

---

## **Table of Contents**

* Overview  
* Learning Outcomes  
* Exam Objectives  
* Lab Environment  
* Project Walkthrough  
* Tools Used  
* Why This Project Matters  
* Summary

---

## **Overview**

Security analysts rely on a combination of network monitoring, malware analysis, and threat-intelligence validation to detect and investigate malicious activity. In this lab, I applied these techniques using industry-standard tools to analyze network traffic, evaluate suspicious files, and validate indicators of compromise (IOCs).

This project reflects real-world workflows used in **Security Operations Centers (SOC)** and **incident response** teams.

---

## **🎯 Learning Outcomes**

By completing this module, I demonstrated the ability to:

* Customize the Wireshark application  
* Capture network traffic using Wireshark  
* Capture network traffic using Tcpdump  
* Analyze potentially malicious code in a sandboxed environment  
* Validate domain names using WHOIS  
* Assess IP and domain reputation using AbuseIPDB  
* Verify URLs and files using VirusTotal

---

## **🧪 Exam Objectives Covered**

This project aligns with the **CompTIA CySA+** exam objective:

**1.3 – Given a scenario, use appropriate tools or techniques to determine malicious activity**, including:

* Network-related indicators  
* Host-related indicators  
* Application-related indicators

---

## **🖥️ Lab Environment**

The following systems were used during this lab:

* **ACIDC01** – Windows Server 2022 (Domain Controller)  
* **ACIDM01** – Windows Server 2022 (Domain Member Server)  
* **ACIWIN11** – Windows 11 (Domain Member Workstation)  
* **ACIALMA** – Alma Linux (Standalone Workstation)  
* **ACIKALI** – Kali Linux (Standalone Workstation)

---

## **🚀 Project Walkthrough**

### **Exercise 1 – Monitoring Network Activity**

In this exercise, I monitored and analyzed network traffic to identify suspicious behavior and indicators of malicious activity.

#### **Wireshark Network Analysis**

* Customized Wireshark settings to improve packet visibility  
* Captured live network traffic  
* Applied display filters to analyze protocols and traffic patterns

01-wireshark-capture.png

---

#### **Tcpdump Network Capture**

* Captured network traffic directly from the command line  
* Reviewed packet data for anomalies and suspicious connections

Example command:

`tcpdump -i eth0`

(02-tcpdump-capture.png)

---

### **Exercise 2 – Using a Sandbox for Analyzing Malicious Files**

In this exercise, I analyzed potentially malicious files in a sandboxed environment to safely observe behavior and identify indicators of compromise.

* Uploaded suspicious files for analysis  
* Reviewed execution behavior and sandbox reports

*(03-sandbox-analysis.png)*

---

### **Exercise 3 – Validating Domain Names and IP Addresses**

I validated suspicious domains and IP addresses using multiple threat-intelligence platforms.

#### **WHOIS Validation**

* Retrieved domain registration details  
* Analyzed ownership and registration history

*(04-whois-lookup.png)*

---

#### **AbuseIPDB Validation**

* Reviewed IP reputation and abuse confidence scores  
* Analyzed reported malicious activity

*(05-abuseipdb-check.png)*

---

#### **VirusTotal Verification**

* Verified URLs and file hashes  
* Reviewed detection results from multiple antivirus engines

*(06-virustotal-analysis.png)*

---

## **🛠️ Tools Used**

* Wireshark  
* Tcpdump  
* Sandbox analysis platform  
* WHOIS  
* AbuseIPDB  
* VirusTotal

---

## **📌 Why This Project Matters**

Attackers often leave detectable traces in network traffic, malicious files, and infrastructure such as domains and IP addresses. This project demonstrates how multiple security tools are used together to investigate threats, validate indicators, and support informed security decisions in SOC environments.

---

## **Summary**

In this project, I completed a series of hands-on exercises focused on identifying and analyzing potentially malicious activity using common SOC tools and techniques.

The completed exercises included:

* **Exercise 1 – Monitoring Network Activity**  
* **Exercise 2 – Using a Sandbox for Analyzing Malicious Files**  
* **Exercise 3 – Validating Domain Names and IP Addresses**

As a result, I demonstrated the ability to:

* Capture and analyze network traffic using Wireshark and Tcpdump  
* Analyze suspicious files safely in a sandboxed environment  
* Validate domains and IP addresses using threat-intelligence platforms  
* Apply SOC workflows for identifying malicious activity
