# 🧩 VLAN

A VLAN (Virtual Local Area Network) logically divides a physical network into separate networks.

## Examples

A switch can separate devices into different VLANs:

```text
VLAN 10 → Employees
VLAN 20 → Servers
VLAN 30 → Guest Devices
```

Devices in different VLANs normally require routing to communicate:

```text
VLAN 10 → Router/Layer 3 Switch → VLAN 20
```

## Characteristics

- Creates logical network separation
- Reduces broadcast domains
- Improves network organization
- Commonly configured on managed switches
- Different VLANs require routing to communicate

## Key Takeaway

**VLAN → Logically separates one physical network into multiple networks.**