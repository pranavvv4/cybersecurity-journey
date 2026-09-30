# 📦 TCP Segmentation

TCP segmentation is the process of dividing application data into smaller segments before transmission.

## Examples

Large data can be divided into multiple TCP segments:

```text
Application Data
       ↓
TCP Segments
       ↓
Network Packets
       ↓
Destination
```

## Characteristics

- TCP divides data into smaller segments
- Each segment contains a TCP header
- Sequence numbers help maintain the correct order
- Lost segments can be retransmitted
- The receiver reassembles the data

## Key Takeaway

**TCP Segmentation → Dividing large data into smaller TCP segments for reliable transmission.**