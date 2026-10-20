# 🔄 Backup & Disaster Recovery

Backup and Disaster Recovery (DR) are practices used to protect data and restore systems after data loss, cyberattacks, or major failures.

## Examples

```text
Production System
       ↓
Regular Backups
       ↓
Storage in a Separate Location
       ↓
Incident or Failure
       ↓
Restore Data & Services
```

Important concepts:

```text
Backup → Copy of data for recovery
Recovery → Restoring data or services
RPO → Maximum acceptable data loss measured in time
RTO → Target time for restoring a service
```

## Characteristics

- Backups protect against accidental deletion, corruption, and ransomware
- Offline or immutable backups help resist unauthorized modification
- **RPO (Recovery Point Objective)** → How much data loss is acceptable
- **RTO (Recovery Time Objective)** → How quickly a service should be restored
- Recovery plans should be tested regularly
- Backup access should be protected with strong permissions

## Key Takeaway

**Backup → Protects recoverable data.**

**Disaster Recovery → Restores systems and services after disruption.**