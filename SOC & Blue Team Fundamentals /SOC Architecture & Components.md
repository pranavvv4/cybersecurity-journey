# 🏗️ SOC Architecture & Components

SOC architecture consists of the systems, tools, and data sources used to monitor security activity, detect threats, and investigate incidents.

## Examples

```text
Endpoints / Servers / Network Devices
                 ↓
            Log Collection
                 ↓
                SIEM
                 ↓
       Detection Rules & Alerts
                 ↓
          SOC Analyst
                 ↓
       Investigation & Response
```

## Characteristics

- **Log Sources** → Windows, Linux, firewalls, applications, and cloud services
- **Log Collection** → Gathers security events from different sources
- **SIEM** → Centralizes and analyzes logs to detect suspicious activity
- **EDR** → Monitors endpoints and supports threat detection and investigation
- **IDS/IPS** → Detects suspicious network activity; IPS can also block traffic
- **Detection Rules** → Identify patterns or behaviors that may indicate threats
- **Dashboards & Alerts** → Help analysts prioritize and investigate suspicious events

## Key Takeaway

**SOC Architecture → Connects security data sources, monitoring tools, detection capabilities, and analysts to identify and respond to threats.**