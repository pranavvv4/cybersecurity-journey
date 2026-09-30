# ⚙️ Linux Processes & Services

A process is a running program, while a service is a background program that provides a specific function.

## Examples

View running processes:

```bash
ps aux
```

Monitor processes:

```bash
top
```

View a service:

```bash
systemctl status ssh
```

Start a service:

```bash
sudo systemctl start ssh
```

## Characteristics

- Processes are running instances of programs
- Each process has a Process ID (PID)
- Services commonly run in the background
- `ps` and `top` help monitor processes
- `systemctl` manages services
- Processes can be started, stopped, or terminated

## Key Takeaway

**Processes → Running programs.**  
**Services → Background programs that provide system functions.**