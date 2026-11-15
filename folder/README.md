# Sentinel SOC Home Lab
During my MyFirstHack Security internship, I created a home SOC Lab in Microsoft Azure to gain an insight into building a functioning SIEM pipeline: from generating real endpoint telemetry, to running detections with live data.

## Tools
- Azure VM
- Azure Monitor Agent
- Log Analytics
- Microsoft Sentinel
- Sysmon

## What I actually learned:
- How data travels through an endpoint to a SIEM; from the Monitor Agent with a Collection Rule, landing in the Log Analytics Workspace.
- Why Windows logging isn't enough for this and what Sysmon offers instead.
- Writing KQL Queries to filter events from the raw logs of data. The queries I used can be found in "/queries".
- Running commands on the VM to trace back through the logs to prove the Lab was successful.
