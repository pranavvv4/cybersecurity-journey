# 🛡️ Windows Defender & Endpoint Protection

Windows Defender provides built-in protection against malware and other security threats on Windows systems.

## Examples

Check Defender status:

```powershell
Get-MpComputerStatus
```

Start a quick scan:

```powershell
Start-MpScan -ScanType QuickScan
```

Update Defender security intelligence:

```powershell
Update-MpSignature
```

## Characteristics

- Provides real-time malware protection
- Detects and removes malicious software
- Performs security scans
- Receives updated threat intelligence
- Can be managed using PowerShell
- Helps protect endpoints from common threats

## Key Takeaway

**Windows Defender → Built-in endpoint protection that detects and helps defend against malware and other threats.**