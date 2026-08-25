# 04. Security Monitoring and Threat Detection with KQL

## 📌 Overview
This project implements central log telemetry aggregation and builds custom threat detection rules using Kusto Query Language (KQL) to alert on suspicious administrative and network behavior.

## 🛠️ Built With & Technologies Used
* **Log Analytics Workspace** (Diagnostic Telemetry Aggregation)
* **Kusto Query Language (KQL)** (Threat Hunting & Log Queries)
* **Azure Monitor Alerts** (Automated Incident Alerts)
* **Microsoft Sentinel** (SIEM/SOAR Rule Integration)

## 🎯 Key Implementation Steps
1. **Telemetry Pipeline:** Connected VM syslog, Entra ID Audit Logs, and Azure Activity Logs to a central Log Analytics Workspace.
2. **KQL Threat Detection:** Authored KQL queries to detect brute-force login attempts, unauthorized RBAC role changes, and anomalous outbound network traffic.
3. **Alerting Automation:** Created metric/log alert rules that trigger automated email/webhook notifications when threat queries return matches.

---
## 🖼️ Verification & Proof of Concept
*(Upload screenshots of your KQL query code, detected log events, and alert notifications)*
