# splunk-soc-l1-incident-investigation
SOC L1 incident investigation using Splunk, authentication log analysis, detection queries, and security monitoring dashboard.
Overview
SOC L1 investigation project using **Splunk Enterprise** to analyze authentication logs, detect suspicious login activity, and monitor security events.

Tools
- Splunk Enterprise
- SPL
- Authentication Logs
- SIEM / SOC Investigation

Investigation
- Ingested authentication logs into Splunk
- Analyzed successful and failed logins
- Identified suspicious source IPs
- Investigated repeated failed login attempts
- Correlated login activity with privilege escalation
- Created a SOC monitoring dashboard

 Key Finding
Multiple failed login attempts were identified from:

`185.220.**.**`

The activity was followed by a successful `admin` login and a `PRIVILEGE_ESCALATION` event, making the sequence suspicious.
