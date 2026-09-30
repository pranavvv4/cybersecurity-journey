# 🔐 Linux Special Permissions

Linux provides special permissions that control how certain files and directories are executed or accessed.

## Examples

Set SUID:

```bash
chmod u+s program
```

Set SGID:

```bash
chmod g+s directory
```

Set sticky bit:

```bash
chmod +t directory
```

View permissions:

```bash
ls -l
```

## Characteristics

- **SUID** → Program runs with the file owner's privileges
- **SGID** → Program can run with the file group's privileges; directories can inherit the group
- **Sticky Bit** → Users can normally delete only their own files in a shared directory
- Special permissions can affect privilege and access control
- Misconfigured permissions can create security risks

## Key Takeaway

**SUID → Owner privileges**  
**SGID → Group privileges**  
**Sticky Bit → Restricts deletion in shared directories**