# 🛡️ Linux Security & Privilege Management

Linux provides built-in tools to manage privileges, users, processes, and system security.

## Examples

Run a command with administrative privileges:

```bash
sudo <command>
```

Switch to another user:

```bash
su <username>
```

View the current user's identity:

```bash
id
```

View command history:

```bash
history
```

## Characteristics

- `sudo` → Runs commands with elevated privileges
- `su` → Switches to another user
- `id` → Displays user and group information
- `history` → Shows previously executed commands
- Least privilege reduces unnecessary access
- Administrative commands should be used carefully

## Key Takeaway

**Linux security → Control privileges and access while minimizing unnecessary permissions.**