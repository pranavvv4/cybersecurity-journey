# ⏰ Cron & Scheduled Tasks

Cron is a Linux service used to automatically run commands or scripts at scheduled times.

## Examples

View scheduled tasks:

```bash
crontab -l
```

Edit scheduled tasks:

```bash
crontab -e
```

Example:

```text
0 2 * * * /home/user/backup.sh
```

This runs the script every day at **2:00 AM**.

## Characteristics

- Automates recurring tasks
- Uses `crontab` to define schedules
- Can run commands or scripts
- Commonly used for backups, maintenance, and monitoring
- Misconfigured cron jobs can create security risks

## Key Takeaway

**Cron → Automatically runs commands or scripts according to a schedule.**