
# 🎯 MITRE ATT&CK — Enterprise Tactics

## 📌 Definition
Tactics represent an adversary's objectives — the WHY behind their actions.

## 🔑 The 14 Enterprise Tactics

1. **Reconnaissance (TA0043):** Gather information about a target.
2. **Resource Development (TA0042):** Prepare resources for an attack.
3. **Initial Access (TA0001):** Gain an initial foothold.
4. **Execution (TA0002):** Run malicious commands or code.
5. **Persistence (TA0003):** Maintain access to a compromised environment.
6. **Privilege Escalation (TA0004):** Obtain higher-level permissions.
7. **Defense Evasion (TA0005):** Avoid or bypass security defenses.
8. **Credential Access (TA0006):** Obtain credentials or authentication material.
9. **Discovery (TA0007):** Learn about systems, accounts, and resources.
10. **Lateral Movement (TA0008):** Move between compromised systems.
11. **Collection (TA0009):** Gather data of interest.
12. **Command and Control (TA0011):** Communicate with compromised systems.
13. **Exfiltration (TA0010):** Transfer data out of the target environment.
14. **Impact (TA0040):** Disrupt operations or damage data and systems.

## 🔍 SOC Example
- Suspicious PowerShell execution → Execution
- Credential dumping → Credential Access
- Accessing another server → Lateral Movement
- Uploading confidential files → Exfiltration

## 🎯 Key Takeaway
MITRE ATT&CK tactics help SOC analysts classify adversary objectives, investigate suspicious behavior, and improve security detections.

**Note:** Tactics are not a mandatory attack sequence.

## 📚 Official Resource
https://attack.mitre.org/
