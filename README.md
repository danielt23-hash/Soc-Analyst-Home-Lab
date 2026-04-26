# SOC Analyst Home Lab

## Overview
This project documents a beginner SOC analyst home lab built to collect logs, detect suspicious activity, and investigate security events using Splunk, Sysmon, Windows, and Kali Linux.

## Lab Objectives
- Build a small SOC-style lab environment
- Collect Windows endpoint logs
- Use Splunk to search and analyze security events
- Detect failed login attempts, suspicious PowerShell activity, and network scanning
- Document findings in clear case reports

## Tools Used
- Splunk Enterprise
- Windows 10/11 Virtual Machine
- Sysmon
- Kali Linux
- VirtualBox

## Lab Architecture
Kali Linux VM → Windows VM → Splunk

## Planned Detections
1. Failed login attempts
2. Successful login after multiple failures
3. Suspicious PowerShell execution
4. Network scanning activity

## Case Reports
- [Failed Login Detection - Windows Event ID 4625](case-reports/failed-login-detection.md)

## Screenshots
- [Windows Security Log Event Viewer](screenshots/01-windows-security-log-event-viewer.png)
- [Failed Login Event ID 4625](screenshots/02-failed-login-events-4625.png)

## What I Learned
- How Windows Security logs record authentication activity
- How failed login attempts appear as Event ID 4625
- How to use Event Viewer to investigate suspicious login behavior
- How to document SOC-style findings in a case report
