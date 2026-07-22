# SOC-Home-Lab
A SOC monitoring lab using Kali Linux, Windows 11, Sysmon, and security event analysis.
# SOC Home Lab: Security Monitoring & Incident Investigation

## Overview

A hands-on SOC laboratory built to simulate security monitoring and incident investigation using Kali Linux, Windows 11, and Sysmon.

The lab demonstrates endpoint monitoring, network reconnaissance detection, and process activity analysis.

---

## Lab Architecture

```
Kali Linux
(Attack Simulation)
        |
        ↓
Windows 11 Endpoint
(Sysmon Monitoring)
        |
        ↓
Security Event Analysis
```

---

## Tools Used

- Kali Linux
- Windows 11
- Sysmon
- Event Viewer
- Nmap
- Wireshark

---

## Investigations Completed

### 1. Network Reconnaissance Detection

- Performed Nmap service scanning from Kali Linux.
- Detected network activity using Sysmon Event ID 3.
- Analyzed source and destination IP addresses.

MITRE ATT&CK:
- T1046 - Network Service Scanning

---

### 2. PowerShell Process Investigation

- Monitored PowerShell-related execution activity.
- Investigated Sysmon Event ID 1 process creation logs.
- Analyzed parent-child process relationships.

MITRE ATT&CK:
- T1059.001 - PowerShell

---

## Skills Demonstrated

- Security Monitoring
- Windows Event Analysis
- Endpoint Detection
- Network Analysis
- Incident Documentation
- MITRE ATT&CK Mapping
