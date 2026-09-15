# Enterprise Cybersecurity & SIEM Engineering Labs Hub

Welcome to my central cybersecurity engineering control hub. This repository serves as a master catalog for my production-ready deployment frameworks, advanced Threat Hunting architectures, and automated Incident Response playbooks engineered across cloud, identity, and network monitoring environments.

---

## 🚀 Specialized Technical Laboratories (Splunk SIEM Index)

Below is the verified portfolio matrix mapping distinct security disciplines to active code environments:

### 🌐 1. Edge & Network Perimeter Security
* **[Email & Phishing Analytics](../splunk-siem-email-analytics)**: Engineered a dynamic Splunk Studio dashboard mapping email delivery metrics and tracking corporate phishing vectors.
* **[Firewall Traffic Analysis](../splunk-firewall-log-analysis)**: Normalized boundary firewall logs to detect port scanning activities and map inbound traffic geolocations.
* **[Network Packet Reconnaissance](../splunk-wireshark-portscan-detection)**: Correlated Wireshark packet capture metadata inside a SIEM layer to intercept vertical network scanning footprints.

### 🔐 2. Identity & Access Management (IAM) Security
* **[Brute Force Detection Pipeline](../splunk-brute-force-detection)**: Developed automated volumetric parsing rules to flag high-frequency SSH password-spraying attacks.
* **[Active Directory Threat Hunting](../splunk-active-directory-threat-hunting)**: Designed behavioral analytics rules to isolate Kerberos token forgery anomalies (Golden Ticket attacks) aligned with CISA standards.
* **[VIP Target Threshold Protection](../splunk-soc-alert-thresholds)**: Established high-priority triage gateways to isolate credential spikes targeting privileged directory executives.

### 🛡️ 3. Host, Cloud & Advanced Application Security
* **[AWS Cloud Incident Response](../splunk-aws-incident-response)**: Built cloud security playbooks tracking compromised IAM keys and automating containment triggers.
* **[Ransomware Behavior Analysis](../splunk-ransomware-behavior-detection)**: Modeled endpoint audit events to detect mass file modification and automated process encryption patterns.
* **[OWASP Top 10 WAF Ingestion](../splunk-owasp-sqli-detection)**: Programmed custom string regex matchers within a SIEM pipeline to detect active SQL Injection (SQLi) payloads.
* **[DNS Covert Channel Detection](../splunk-dns-tunneling-detection)**: Formulated data exfiltration metrics tracking query-length anomalies to prevent malicious payload egress.

---

## 🛠️ Core Technology Stack
- **SIEM / Logging Platform**: Splunk Enterprise, Splunk Cloud, Dashboard Studio
- **Languages**: Splunk Processing Language (SPL), Markdown
- **Frameworks**: OWASP Top 10, CISA Hardening Standards, NIST Identity Guidelines
- **Network Tooling**: Wireshark, AWS CloudTrail, Windows Event Logs (ID 4624 / 4769)
