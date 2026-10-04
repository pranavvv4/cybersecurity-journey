# 🔎 Windows Security Auditing

Windows security auditing records and tracks security-related activities to help detect and investigate suspicious behavior.

## Examples

View the Security event log:

```powershell
Get-WinEvent -LogName Security
```

Look for failed logon events:

```powershell
Get-WinEvent -FilterHashtable @{LogName='Security'; Id=4625}
```

Common event IDs:

```text
4624 → Successful logon
4625 → Failed logon
4688 → New process created
4720 → User account created
```

## Characteristics

- Records security-related activities
- Helps detect suspicious authentication
- Provides useful evidence during investigations
- Uses Event IDs to identify specific events
- Security logs can be analyzed manually or through a SIEM

## Key Takeaway

**Windows Security Auditing → Records security activity for detection, investigation, and incident response.**