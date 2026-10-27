# 📋 Log Sources & Windows Event IDs

Log sources record activity from operating systems, applications, networks, and security tools. SOC analysts examine these logs to investigate suspicious behavior and security incidents.

## Examples

Common log sources:

```text
Windows → Security & System Event Logs
Linux   → Authentication & System Logs
Firewall → Allowed & Blocked Traffic
EDR     → Endpoint Activity & Threat Alerts
DNS     → Domain Lookup Activity
Cloud   → Login, API & Resource Activity
```

Important Windows Security Event IDs:

| Event ID | Meaning |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4688 | New process created |
| 4720 | User account created |
| 4728 | Member added to a security-enabled global group |
| 4732 | Member added to a security-enabled local group |
| 1102 | Security audit log cleared |

## Characteristics

- **Log Sources** → Provide evidence of system and user activity
- **Event IDs** → Identify specific types of Windows events
- **Authentication Logs** → Help investigate successful and failed logins
- **Process Logs** → Help identify suspicious program execution
- **Account Management Logs** → Reveal user or group changes
- **Log Clearing** → May be suspicious and should be investigated in context
- Some events require the appropriate Windows audit policy to be enabled

## Key Takeaway

**Log Sources → Show what happened.**

**Windows Event IDs → Help identify and investigate specific security activities.**