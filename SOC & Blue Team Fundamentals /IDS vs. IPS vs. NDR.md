# 🛡️ IDS vs. IPS vs. NDR

IDS, IPS, and NDR are security technologies used to detect or prevent suspicious activity on networks.

## Examples

```text
Network Traffic
      ↓
IDS → Detects suspicious activity and generates alerts
IPS → Detects and can block malicious traffic
NDR → Analyzes network activity to detect threats
```

Common examples:

- **IDS** → Suricata in IDS mode
- **IPS** → Suricata in IPS mode
- **NDR** → Network Detection and Response platforms that analyze network traffic and behavior

## Characteristics

- **IDS (Intrusion Detection System)** → Monitors traffic and alerts on suspicious activity; normally does not block traffic inline
- **IPS (Intrusion Prevention System)** → Can block or drop malicious traffic, often inline
- **NDR (Network Detection and Response)** → Uses network traffic analysis and behavioral detection to identify threats and support investigation
- IDS and IPS can use signatures and detection rules
- NDR can help detect unusual communication, lateral movement, and command-and-control activity
- These technologies can provide alerts to a SIEM for centralized monitoring

## Key Takeaway

**IDS → Detects.**

**IPS → Detects and can prevent.**

**NDR → Analyzes network activity to detect and investigate threats.**