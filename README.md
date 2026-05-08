</> Markdown

# Splunk Failed Login Dashboard

## Overview
This project demonstrates the creation of a cybersecurity monitoring dashboard in Splunk focused on analyzing Windows failed authentication events (Event ID 4625). The dashboard was built using manually generated Windows failed login attempts collected through Event Viewer and imported into Splunk for SIEM-based monitoring and analysis. 

The purpose of this project is to simulate basic SOC (Security Operations Center) monitoring workflows by visualizing authentication failures, tracking suspicious login behavior, and creating security-focused reporting panels.

---

# Objectives
- Generate Windows failed login events using Events Viewer
- Export and ingest Windows security logs into Splunk
- Analyze authentication failures using SPL (Search Processing Language)
- Create visual dashboard panels for security monitoring
- Simulate SIEM-based detection and reporting workflows

---

# Technologies Used
- Splunk Enterprise
- Windows Event Viewer
- SPL
- Windows Security Logs
- Event ID 4625

---

# Dashboard Features 

## Failed Login Activity Monitoring
A visualization panel used to track failed login attempts over time and identify spikes in authentication failures.

## Statistical Reporting
Statistical tables displaying authentication failure date, event aggregation, and monitoring metrics for suspicious login activity.

## Single Value Metrics 
A KPI-style panel displaying the total number of failed login attempts detected in the imported logs.

## Detailed Event Reporting
A report table containing detailed authentication failure events used for investigation and security analysis.

---

## Event ID 4625
Event ID 4625 is a Windows Security event generated when a user authentication attempt fails. These events are commonly monitored in SOC environment to identify:
- Failed authentication attempts
- Potential brute-force attacks
- Unauthorized access attempts
- Suspicious login activity

---

# Log Generation Process
Failed login events were manually generated in a Windows environment by performing repeated unsuccessful authentication attempts. The generated security events were filtered within Event Viewer and exported for ingestion into Splunk.

---

# Screenshots

## Event Viewer Failed Login Events 
![Event Viewer Failed Login Events](screenshots/event_viewer_failed_login.png)

## Statistical Report Panel
![Statistical Report Panel](screenshots/top_daily_failed_logins_NamingFields.png)

## Single Numeric Value Panel
![Single Numeric Value Panel](screenshots/single_value_metric.png)

## Final Dashboard
![Final Dashboard](screenshots/final_dashboard.png)

## Final Dashboard Five Panels
![Final Dashboard Five Panels](screenshots/final_completed_dashboard.png)

---

# Skills Demonstrated
- SIEM dashboard creation
- Log ingestion and parsing
- Windows authentication monitoring
- SPL query development
- Cybersecurity event analysis
- Dashboard visualization
- Security reporting and investigation

---

# Future Improvements 
- Add brute-force detection logic
- Implement authentication anomaly detection
- Expand dashboard with aditional Windows security events
- Integrate alerting functionality
- Add geographic login analysis

---

# Author 
Cybersecurity and SIEM portofolio project created for hands-on Splunk practice and security monitoring experience. 
