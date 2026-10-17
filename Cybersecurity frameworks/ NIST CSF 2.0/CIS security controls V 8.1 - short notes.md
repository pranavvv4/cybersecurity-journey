
# 🛡️ CIS Critical Security Controls v8.1 — Short Notes

## 📌 Definition
CIS Controls are a prioritized set of practical cybersecurity safeguards designed to defend against common cyberattacks.

- **Structure:** 18 Controls containing Safeguards.
- **Implementation Groups:** IG1, IG2, IG3.
- **Purpose:** Reduce cybersecurity risks through practical security measures.

## ⭐ Important Controls for SOC & Cloud Security

### 🖥️ Control 1 — Enterprise Asset Inventory
Identify and manage computers, servers, network devices, and cloud resources.

**Example:** Inventory all AWS EC2 instances.

### 💻 Control 2 — Software Asset Inventory
Track authorized software and identify unauthorized applications.

**Example:** Detect unauthorized software on an endpoint.

### 🔐 Control 3 — Data Protection
Classify, protect, encrypt, and securely dispose of sensitive data.

**Example:** Protect sensitive information stored in Amazon S3.

### ⚙️ Control 4 — Secure Configuration
Apply and maintain secure configurations for systems and software.

**Example:** Restrict unnecessary inbound traffic in AWS security groups.

### 👤 Control 5 — Account Management
Manage user, administrator, and service accounts throughout their lifecycle.

**Example:** Disable accounts when employees leave.

### 🔑 Control 6 — Access Control Management
Apply least privilege, MFA, and appropriate access permissions.

**Example:** Grant an AWS IAM role only the permissions it requires.

### 🐛 Control 7 — Vulnerability Management
Identify, prioritize, track, and remediate vulnerabilities.

**Example:** Scan servers and patch critical vulnerabilities.

### 📜 Control 8 — Audit Log Management
Collect, protect, review, and retain logs for security investigations.

**Example:** Use AWS CloudTrail to investigate suspicious API calls.

### 🦠 Control 10 — Malware Defenses
Prevent, detect, and contain malicious software.

**Example:** Investigate an EDR alert for ransomware activity.

### 📡 Control 13 — Network Monitoring and Defense
Monitor network traffic and detect suspicious communications.

**Example:** Investigate connections to known malicious IP addresses.

### 🚨 Control 17 — Incident Response Management
Prepare for, investigate, contain, and recover from security incidents.

**Example:** Revoke compromised AWS credentials and investigate related activity.

### 🧪 Control 18 — Penetration Testing
Simulate authorized attacks to identify exploitable weaknesses.

**Example:** Test an application for access-control vulnerabilities.

## 🎯 Key Takeaway
- **Controls 1, 2, 4:** Asset inventory and secure configuration.
- **Controls 5, 6:** Accounts and access management.
- **Controls 7, 8:** Vulnerability management and security logs.
- **Controls 10, 13:** Malware and network defense.
- **Control 17:** Incident response.
- **Control 18:** Authorized security testing.

These are study priorities, not an official CIS ranking. All 18 Controls can be important depending on the organization's risks.

## 📚 Official Resources
- https://www.cisecurity.org/controls/v8-1
- https://www.cisecurity.org/controls/cis-controls-list
