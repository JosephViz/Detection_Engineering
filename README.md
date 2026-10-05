# Detection_Engineering

## Objective
Built a Windows endpoint detection lab using Sysmon and Wazuh to detect suspicious PowerShell command-line activity and tune alerts to reduce false positives.<b/>

## Lab Environment
- Wazuh Server: Ubuntu
- Endpoint: Windows 10/11 with Wazuh Agent
- Logging Source: Sysmon
- Detection Platform: Wazuh
- Framework: MITRE ATT&CK

## Detection Focus
- Suspicious PowerShell execution
- Command-line behavior
- False positive tuning
- MITRE ATT&CK mapping

### Skills Learned
- Created and tuned custom Wazuh detection rules for Windows endpoint activity using Sysmon logs.
- Mapped detections to MITRE ATT&CK techniques, including Command and Scripting Interpreter, Account Discovery, Valid Account, and LSASS Memory access.
- Tuned detection logic to reduce false positives while preserving alers for realistic malicious activity.
- Practiced SOC analyst workflow: Collect logs, create detection, test alert, tune rule, document findings.


## SOC-focused questions answered behind each engineered rule:
1. What specific attacker behavior is this rule designed to detect?
2. What legitimate administrative or system activity could cause a false positive?
3. What log evidence confirms this alert should be investigated?
