# 📨 ICMP

ICMP (Internet Control Message Protocol) is used to send network error messages and diagnostic information.

## Examples

`ping` uses ICMP Echo Request and Echo Reply messages:

```text
Device A → ICMP Echo Request → Device B
Device A ← ICMP Echo Reply ← Device B
```

## Characteristics

- Works at the Internet/Network Layer
- Used for network diagnostics
- `ping` commonly uses ICMP
- Does not use TCP or UDP ports
- Can report errors such as unreachable destinations

## Key Takeaway

**ICMP → Used for network diagnostics and error reporting.**