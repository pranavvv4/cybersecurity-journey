# 📝 Linux Logs

Linux logs record system, application, authentication, and security-related events.

## Examples

View system logs:

```bash
journalctl
```

View authentication logs on Debian/Ubuntu/Kali:

```bash
cat /var/log/auth.log
```

Search logs:

```bash
grep "failed" /var/log/auth.log
```

## Characteristics

- Logs help investigate system activity
- Authentication logs record login-related events
- System logs contain operating system events
- Logs are commonly stored in `/var/log`
- `journalctl` can query systemd logs
- Useful for troubleshooting and security investigations

## Key Takeaway

**Linux logs → Provide records of system activity that can be used for troubleshooting and security analysis.**