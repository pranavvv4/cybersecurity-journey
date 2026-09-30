# 🛡️ Linux Security Hardening

Linux hardening is the process of reducing unnecessary security risks by securing system configuration, services, accounts, and access.

## Examples

Check listening services:

```bash
ss -tuln
```

Check SSH configuration:

```bash
sudo nano /etc/ssh/sshd_config
```

Update installed packages:

```bash
sudo apt update
sudo apt upgrade
```

## Characteristics

- Disable unnecessary services
- Keep the operating system and software updated
- Use strong authentication
- Apply least-privilege permissions
- Restrict unnecessary network access
- Monitor system and authentication logs
- Secure SSH configuration

## Key Takeaway

**Linux Hardening → Reduce the attack surface and strengthen system security.**