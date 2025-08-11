
# SOC Analyst Portfolio

This repository documents my journey and hands-on practice as a SOC Analyst with a focus on Microsoft Security tools (SC-200 path).  
It contains practical labs, incident investigation notes, and KQL queries developed through platforms like Microsoft Learn, TryHackMe, and Blue Team Labs Online.

---

## 📂 Repository Structure

```
/kql-queries       → Saved KQL scripts and queries
/lab-reports       → Investigation notes and lab walkthroughs
/screenshots       → Evidence and screenshots from lab environments
README.md          → Overview of portfolio and progress
```

---

## 🛠 Skills Covered
- Kusto Query Language (KQL)
- Microsoft Sentinel (SIEM) operations
- Microsoft 365 Defender Advanced Hunting (XDR)
- Log analysis and threat detection
- Incident response and case documentation
- MITRE ATT&CK mapping

---

## 📜 Labs Completed

### 1. TryHackMe – KQL 101
**Skills Learned:**
- Writing basic to advanced KQL queries
- Filtering and aggregating log data
- Joining multiple data tables

**Sample Query:**
```kql
SecurityEvent
| where EventID == 4625
| summarize FailedLogins = count() by Account
```

**Key Findings:**
- Identified multiple brute-force attempts targeting a specific account.
- Learned how to pivot investigation from account to source IP.

**Evidence:**  
![Failed Login Screenshot](screenshots/kql101-failed-logins.png)

---

### 2. Microsoft Sentinel – Incident Investigation
**Skills Learned:**
- Connecting data sources
- Creating custom analytics rules
- Investigating and closing incidents

**Key Findings:**
- Successfully investigated a simulated brute force attack.
- Created an automated alert rule to catch similar patterns in the future.

---

## 📌 Upcoming Labs
- Microsoft 365 Defender Advanced Hunting
- TryHackMe SOC Level 1: Log Analysis
- BTLO: Suspicious PowerShell Investigation

---

## 📧 Contact
- Email: your.email@example.com  
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- GitHub: [Your GitHub Profile](https://github.com/yourusername)

---

**Note:** This portfolio is for educational and demonstration purposes only. All lab data is simulated or anonymized.
