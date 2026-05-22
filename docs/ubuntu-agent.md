# Ubuntu Agent Monitoring

## Overview
This document explains the Ubuntu Server agent installation and monitoring configuration.

## Installation Process
- Install Ubuntu Server virtual machine
- Install SSH and Tailscale
- Install Wazuh Agent
- Configure ossec.conf
- Connect the agent to Wazuh Manager

## Activities Monitored
- SSH brute force attacks
- User creation activity
- Linux authentication logs

## Testing Scenario
A new user creation simulation was performed using the sudo adduser command to generate monitoring logs.

## Result
Ubuntu monitoring logs successfully appeared on the Wazuh Dashboard and Telegram notifications.
