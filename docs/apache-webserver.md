# Apache Web Server Monitoring

## Overview
This document explains the implementation and monitoring process of the Apache Web Server using Wazuh.

## Web Server Configuration
- Install Apache Web Server
- Configure /admin endpoint
- Configure /phpmyadmin endpoint
- Configure Apache security settings

## Monitored Logs
- /var/log/apache2/access.log

## Detection Activities
- Admin panel access detection
- phpMyAdmin access detection
- Port scanning detection

## Result
Suspicious web activities and reconnaissance attempts were successfully monitored and detected by Wazuh SIEM.
