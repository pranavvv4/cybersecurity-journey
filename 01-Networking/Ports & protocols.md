# 🔌 Ports and Protocols

A **protocol** is a set of rules that devices use to communicate over a network.

A **port** is a logical number used to identify a specific service or application on a device.

## Examples

Some common protocols and their ports:

| Protocol | Port | Purpose |
|---|---:|---|
| HTTP | 80 | Web traffic |
| HTTPS | 443 | Secure web traffic |
| SSH | 22 | Secure remote access |
| FTP | 21 | File transfer |
| Telnet | 23 | Remote access |
| DNS | 53 | Domain name resolution |
| DHCP | 67/68 | Automatic IP configuration |

## Characteristics

### Ports

- Range from `0` to `65535`
- Identify network services
- TCP and UDP have separate port numbers
- Well-known ports are `0–1023`

### Protocols

- Define how devices communicate
- Different protocols serve different purposes
- Can operate over TCP or UDP

## Example

When accessing a website using HTTPS:

```text
Your Computer
     ↓
TCP Port 443
     ↓
Web Server