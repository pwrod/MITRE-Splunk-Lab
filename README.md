# 🛡️Azure Splunk SOC Lab
Built a cloud-based SOC lab in Microsoft Azure using Splunk Enterprise, Sysmon, Atomic Red Team, and Tines to simulate attacker techniques, generate detections, automate alerting workflows, and visualize telemetry using MITRE ATT&CK-aligned dashboards.

---

# 📃Objectives

- Build a realistic SOC environment in Azure
- Ingest Windows telemetry into Splunk
- Simulate attacks using Atomic Red Team
- Create ATT&CK-mapped detections
- Build Splunk dashboards and reports
- Automate alert workflows using Tines and Slack

---

# ⚙️Technologies Used

- Microsoft Azure
- Splunk Enterprise
- Sysmon
- Splunk Universal Forwarder
- Atomic Red Team
- Tines
- Slack
- Windows 11 (Victim VM)
- Ubuntu (Splunk Host)

---

# ⚠️MITRE ATT&CK Techniques Simulated

| Technique | Description              |
| --------- | ------------------------ |
| T1059.001 | PowerShell               |
| T1053.005 | Scheduled Tasks          |
| T1003.001 | LSASS Credential Dumping |
| T1071     | Command & Control        |

---

# ✅Lessons Learned

This project strengthened my hands-on experience with SIEM administration, detection engineering, MITRE ATT&CK mapping, and security automation. Through building an Azure-based SOC lab with Splunk, Sysmon, Atomic Red Team, and Tines, I gained practical experience analyzing endpoint telemetry, creating detections, automating alert workflows, and visualizing security events in a cloud environment.

---

# 🖼️Lab Images

Screenshots and visual documentation of the lab environment, Splunk dashboards, detections, automation workflows, and Azure infrastructure can be found in the [`lab-images`](./lab-images) folder.

---

# 🛠️SPL Queries

Custom Splunk SPL queries used for detections, dashboards, reports, and threat hunting can be found in the [`spl-queries`](./spl-queries) folder.


# 🖇️References

- MITRE ATT&CK Framework  
  https://attack.mitre.org/
- Splunk Enterprise Documentation  
  https://docs.splunk.com/Documentation/Splunk
- Microsoft Azure Documentation  
  https://learn.microsoft.com/en-us/azure/
- Sysmon Documentation  
  https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon
- SwiftOnSecurity Sysmon Configuration  
  https://github.com/SwiftOnSecurity/sysmon-config
- Atomic Red Team  
  https://github.com/redcanaryco/atomic-red-team
- Splunk Universal Forwarder Documentation  
  https://docs.splunk.com/Documentation/Forwarder
- Tines Documentation  
  https://www.tines.com/docs/
