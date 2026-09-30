# 👤 Linux Users, Groups & Permissions

Linux uses users, groups, and permissions to control access to files and resources.

## Examples

View the current user:

```bash
whoami
```

View file permissions:

```bash
ls -l
```

Example:

```text
-rwxr-xr--  user  developers  script.sh
```

Permission types:

```text
r → Read
w → Write
x → Execute
```

Change permissions:

```bash
chmod 755 script.sh
```

Change file owner:

```bash
chown user script.sh
```

## Characteristics

- Every file has an owner and group
- Permissions control read, write, and execute access
- Permissions apply to owner, group, and others
- `root` has administrative privileges
- `chmod` changes permissions
- `chown` changes ownership

## Key Takeaway

**Linux permissions → Control who can read, modify, or execute files and resources.**