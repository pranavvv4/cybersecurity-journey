# ⚙️ Linux Process Control

Linux provides tools to manage running processes, including stopping, continuing, and terminating them.

## Examples

Find a process:

```bash
ps aux
```

Terminate a process using its PID:

```bash
kill <PID>
```

Forcefully terminate a process:

```bash
kill -9 <PID>
```

Run a command in the background:

```bash
command &
```

Bring a background job to the foreground:

```bash
fg
```

## Characteristics

- Every running process has a PID
- `kill` sends a signal to a process
- `SIGTERM` allows a process to terminate gracefully
- `SIGKILL` forcefully terminates a process
- `&` runs a command in the background
- `fg` brings a background job to the foreground

## Key Takeaway

**Process control → Manage running programs by starting, stopping, and controlling their execution.**