# Wazuh Detection Engineering Lab

## Objective
Built and tuned three custom Wazuh detection rules using Sysmon telemtry and Atomic Red Team. Each rule included a broad/basic version to expose false positives and a tuned version to improve detection accuracy.

## MITRE ATT&CK Techniques

| Technique | Detection |
| --- | --- |
| T1087.001 | PowerShell Execution |
| T1053.005 | Scheduled Task Persistence |
| T1059.001 | Local Account Discovery |

## Detection Engineering Process
- Simulated adversary behavior with Atomic Red Team.
- Analyzed 'image', 'commandLine', 'parentImage', 'parentCommandLine', and execution context in Wazuh.
- Created broad detection rules and tested them against legitimate administrative activity.
- Tuned rules with PCRE2 and behavioral context to reduce false positives while perserving malicious detection.

## Skills Demonstrated
- Wazuh custom rule development
- Sysmon telemetry analysis
- PCRE2 regular expressions
- MITRE ATT&CK mapping
- False-positive tuning
- Process and command-Line analysis
- Atomic Red Team testing
- Detection validation

## Key Takeway
A command or executable alone is rarely enough to identify malicious behavior. Reliable detection requires combining process, command-line, execution context, and legitimate-use testing.

