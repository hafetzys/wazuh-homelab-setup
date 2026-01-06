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

![Static Badge](https://img.shields.io/badge/the-process-red?style=flat-square&logoSize=300x300&link=https%3A%2F%2Fgithub.com%2Fhafetzys%2Fwazuh-homelab-setup%2Fblob%2Fmain%2FWazuh%2520Installation%2520and%2520File%2520Integrity%2520Monitoring.pdf)


