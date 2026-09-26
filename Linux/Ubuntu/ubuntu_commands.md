# 🐧 Ubuntu Commands Reference

A practical reference for commonly used Ubuntu Linux commands.

---

## 📁 File & Directory Commands

| Command                  | Description                 |
| ------------------------ | --------------------------- |
| `pwd`                    | Show current directory      |
| `ls`                     | List files and directories  |
| `ls -la`                 | List all files with details |
| `cd folder`              | Enter a directory           |
| `cd ..`                  | Go to parent directory      |
| `mkdir folder`           | Create a directory          |
| `touch file.txt`         | Create a file               |
| `cp file.txt backup.txt` | Copy a file                 |
| `mv file.txt folder/`    | Move a file                 |
| `rm file.txt`            | Delete a file               |
| `rm -r folder`           | Delete a directory          |

---

## 📦 APT Package Management

### Update Package List

```bash
sudo apt update
```

### Upgrade Packages

```bash
sudo apt upgrade
```

### Install a Package

```bash
sudo apt install package-name
```

### Remove a Package

```bash
sudo apt remove package-name
```

### Search for a Package

```bash
apt search package-name
```

### Show Installed Packages

```bash
apt list --installed
```

---

## ⚙️ System Management

### Check System Information

```bash
uname -a
```

### Check Ubuntu Version

```bash
lsb_release -a
```

### Show Running Processes

```bash
ps aux
```

### Monitor Processes

```bash
top
```

### Show Disk Usage

```bash
df -h
```

### Show Memory Usage

```bash
free -h
```

---

## 🔧 Systemd & Services

### Check Service Status

```bash
sudo systemctl status service-name
```

### Start a Service

```bash
sudo systemctl start service-name
```

### Stop a Service

```bash
sudo systemctl stop service-name
```

### Restart a Service

```bash
sudo systemctl restart service-name
```

### Enable Service at Boot

```bash
sudo systemctl enable service-name
```

### Disable Service at Boot

```bash
sudo systemctl disable service-name
```

---

## 🔐 File Permissions

### Change File Permissions

```bash
chmod 755 file.sh
```

### Change File Owner

```bash
sudo chown username file.txt
```

### Show File Permissions

```bash
ls -l
```

---

## 🌐 Network Commands

### Show IP Address

```bash
ip addr
```

### Test Network Connection

```bash
ping google.com
```

### Show Network Routes

```bash
ip route
```

### DNS Lookup

```bash
nslookup google.com
```

---

## 🧹 Useful Commands

### Clear Terminal

```bash
clear
```

### Show Command History

```bash
history
```

### Find a Command

```bash
which command-name
```

### Find Files

```bash
find /path -name "filename"
```

### Search Text

```bash
grep "text" file.txt
```

---

## 📌 Notes

Use `sudo` carefully because commands executed with administrator privileges can modify important system files and settings.

Always understand a command before running it on a real system.
