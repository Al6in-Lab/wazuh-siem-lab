# Cloud-Hosted SIEM & Telemetry Triage Laboratory

## Project Overview
This laboratory environment focuses on the centralized collection, correlation, and analysis of enterprise endpoint logs. The objective is to establish a robust visibility perimeter by deploying an open-source SIEM platform and configuring advanced endpoint telemetry agents to track indicators of compromise (IoCs).

---

## Infrastructure Architecture & Components
* **SIEM Core:** Wazuh Server deployed on a cloud-hosted Linux virtual machine instance.
* **Telemetry Source:** Windows Server virtual endpoint configured with Microsoft Sysmon.
* **Data Flow:** Secured transport protocols routing raw host events from endpoint agents to the centralized correlation engine.

---

## Technical Workflows Implemented

### 1. Centralized Log Ingestion
* Configured the centralized SIEM architecture to ingest and parse standard system logs, network telemetry, and audit event logs.
* Mapped raw JSON and Syslog alerts against the structured taxonomy of the **MITRE ATT&CK Matrix**.

### 2. Advanced Endpoint Telemetry (Sysmon)
* Deployed Microsoft Sysmon to capture system behaviors beyond generic operating system logging.
* Structured surveillance rules to track high-risk activities including process creations, remote thread injections, and unauthorized network connections.

### 3. Alert Triage & Simulation Analysis
* Analyzed security alerts generated from controlled command-line activity and privilege escalation simulations.
* Performed log analysis to isolate malicious indicator attributes, differentiate real threats from false positives, and verify defense detection capabilities.

---

## Core Competencies Demonstrated
* Enterprise Log Correlation & SIEM Management
* Windows & Linux Host Telemetry Analysis
* Incident Verification & False Positive Filtering
* Threat Modeling Framework Alignment (NIST / MITRE ATT&CK)
