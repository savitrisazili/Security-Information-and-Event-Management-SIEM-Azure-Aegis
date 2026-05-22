# Windows Agent Monitoring

## Overview
This document explains the installation and monitoring process of the Windows Wazuh Agent.

## Installation Process
- Install Windows 10 virtual machine
- Install Wazuh Agent
- Configure Wazuh Manager IP address
- Register the agent to Wazuh Manager
- Verify Wazuh Agent service status

## Activities Monitored
- Failed login attempts
- Successful login after brute force
- Windows authentication events

## Testing Scenario
Multiple failed login attempts were simulated to trigger security alerts on the Wazuh Dashboard and Telegram notifications.

## Result
The Windows agent successfully connected to the Wazuh Manager and generated monitoring alerts in real time.
