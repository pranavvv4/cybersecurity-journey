# 🚨 Security Events vs. Alerts vs. Incidents

Security events, alerts, and incidents are related concepts used by a SOC to monitor activity and investigate potential threats.

## Examples

```text
Security Event → Failed login recorded
       ↓
Security Alert → Multiple failed logins detected
       ↓
Security Incident → Investigation confirms account compromise
```

## Characteristics

- **Security Event** → An observable activity recorded by a system, application, or security tool
- **Security Alert** → A notification generated when activity matches a detection rule or suspicious condition
- **Security Incident** → An event or series of events that requires response because a security compromise or violation has occurred or is reasonably suspected
- Not every event generates an alert
- Not every alert becomes a confirmed security incident
- Analysts investigate alerts and use evidence to determine the appropriate response

## Key Takeaway

**Event → Something happened.**

**Alert → Something may need attention.**

**Incident → A security issue requiring response.**