# PowerShell Process Investigation

## Project Overview

This project investigates Windows Process Creation Events (Event ID 4688) to analyze PowerShell activity and parent-child process relationships in a controlled cybersecurity home lab.

The investigation reconstructs the execution timeline of PowerShell launching native Windows utilities, including `whoami.exe`, `hostname.exe`, `ipconfig.exe`, and `cmd.exe`. The observed behavior was analyzed using Windows Event Viewer and mapped to the MITRE ATT&CK framework to determine whether it represented malicious or legitimate activity.

The investigation concluded that the observed activity was benign and consistent with authorized user actions performed during a SOC analyst training exercise.

## Tools Used

- Windows Event Viewer
- Windows Security Logs
- Windows 10
- PowerShell
- Oracle VirtualBox

## Skills Demonstrated

- Windows Event Log Analysis
- Event ID 4688 Investigation
- Process Creation Monitoring
- Parent-Child Process Analysis
- Threat Hunting
- MITRE ATT&CK Mapping
- Incident Documentation

## Project Documentation

- 📄 [Process Investigation Report](./Report/Process_Investigation_Report.pdf)
