# 🔐 Windows Authentication & Kerberos

Windows authentication verifies user identities. In Active Directory environments, Kerberos is the primary authentication protocol used for domain authentication.

## Examples

Basic authentication flow:

```text
User → Domain Controller → Authentication → Access
```

Kerberos uses tickets:

```text
User → KDC → Ticket → Service
```

Common concepts:

```text
KDC → Key Distribution Center
TGT → Ticket Granting Ticket
TGS → Ticket Granting Service
SPN → Service Principal Name
```

## Characteristics

- Kerberos is commonly used in Active Directory domains
- Uses tickets instead of sending passwords to every service
- The KDC is part of the domain controller
- TGTs are used to request service tickets
- Authentication and authorization are separate concepts

## Key Takeaway

**Windows Authentication → Verifies identity.**  
**Kerberos → Uses ticket-based authentication in Active Directory environments.**