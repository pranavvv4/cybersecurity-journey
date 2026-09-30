# 🛣️ Routing

Routing is the process of determining the path that network traffic takes from a source to a destination.

## Examples

A router can forward traffic between networks:

```text
192.168.1.10 → Router → 10.0.0.20
```

A routing table contains information about available network paths.

```bash
ip route
```

## Characteristics

- Routers use routing tables
- Determines where packets should be forwarded
- Works at the Network Layer
- Uses destination IP addresses
- Can connect different networks

## Key Takeaway

**Routing → Determines where packets should go to reach their destination.**