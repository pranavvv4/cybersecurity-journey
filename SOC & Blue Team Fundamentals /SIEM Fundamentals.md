# 📊 SIEM Fundamentals

SIEM (Security Information and Event Management) is a security solution that collects and analyzes logs from multiple sources to detect suspicious activity and support investigations.

## Examples

Common SIEM platforms:

- Wazuh
- Splunk
- Microsoft Sentinel
- Elastic Security

```text
Windows Logs ──┐
Linux Logs ────┤
Firewall Logs ─┼──→ SIEM → Detection Rules → Alerts
Cloud Logs ────┘                         ↓
                                  SOC Investigation
```

## Characteristics

- **Log Ingestion** → Collects security events from different sources
- **Normalization** → Converts events into a consistent structure
- **Correlation** → Connects related events to identify suspicious patterns
- **Detection Rules** → Identify activity matching defined conditions
- **Alerting** → Notifies analysts about potentially malicious activity
- **Dashboards** → Display events, alerts, and security trends
- **Investigation** → Helps analysts search logs and build incident timelines

## Key Takeaway

**SIEM → Centralizes security logs, detects suspicious patterns, and supports SOC investigations.**