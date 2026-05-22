# Detection Rules and Monitoring Configuration

## Overview
This document explains the detection rules used in the SIEM Wazuh project.

## Detection Rules

### SSH Brute Force Detection
Detects repeated SSH login attempts on the Ubuntu agent.

### Port Scanning Detection
Detects suspicious scanning activities against the Apache web server.

### Admin and phpMyAdmin Access Detection
Detects access attempts to sensitive web endpoints.

### Successful Login After Brute Force
Detects successful authentication after multiple failed login attempts on Windows systems.

### New User Detection
Detects user creation activities on Ubuntu systems.

## Configuration Files
- ossec.conf
- local_rules.xml

## Result
The implemented rules successfully detected suspicious activities and generated real-time alerts through the Wazuh Dashboard and Telegram integration.
