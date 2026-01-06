![wazuhlogo](https://miro.medium.com/v2/resize:fit:1400/1*FaRdBo_MuVp0F0AMY6EGIg.png)

# Wazuh Homelab Setup

## Overview
This project documents my personal **homelab setup using Wazuh**, an open-source security monitoring and SIEM solution. 
The objective for this project is to mimic the real SOC Monitoring and familiarise myself to SIEM tasks.

The setup includes:

- **Wazuh Manager**: **Kali Linux 2025.2**, managing agents and analyzing alerts.
- **Wazuh Agent**: Installed on a **Windows 11** client machine for monitoring.
- **File Integrity Monitoring (FIM)**: Tested to track changes to files.

This project demonstrates hands-on experience with SIEM deployment, alerting, and basic security monitoring.

---

## Tools and Techs

- Virtual Machine: Oracle VirtualBox 7.1.8
- **Manager OS**: Kali Linux 2025.2 hosted by Virtual Machine
- **Agent OS**:  Windows 11 client
- **Wazuh SIEM**: Wazuh manager (v4.12) and agents (v4.12) communicate securely via TCP Port 1559.

---

## The Process

> Disclaimer: This is a simplified overview. For full setup instructions, refer to [Wazuh Official Docs](https://documentation.wazuh.com/current/).

<a href="https://github.com/hafetzys/wazuh-homelab-setup/blob/main/Wazuh%20Installation%20and%20File%20Integrity%20Monitoring.pdf"><img src="https://img.shields.io/badge/Click-HERE-blue?style=flat-square&logoSize=300x300" /></a>

