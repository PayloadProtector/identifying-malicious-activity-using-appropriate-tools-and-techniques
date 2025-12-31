## **Introduction**

This project demonstrates the use of common network analysis, sandboxing, and threat-intelligence tools to identify and analyze potentially malicious activity. The lab focuses on monitoring network traffic, analyzing suspicious files, and validating domains and IP addresses using industry-standard tools commonly used by SOC analysts.

---

## **Objective**

The objective of this lab is to develop hands-on skills for identifying malicious activity using appropriate tools and techniques. The exercises simulate real-world security analysis tasks performed in security operations and incident response environments.

---

## **Overview**

Security analysts rely on a combination of network monitoring, malware analysis, and threat-intelligence validation to detect and investigate malicious behavior. In this lab, I applied these techniques across Windows and Linux systems to identify suspicious activity and validate indicators of compromise (IOCs).

---

## **Learning Outcomes**

By completing this module, I demonstrated the ability to:

* Customize the Wireshark application

* Capture network traffic using the Wireshark application

* Capture network traff
* Verify URLs and files using the VirusTotal website

---
ic using Tcpdump

* Analyze potentially malicious code

* Validate domain names using WHOIS

* Validate IP addresses and domains using AbuseIPDB

## **Exam Objectives Covered**

This project aligns with the **CompTIA CySA+** exam objective:

**1.3 – Given a scenario, use appropriate tools or techniques to determine malicious activity**, including:

* Network-related indicators

* Host-related indicators

* Application-related indicators

---

## **Lab Environment**

The following systems were used during this lab:

* **ACIDC01** – Windows Server 2022 (Domain Controller)

* **ACIDM01** – Windows Server 2022 (Domain Member Server)

* **ACIWIN11** – Windows 11 (Domain Member Workstation)

* **ACIALMA** – Alma Linux (Standalone Workstation)

* **ACIKALI** – Kali Linux (Standalone Workstation)

---

## **Project Walkthrough**

### **Exercise 1 – Monitoring Network Activity**

In this exercise, I monitored and analyzed network traffic to identify suspicious behavior and potential indicators of malicious activity.

#### **Wireshark Configuration and Traffic Capture**

* Customized Wireshark settings for improved packet visibility

* Captured live network traffic

* Applied display filters to analyze protocols and traffic patterns

*01-wireshark-capture.png*

#### **Tcpdump Network Capture**

* Captured network traffic using Tcpdump

* Reviewed packet output for abnormal or suspicious behavior

Example command:

`tcpdump -i eth0`

*02-tcpdump-capture.png*

---

### **Exercise 2 – Using a Sandbox for Analyzing Malicious Files**

In this exercise, I analyzed potentially malicious files in a sandboxed environment to safely observe behavior without risking system compromise.

* Uploaded suspicious files for analysis

* Reviewed execution behavior and indicators of compromise (IOCs)

*03-sandbox-analysis.png*

---

### **Exercise 3 – Validating Domain Names and IP Addresses**

In this exercise, I validated domains and IP addresses using multiple threat-intelligence platforms.

#### **WHOIS Validation**

* Retrieved domain registration information

* Analyzed ownership, registration dates, and registrar details

*04-whois-lookup.png*

#### **AbuseIPDB Validation**

* Checked IP reputation scores

* Reviewed abuse confidence levels and historical reports

*05-abuseipdb-check.png*

#### **VirusTotal Verification**

* Verified URLs and file hashes

* Reviewed detection results from multiple antivirus engines

*06-virustotal-analysis.png*

---

## **Tools Used**

* Wireshark

* Tcpdump

* Sandbox analysis platform

* WHOIS

* AbuseIPDB

* VirusTotal

---

## **Screenshots**

All screenshots for this project are stored in an `images/` directory and are named chronologically to reflect the workflow of the lab.

---

## **Why This Project Matters**

Attackers often leave detectable traces in network traffic, malicious files, and infrastructure such as domains and IP addresses. This project demonstrates how security analysts use multiple tools together to investigate threats, validate indicators, and make informed security decisions in real-world environments.

---

## **Summary**

In this project, I completed a series of hands-on exercises focused on identifying and analyzing potentially malicious activity using common SOC tools and techniques.

The completed exercises included:

* **Exercise 1 – Monitoring Network Activity**

* **Exercise 2 – Using a Sandbox for Analyzing Malicious Files**

* **Exercise 3 – Validating Domain Names and IP Addresses**

As a result of completing this lab, I demonstrated the ability to:

* Customize the Wireshark application for effective traffic analysis

* Capture and analyze network traffic using Wireshark

* Capture network traffic using Tcpdump

* Analyze potentially malicious code in a sandboxed environment

* Validate domain names using WHOIS

* Assess IP and domain reputation using AbuseIPDB

* Verify URLs and files using VirusTotal

This project reinforces practical SOC workflows involving network monitoring, malware analysis, and threat-intelligence validation across Windows and Linux environments.

---

