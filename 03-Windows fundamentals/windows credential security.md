# 🔑 Windows Credential Security

Windows uses several mechanisms to securely store and manage credentials used for authentication and access to resources.

## Examples

View Windows Credential Manager:

```text
Control Panel → Credential Manager
```

List cached Kerberos tickets:

```powershell
klist
```

View the current user:

```powershell
whoami
```

## Characteristics

- Credentials are used to authenticate users and access resources
- Windows can store credentials for applications and network resources
- Kerberos uses tickets for domain authentication
- Credential Manager stores certain saved credentials
- Protecting credentials is important for preventing unauthorized access
- Security tools can monitor suspicious credential-related activity

## Key Takeaway

**Credential Security → Protecting authentication information and preventing unauthorized access to accounts and resources.**