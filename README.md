# APT34 (OilRig) Threat Intelligence & Defense Simulation

## 📌 Project Overview
This project is a threat intelligence and defensive security analysis of APT34 (also known as OilRig), a state-sponsored cyber threat group.

The project simulates the role of a Security Operations Center (SOC) analyst tasked with analyzing threat actor behavior and recommending defensive strategies to protect organizational infrastructure.

## 👨‍💻 Role Simulation

In this scenario, I acted as a Cybersecurity Analyst responsible for:

- Analyzing threat actor tactics, techniques, and procedures (TTPs)
- Mapping attacks to the MITRE ATT&CK framework
- Identifying indicators of compromise (IOCs)
- Recommending defensive and monitoring strategies

## 🧠 Threat Actor Overview

APT34 (also known as OilRig or Helix Kitten) is a state-sponsored cyber espionage group believed to be linked to Iran.

- Active since: ~2014
- Primary objective: Intelligence gathering
- Target sectors: Government, energy, telecommunications, finance

The group is known for spear-phishing campaigns, credential harvesting, and use of custom malware. :contentReference

## 🧰 Tools & Resources Used

- **OSINT Tools**:
  - [Mandiant](https://www.mandiant.com/resources/blog)
  - [CrowdStrike](https://www.crowdstrike.com/)
  - [Recorded Future](https://www.recordedfuture.com/)
  - [SecureWorks](https://www.secureworks.com/)
  - [Kaspersky Threat Intelligence](https://www.kaspersky.com/)
  - [MITRE ATT&CK](https://attack.mitre.org/)

- **Cybersecurity News Sources**:
  - [CyberScoop](https://www.cyberscoop.com/)
  - [Dark Reading](https://www.darkreading.com/)
  - [The CyberWire](https://thecyberwire.com/)
  - [CISA](https://www.cisa.gov/)
  - [US-CERT](https://www.us-cert.gov/)

## 📁 Project Structure
```
Defending-Against-APT34_A-DATACOM-Project/
│
├── README.md                                      - Project overview, methodology, and documentation.
└── DATACOM Cybersecurity Project.pdf              - The original project brief and requirements (uploaded as reference).
```

## 🎯 Attack Lifecycle (MITRE ATT&CK Mapping)

APT34 operations can be mapped to key MITRE ATT&CK tactics:

### 1. Initial Access
- Spear-phishing emails with malicious attachments
- Credential harvesting via phishing pages

### 2. Execution
- PowerShell scripts
- Malicious macros

### 3. Persistence
- Scheduled tasks
- Registry modifications

### 4. Credential Access
- Credential dumping
- Abuse of valid accounts (T1078)

### 5. Command & Control (C2)
- HTTP/DNS communication channels

### 6. Exfiltration
- Data exfiltration over network protocols

## 🔍 Indicators of Compromise (IOCs)

- Suspicious phishing emails or attachments
- Unusual PowerShell activity
- Unknown scheduled tasks
- Outbound traffic to suspicious domains
- Unauthorized credential usage

## ⚠️ Risk Assessment

### Potential Impact:
- Unauthorized access to internal systems
- Data exfiltration
- Long-term persistence within network
- Compromise of sensitive organizational data

### Risk Level:
- **Likelihood:** High
- **Impact:** High
- **Overall Risk:** Severe

APT34 is known for persistent and stealthy operations, often maintaining long-term access to compromised systems.

## 🛡️ Defensive Strategies

To defend against APT34-style attacks:

### 🔐 Prevention
- Implement Multi-Factor Authentication (MFA)
- Apply email filtering and phishing protection
- Regularly patch systems

### 🔍 Detection
- Monitor logs for abnormal behavior
- Use SIEM tools for correlation and alerting
- Detect unusual PowerShell activity

### 🚨 Response
- Isolate compromised systems
- Reset credentials
- Conduct forensic investigation

## 🧪 Simulated Attack Scenario

### Example Attack Flow:
1. User receives spear-phishing email
2. Malicious document executes PowerShell script
3. Attacker establishes persistence
4. Credentials are harvested
5. Data is exfiltrated

## 📊 SOC Relevance

This project demonstrates:

- Threat intelligence analysis
- MITRE ATT&CK mapping
- Incident detection awareness
- Risk assessment
- Defensive strategy development

## 🧠 Key Takeaway

APT34 represents a persistent and evolving cyber threat. Understanding attacker behavior is essential for building effective detection and response strategies in modern security operations.

## 📈 Outcome

This project demonstrates the use of industry-standard frameworks and open-source tools to investigate and defend against state-sponsored cyber threats. It serves as a practical example of how OSINT and threat intelligence can be used to enhance an organization’s security strategy.

## 👤 Authors

**Uchendu, Favour Eni**

Cybersecurity Analyst | OSINT Researcher

[LinkedIn Profile - www.linkedin.com/in/favour-uchendu] • [Email Address - uchenduphayvurh@gmail.com] • [GitHub Profile - https://github.com/enibody1]

&

**Oladimeji, Richard**

Cybersecurity Analyst | OSINT Researcher 

[LinkedIn Profile - www.linkedin.com/in/Richard-oladimeji] • [Email Address - Tunevert@aol.com] • [GitHub Profile - https://github.com/tunevert-alt]

---

> *For educational and informational purposes only. This repository does not contain any proprietary threat intelligence or classified data.*

