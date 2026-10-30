# 🌍 Threat Intelligence Feeds & IOC Enrichment

Threat intelligence feeds provide information about known malicious indicators, while IOC enrichment adds context to indicators to help SOC analysts investigate suspicious activity.

## Examples

Common Indicators of Compromise (IOCs):

```text
IP Address  →  Malicious network address
Domain      →  Suspicious website or domain
File Hash   →  Identifies a file
URL         →  Suspicious web address
Email       →  Suspicious sender address
```

Common threat intelligence platforms:

- VirusTotal
- AbuseIPDB
- AlienVault OTX
- URLhaus
- MISP

Example enrichment workflow:

```text
Suspicious IP Detected
        ↓
Search Threat Intelligence Sources
        ↓
Check Reputation & Related Activity
        ↓
Collect Additional Context
        ↓
Assess Risk
        ↓
Document Findings
```

## Characteristics

- **Threat Intelligence Feed** → Supplies information about known threats and malicious indicators
- **IOC Enrichment** → Adds reputation, context, and related threat information to an indicator
- **IP Reputation** → Helps identify potentially malicious network addresses
- **Domain Reputation** → Helps investigate suspicious domains
- **File Hash Analysis** → Helps identify known malicious files
- **Contextual Analysis** → Combines intelligence with internal logs and observed activity
- **False Positive Validation** → Intelligence matches must be investigated before taking action

## Key Takeaway

**Threat Intelligence Feeds → Provide information about known threats.**

**IOC Enrichment → Adds context to indicators to support SOC investigations.**