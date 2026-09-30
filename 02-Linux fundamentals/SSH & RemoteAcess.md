# 🔐 SSH & Remote Access

SSH (Secure Shell) is a protocol used to securely access and manage remote systems.

## Examples

Connect to a remote Linux system:

```bash
ssh username@<TARGET_IP>
```

Copy a file to a remote system:

```bash
scp file.txt username@<TARGET_IP>:/home/username/
```

## Characteristics

- Uses TCP
- Default port is `22`
- Encrypts communication
- Supports password and key-based authentication
- Commonly used for remote administration
- `scp` can securely transfer files over SSH

## Key Takeaway

**SSH → Secure remote access and communication with Linux systems.**