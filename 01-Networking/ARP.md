# 🧭 ARP

ARP (Address Resolution Protocol) is used to find the MAC address associated with an IPv4 address on a local network.

## Examples

A device wants to communicate with:

```text
IP: 192.168.1.20
```

It uses ARP to discover:

```text
192.168.1.20 → AA:BB:CC:DD:EE:FF
```

Common command:

```bash
arp -a
```

## Characteristics

- Works with IPv4
- Maps IP addresses to MAC addresses
- Used mainly on local networks
- Uses ARP requests and replies
- ARP information is stored in an ARP cache

## Key Takeaway

**ARP → Finds the MAC address associated with an IPv4 address on a local network.**