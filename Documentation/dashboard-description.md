# SOC Incident Response Dashboard

## Project Overview

This project presents a SOC (Security Operations Center) Incident Response Dashboard developed using Splunk. The dashboard is designed to monitor, detect, and investigate security events by analyzing authentication logs and suspicious command execution. It provides security analysts with a centralized view of incidents, helping them identify threats, investigate attacker activity, and support incident response.

---

## Dashboard Features

The dashboard includes the following security monitoring panels:

- Failed Login Detection
- Successful Login Monitoring
- Authentication Correlation
- Top Attacker IP Addresses
- Top Targeted User Accounts
- Suspicious Command Execution
- Incident Timeline
- MITRE ATT&CK Mapping
- Indicators of Compromise (IOCs)
- Analyst Investigation Summary

---

## Detected Attack Scenarios

The dashboard is capable of detecting and monitoring:

- SSH Brute Force Attacks through repeated failed login attempts.
- Successful authentication following multiple failed attempts.
- Suspicious file downloads using the `curl` command.
- Archive file download activity involving `cache_bkp.tar.gz`.
- Potential account compromise based on authentication behavior.
- Suspicious command execution during the investigation.

---

## MITRE ATT&CK Mapping

The dashboard maps detected activities to the MITRE ATT&CK Framework.

| Technique ID | Technique Name |
|--------------|-------------------------------|
| T1110 | Brute Force |
| T1059 | Command and Scripting Interpreter |
| T1560 | Archive Collected Data |

---

## Technologies Used

- Splunk Enterprise
- Search Processing Language (SPL)
- Linux Authentication Logs
- MITRE ATT&CK Framework

---

## Skills Demonstrated

This project demonstrates practical SOC Analyst skills including:

- Log Analysis
- Threat Detection
- Incident Investigation
- Authentication Monitoring
- IOC Identification
- MITRE ATT&CK Mapping
- Splunk Dashboard Development
- Security Monitoring
- Incident Response

---

## Purpose

The objective of this project is to demonstrate the workflow of a SOC analyst by collecting security events, correlating suspicious activities, visualizing attack patterns, and documenting findings through an interactive Splunk dashboard.