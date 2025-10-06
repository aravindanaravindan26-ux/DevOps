---

# 🔍 7. Monitoring & Logging

## 🔹 Why Monitoring Matters
To ensure your systems and applications are **healthy, available, and efficient.**

---

## 🔹 Basic Linux Monitoring Commands
| Command | Purpose |
|----------|----------|
| `top` | CPU/memory usage |
| `df -h` | Disk usage |
| `free -m` | Memory stats |
| `uptime` | System uptime |
| `ps -ef` | List processes |

---

## 🔹 Logs
| File | Description |
|------|--------------|
| `/var/log/syslog` | System logs |
| `/var/log/auth.log` | Login info |
| `/var/log/nginx/access.log` | Web access logs |

Check logs:
```bash
tail -f /var/log/syslog
