# 🏹 Arch Linux Commands Reference

A practical reference for commonly used Arch Linux commands, package management, system administration, and troubleshooting.

---

## 📁 File & Directory Commands

| Command                  | Description                           |
| ------------------------ | ------------------------------------- |
| `pwd`                    | Show current directory                |
| `ls`                     | List files and directories            |
| `ls -la`                 | List all files including hidden files |
| `cd folder`              | Enter a directory                     |
| `cd ..`                  | Go to parent directory                |
| `mkdir folder`           | Create a directory                    |
| `touch file.txt`         | Create a file                         |
| `cp file.txt backup.txt` | Copy a file                           |
| `mv file.txt folder/`    | Move a file                           |
| `rm file.txt`            | Delete a file                         |
| `rm -r folder`           | Delete a directory                    |

---

## 📦 Pacman Package Manager

### Synchronize Package Database

```bash id="u5l4v2"
sudo pacman -Sy
```

### Update System

```bash id="4x5q2m"
sudo pacman -Syu
```

### Install a Package

```bash id="yq5m7c"
sudo pacman -S package-name
```

### Remove a Package

```bash id="vq6w1t"
sudo pacman -R package-name
```

### Search for a Package

```bash id="u8j4s6"
pacman -Ss package-name
```

### Show Installed Packages

```bash id="2b5j0r"
pacman -Q
```

### Show Package Information

```bash id="3o0l8r"
pacman -Qi package-name
```

---

## ⚙️ System Management

### Kernel Information

```bash id="a9z1qf"
uname -a
```

### System Information

```bash id="0f1c5v"
hostnamectl
```

### Disk Usage

```bash id="9x1k3z"
df -h
```

### Memory Usage

```bash id="j6d2qp"
free -h
```

### System Uptime

```bash id="w4c7ny"
uptime
```

---

## 🔧 Systemd Commands

### Check Service Status

```bash id="f8k2mj"
systemctl status service-name
```

### Start a Service

```bash id="7q0x1n"
sudo systemctl start service-name
```

### Stop a Service

```bash id="z4w6pc"
sudo systemctl stop service-name
```

### Restart a Service

```bash id="h1t5vk"
sudo systemctl restart service-name
```

### Enable Service at Boot

```bash id="m8r3yd"
sudo systemctl enable service-name
```

### Disable Service at Boot

```bash id="c6v2pa"
sudo systemctl disable service-name
```

---

## 🔐 File Permissions

### Show Permissions

```bash id="n2f7qx"
ls -l
```

### Change Permissions

```bash id="p5y8kd"
chmod 755 script.sh
```

### Change Owner

```bash id="r3m6wt"
sudo chown username file.txt
```

---

## 🌐 Network Commands

### Show IP Address

```bash id="b7k4hs"
ip addr
```

### Show Network Interfaces

```bash id="q2v8mj"
ip link
```

### Test Internet Connection

```bash id="e5n1zc"
ping archlinux.org
```

### Show Routing Table

```bash id="k9d3wf"
ip route
```

### DNS Lookup

```bash id="s4x6py"
dig example.com
```

### Show Listening Ports

```bash id="t7m2qa"
ss -tuln
```

---

## 🛠️ Process Management

### List Processes

```bash id="x8c5vd"
ps aux
```

### Monitor Processes

```bash id="g3n7lk"
top
```

### Find a Process

```bash id="w6p2zr"
ps aux | grep process-name
```

### Stop a Process

```bash id="m4j8sx"
kill PID
```

---

## 📦 AUR

The Arch User Repository (AUR) contains community-maintained package build scripts.

AUR helpers such as `yay` can be used to simplify package installation.

### Search AUR with yay

```bash id="v2k9fd"
yay -Ss package-name
```

### Install an AUR Package

```bash id="n5r3xq"
yay -S package-name
```

### Update AUR Packages

```bash id="c8m1zt"
yay -Syu
```

> Only install AUR packages from sources you trust and review package build instructions when appropriate.

---

## 🧹 Useful Commands

### Clear Terminal

```bash id="p3w7mb"
clear
```

### Show Command History

```bash id="d9k2vf"
history
```

### Find a Command

```bash id="j5r8cx"
which command-name
```

### Find Files

```bash id="s1q6hp"
find /path -name "filename"
```

### Search Text

```bash id="z7m4kn"
grep "text" file.txt
```

---

## ⚠️ Notes

Use `sudo` carefully because administrative commands can modify important system files and settings.

Keep the system updated and always review commands before executing them.
