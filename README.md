# SIEM Lab

# Project Description

This project involves setting up a Security Information and Event Management (SIEM) system using Wazuh, an open-source security monitoring solution. The SIEM stack is deployed on a single-node Docker container and collects logs from multiple virtual machines (VMs) running Wazuh agents. The VMs are configured with deprecated software and run malicious code to simulate real-world attack scenarios. Additionally, vulnerability scans are conducted using Qualys, and the scan results are aggregated into the SIEM for comprehensive analysis.

# Objectives

- Deploy a Single Node SIEM Stack: Set up a Wazuh server on a Docker container to act as the central SIEM system.
- Deploy Wazuh Agents: Install and configure Wazuh agents on multiple VMs to monitor and collect logs.
- Simulate Attack Scenarios: Install deprecated software and execute malicious code on the VMs to generate security events.
- Vulnerability Scanning: Conduct vulnerability scans using Qualys and collect the results.
- Log Aggregation and Analysis: Aggregate logs from Wazuh agents and Qualys into the SIEM and perform data analysis to identify security incidents.
