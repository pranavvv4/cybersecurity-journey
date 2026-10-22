
# 🎯 MITRE ATT&CK — Techniques and Sub-techniques

## 📌 Definition
- **Technique:** Describes HOW an attacker attempts to achieve an objective.
- **Sub-technique:** Describes a more specific method under a technique.
- **Tactic:** Describes WHY the attacker performs an action.

## 🔑 Important Techniques

| Technique | ATT&CK ID | Purpose |
|---|---|---|
| Phishing | T1566 | Attempt to gain access through phishing |
| Command and Scripting Interpreter | T1059 | Execute commands or scripts |
| OS Credential Dumping | T1003 | Attempt to obtain operating system credentials |
| Scheduled Task/Job | T1053 | Execute tasks or maintain persistence |
| Remote Services | T1021 | Access remote systems |
| Valid Accounts | T1078 | Abuse legitimate accounts |

## 🔍 Example: Suspicious PowerShell
- **Tactic:** Execution
- **Technique:** Command and Scripting Interpreter (T1059)
- **Sub-technique:** PowerShell (T1059.001), if supported by the evidence
- **Investigation:** Review process activity, command lines, user context, and related logs.

## 🎯 Key Takeaway
Map observed behavior to ATT&CK techniques only when supported by evidence. An alert or technique match alone does not prove malicious activity.

## 📚 Official Resource
https://attack.mitre.org/
