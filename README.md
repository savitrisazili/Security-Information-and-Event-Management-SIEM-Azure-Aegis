# SIEM Wazuh Lab – Azure Aegis (Blue Team 7)

## Overview
This project demonstrates the implementation of a Security Information and Event Management (SIEM) system using Wazuh in a virtual lab environment. The system was developed to monitor, analyze, and detect suspicious activities in real time using centralized log management and custom detection rules.

The project integrates multiple monitored systems including Windows, Ubuntu Server, and Apache Web Server, while also implementing Telegram alert notifications for incident monitoring.

---

## Project Objectives

- Implement Wazuh as an open-source SIEM platform
- Monitor logs from multiple agents and systems
- Detect suspicious security activities in real time
- Create custom detection rules for attack scenarios
- Visualize alerts and events through the Wazuh Dashboard
- Integrate Telegram notifications for security alerts

---

## Implemented Scenarios

The project implements several attack simulation and monitoring scenarios:

- SSH Brute Force Detection
- Port Scanning Detection
- Admin Panel Access Detection
- phpMyAdmin Access Detection
- Successful Login After Brute Force
- New User / User Creation Detection

---

## Technologies and Tools

### SIEM Platform
- Wazuh Manager
- Wazuh Dashboard
- Wazuh Indexer

### Operating Systems
- Ubuntu Server
- Windows 10

### Web Services
- Apache Web Server
- phpMyAdmin

### Attack Simulation Tools
- Hydra
- Nmap

### Other Tools
- VirtualBox
- Tailscale
- Telegram Bot Integration

---

## System Architecture

The SIEM environment consists of:

- Wazuh Server as the central monitoring system
- Windows Agent
- Ubuntu Agent
- Apache Web Server
- Attacker Machine for attack simulations
- Telegram notification system
- OpenSearch Dashboard for monitoring visualization

---

## Features

- Real-time log monitoring
- Security alert visualization
- Centralized log collection
- Telegram alert notifications
- Custom detection rules
- Apache access monitoring
- Windows authentication monitoring
- Linux user activity monitoring
- Attack simulation and testing

---

## Repository Structure

```text
SIEM-WAZUH-LAB-AZURE-AEGIS-BLUE-TEAM-7/
│
├── docs/
├── screenshots/
├── reports/
├── presentation/
└── configs/
```

---

## Documentation

### docs/
Contains technical documentation including:
- Wazuh installation and setup
- Agent integration
- Attack simulation scenarios
- Detection rules
- Apache monitoring
- Telegram integration

### screenshots/
Contains dashboard screenshots, alerts, monitoring activities, and implementation evidence.

### reports/
Contains the final SIEM project report and implementation documentation.

### presentation/
Contains presentation slides related to the SIEM project implementation.

### configs/
Contains Wazuh configuration files and custom detection rules.


---

## Detection Results

The SIEM implementation successfully detected:

- SSH brute force attempts
- Port scanning activities
- Access to sensitive endpoints
- Multiple failed login attempts
- Successful login after brute force
- New user creation activities

All alerts were successfully displayed on the Wazuh Dashboard and delivered through Telegram notifications.

---

## Team Members

Azure Aegis – Blue Team 7

- Savitri — Team Leader & Wazuh Server
- Davin Gabriel Jonathan — Windows Agent
- Raditya Ihsan — Attacker Simulation
- Kgs Abdul Fatah Revaldo — Ubuntu Agent
- Jeanne Septiani — Documentation
- M. Rizqi — Web Server

---

## Conclusion

The project successfully implemented a functional SIEM environment using Wazuh for centralized monitoring, attack detection, and security event analysis. The system demonstrated effective real-time monitoring capabilities and successfully generated alerts for multiple simulated attack scenarios.

---

## Disclaimer

This project was developed for educational and cybersecurity learning purposes only.
