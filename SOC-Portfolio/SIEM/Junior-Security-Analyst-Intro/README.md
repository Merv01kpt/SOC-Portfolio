# Junior Security Analyst Intro

## Overview

This TryHackMe room introduced the responsibilities of a Junior Security Analyst working in a Security Operations Center (SOC). The objective was to investigate security alerts, identify malicious activity, escalate the incident appropriately, and perform basic remediation.

---

## Objectives

- Review SIEM alerts
- Identify malicious activity
- Investigate suspicious IP addresses
- Escalate security incidents
- Apply firewall remediation
- Validate incident resolution

---

## Environment

Platform: TryHackMe

Lab: Junior Security Analyst Intro

Tools Used:

- SIEM Dashboard
- IP Hunter
- Incident Escalation Portal
- Firewall Console

---

## Investigation Summary

The SIEM dashboard displayed two Critical alerts involving suspicious SSH activity.

### Findings

- Malicious IP Address: **221.181.185.159**
- Attack Type: Suspicious SSH login attempts
- Port Involved: 22 (SSH)

### Actions Taken

1. Reviewed the SIEM alerts.
2. Investigated the malicious IP using IP Hunter.
3. Escalated the incident to the assigned analyst.
4. Blocked the IP address using the firewall.
5. Confirmed successful remediation.

---

## Challenges Encountered

Although this is an introductory SOC lab, it reinforced the importance of following the correct incident response workflow rather than immediately taking action.

The exercise also demonstrated that alerts should first be investigated and validated before remediation takes place.

---

## Key Lessons Learned

- SIEM alerts should be triaged according to severity.
- Multiple alerts can point to the same security incident.
- IP reputation analysis helps validate malicious activity.
- Proper escalation is an important part of the SOC workflow.
- Containment (blocking an IP) should only happen after sufficient investigation.
- Documenting each step creates an audit trail for future investigations.

---

## Skills Demonstrated

- SIEM Alert Analysis
- SOC Triage
- Incident Investigation
- IP Reputation Analysis
- Firewall Administration
- Incident Escalation
- Security Documentation
<img width="959" height="511" alt="Screenshot 2026-07-21 082116" src="https://github.com/user-attachments/assets/48ffd5ed-0821-444a-87b1-acad4e8ebfad" />
<img width="958" height="539" alt="Screenshot 2026-07-21 080432" src="https://github.com/user-attachments/assets/3db17a38-4835-4f84-b10c-d63f667562f7" />
<img width="950" height="538" alt="Screenshot 2026-07-21 080316" src="https://github.com/user-attachments/assets/e9fb69a7-352a-4a5b-828a-5f287ed73dba" />

---

## Evidence

The screenshots in this repository demonstrate:

- SIEM dashboard review
- Investigation of the malicious IP
- Successful completion of the remediation process
