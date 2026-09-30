# 🧠 Stateful vs Stateless

Stateful and stateless describe whether a network device or protocol keeps track of previous connections or requests.

## Examples

**Stateful:**

```text
Client → Firewall → Server
          ↓
     Connection State
```

**Stateless:**

```text
Request 1 → Checked independently
Request 2 → Checked independently
```

## Characteristics

- **Stateful** → Tracks connection or session information
- **Stateless** → Treats each packet/request independently
- Stateful firewalls can track TCP connections
- Stateless filtering mainly checks individual packets against rules

## Key Takeaway

**Stateful → Remembers connection state.**  
**Stateless → Handles each request or packet independently.**