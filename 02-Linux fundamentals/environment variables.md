# 🕵️ Linux Environment Variables

Environment variables are dynamic values used by the system and applications to store configuration information.

## Examples

View an environment variable:

```bash
echo $PATH
```

View all environment variables:

```bash
env
```

Set a variable:

```bash
export NAME="Kali"
```

## Characteristics

- Store configuration information
- Available to processes and applications
- `PATH` determines where the shell searches for commands
- `env` displays environment variables
- `export` makes a variable available to child processes
- Useful for system administration and scripting

## Key Takeaway

**Environment variables → Store configuration values used by the Linux system and applications.**