# PowerShell-Enumeration-and-LOLBin-Detection-via-Microsoft-Defender-Endpoint
# 🛡️ Cybersecurity Lab: Defender for Endpoint Simulation

## 📌 Overview
This project simulates a real-world SOC scenario using Microsoft Defender for Endpoint (MDE). It demonstrates how benign and suspicious activities generate telemetry, which can be validated through advanced hunting queries. The lab is designed to reinforce endpoint visibility, threat detection, and incident response readiness.

## 🎯 Goal
- Onboard a Windows VM to Defender for Endpoint
- Simulate benign and suspicious activity
- Validate telemetry and detection using KQL queries
- Strengthen understanding of endpoint logging and SOC workflows

## 🧪 What I Did
- Ran PowerShell enumeration commands (`Get-Process`, `Get-Service`)
- Simulated LOLBIN behavior using `Invoke-WebRequest` to download a payload from Ubuntu
- Enabled Command Line Auditing and Script Block Logging policies
- Verified telemetry via MDE’s Advanced Hunting using `DeviceProcessEvents`

## 🛠️ Tools & Setup
- Windows 10 VM (Defender for Endpoint onboarded)
- Ubuntu VM (hosted payload.txt)
- Microsoft Defender for Endpoint portal
- PowerShell
- Group Policy Editor (for logging policies)
- KQL (Advanced Hunting)

## 📖 Full Lab Walkthrough
1. **VM Onboarding**: Connected Windows VM to MDE via onboarding script.
2. **Telemetry Generation**: Executed benign PowerShell commands and verified logs.
3. **Suspicious Activity Simulation**: Used LOLBIN technique to mimic attacker behavior.
4. **Logging Configuration**: Enabled auditing policies for deeper visibility.
5. **Detection Validation**: Queried telemetry using KQL to confirm visibility.

## 🔍 Why It Matters
This lab demonstrates how defenders can simulate realistic attack scenarios, validate endpoint telemetry, and improve detection logic. It reinforces the importance of visibility, proactive hunting, and logging in modern SOC environments.

