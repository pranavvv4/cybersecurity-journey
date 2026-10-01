# ⚙️ Windows Processes & Services

A process is a running program, while a service is a background program that provides system or application functionality.

## Examples

View running processes:

```powershell
Get-Process
```

View services:

```powershell
Get-Service
```

View a specific process:

```powershell
Get-Process -Name explorer
```

Stop a process:

```powershell
Stop-Process -Name notepad
```

## Characteristics

- Processes are running instances of programs
- Each process has a Process ID (PID)
- Services usually run in the background
- Services can start automatically with Windows
- PowerShell can monitor and manage processes and services
- Unexpected processes or services can be investigated during security analysis

## Key Takeaway

**Processes → Running programs.**  
**Services → Background programs that provide system functionality.**