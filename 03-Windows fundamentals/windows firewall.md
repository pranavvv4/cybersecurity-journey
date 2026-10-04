# 🧱 Windows Firewall

Windows Firewall is a host-based firewall that monitors and controls network traffic to and from a Windows system.

## Examples

View firewall profiles:

```powershell
Get-NetFirewallProfile
```

View firewall rules:

```powershell
Get-NetFirewallRule
```

Enable the firewall:

```powershell
Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled True
```

## Characteristics

- Controls inbound and outbound network traffic
- Uses firewall rules to allow or block connections
- Supports Domain, Private, and Public network profiles
- Helps reduce unauthorized network access
- Can be managed through PowerShell or Windows Defender Firewall

## Key Takeaway

**Windows Firewall → Controls network traffic entering and leaving a Windows system.**