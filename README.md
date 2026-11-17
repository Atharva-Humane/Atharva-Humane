# Hello, I'm Atharva Humane

<a href="http://www.linkedin.com/in/atharva-humane-6715232b3"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://img.shields.io/badge/-CompTIA%20Security+-C8202F?&style=for-the-badge&logo=comptia&logoColor=white"><img src="https://img.shields.io/badge/-CompTIA%20Security+-C8202F?&style=for-the-badge&logo=comptia&logoColor=white" /></a>

I am a Computer Engineering graduate and **CompTIA Security+ certified** (SY0-701) with hands-on experience in building cybersecurity labs focused on attack simulation and detection. I have worked with Active Directory environments, SIEM tools, endpoint telemetry, and PCAP-based malware analysis to understand how real-world threats are generated, detected, and investigated.

## Objective

I am seeking an entry-level role in cybersecurity, particularly in a Security Operations Center (SOC), where I can apply my skills in log analysis, threat detection, and incident investigation while continuing to develop practical defensive security expertise.

## Skills

| Skill |
|------|
| SIEM Implementation & Log Analysis |
| Endpoint Monitoring (Sysmon) |
| Active Directory Environment Setup |
| MITRE ATT&CK Simulation |
| RDP Attack Simulation & Analysis |
| PCAP Analysis & C2 Traffic Detection |
| IOC Extraction & Incident Reporting |
| Threat Detection & Investigation |

## Tools

### Network
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
</div>

### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Sysmon-000000?&style=for-the-badge&logo=Windows&logoColor=white" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
</div>

### Attack Simulation
<div>
    <img src="https://img.shields.io/badge/-Atomic%20Red%20Team-8B0000?&style=for-the-badge&logo=github&logoColor=white" />
</div>

## Certifications

- **CompTIA Security+ (SY0-701)**: November 2026

## Virtual Experience Programs

- **Deloitte Cybersecurity Job Simulation**: analysed web activity logs to trace anomalous access in a simulated breach
- **Mastercard Security Awareness Job Simulation**: identified simulated phishing threats and designed targeted training programmes
- **TCS Identity & Access Management Job Simulation**: delivered IAM design and solution architecture documentation

## Projects

### <a href="https://github.com/Atharva-Humane/active-directory-soc-lab">Active-directory-soc-lab</a>

Built a home lab to simulate attacks and detect them using a SIEM.

* Active Directory environment with Windows Server 2022
* Endpoint telemetry using Sysmon
* Log analysis and detection in Splunk
* Attack simulation using Atomic Red Team (T1136.001, T1059.001) and RDP brute force with Hydra
* Detections built on Windows Event IDs 4625 (failed logons) and 4720 (account creation)

### NetSupport Manager RAT PCAP Analysis & Incident Report

Investigated RAT command-and-control activity in two real-world PCAPs.

* Identified infected hosts using DHCP, NBNS, and Kerberos traffic
* Traced C2 beaconing to `45.131.214[.]85` and `194.180.191[.]64` via `/fakeurl.htm` at 60-second intervals
* Extracted IOC sets and mapped activity to MITRE ATT&CK (T1219, T1071.001)
* Produced a formal incident report with timeline and remediation steps
