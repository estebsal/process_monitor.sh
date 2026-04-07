# 🔍 Process Monitor

![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Automated process monitoring with logging and status tracking**

---

## 📋 Overview

`process_monitor.sh` is a lightweight Bash script that monitors critical system processes and logs their status with timestamps. Perfect for ensuring service availability and detecting process failures before they impact users.

## ✨ Features

- 🔍 **Process monitoring** using `pgrep`
- 📊 **PID tracking** for running processes
- 🕐 **Timestamp logging** for audit trails
- ✅ **Status detection** (running/not running)
- 📝 **Automatic log file** generation
- ⚡ **Configurable check intervals**

## 🚀 Usage

### Basic execution
```bash
./process_monitor.sh
