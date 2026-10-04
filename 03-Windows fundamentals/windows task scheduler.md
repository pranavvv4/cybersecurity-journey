# 🧰 Windows Task Scheduler

Task Scheduler is a Windows feature that automatically runs programs, scripts, or tasks based on defined triggers.

## Examples

Open Task Scheduler:

```text
Win + R → taskschd.msc
```

View scheduled tasks using PowerShell:

```powershell
Get-ScheduledTask
```

## Characteristics

- Runs tasks automatically
- Tasks can be triggered by time, startup, login, or other events
- Can execute programs and scripts
- Commonly used for system maintenance and automation
- Suspicious scheduled tasks can be investigated during security analysis

## Key Takeaway

**Task Scheduler → Automatically executes programs or scripts based on defined triggers.**