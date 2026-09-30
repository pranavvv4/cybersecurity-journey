# 🌐 CIDR and Subnetting

CIDR (Classless Inter-Domain Routing) is a method of representing IP networks using a prefix length.

## Examples

```text
192.168.1.0/24
```

The `/24` means **24 bits are used for the network portion**.

## Characteristics

- Written using `/number` notation
- The number represents network bits
- A smaller prefix generally means a larger network
- A larger prefix generally means a smaller network
- Helps divide networks into smaller subnets

## Common Prefixes

- `/8` → 16,777,216 total addresses
- `/16` → 65,536 total addresses
- `/24` → 256 total addresses
- `/30` → 4 total addresses

## Key Takeaway

**CIDR `/number` = number of network bits in an IP address.**