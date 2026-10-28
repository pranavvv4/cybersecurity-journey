# 🔎 Threat Hunting & Detection Engineering

Threat hunting is the proactive search for suspicious activity that may have bypassed existing security detections. Detection engineering involves creating, testing, and improving rules that identify potential threats.

## Examples

Threat hunting workflow:

```text
Form a Hypothesis
       ↓
Collect Relevant Data
       ↓
Search for Suspicious Activity
       ↓
Investigate Findings
       ↓
Create or Improve Detection
       ↓
Test & Monitor
```

Example hypothesis:

```text
Hypothesis → An attacker may be using PowerShell
Data       → Process logs and command-line activity
Search     → Identify unusual PowerShell executions
Action     → Investigate findings and improve detection rules
```

## Characteristics

- **Threat Hunting** → Proactively searches for hidden threats
- **Detection Engineering** → Develops and maintains detection rules
- **Hypothesis-Driven Hunting** → Starts with a testable security question
- **False Positives** → Legitimate activity incorrectly flagged as suspicious
- **Detection Testing** → Verifies whether rules identify expected activity
- **Continuous Improvement** → Refines rules as threats and environments change

## Key Takeaway

**Threat Hunting → Search proactively for threats.**

**Detection Engineering → Build, test, and improve detections to identify suspicious activity.**