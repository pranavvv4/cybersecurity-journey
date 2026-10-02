# 🌐 Windows Networking

Windows provides built-in tools to view network configuration, test connectivity, inspect connections, and troubleshoot network issues.

## Examples

View IP configuration:

```powershell
ipconfig
```

Test connectivity:

```powershell
ping <TARGET_IP>
```

View network connections and listening ports:

```powershell
netstat -ano
```

View detailed network configuration:

```powershell
Get-NetIPConfiguration
```

View the routing table:

```powershell
route print
```

## Characteristics

- `ipconfig` → Shows IP configuration
- `ping` → Tests network connectivity
- `netstat` → Shows connections and listening ports
- `Get-NetIPConfiguration` → Shows detailed network configuration
- `route print` → Shows routing information
- Useful for troubleshooting and security investigations

## Key Takeaway

**Windows Networking → Use built-in tools to inspect, test, and troubleshoot network communication.**