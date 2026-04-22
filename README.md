# Threat Detection & Attack Mapping (MITRE ATT&CK & Cyber Kill Chain)

## 📌 Overview
This project analyzes a brute-force attack using Splunk SIEM and maps it to MITRE ATT&CK and Cyber Kill Chain frameworks.

## 🛠️ Technologies
- Splunk
- Windows Event Logs
- MITRE ATT&CK
- Cyber Kill Chain

## 🔍 Detection
- Identified multiple failed login attempts (Event ID 4625)
- Detected brute-force attack from a single IP

## 📊 Visualizations

### Attack Timeline
Shows spike in login attempts  
![Timeline](images/timeline.png)

### Top Attacker IP
Identifies attacking source  
![IP](images/attacker_ip.png)

### Targeted Accounts
Shows targeted users  
![Accounts](images/targeted_accounts.png)

### IP vs Account Correlation
Shows attack pattern  
![Correlation](images/correlation.png)

## 🧠 MITRE ATT&CK Mapping
- T1110 – Brute Force
- T1021 – Remote Services (RDP)

## 🔗 Cyber Kill Chain
- Reconnaissance → RDP identified  
- Weaponization → brute-force tool  
- Delivery → login attempts  
- Exploitation → password guessing  

## 📄 Report
Full report available in the repository.
