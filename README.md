# **Wazuh SIEM Deployment and Log Analysis**

## **Overview**

This project documents the deployment and operation of a Wazuh-based SIEM used to collect, analyse, and alert on security events from multiple hosts in a lab environment. The focus is on SOC-style alert triage, log analysis, and detection tuning.

## **Lab Architecture**

- Wazuh Manager
- Wazuh Indexer and Dashboard
- Windows and Linux endpoints

## 📸 **Screenshot(s):**

### Wazuh Dashboard:
---
<img width="1880" height="914" alt="Wazuh Dashboard" src="https://github.com/user-attachments/assets/88b50140-87d7-41ee-8d1f-a89a455ad660" />

### Wazuh Agent Status:
---
<img width="1904" height="588" alt="Wazuh Agent Summary" src="https://github.com/user-attachments/assets/040379a8-d3e0-478d-a20a-405e12472179" />


## **What I Implemented**

- Installed and configured Wazuh Manager, Indexer, and Dashboard
- Deployed Wazuh agents to Windows and Linux systems
- Centralised Windows Event Logs and Linux syslogs
- Tuned rules to reduce false positives

## 📸 **Screenshot(s):**

screenshots/alert-details.png

## **Investigation Examples**

- Authentication failures
- Suspicious process execution
- Policy and compliance alerts

## 📸 ***Screenshot placeholder:***

screenshots/alert-investigation.png

## **Tools Used**

Wazuh, Elastic Stack, Linux, Windows

## **Key Skills Demonstrated**

SIEM deployment, alert triage, log analysis, SOC workflows
