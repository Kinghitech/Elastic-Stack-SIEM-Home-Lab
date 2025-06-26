#  Elastic Stack SIEM Home Lab
> Built a home lab using the Elastic Stack (ELK) to simulate security event monitoring, log collection, and alerting in a real-world SOC environment.

## Project Duration
**Jan 2024 – Mar 2024**

## Tools & Technologies Used
- Elastic Stack (Elasticsearch, Logstash, Kibana, Beats)
- Windows 10 VM (log source)
- Ubuntu Server (ELK host)
- pfSense (simulated firewall logs)
- Sysmon, Winlogbeat
- VirtualBox / VMware Workstation

## Project Overview
This project simulates a basic SOC environment using the Elastic Stack for centralized log collection and security analytics. Logs were collected from a Windows endpoint and ingested into Elasticsearch via Logstash and Beats for monitoring and visualization in Kibana.

## Key Features / Tasks Performed
- Installed and configured Elasticsearch, Logstash, and Kibana on Ubuntu.
- Deployed Winlogbeat and Sysmon on a Windows VM to collect system logs.
- Parsed and enriched logs using Logstash pipelines.
- Created custom Kibana dashboards to visualize login attempts, process activity, and PowerShell usage.
- Developed basic alert rules to detect suspicious login patterns and privilege escalation behavior.

## Results / What I Learned
- Gained hands-on experience configuring and managing the Elastic Stack.
- Learned how to create meaningful visualizations for security events.
- Developed foundational understanding of log parsing and event correlation.
- Practiced detection engineering techniques used in real SOCs.
