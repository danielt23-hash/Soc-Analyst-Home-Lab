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
Screenshots will be added as detections are completed.

## What I Learned
This section will be updated as the lab is built and detections are completed.
