# Wazuh SOC Threat Hunting Lab

## Project 1: Windows Log Monitoring & Suspicious Login Detection

### 📌 Project Overview
This project demonstrates a SOC Analyst workflow for monitoring Windows security logs using Wazuh SIEM and investigating suspicious login activity.

### 🛠️ Tools & Technologies
- Wazuh SIEM
- Wazuh Agent
- Windows Security Logs
- Ubuntu Server
- VirtualBox
- Threat Hunting

### 🎯 Objectives
- Monitor Windows security events
- Detect failed login attempts
- Investigate Windows Event ID 4625
- Analyze authentication failure details
- Perform basic SOC-level investigation

### 🔍 Investigation
A Windows Event ID 4625 was identified during threat hunting.

Key observations:
- Rule: Logon Failure – Unknown user or bad password
- Logon Type: 2 (Interactive)
- Authentication failure was confirmed
- The event was reviewed for process and authentication context

### 🧑‍💻 SOC Analyst Conclusion
The investigated event confirmed a failed authentication attempt. Based on the available evidence, there was no confirmed malicious brute-force pattern. The event was treated as a suspicious/failed login requiring monitoring.

### 📄 Project Documentation
Detailed project documentation and investigation evidence are available in:

`Project_1_Wazuh_SOC_Documentation_Ayush_Dubey.pdf`

### 📸 Evidence
The documentation contains screenshots covering:
- Wazuh services
- Wazuh Dashboard
- Windows Agent
- Threat Hunting
- Event ID 4625 investigation
- Event details and process context

### 🚀 Skills Demonstrated
- SIEM Monitoring
- Threat Hunting
- Windows Log Analysis
- Authentication Event Investigation
- Incident Analysis
- SOC Analyst L1 Workflow
