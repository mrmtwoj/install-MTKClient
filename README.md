# 🔧 MTKClient Installation Guide (Windows)

This guide explains how to install [MTKClient](https://github.com/bkerler/mtkclient) on **Windows OS**, covering all necessary dependencies and tools required for working with MediaTek-based Android devices.

---

## 📌 Requirements

Before installing MTKClient, make sure the following components are installed on your system.

---

### 1. 🐍 Python (3.7+)

Required for running MTKClient scripts.  
👉 https://www.python.org/

> ⚠️ Important: During installation, check **“Add Python to PATH”**.

---

### 2. 📁 Windows File System Proxy (WinFsp)

Provides FUSE compatibility for filesystem operations.  
👉 https://winfsp.dev/rel/

---

### 3. 🔐 Win64 OpenSSL v3.5.1

Used for secure SSL/TLS communication in Python modules.  
👉 https://slproweb.com/products/Win32OpenSSL.html

> 💡 Download **Win64 OpenSSL v3.5.1 (Light)**.

---

### 4. 🧰 Visual Studio 2022 Build Tools

Needed to compile native Python dependencies.  
👉 https://visualstudio.microsoft.com/downloads/?q=build+tools

> ✅ Select the following during installation:
- **Desktop development with C++**
- Include **Windows 10/11 SDK**

---

## 🚀 MTKClient Installation

Follow these steps to install MTKClient on Windows:

```bash
git clone https://github.com/bkerler/mtkclient
cd mtkclient
pip install -r requirements.txt
pip install .
```

## 5 Install UsbDk (USB Development Kit)
UsbDk enables low-level USB communication with MediaTek devices.
👉 https://github.com/daynix/UsbDk/releases/
📥 Download the latest UsbDk_*.msi and install it.

---
## 6 Install Qcom & MTK USB Drivers (Version 3.1.9)
These drivers ensure proper detection of your device by Windows.
> 👉 https://www.gsmofficial.com/oppo-qcom-mtk-driver/
- 🧩 Install the drivers after connecting your phone (powered off) in BROM mode.
---
## 7 (Optional) Install ChimeraTool
ChimeraTool is useful for advanced operations like FRP removal, IMEI repair, and flashing.
> 👉 https://chimeratool.com/en/download
- ⚠️ This is optional, but helpful for users working with multiple tools.
