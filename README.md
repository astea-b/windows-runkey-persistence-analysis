# Windows RunKey Persistence Detection & Technical Analysis

## 📌 Project Overview
This repository features a comprehensive technical report and automated detection configurations focused on identifying Registry RunKey persistence mechanisms. These methods are frequently exploited by advanced threats and malware to maintain unauthorized access within Windows environments.

## 🎯 Business Value & Problem Solved
* **The Threat:** Attackers modify registry run keys (`Software\Microsoft\Windows\CurrentVersion\Run`) to survive system reboots, silently executing malicious code in the background.
* **The Solution:** Implemented high-fidelity Sysmon monitoring rules combined with strict behavioral analysis to flag anomalous persistence attempts.
* **The Outcome:** Enables Security Operations Center (SOC) analysts to intercept persistent threats instantly, protecting critical business infrastructure from long-term compliance breaches and data theft.

## 📁 Repository Structure
* `RunKey Persistence.xml` — Advanced Sysmon detection baseline configuration.
* `Create RunKey Persistence Activity — Technical Report.md` — Deep-dive analysis, log forensics, and step-by-step mitigation guide.

## 🛠️ Technologies Used
* **OS Baseline:** Windows Enterprise / Server
* **Monitoring:** Microsoft Sysmon, Windows Event Logs
* **Analysis Tools:** Registry Editor, PowerShell, Event Viewer
