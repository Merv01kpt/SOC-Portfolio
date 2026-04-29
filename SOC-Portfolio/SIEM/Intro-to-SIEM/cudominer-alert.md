# SIEM Alert Investigation – Suspicious Process (cudominer.exe)

## 1. Alert Overview
- **Alert Trigger:** Suspicious process detected
- **Process Name:** cudominer.exe

## 2. Investigation Steps
- Opened the SIEM alert dashboard
- Identified highlighted process flagged in red (cudominer.exe)
- Reviewed event logs associated with the alert
- Observed multiple processes (python, QuickTime, cudominer.exe)
- Located the relevant event entry
- Identified the associated user from the event details

## 3. Findings
- **Suspicious Process:** cudominer.exe
- **User:** Chris
- **Other Processes Observed:** python, QuickTime

## 4. Analysis
- The process cudominer.exe is commonly associated with cryptocurrency mining malware
- It's execution may indicate unauthorized use of system resources
- The presence of this process suggests a potential security compromise or misuse of the endpoint

## 5. Conclusion
- The alert was triggered by cudominer.exe
- The activity is associated with user Chris
- Further investigation is required to determine if the process is malicious
![Alert Screenshot] (images/alert.png)
![Event Log] (images/event.png)
