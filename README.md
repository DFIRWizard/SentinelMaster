🛡️ Cloud DFIR & Threat Hunting Repository
Microsoft Sentinel • Azure • Microsoft 365 • Defender XDR • DFIR Playbooks & Artifacts
Welcome to my Cloud DFIR (Digital Forensics & Incident Response) and Threat Hunting repository.
This project focuses on everything related to modern cloud security operations, with an emphasis on the Microsoft ecosystem—including Sentinel, Defender XDR, Azure, and Microsoft 365.
This repo is designed for security analysts, detection engineers, and SOC teams looking for practical, real‑world artifacts, including hunting queries, JSON workbooks, notebook configs, and automation examples.

🔍 What You’ll Find Here
🕵️ Threat Hunting Queries (KQL)
A curated collection of Microsoft Sentinel/Defender KQL queries for:

Credential access
Persistence & backdoors
Lateral movement
Cloud identity abuse
OAuth / consent phishing
Malware investigations
M365 & Entra ID activity
Endpoint telemetry analysis
Network anomaly detection
Suspicious Azure resource operations

Queries are tagged for easy filtering by MITRE ATT&CK, data source, and purpose.

📊 Microsoft Sentinel Workbooks (JSON)
Pre‑built and fully customizable JSON templates for:

DFIR dashboards
Identity threat monitoring
Email security investigation
Endpoint visibility
Cloud resource changes
Authentication analytics
High‑fidelity SOC triage views

Each workbook includes:

Parameters
KQL query blocks
Visualizations
Metadata
Version history


📓 Sentinel Notebooks (Azure ML / KQL + PySpark)
Notebook templates for:

Automated triage
Log parsing at scale
Cross‑table correlation
IOC/IOA enrichment
OSINT integration
ML‑assisted anomaly detection
Threat intel ingestion & correlation

Includes exported .ipynb files and JSON configurations for:

Environment setup
Data sources
AI enrichment steps


🔧 SOAR / Automation Artifacts
Logic Apps & automation assets such as:

Incident enrichment playbooks
Alert-to-ticket workflows
User notification workflows
File hashing, sandboxing, and triage automations
Access review/justification prompts
Defender API call templates
Sentinel alert grouping patterns


🛡️ Microsoft Defender XDR Artifacts
Configurations and scripts for:

Detections & custom rules
API queries
Device inventory automation
Kusto-based correlation queries
URL/file reputation checks
Endpoint forensics helper scripts


📁 Additional DFIR Resources
This repo also contains:

Memory/endpoint triage cheat sheets
Evidence collection scripts
IR flowcharts
Artifact parsing helpers (PowerShell/Python)
Forensic indicators & common threat patterns


🏗️ Roadmap
Planned additions:

More advanced AI-driven hunting notebooks
Workbook gallery with screenshots
Automated IOC ingestion pipelines
Full DFIR case studies
Detection-as-code examples (Infrastructure-as-Code for Sentinel analytics rules)


🤝 Contributing
Contributions are welcome.
If you have:

Better queries
Useful dashboards
IR tooling
Cloud forensics enhancements

…feel free to submit a PR.


