 Lab Write-Up Junior Security Analyst Intro

**Date:** July 27, 2026

**Platform:** TryHackMe

## 1. What is a Junior SOC Analyst?
* A Junior (Tier 1) Security Analyst works within a SOC team to monitor network traffic, perform initial triage on security alerts, investigate potential threats, and assist in containing security incidents to protect the organization's infrastructure.

## 2. Key Tools & Concepts Learned
* **SIEM Dashboard & Log Analysis:** Monitored real-time event logs and identified suspicious activity (e.g., failed logins or malicious IP traffic).
    
- **Firewall Remediation / IP Blocking:** Extracted the attacker’s malicious IP address and added it to the firewall rule list to block further connection attempts and contain the threat.
* **Alert Triage:** The process of inspecting an alert to determine if it is a **True Positive** (a genuine threat requiring containment) or a **False Positive** (a benign event that can be closed).

### Key Takeaways

- **Incident Escalation & Remediation:** Learned how to identify malicious traffic from a SIEM dashboard, escalate critical findings to the SOC Manager, and immediately contain the threat by applying block rules on the firewall.
    
- **Basic Investigation Workflow:** Practiced the core Tier 1 workflow: **Detect** (monitor logs) $\rightarrow$ **Analyze** (verify malicious IP) $\rightarrow$ **Report** (notify manager) $\rightarrow$ **Remediate** (block on firewall).
