
# 🔍 MITRE ATT&CK — Practical Incident Investigation

## 📌 Scenario
Suspicious activity is detected on a Windows server.

## 🚨 Observed Behaviors
- Suspicious email attachment opened.
- Unusual PowerShell execution.
- Attempted access to LSASS memory.
- Suspicious remote access to another server.

## 🎯 Possible ATT&CK Mappings
- **Phishing:** T1566
- **PowerShell:** T1059.001
- **LSASS Memory:** T1003.001
- **Remote Services:** T1021, when supported by the evidence

## 🛡️ SOC Investigation Steps
1. Validate alerts using endpoint and system logs.
2. Investigate process trees and account activity.
3. Determine the affected assets and scope.
4. Follow incident response procedures for containment.
5. Document evidence and ATT&CK mappings.

## 🎯 Key Takeaway
Use MITRE ATT&CK to classify observed adversary behavior and guide investigations. Confirm each mapping with evidence instead of assuming an alert proves an attack.

## 📚 Official Resource
https://attack.mitre.org/
