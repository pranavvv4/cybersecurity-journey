# 📋 Windows Event Logs

Windows Event Logs record system, application, security, and other events that occur on a Windows system.

## Examples

Open Event Viewer:

```text
Win + R → eventvwr.msc
```

View event logs using PowerShell:

```powershell
Get-WinEvent -LogName Security
```

Find recent failed logons:

```powershell
Get-WinEvent -FilterHashtable @{LogName='Security'; Id=4625}
```

## Characteristics

- **Security Log** → Authentication and security events
- **System Log** → Operating system and service events
- **Application Log** → Application-related events
- Events contain information such as time, event ID, and details
- Useful for troubleshooting and security investigations

## Key Takeaway

**Windows Event Logs → Records system and security activity that can be analyzed during investigations.**