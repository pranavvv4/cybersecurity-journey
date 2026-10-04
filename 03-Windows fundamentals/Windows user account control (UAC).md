# 🛂 Windows User Account Control (UAC)

User Account Control (UAC) is a Windows security feature that helps prevent unauthorized changes to the system.

## Examples

When an application needs administrator privileges:

```text
Application
     ↓
UAC Prompt
     ↓
User Approval
     ↓
Elevated Privileges
```

View UAC settings:

```text
Control Panel → User Accounts → Change User Account Control settings
```

## Characteristics

- Helps prevent unauthorized system changes
- Prompts users before elevated actions
- Supports the principle of least privilege
- Helps protect against malicious applications running with administrator privileges
- Commonly appears when administrative privileges are required

## Key Takeaway

**UAC → Helps prevent unauthorized actions by requiring approval for elevated privileges.**