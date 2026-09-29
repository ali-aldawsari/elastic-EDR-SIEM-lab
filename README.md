Elastic EDR/SIEM Home Lab

A hands-on cybersecurity home lab built using Elastic Security and Elastic Defend to demonstrate endpoint monitoring, security telemetry collection, detection rules, and event investigation.

 Project Overview

This lab demonstrates the implementation of an Endpoint Detection and Response (EDR) and SIEM environment using Elastic Security.

The main objective was to deploy Elastic Defend on a Windows endpoint, collect endpoint telemetry, configure detection rules, and investigate security events through Elastic Security.

> This project focuses on EDR and SIEM capabilities rather than a full XDR implementation.

 Lab Architecture

```text
Windows 11 Endpoint
        │
        ▼
Elastic Agent + Elastic Defend
        │
        ▼
Fleet Server
        │
        ▼
Elasticsearch
        │
        ▼
Kibana / Elastic Security
        │
        ├── Detection Rules
        ├── Endpoint Events
        └── Timeline Investigation

---

 Technologies Used

- Elastic Security
- Elastic Defend
- Elastic Agent
- Fleet Server
- Elasticsearch
- Kibana
- Docker
- Windows 11
- KQL

---

 What I Implemented

- Deployed Elasticsearch and Kibana using Docker.
- Configured Fleet Server for agent management.
- Deployed Elastic Defend on a Windows 11 endpoint.
- Enrolled and verified the Elastic Agent.
- Collected endpoint security telemetry.
- Enabled the Endpoint Security detection rule.
- Investigated endpoint events using Elastic Security Timeline.
- Inspected detailed event information and JSON fields.

---

 Investigation Workflow

```text
Windows Endpoint
       ↓
Elastic Agent + Elastic Defend
       ↓
Fleet Server
       ↓
Elasticsearch
       ↓
Kibana / Elastic Security
       ↓
Detection Rules
       ↓
Endpoint Events
       ↓
Timeline Investigation
       ↓
Event Details / JSON
