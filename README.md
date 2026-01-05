☁️ Cloud Engineering & Security Portfolio

## 👤 About Me
I am a cloud engineering–focused student with hands-on experience designing, deploying, and operating cloud infrastructure.

My primary interest is cloud engineering, with a strong focus on Linux systems, networking, and observability.  
Security is used as a supporting layer to validate that cloud environments are properly monitored, resilient, and operationally sound.

---

## 🎯 Core Focus Areas
- Cloud infrastructure engineering  
- Linux server administration  
- Cloud networking and subnet design  
- Observability, logging, and monitoring  
- Automation and operational security  

---

## 🛠️ Technical Skills

### Cloud & Infrastructure
- Cloud VM provisioning using Vultr  
- Virtual networking, subnets, and IP range planning  
- Linux and Windows system administration  
- Secure SSH and RDP configuration  
- Firewall rules and access control  

### Observability & Operations
- ELK Stack (Elasticsearch, Logstash, Kibana)  
- Centralized log ingestion and correlation  
- Custom alert and detection creation  
- Incident tracking and workflows using osTicket  
- Log investigation with Kibana Discover  

### Security in Cloud Environments
- RDP brute-force attack simulation  
- C2 activity simulation using Mythic (Apollo agent)  
- Detection validation using real attack telemetry  
- Post-exploitation analysis and controlled data retrieval  

---

## 📂 Featured Project: Secure Cloud Infrastructure & Observability Lab

### Project Overview
This project demonstrates the design and deployment of a cloud-based lab environment focused on centralized logging, monitoring, and alerting.

Controlled attack simulations were performed to validate observability, detection logic, and incident response workflows in a realistic cloud setup.

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
- Simulated RDP brute-force activity against a Windows VM  
- Authentication and security logs generated and collected  

### Mythic C2 Agent Activity
- Deployed the Mythic framework and Apollo agent  
- Established command-and-control communication with a Windows target  
- Executed post-exploitation commands  
- Retrieved a password-protected file from the compromised system  

*Note: SSH brute-force was not simulated; however, detection rules for SSH activity were implemented and validated.*

---

## 🔍 Detection Validation

### SSH Authentication Detection
- Monitored Linux authentication logs  
- Alerts triggered for suspicious SSH login activity  

### RDP Brute-Force Detection
- ELK detected repeated failed RDP authentication attempts  
- Alerts generated and tickets created in osTicket  

### Mythic C2 Activity Detection
- Alerts triggered on C2-related behavior  
- Detection validated through Kibana investigation  
- Alerts include direct links to Kibana for efficient analysis  
- Queries verified using Kibana Discover  
- Logs confirm malicious and post-exploitation activity  

---

## 🎥 Project Demonstration
This project is fully demonstrated in a recorded video walkthrough, covering:
- Cloud architecture and subnet design  
- ELK stack deployment and alert creation  
- RDP brute-force simulation  
- Mythic C2 agent execution and data retrieval  
- Detection validation for SSH, RDP, and Mythic activity  

**Video available on:**
- LinkedIn: [ADD LINK HERE](https://www.linkedin.com/in/med-nour-i-houjri-503085324/)  
- GitHub (linked in this repository)

---

## ⚠️ Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.  
All attack simulations were performed on systems owned and authorized by the author.

---

## 📫 Contact
- LinkedIn: (https://www.linkedin.com/in/med-nour-i-houjri-503085324/)  
- GitHub: https://github.com/NourHoujri
