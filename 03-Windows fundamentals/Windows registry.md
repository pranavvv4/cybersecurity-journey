# 🧾 Windows Registry

The Windows Registry is a hierarchical database that stores configuration settings for Windows, users, applications, and hardware.

## Examples

Open Registry Editor:

```text
Win + R → regedit
```

View a registry key using PowerShell:

```powershell
Get-Item "HKLM:\SOFTWARE"
```

## Characteristics

- Stores Windows and application configuration
- Contains keys, subkeys, and values
- `HKLM` → System-wide settings
- `HKCU` → Current user's settings
- Applications can create and modify registry entries
- Incorrect registry changes can affect system stability

## Key Takeaway

**Windows Registry → Stores configuration information used by Windows and applications.**