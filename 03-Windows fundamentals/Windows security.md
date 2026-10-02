# 🔐 Windows Security

Windows provides built-in security features to protect users, systems, applications, and network resources.

## Examples

Check Windows Defender status:

```powershell
Get-MpComputerStatus
```

View Windows Firewall profiles:

```powershell
Get-NetFirewallProfile
```

View local security-related information:

```powershell
Get-LocalUser
```

## Characteristics

- Windows Defender provides malware protection
- Windows Firewall controls network traffic
- User Account Control (UAC) helps prevent unauthorized system changes
- NTFS permissions control access to files and folders
- Security logs record authentication and other security events
- Least privilege reduces unnecessary administrative access

## Key Takeaway

**Windows Security → Uses authentication, access control, firewall, malware protection, and logging to protect the system.**