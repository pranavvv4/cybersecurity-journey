# 🌐 Linux Networking Commands

Linux provides commands to view network interfaces, connections, routes, and connectivity.

## Examples

View IP addresses and interfaces:

```bash
ip addr
```

View routing table:

```bash
ip route
```

Test connectivity:

```bash
ping <TARGET_IP>
```

View listening ports:

```bash
ss -tuln
```

Test DNS resolution:

```bash
nslookup example.com
```

## Characteristics

- `ip addr` → Shows network interfaces and IP addresses
- `ip route` → Shows routing information
- `ping` → Tests connectivity
- `ss` → Shows network connections and listening ports
- `nslookup` → Queries DNS information
- Useful for network troubleshooting and security analysis

## Key Takeaway

**Linux networking commands → Help inspect, test, and troubleshoot network communication.**