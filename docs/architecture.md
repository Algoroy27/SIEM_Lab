
# Key Components

Docker Host (Single Node SIEM Stack):

Wazuh Server: The core component that collects and analyzes logs.
Wazuh Manager: Manages communication and data collection from agents on various VMs.
VMs (Virtual Machines):

Wazuh Agents: Installed on multiple VMs to monitor and send logs to the Wazuh server.
Deprecated Software and Malicious Code: These VMs will run deprecated software and malicious code for testing and analysis purposes.

Vulnerability Scanning Tool (Qualys):
Scans the VMs for vulnerabilities and sends logs to the Wazuh server for aggregation and analysis.
Diagram Explanation
Docker Host: The Docker host runs the Wazuh server and manager, forming the central SIEM stack. It collects and processes logs from the Wazuh agents installed on the VMs.
VMs: Each VM has a Wazuh agent that sends logs to the Wazuh server. The VMs will also run deprecated software and malicious code to generate logs for analysis.

Qualys: This external vulnerability scanning tool scans the VMs and sends the scan results to the Wazuh server for aggregation and analysis.
This architecture ensures centralized log collection and analysis using the Wazuh SIEM, with VMs simulating a realistic environment where deprecated software and malicious code can be tested and analyzed
