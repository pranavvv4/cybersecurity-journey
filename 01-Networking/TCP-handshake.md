# 🔗 TCP Handshake

The TCP three-way handshake is the process used to establish a TCP connection between two devices.

## Examples

The connection is established using three messages:

```text
Client → SYN → Server
Client ← SYN-ACK ← Server
Client → ACK → Server
```

After the handshake, data can be transmitted.

## Characteristics

- Uses TCP
- Establishes a reliable connection
- Uses `SYN`, `SYN-ACK`, and `ACK`
- Synchronizes sequence numbers
- Happens before TCP data transmission

## Key Takeaway

**TCP Three-Way Handshake → SYN → SYN-ACK → ACK → Connection established.**