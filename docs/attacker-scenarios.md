# Attack Simulation Scenarios

## Overview
This document explains the attack simulations performed during the SIEM project implementation.

## Attack Tools
- Hydra
- Nmap

## Simulated Attacks

### SSH Brute Force
Repeated SSH login attempts were simulated against the Ubuntu agent.

### Port Scanning
Vertical, horizontal, and targeted port scanning activities were performed against the web server.

### Admin and phpMyAdmin Access
Access attempts were made to sensitive endpoints such as /admin and /phpmyadmin.

## Result
All attack simulations successfully generated alerts and monitoring events on the Wazuh Dashboard and Telegram notifications.
