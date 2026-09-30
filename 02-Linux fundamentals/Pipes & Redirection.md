# 📦 Linux Archives & Compression

Linux provides tools to create, extract, and manage compressed archives.

## Examples

Create a tar archive:

```bash
tar -cvf backup.tar folder/
```

Extract a tar archive:

```bash
tar -xvf backup.tar
```

Create a compressed archive:

```bash
tar -czvf backup.tar.gz folder/
```

Extract it:

```bash
tar -xzvf backup.tar.gz
```

## Characteristics

- `tar` → Creates and extracts archives
- `gzip` → Compresses data
- `.tar.gz` → Common Linux compressed archive
- Useful for backups and transferring files
- Archives can contain multiple files and directories

## Key Takeaway

**Linux archives & compression → Package multiple files and reduce their size for storage or transfer.**