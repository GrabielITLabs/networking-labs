# Linux DNS Troubleshooting Lab

## 📌 Overview
In this lab, I worked inside an Ubuntu VM to troubleshoot DNS resolution issues.

## 🧪 Problem
- Unable to resolve domain names (e.g., google.com)
- Network connectivity was working (ping by IP worked)

## 🔍 Troubleshooting Steps
- Checked `/etc/resolv.conf`
- Attempted to configure DNS using `resolvectl`
- Verified hostname resolution in `/etc/hosts`
- Restarted `systemd-resolved`

## ✅ Solution
- Corrected DNS configuration
- Ensured proper hostname resolution
- Verified DNS functionality using `ping google.com`

---

## 📸 Screenshots

### 🔴 Problem
![Problem](linux-dns-troubleshooting/linux-dns-troubleshooting/screenshots/problem.png)

### 🛠️ Troubleshooting
![Work](linux-dns-troubleshooting/linux-dns-troubleshooting/screenshots/work.png)

### ✅ Result
![Result](linux-dns-troubleshooting/linux-dns-troubleshooting/screenshots/result.png)
