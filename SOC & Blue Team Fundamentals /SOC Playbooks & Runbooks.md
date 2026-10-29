# 📘 SOC Playbooks & Runbooks

SOC playbooks and runbooks guide analysts through security investigations and response actions. A playbook describes the overall workflow, while a runbook provides specific operational steps.

## Examples

```text
Playbook → Suspicious Login Investigation
    ↓
Review Authentication Logs
    ↓
Check User & Source IP
    ↓
Identify Related Activity
    ↓
Determine Risk
    ↓
Escalate or Respond
```

Example runbook actions:

```text
1. Record the alert ID and timestamp
2. Review related authentication events
3. Check for unusual successful logins
4. Verify activity with the account owner if appropriate
5. Escalate according to SOC procedures
6. Document evidence and findings
```

## Characteristics

- **Playbook** → Defines the workflow for handling a type of security event
- **Runbook** → Provides detailed, repeatable operational instructions
- **Consistency** → Helps analysts follow approved procedures
- **Efficiency** → Reduces delays and missed investigation steps
- **Escalation** → Defines when and how to involve other teams
- **Documentation** → Records actions, evidence, and outcomes
- **Automation** → Some steps can be automated using SOAR tools

## Key Takeaway

**Playbook → Overall response workflow.**

**Runbook → Step-by-step operational instructions.**