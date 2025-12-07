# 🌟 NexaOS
**Give Old Devices New Life.**

NexaOS is a lightweight, fast, and modern **Debian-based Linux distribution** designed to restore performance on aging hardware while still delivering a smooth experience on new systems.  
With support for both **x86_64** and **ARM64**, and offering **KDE Plasma** and **GNOME**, NexaOS blends speed, beauty, and stability.

---

## 🖥️ Screenshots




### Desktop Preview  
<img src="desktop.png"/>

---

# 🚀 Features

- ⚡ **Optimized for old devices** — breathe new life into aging hardware  
- 🧩 **Debian-based** — stable, secure, and familiar  
- 🖥 **Two desktop environments** — KDE Plasma & GNOME  
- 💻 Supports **x86_64** and **ARM64**  
- 🌙 Fast boot and lightweight resource usage  
- 🔐 Open-source & MIT-licensed  
- 🔄 Development builds updated regularly  

---

# 🖥️ Supported Architectures

| Architecture | Status |
|--------------|--------|
| **x86_64**   | ✔ Supported |
| **ARM64**    | ✔ Supported |

---

# 📥 Downloads

## 🧪 NexaOS 0.1 – Developer Build  
This is the **first public release** of NexaOS.  
It is an early developer build intended for:

- Testers  
- Developers  
- Contributors  
- Early adopters  

⚠️ **Not recommended for daily use yet.**

### 📦 Downloads (Archive.org)

| Version | Architecture | Status | Download |
|---------|--------------|---------|----------|
| **NexaOS 0.1 (Developer Build)** | x86_64 | Unavilable |

---

# 💿 How to Install NexaOS

### 1. Download ISO  
Get the ISO from Archive.org using the links above.

### 2. Create a bootable USB  
Use any tool you prefer:

- **BalenaEtcher**  
- **Rufus**  
- **Ventoy**  
- **dd (Linux terminal)**

Example using `dd`:

```bash
sudo dd if=nexaos.iso of=/dev/sdX bs=4M status=progress oflag=sync
