# 🖥️ EDR & Endpoint Monitoring

EDR (Endpoint Detection and Response) is a security technology that monitors endpoint activity, detects suspicious behavior, and supports investigation and response.

## Examples

Common EDR platforms:

- Microsoft Defender for Endpoint
- CrowdStrike Falcon
- SentinelOne
- Wazuh endpoint monitoring

```text
Endpoint Activity
       ↓
EDR Collects Telemetry
       ↓
Detection & Analysis
       ↓
Alert Generated
       ↓
SOC Investigation
       ↓
Response Action
```

## Characteristics

- **Endpoint Telemetry** → Collects process, file, login, and other activity
- **Threat Detection** → Identifies suspicious behavior and known threats
- **Investigation** → Helps analysts examine processes and activity timelines
- **Response** → May support isolating an endpoint or stopping a malicious process
- **Visibility** → Helps identify suspicious activity that network logs alone may miss
- **EDR vs. Antivirus** → Antivirus focuses heavily on preventing and detecting malware; EDR adds broader activity monitoring, investigation, and response capabilities

## Key Takeaway

**EDR → Monitors endpoints, detects suspicious behavior, and helps security teams investigate and respond to threats.**