# 🤖 SOAR Fundamentals

SOAR (Security Orchestration, Automation, and Response) is a security technology that connects security tools, automates repetitive tasks, and coordinates incident response workflows.

## Examples

```text
SIEM Detects Suspicious Activity
              ↓
        SOAR Playbook
              ↓
       Enrich Alert Data
              ↓
       Check Threat Intel
              ↓
       Analyst Review
              ↓
     Approved Response Action
```

Example: suspicious IP address detection

```text
1. Receive an alert from SIEM
2. Collect IP reputation information
3. Search for related events
4. Notify the SOC analyst
5. Block the IP if authorized
6. Record the response actions
```

## Characteristics

- **Orchestration** → Connects different security tools and systems
- **Automation** → Performs repetitive tasks automatically
- **Response** → Coordinates actions to handle security incidents
- **Playbooks** → Define automated investigation and response workflows
- **Human Approval** → Can require analyst approval for high-impact actions
- **Integration** → Works with SIEM, EDR, threat intelligence, and ticketing systems

## SIEM vs. SOAR

- **SIEM** → Collects and analyzes logs to detect suspicious activity
- **SOAR** → Automates and coordinates investigation and response workflows

## Key Takeaway

**SOAR → Connects security tools and automates repetitive investigation and response tasks.**