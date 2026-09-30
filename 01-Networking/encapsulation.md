# 📦 Encapsulation

Encapsulation is the process of adding information to data as it moves through the networking layers.

## Examples

When data is sent:

```text
Data → Segment → Packet → Frame → Bits
```

When data is received, the process is reversed. This is called **decapsulation**.

```text
Bits → Frame → Packet → Segment → Data
```

## Characteristics

- Each layer adds its own information
- Headers are added as data moves down the layers
- Data gets a different name at different layers
- The receiving device removes the added information

## Data Units

- Application Layer → Data
- Transport Layer → Segment
- Network Layer → Packet
- Data Link Layer → Frame
- Physical Layer → Bits

## Key Takeaway

- **Encapsulation → Adding information**
- **Decapsulation → Removing information**