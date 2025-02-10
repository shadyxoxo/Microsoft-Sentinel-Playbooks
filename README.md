# Microsoft-Sentinel-Playbooks

## Objective
The Microsoft-Sentinel-Playbooks project was designed to establish a controlled Microsoft Azure environment for simulating, detecting, and responding to cyberattacks. The primary focus was to deploy a honeypot using Cowrie to attract and log attacker activities, revealing their Tactics, Techniques, and Procedures (TTPs). These logs were then ingested into Microsoft Sentinel (SIEM) for analysis, correlation, and detection of malicious behaviors.Additionally, Sentinel Playbooks were developed using Azure Logic Apps to automate incident response workflows, demonstrating how security teams can proactively defend against threats in cloud environments. This hands-on project provided in-depth exposure to cloud security, network defense strategies, and automated threat detection.

### Skills Learned
- Microsoft Sentinel SIEM Operations – Hands-on experience with log ingestion, rule creation, and incident analysis in a cloud-native SIEM.
- Honeypot Deployment and Management – Configuring and operating Cowrie to capture attacker interactions and analyze attack patterns.
- Threat Detection and Analysis – Understanding attacker behavior by interpreting logs and identifying TTPs.
- Security Automation and Orchestration – Developing Sentinel Playbooks using Azure Logic Apps to automate security responses.
- Threat Intelligence Integration – Enriching security alerts with external sources like Microsoft Threat Intelligence, VirusTotal, and AbuseIPDB.
- Log Ingestion and Correlation – Configuring Sentinel data connectors to ingest logs from honeypots, cloud workloads, and network devices.
- Cloud Security and Azure Services – Enhancing security posture within Microsoft Azure through best practices and monitoring.
- Incident Response and Investigation – Developing workflows for detecting, triaging, and mitigating security incidents.
- SIEM Dashboarding & Visualization – Creating custom workbooks and dashboards for real-time security monitoring.
- Network Traffic Analysis – Using tools like Wireshark to validate attacks and gain deeper insights into network activity.
- MITRE ATT&CK Mapping – Aligning detected attack behaviors with known adversarial tactics and techniques.
- Scripting and Automation – Utilizing PowerShell and Python for log parsing, data enrichment, and API integrations.

### Tools Used
- Microsoft Sentinel – Cloud-native SIEM for log correlation, detection, and response.
- Cowrie – SSH/Telnet honeypot for capturing attacker interactions.
- Azure Logic Apps – Automating security playbooks for incident response.
- Azure Monitor & Log Analytics – Querying logs, setting alerts, and visualizing security events.
- Threat Intelligence Feeds – Integrated external sources (Microsoft Threat Intelligence, VirusTotal, AbuseIPDB) for enhanced detection.
- PowerShell & Python – Used for automation, data enrichment, and custom log analysis.
- SIEM Data Connectors – Configured for ingesting logs from multiple sources, including honeypots and cloud workloads.
- Security Workbooks & Dashboards – Created real-time visualizations for tracking security trends.
- Azure Virtual Machines – Hosted honeypots and test environments in a controlled Azure setup.
- MITRE ATT&CK Framework – Used to categorize and map detected threats to known TTPs.
- Wireshark & Network Analysis Tools – Examined network traffic and attacker activity targeting the honeypot.

## Steps
*Ref 1: Network Diagram*
