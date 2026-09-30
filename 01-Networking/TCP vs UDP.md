# 🔄 TCP vs UDP

TCP and UDP are **Transport Layer (Layer 4)** protocols.

## TCP

**TCP (Transmission Control Protocol)** is connection-oriented and provides reliable communication.

### Examples

- HTTP/HTTPS
- SSH
- FTP
- Telnet

### Characteristics

- Connection-oriented
- Reliable delivery
- Data arrives in order
- Uses acknowledgements
- Retransmits lost data

---

## UDP

**UDP (User Datagram Protocol)** is connectionless and does not guarantee delivery.

### Examples

- DNS
- DHCP
- VoIP
- Online gaming

### Characteristics

- Connectionless
- Faster and lightweight
- No delivery guarantee
- No ordering guarantee
- No retransmission

---

## TCP vs UDP

| Feature | TCP | UDP |
|---|---|---|
| Connection | Connection-oriented | Connectionless |
| Reliability | Reliable | No guarantee |
| Ordering | Yes | No guarantee |
| Retransmission | Yes | No |
| Overhead | Higher | Lower |

## Key Takeaway

**TCP = Reliable and connection-oriented**

**UDP = Fast and connectionless**