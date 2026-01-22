# Prosperity Bank SOC Capstone Project

## Overview
This repository contains my **Security Operations Center (SOC) Analysis & Threat Detection** capstone project, conducted as part of the SOC Analysis specialization. The project simulates a real-world incident response scenario at **Prosperity Bank**, focusing on **Ubuntu server log analysis, detection of suspicious activity, and recommended mitigations**.

## Project Objectives
- Simulate suspicious activities on Ubuntu systems:
  - Privilege escalation (sudo → root)
  - Unauthorized local user creation
- Detect and analyze security events using system logs (`/var/log/auth.log`)
- Correlate activity to identify potential threats
- Produce a professional SOC incident report including:
  - Executive summary
  - Key detections with screenshots
  - Threat assessment and impact analysis
  - Mitigation recommendations (pfSense VLAN segmentation)

## Evidence & Artifacts
- **PDF Report:** `Prosperity_Bank_SOC_Incident_Report.pdf`  
  Contains:
  - Screenshots of privilege escalation and unauthorized user creation
  - Log analysis excerpts
  - Threat assessment and mitigation strategies

## Key Findings
- Detected **privilege escalation** from standard user to root
- Detected **unauthorized user account creation** (`hacker`)
- Assessed potential impact on confidentiality, integrity, and availability
- Recommended network segmentation and monitoring strategies to prevent lateral movement

## Tools & Environment
- **OS:** Ubuntu Server (VirtualBox VM)
- **Tools:** Wazuh Agent (log-based monitoring), system logs (`/var/log/auth.log`)
- **Optional / conceptual:** pfSense for VLAN segmentation

## How to Use
1. Review the PDF report for all findings, evidence, and recommendations.
2. The repo is primarily intended for **educational and portfolio purposes**.
3. Screenshots in the report demonstrate real SOC-style analysis and evidence collection.

## Author
**[Akin Aremu]**  
SOC Analysis & Threat Detection Capstone Project  

