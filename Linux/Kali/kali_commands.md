# 🐉 Kali Linux Commands Reference

A practical reference for commonly used Kali Linux terminal, networking, system administration, and security-learning commands.

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

## 📦 Package Management

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

---

## 🌐 Network Commands

### Show IP Address

```bash
ip addr
```

### Show Network Interfaces

```bash
ip link
```

### Test Network Connectivity

```bash
ping google.com
```

### Show Routing Table

```bash
ip route
```

### DNS Lookup

```bash
nslookup example.com
```

### Check Open Network Connections

```bash
ss -tuln
```

---

## 🔎 Network Diagnostic Tools

### Check Route to a Host

```bash
traceroute example.com
```

### DNS Information

```bash
dig example.com
```

### HTTP Request

```bash
curl https://example.com
```

### Download a File

```bash
wget https://example.com/file.zip
```

---

## 🔐 Permissions & Administration

### Show File Permissions

```bash
ls -l
```

### Change Permissions

```bash
chmod 755 script.sh
```

### Change File Owner

```bash
sudo chown username file.txt
```

### Run Command as Administrator

```bash
sudo command
```

---

## 🛠️ Process Management

### Show Running Processes

```bash
ps aux
```

### Monitor Processes

```bash
top
```

### Find a Process

```bash
ps aux | grep process-name
```

### Stop a Process

```bash
kill PID
```

---

## 🛡️ Security Learning Tools

Kali Linux includes many tools designed for authorized security testing and learning.

### Nmap

Used for network discovery and security auditing on systems you are authorized to test.

```bash
nmap <authorized-host>
```

### Netcat

Useful for network troubleshooting and testing in controlled environments.

```bash
nc -h
```

### Wireshark

A graphical network protocol analyzer.

```bash
wireshark
```

### Nikto

A web server assessment tool for authorized testing.

```bash
nikto -h <authorized-host>
```

---

## 📊 System Information

### Kernel Information

```bash
uname -a
```

### Kali Version

```bash
cat /etc/os-release
```

### Disk Usage

```bash
df -h
```

### Memory Usage

```bash
free -h
```

### System Uptime

```bash
uptime
```

---

## 🧹 Useful Terminal Commands

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

### Search Files

```bash
find /path -name "filename"
```

### Search Text

```bash
grep "text" file.txt
```

---

## ⚠️ Security Notice

Security tools should only be used on systems, networks, websites, and devices that you own or have explicit permission to test.

Unauthorized scanning, access attempts, interception, or exploitation may be illegal.

---

## 📌 Notes

Kali Linux is primarily designed for security testing, digital forensics, and security education.

Always practice in a controlled lab environment when learning security tools.
