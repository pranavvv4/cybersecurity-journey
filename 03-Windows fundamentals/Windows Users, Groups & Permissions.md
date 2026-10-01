# 👥 Windows Users, Groups & Permissions

Windows uses users, groups, and permissions to control access to files, folders, and system resources.

## Examples

View the current user:

```powershell
whoami
```

View local users:

```powershell
Get-LocalUser
```

View local groups:

```powershell
Get-LocalGroup
```

View file permissions:

```powershell
icacls <FILE_OR_FOLDER>
```

## Characteristics

- Users represent individual accounts
- Groups organize users with common permissions
- NTFS permissions control access to files and folders
- Common permissions include Read, Write, Modify, and Full Control
- Administrator accounts have elevated privileges
- Access should follow the principle of least privilege

## Key Takeaway

**Windows permissions → Control which users and groups can access or modify system resources.**