# ☁️ Cloud Engineering & Security Portfolio

## 👤 About Me

I am a **cloud engineering–focused student** with hands-on experience designing,
deploying, and operating secure cloud infrastructure.

My main interest is cloud engineering, including infrastructure design,
Linux systems, networking, and observability.  
Security is used as a validation layer to ensure cloud environments are
monitored, resilient, and production-ready.

---

## 🎯 Core Focus Areas

- Cloud Infrastructure Engineering  
- Linux Server Administration  
- Cloud Networking & Subnet Design  
- Observability, Logging, and Monitoring  
- Automation and Operational Security  

---

## 🛠️ Technical Skills

### Cloud & Infrastructure
- Cloud VM provisioning (Vultr)
- Virtual networks, subnets, and IP range planning
- Linux and Windows system administration
- Secure SSH and RDP configuration
- Firewall rules and access control

### Observability & Operations
- ELK Stack (Elasticsearch, Logstash, Kibana)
- Centralized log ingestion and correlation
- Custom detection and alert creation
- Incident tracking and workflows (osTicket)
- Investigation using Kibana Discover

### Security in Cloud Environments
- RDP brute-force attack simulation
- C2 activity simulation using Mythic (Apollo agent)
- Detection validation using real attack telemetry
- Post-exploitation analysis and data retrieval

---

## 📂 Featured Project: Secure Cloud Infrastructure & Observability Lab

### Project Overview

This project demonstrates the design and deployment of a **cloud-based lab
environment** with centralized logging, monitoring, and alerting.

Controlled attack simulations were executed to **validate observability,
detection logic, and incident response workflows** in a realistic cloud setup.

---

## 🏗️ Architecture Summary

- Cloud-hosted Linux and Windows virtual machines
- Segmented networking with defined subnets and IP ranges
- Centralized logging using the ELK Stack
- Custom alert rules mapped to attack behavior
- Automated incident ticketing using osTicket
- Mythic C2 framework for adversary simulation

---

## ⚔️ Attack Simulation

### RDP Brute-Force Attempt
- Simulated RDP brute-force attack against a Windows VM
- Authentication and security logs generated and collected

### Mythic C2 Agent Activity
- Deployed Mythic framework and Apollo agent
- Established command-and-control communication with a Windows target
- Executed post-exploitation commands
- Retrieved a password-protected file from the compromised system

> **Note:** SSH brute-force was **not simulated**, but detection rules were in place.

---

## 🔍 Detection Validation

- **SSH Authentication Detection**
  - Monitored Linux authentication logs
  - Alerts triggered for suspicious SSH login attempts
- **RDP Brute-Force Detection**
  - ELK detected repeated failed RDP login attempts
  - Alerts generated and tickets created in osTicket
- **Mythic C2 Activity Detection**
  - Alerts triggered on C2 activity
  - Confirmed detection and investigation workflow
- Alerts include direct links to Kibana for fast investigation
- Queries verified using Kibana Discover
- Logs confirm malicious behavior and post-exploitation activity

---

## 🎥 Project Demonstration

This project is fully demonstrated in a **video walkthrough**, including:
- Cloud architecture and subnet design
- ELK stack deployment and alert creation
- RDP brute-force attack simulation
- Mythic C2 agent execution and data retrieval
- Detection validation for SSH, RDP, and Mythic activity

Video available on:
- LinkedIn: ADD LINK HERE
- GitHub (linked in this repository)

---

## ⚠️ Disclaimer

This project was conducted in a **controlled lab environment** for educational
purposes only.  
All attack simulations were performed on systems owned and authorized by the author.

---

## 📫 Contact

- LinkedIn: ADD LINK HERE
- GitHub: https://github.com/NourHoujri
