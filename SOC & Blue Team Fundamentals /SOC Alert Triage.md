# 🚨 SOC Alert Triage

SOC alert triage is the process of reviewing security alerts, validating suspicious activity, assessing risk, and deciding what action is required.

## Examples

```text
Alert Received
      ↓
Validate the Alert
      ↓
Gather Evidence
      ↓
Assess Severity & Priority
      ↓
Investigate or Escalate
      ↓
Document Findings
```

Example:

```text
Alert → Multiple Failed Logins
Severity → High
Priority → High
Action → Investigate source IP, account activity, and successful logins
```

## Characteristics

- **Alert Validation** → Determine whether the alert is genuine or a false positive
- **Severity** → Measures the potential seriousness of the security event
- **Priority** → Determines how urgently the alert should be handled
- **Investigation** → Review logs, timestamps, IP addresses, users, and related events
- **Escalation** → Send confirmed or complex incidents to the appropriate team
- **Documentation** → Record evidence, findings, and actions taken

## Severity vs. Priority

- **Severity** → How serious the potential impact is
- **Priority** → How quickly the issue needs attention, considering severity, context, and business impact

## Key Takeaway

**Alert Triage → Validate, assess, investigate, prioritize, and route security alerts for appropriate action.**