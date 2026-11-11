# ⚠️ SOC False Positives & False Negatives

## Definition
False Positives and False Negatives are errors in security detection systems that affect the accuracy of alerts and threat detection.

- **False Positive:** A security system generates an alert for activity that is actually legitimate.
- **False Negative:** A security system fails to detect an actual security threat.

## Examples
- **False Positive:** A legitimate employee login is incorrectly flagged as suspicious.
- **False Positive:** An authorized application is mistakenly detected as malware.
- **False Negative:** Malware runs on a system without triggering an alert.
- **False Negative:** An attacker successfully accesses an account without detection.

## Characteristics
- **False Positives:**
  - Generate unnecessary alerts.
  - Increase the SOC team's workload.
  - Waste investigation time.
  - Can cause alert fatigue.

- **False Negatives:**
  - Allow real threats to go undetected.
  - Increase the risk of data breaches.
  - May allow attackers to remain inside a network.
  - Can cause serious security damage.

## Important Details

| Aspect | False Positive | False Negative |
|---|---|---|
| Detection result | Incorrect alert | Missed threat |
| Actual activity | Benign | Malicious |
| Main problem | Unnecessary investigation | Undetected attack |
| Impact | Wasted resources | Security compromise |

**How to Reduce Them**
- Fine-tune SIEM detection rules.
- Use threat intelligence and updated indicators.
- Correlate multiple security events.
- Regularly test detection rules.
- Monitor user and system behavior.
- Review alerts and investigate missed threats.

## Key Takeaway
False Positives create unnecessary alerts, while False Negatives allow real threats to go undetected. SOC teams must minimize both to improve detection accuracy.