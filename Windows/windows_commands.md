# 🪟 Windows Commands Reference

A practical reference for commonly used Windows CMD and PowerShell commands.

---

## 📌 CMD Commands

| Command                 | Description                |
| ----------------------- | -------------------------- |
| `dir`                   | List files and folders     |
| `cd folder`             | Enter a folder             |
| `cd ..`                 | Go back one folder         |
| `mkdir folder`          | Create a folder            |
| `rmdir folder`          | Remove a folder            |
| `del file.txt`          | Delete a file              |
| `cls`                   | Clear the terminal         |
| `copy file.txt D:\`     | Copy a file                |
| `move file.txt D:\`     | Move a file                |
| `ipconfig`              | Show network configuration |
| `ping google.com`       | Test network connectivity  |
| `hostname`              | Show computer name         |
| `tasklist`              | Show running processes     |
| `taskkill /PID 1234 /F` | Stop a process             |
| `systeminfo`            | Display system information |

---

## ⚡ PowerShell Commands

| Command                               | Description                |
| ------------------------------------- | -------------------------- |
| `Get-Location`                        | Show current directory     |
| `Get-ChildItem`                       | List files and folders     |
| `Set-Location folder`                 | Change directory           |
| `New-Item folder -ItemType Directory` | Create a folder            |
| `Remove-Item file.txt`                | Delete a file              |
| `Copy-Item file.txt D:\`              | Copy a file                |
| `Move-Item file.txt D:\`              | Move a file                |
| `Clear-Host`                          | Clear the terminal         |
| `Get-Process`                         | Show running processes     |
| `Stop-Process -Id 1234`               | Stop a process             |
| `Get-Service`                         | Show Windows services      |
| `Get-ComputerInfo`                    | Display system information |

---

## 🌐 Network Commands

### Check IP Address

```powershell
ipconfig
```

### Test Internet Connection

```powershell
ping google.com
```

### Show Detailed Network Information

```powershell
ipconfig /all
```

### Check DNS

```powershell
nslookup google.com
```

---

## 💻 System Commands

### Check Windows Version

```powershell
winver
```

### System Information

```powershell
systeminfo
```

### Show Running Processes

```powershell
tasklist
```

### Show Computer Name

```powershell
hostname
```

---

## 📁 File & Folder Operations

### Create Folder

```powershell
mkdir Projects
```

### Enter Folder

```powershell
cd Projects
```

### Go Back

```powershell
cd ..
```

### List Files

```powershell
dir
```

### Delete Folder

```powershell
rmdir Projects
```

---

## 🔗 Useful Links

* Windows CMD documentation
* PowerShell documentation
* Windows Terminal documentation

---

## 📌 Notes

Commands may require administrator privileges depending on the operation.

Always verify a command before using it to modify system files, processes, or configuration.
