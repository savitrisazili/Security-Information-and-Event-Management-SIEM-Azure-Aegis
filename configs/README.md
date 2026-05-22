# Configuration Files

This folder contains the main configuration files used in the SIEM Wazuh project.

## Included Files

### ossec.conf
Main Wazuh configuration file used to manage log monitoring, agent behavior, log collection, and system monitoring settings.

### local_rules.xml
Custom detection rules used to identify suspicious activities such as:
- SSH brute force attacks
- Port scanning
- Admin and phpMyAdmin access
- Successful login after brute force
- New user creation

## Purpose

These configuration files support:
- Real-time log monitoring
- Threat detection
- Alert generation
- Apache web server monitoring
- Windows and Ubuntu agent monitoring
- Telegram alert integration

## Result

The implemented configurations successfully enabled centralized monitoring and real-time threat detection within the Wazuh SIEM environment.
