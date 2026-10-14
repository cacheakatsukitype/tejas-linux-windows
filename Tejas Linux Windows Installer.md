# 🧰 Tejas Linux for Windows — Complete Guide

<div align="center">

![Tejas Linux](https://img.shields.io/badge/Tejas-Linux%20for%20Windows-DC2626?style=for-the-badge&logo=linux&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![WSL](https://img.shields.io/badge/WSL-2%20Ready-7C3AED?style=for-the-badge&logo=windowsterminal&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-95K-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white)

### 🐧 A Lightweight Linux Experience Built for Windows Users

*A complete guide to installing, configuring, and using Tejas Linux on Windows*

</div>

---

## 🚀 Quick Start Path

> **⏱️ Get running in 4 steps**

| Step | Action | Time |
|:----:|--------|:----:|
| 1️⃣ | [Check Requirements](#-system-requirements) | 2 min |
| 2️⃣ | [Get Instructions](#-get-instructions) | 1 min |
| 3️⃣ | [Install (WSL Method)](#-method-a--wsl-2-recommended) | 5 min |
| 4️⃣ | [Configure & Verify](#-verification) | 5 min |

---

## 🎯 Overview

**Tejas Linux** is a lightweight, Debian-based Linux distribution designed with Windows users in mind. It ships with a familiar layout, pre-configured tools for developers and students, and seamless integration with Windows through **WSL 2**, **VirtualBox**, or **dual-boot**.

The name *Tejas* (तेजस्) means "radiance" or "sharpness" in Sanskrit — reflecting the distro's goal: a sharp, efficient, and illuminating computing experience.

### 🧩 What Makes It Different

| Feature | Benefit |
|---------|---------|
| 🪟 **Windows-Friendly UI** | Familiar layout from day one |
| ⚡ **Lightweight** | Runs on modest hardware |
| 🧰 **Pre-Bundled Tools** | Dev, office, media ready |
| 🔗 **WSL 2 Support** | Runs inside Windows |
| 🔐 **Secure by Default** | Firewall + updates on install |
| 🌐 **Broad Hardware Support** | WiFi, GPU, printers |
| 📚 **Beginner Docs** | Step-by-step guidance |
| 🎨 **Customizable** | Themes and layouts |

---

## 💡 Why Tejas?

| Reason | Explanation |
|--------|-------------|
| 🎓 **Learning Linux** | Gentle transition from Windows |
| 💻 **Reviving Old PCs** | Low resource usage |
| 🧑‍💻 **Developer Ready** | Python, Node, Git preinstalled |
| 🔒 **Privacy Focus** | No telemetry by default |
| 🎯 **Focus on Productivity** | Clean menus, quick actions |
| 🧪 **Sandbox Testing** | WSL for safe experimentation |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 🐧 **Distro** | Linux distribution (Tejas is one) |
| 🧱 **Kernel** | Core of the operating system |
| 🖥️ **Desktop Environment** | GUI layer (XFCE-based) |
| 📦 **APT** | Package manager |
| 🔧 **Terminal** | Command interface |
| 🐳 **WSL** | Windows Subsystem for Linux |
| 💽 **ISO** | Installable image file |
| 🧪 **Live Session** | Try without installing |

---

## 🖥️ System Requirements

### 🔹 Minimum (Native Install)

```
✅ CPU: 1.6 GHz dual-core
✅ RAM: 2 GB
✅ Storage: 15 GB
✅ GPU: Any with 1024×768
✅ Network: Ethernet or WiFi
✅ Boot: USB or DVD drive
```

### 🔸 Recommended (Native Install)

```
⭐ CPU: Quad-core 2.0 GHz+
⭐ RAM: 8 GB
⭐ Storage: 60 GB SSD
⭐ GPU: Any modern integrated
⭐ Network: Gigabit Ethernet
⭐ Display: 1920×1080+
```

### 🪟 For WSL 2

```
✅ Windows: 10 (build 19041+) or 11
✅ Virtualization: Enabled in BIOS
✅ RAM: 4 GB minimum (8 GB recommended)
✅ Storage: 10 GB free
✅ WSL: Version 2 enabled
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-DC2626?style=for-the-badge&logo=linux&logoColor=white&labelColor=7F1D1D)](https://share.google/ler97pqp6ZFsl1xu9)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=14532D)](https://share.google/ler97pqp6ZFsl1xu9)

<br>

*Official • Open Source • Updated 2025*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Install Guide** | Step-by-step setup |
| 📗 **WSL Guide** | Run inside Windows |
| 📙 **VM Guide** | VirtualBox / VMware |
| 📕 **Dual-Boot Guide** | Side-by-side install |
| 📓 **Post-Install Guide** | Essential tweaks |

---

## 🛠️ Installation Methods

### 🔀 Choose Your Path

| Method | Best For | Difficulty | Safety |
|--------|----------|:----------:|:------:|
| 🐧 **WSL 2** | Developers, safest | ⭐ | ⭐⭐⭐⭐⭐ |
| 💽 **VirtualBox** | Experimentation | ⭐⭐ | ⭐⭐⭐⭐ |
| 🔀 **Dual-Boot** | Full-time use | ⭐⭐⭐⭐ | ⭐⭐ |
| 💿 **Live USB** | Try before install | ⭐⭐ | ⭐⭐⭐⭐⭐ |

---

### 🪜 Method A — WSL 2 (Recommended)

#### Step 1 — Enable WSL

```powershell
wsl --install
wsl --set-default-version 2
```

#### Step 2 — Restart Windows

Reboot when prompted.

#### Step 3 — List Available Distros

```powershell
wsl --list --online
```

#### Step 4 — Install Tejas

```powershell
wsl --install -d Tejas
```

#### Step 5 — Create User Account

When prompted, enter:

- 👤 Username
- 🔐 Password
- 🔐 Confirm password

#### Step 6 — Update System

```bash
sudo apt update && sudo apt upgrade -y
```

#### Step 7 — Verify

```bash
cat /etc/os-release
```

Expected output: `Tejas GNU/Linux`

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=linux&logoColor=white&labelColor=4C1D95)](https://share.google/ler97pqp6ZFsl1xu9)

</div>

---

### 🪜 Method B — VirtualBox

#### Step 1 — Install VirtualBox

Download from virtualbox.org.

#### Step 2 — Create VM

| Setting | Value |
|---------|-------|
| Type | Linux |
| Version | Debian (64-bit) |
| RAM | 4096 MB |
| Storage | 30 GB VDI |
| CPU | 2 cores |

#### Step 3 — Mount ISO

Attach the Tejas ISO file.

#### Step 4 — Boot and Install

Follow on-screen installer.

#### Step 5 — Install Guest Additions

```bash
sudo apt install virtualbox-guest-utils
```

---

### 🪜 Method C — Dual Boot

#### Step 1 — Create Windows Restore Point

```
Win + S → "Create a restore point" → Create
```

#### Step 2 — Shrink Windows Partition

```
Disk Management → Right-click C: → Shrink Volume
→ Enter size (60 GB minimum)
```

#### Step 3 — Create Bootable USB

Use **Rufus** or **Balena Etcher** with Tejas ISO.

#### Step 4 — Disable Secure Boot

Enter BIOS (F2/DEL) → Disable Secure Boot.

#### Step 5 — Boot from USB

Press F12 during startup → Select USB.

#### Step 6 — Install Alongside Windows

Choose **"Install alongside Windows"** during setup.

---

## ⚙️ Configuration

### 🖥️ Desktop Setup

| Setting | Recommendation |
|---------|----------------|
| 🎨 Theme | Tejas-Dark or Tejas-Light |
| 🔤 Font | Inter or Cantarell |
| 🖼️ Wallpaper | Tejas Default Pack |
| 🧭 Panel Position | Bottom |
| ⏰ Clock Format | 24-hour |
| 🔊 Audio | PulseAudio or PipeWire |

### 💻 Terminal Setup

```bash
# Install zsh and oh-my-zsh
sudo apt install zsh git curl
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Change default shell
chsh -s $(which zsh)
```

### 🧰 Essential Tools

```bash
# Developer stack
sudo apt install build-essential git curl wget \
  python3 python3-pip nodejs npm docker.io

# Media tools
sudo apt install vlc gimp inkscape

# Office suite
sudo apt install libreoffice
```

### 🌐 Networking

```bash
# Show interfaces
ip addr show

# Configure WiFi
nmcli device wifi list
nmcli device wifi connect "SSID" password "PASSWORD"
```

---

## 📦 Package Management

| Command | Purpose |
|---------|---------|
| `sudo apt update` | Refresh package list |
| `sudo apt upgrade` | Upgrade packages |
| `sudo apt install <pkg>` | Install package |
| `sudo apt remove <pkg>` | Remove package |
| `apt search <term>` | Search packages |

---

## 🔧 System Utilities

| Tool | Purpose |
|------|---------|
| 🧹 **Stacer** | System cleaner |
| 📊 **htop** | Process monitor |
| 💾 **Timeshift** | System snapshots |
| 🔥 **UFW** | Firewall |
| 🔒 **Fail2ban** | Intrusion prevention |

---

## 🎮 Gaming Setup

```bash
# Install Steam
sudo apt install steam

# Install Wine for Windows games
sudo apt install wine64

# Install Lutris
sudo apt install lutris
```

---

## 🔗 Windows Integration

### 📂 File Sharing with WSL

Access Windows files from Tejas:

```bash
cd /mnt/c/Users/YourName/
```

Access Tejas files from Windows:

```
\\wsl$\Tejas\home\yourusername\
```

### 🖥️ GUI Apps in WSL

```bash
# Install GUI support
sudo apt install x11-apps

# Launch a GUI app
xeyes
```

### 🖱️ Launch Tejas Apps from Windows

Create a shortcut:

```
wsl.exe -d Tejas -- command
```

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ OS installed | `cat /etc/os-release` | Tejas |
| ✅ Kernel | `uname -r` | Linux 6.x |
| ✅ Package manager | `apt --version` | APT 2.x |
| ✅ Network | `ping -c 3 1.1.1.1` | Replies |
| ✅ GUI works | Launch app | Window opens |
| ✅ WSL works | `wsl -l -v` | Tejas listed |
| ✅ Files share | `/mnt/c` access | Works |
| ✅ Updates run | `apt update` | Success |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 Won't boot | Secure Boot | Disable in BIOS |
| 🚫 No WiFi | Missing firmware | Install firmware-iwlwifi |
| 🚫 Black screen | GPU driver | Boot with `nomodeset` |
| 🚫 WSL fails | Virtualization off | Enable in BIOS |
| 🚫 Slow performance | Not using SSD | Migrate or upgrade |
| 🚫 Can't install app | Repo missing | Add PPA |
| 🚫 Audio broken | Wrong driver | Reconfigure PulseAudio |
| 🚫 USB not detected | Filesystem | Install exfat-fuse |
| 🚫 Time wrong | Dual-boot drift | Sync with NTP |
| 🚫 Dual-boot menu missing | GRUB overwritten | Repair with live USB |

### 🔄 Reset WSL Distro

```powershell
wsl --unregister Tejas
wsl --install -d Tejas
```

---

## 🧰 Command Reference

| Command | Purpose |
|---------|---------|
| `sudo su` | Switch to root |
| `nano file` | Edit file |
| `ls -la` | List files |
| `cp / mv / rm` | File operations |
| `chmod` | Change permissions |
| `systemctl` | Service control |
| `journalctl` | View logs |
| `df -h` | Disk usage |
| `free -h` | Memory usage |
| `neofetch` | System info |

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Tejas Docs** | Official reference |
| 🐧 **Debian Wiki** | Base system docs |
| 💬 **Community Forum** | Help and discussion |
| 🎥 **Video Tutorials** | Visual guides |
| 📚 **Linux Journey** | Free learning |

---

## 💬 FAQ

**Is Tejas Linux free?**
Yes — open source and free forever.

**Will it erase Windows?**
Only if you choose dual-boot and format the wrong partition.

**Can I run it inside Windows?**
Yes — via WSL 2 (no reboot needed).

**Do I need a fast PC?**
No — it runs well on modest hardware.

**Is it suitable for beginners?**
Yes — designed for Windows users transitioning to Linux.

**Can I use Office apps?**
Yes — LibreOffice or Microsoft 365 via web.

**Does it support gaming?**
Yes — Steam, Wine, and Lutris work.

**How do I uninstall it?**
For WSL: `wsl --unregister Tejas`. For dual-boot: remove the partition.

**Will my peripherals work?**
Most do — printers and scanners included.

**Can I switch back to Windows?**
Yes — reboot and select Windows at the boot menu.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **1.4** | Jan 2025 | WSL 2 support |
| 1.2 | Oct 2024 | Updated kernel |
| 1.0 | Jun 2024 | First stable |
| 0.9 | Feb 2024 | Public beta |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-0891B2?style=for-the-badge&logo=linux&logoColor=white&labelColor=0C4A6E)](https://share.google/ler97pqp6ZFsl1xu9)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the Linux community*

</div>
