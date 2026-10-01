# 🗂️ Windows File System

Windows uses a hierarchical file system to organize files, folders, applications, and system data.

## Examples

View files and directories:

```powershell
Get-ChildItem
```

Create a directory:

```powershell
New-Item -ItemType Directory test
```

Copy a file:

```powershell
Copy-Item file.txt backup.txt
```

Move or rename a file:

```powershell
Move-Item file.txt newfile.txt
```

## Characteristics

- Windows commonly uses the NTFS file system
- Drives are represented using letters such as `C:`
- Files and folders can have access permissions
- NTFS supports security features such as permissions and auditing
- PowerShell provides commands for managing files and directories

## Key Takeaway

**Windows File System → Organizes and manages files, folders, and system data while providing access control.**