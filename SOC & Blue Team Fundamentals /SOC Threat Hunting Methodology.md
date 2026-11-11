# 🔎 SOC Threat Hunting Methodology

## Definition
Threat Hunting is a proactive security process in which SOC analysts search for hidden threats, suspicious activities, and attackers that may have bypassed existing security detection systems.

## Examples
- Searching for unusual login activity.
- Identifying suspicious PowerShell commands.
- Finding unknown processes running on endpoints.
- Detecting unauthorized privilege escalation.
- Investigating unusual outbound network connections.
- Searching for signs of malware or data exfiltration.

## Characteristics
- **Proactive Approach:** Searches for threats before alerts are generated.
- **Hypothesis-Driven:** Begins with a possible threat or suspicious activity.
- **Data Analysis:** Uses logs, endpoint telemetry, and network traffic.
- **Investigation:** Examines suspicious behavior and collects evidence.
- **Continuous Process:** Repeats hunts to discover new attack techniques.
- **Detection Improvement:** Converts confirmed findings into new detection rules.

## Important Details

### Threat Hunting Process

1. **Create a Hypothesis:** Identify a possible attacker behavior.
2. **Collect Data:** Gather endpoint, network, and authentication logs.
3. **Investigate:** Search for suspicious activities using SIEM or EDR tools.
4. **Analyze Findings:** Determine whether the activity is malicious or legitimate.
5. **Respond:** Escalate confirmed threats for incident response.
6. **Improve Detection:** Create or update detection rules based on findings.

### Types of Threat Hunting
- **Hypothesis-Based Hunting:** Starts with a specific threat assumption.
- **IOC-Based Hunting:** Searches for known malicious IP addresses, domains, or file hashes.
- **Behavior-Based Hunting:** Searches for unusual activities and attacker techniques.

## Key Takeaway
Threat Hunting helps SOC teams proactively discover hidden threats that automated security tools may have missed. It improves an organization's ability to detect and respond to attacks.