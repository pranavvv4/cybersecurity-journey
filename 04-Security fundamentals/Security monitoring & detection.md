# 🔍 Security Monitoring & Detection

Security monitoring is the continuous observation of systems, networks, and logs to identify suspicious activity and potential security incidents.

## Examples

```text
Windows Logs ──┐
Linux Logs ────┼──→ SIEM → Alerts → Investigation
Network Logs ──┘
```

Common monitoring tools:

- SIEM → Wazuh, Splunk, Microsoft Sentinel
- Network analysis → Wireshark
- Endpoint monitoring → Sysmon
- Intrusion detection → Suricata

## Characteristics

- Collects logs and security events from multiple sources
- Detects suspicious patterns and unusual activity
- Generates alerts for investigation
- Uses detection rules, analytics, and threat intelligence
- Requires investigation to distinguish genuine threats from false positives
- Supports incident response

## Key Takeaway

**Security Monitoring → Collect and analyze activity to detect potential threats and security incidents.**