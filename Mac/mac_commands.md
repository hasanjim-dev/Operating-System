# 🍎 macOS Commands Reference

A practical reference for commonly used macOS Terminal commands, file management, networking, system administration, and Homebrew.

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

## 🍺 Homebrew

Homebrew is a popular package manager for macOS.

### Check Homebrew

```bash id="7j4n2k"
brew --version
```

### Update Homebrew

```bash id="m8q2xz"
brew update
```

### Upgrade Packages

```bash id="p5k7wd"
brew upgrade
```

### Install a Package

```bash id="v3n6yr"
brew install package-name
```

### Remove a Package

```bash id="c9x4mt"
brew uninstall package-name
```

### Search for a Package

```bash id="h2q8fs"
brew search package-name
```

### List Installed Packages

```bash id="r6m1kp"
brew list
```

---

## ⚙️ System Information

### macOS Version

```bash id="d4y8zn"
sw_vers
```

### Kernel Information

```bash id="x7p2lc"
uname -a
```

### Computer Name

```bash id="f5m9qb"
scutil --get ComputerName
```

### System Uptime

```bash id="k3v6tw"
uptime
```

---

## 💾 Disk & Memory

### Disk Usage

```bash id="n8r4xs"
df -h
```

### Directory Size

```bash id="q1m7zd"
du -sh folder-name
```

### Memory Information

```bash id="w5c9kp"
top
```

---

## 🌐 Network Commands

### Show IP Address

```bash id="t2v8mb"
ifconfig
```

### Test Internet Connection

```bash id="g6q3rx"
ping google.com
```

### DNS Lookup

```bash id="y4n1sf"
nslookup google.com
```

### Show Routing Table

```bash id="j8k5vd"
netstat -rn
```

### Check Listening Ports

```bash id="z3p7qc"
lsof -i -P -n
```

---

## 🔐 File Permissions

### Show Permissions

```bash id="b9w2mk"
ls -l
```

### Change Permissions

```bash id="e6r4yt"
chmod 755 script.sh
```

### Change Owner

```bash id="u1q8pf"
sudo chown username file.txt
```

---

## 🛠️ Process Management

### Show Processes

```bash id="s5m3kx"
ps aux
```

### Monitor Processes

```bash id="a7v9cd"
top
```

### Find a Process

```bash id="q4n6wb"
ps aux | grep process-name
```

### Stop a Process

```bash id="m2x8zr"
kill PID
```

---

## 🧹 Useful Terminal Commands

### Clear Terminal

```bash id="f7k3pn"
clear
```

### Show Command History

```bash id="r9v2lm"
history
```

### Find a Command

```bash id="c5x8qd"
which command-name
```

### Find Files

```bash id="n3m7ws"
find . -name "filename"
```

### Search Text

```bash id="k6p1yr"
grep "text" file.txt
```

---

## 📌 Notes

macOS uses a Unix-based terminal environment, so many commands are similar to Linux commands.

Use `sudo` carefully because administrator-level commands can modify system files and settings.

Homebrew packages should be installed from trusted sources.
