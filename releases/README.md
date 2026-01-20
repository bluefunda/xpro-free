# XPro Free Edition Releases

## Latest Release: v1.0.13

### Downloads

| Package | Description |
|---------|-------------|
| [xpro-free_1.0.13_linux_amd64.tar.gz](v1.0.13/xpro-free_1.0.13_linux_amd64.tar.gz) | Binary archive (Linux x86_64) |
| [xpro-free-1.0.13-1.amd64.deb](v1.0.13/xpro-free-1.0.13-1.amd64.deb) | Debian/Ubuntu package |
| [xpro-free-1.0.13-1.amd64.rpm](v1.0.13/xpro-free-1.0.13-1.amd64.rpm) | RHEL/CentOS/Rocky package |
| [checksums.txt](v1.0.13/checksums.txt) | SHA256 checksums |

### Installation

**Binary Archive (Manual)**
```bash
tar xzf xpro-free_1.0.13_linux_amd64.tar.gz
cd xpro-free_1.0.13_linux_amd64
sudo cp xpro processor file-watcher xmlgen /usr/local/bin/
```

**Debian/Ubuntu**
```bash
sudo dpkg -i xpro-free-1.0.13-1.amd64.deb
sudo apt-get install -f  # if needed for dependencies
```

**RHEL/CentOS/Rocky**
```bash
sudo dnf install xpro-free-1.0.13-1.amd64.rpm
```
