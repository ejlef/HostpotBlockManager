# PC Hotspot Manager v2

![Windows 10/11](https://img.shields.io/badge/OS-Windows%2010%2F11-blue)
![Status](https://img.shields.io/badge/Status-Stable-green)

---

## 📌 Overview

**PC Hotspot Manager v2** is a lightweight, portable **Windows utility** that allows you to quickly **lock or unlock your PC Mobile Hotspot**.  
It handles administrator permissions automatically and lets you check your current hotspot policy status in real time.

---

## ✨ Features

* 🔒 **Lock Hotspot** – Block and disable the PC Mobile Hotspot feature
* 🔓 **Unlock Hotspot** – Enable and restore access to the PC Mobile Hotspot
* 📊 **Check Status** – View the current hotspot policy state in real time
* 🛡 **Automatic UAC Elevation** – Automatically requests administrator privileges on launch
* 💻 **Menu-Driven Interface** – Simple, numbered options for fast navigation
* ⚡ **Lightweight & Portable** – Runs directly as a standalone `.exe` with no installation required

---

## 📥 Download

* **ZIP Package:** [Download HostpotBlockManager.zip](https://github.com/user-attachments/files/27422288/HostpotBlockManager.zip)
* **Portable Executable:** Extract and run `HostpotBlockManager.exe` directly

---

## 🚀 How to Use

1. Download [HostpotBlockManager.zip](https://github.com/user-attachments/files/27422288/HostpotBlockManager.zip) and extract the folder.
2. Double-click `HostpotBlockManager.exe` to launch the utility.
3. Click **Yes** on the Windows User Account Control (UAC) prompt to grant administrator access.
4. Enter a number from the menu to apply your change.
5. Restart your PC if prompted so Windows applies the policy update.

---

## 💻 Menu Options

| Option | Action | Description |
| :--- | :--- | :--- |
| **1** | Lock Hotspot | Blocks the Mobile Hotspot feature via Windows Registry |
| **2** | Unlock Hotspot | Re-enables the Mobile Hotspot feature |
| **3** | Refresh Status | Checks and updates the current Registry policy state |
| **4** | Exit | Closes the application |

---

## 📡 Status Indicators

| Status | Meaning |
| :--- | :--- |
| 🔴 `LOCKED` | Hotspot is disabled and blocked |
| 🟢 `UNLOCKED` | Hotspot is enabled and ready to use |
| ⚪ `UNKNOWN / DEFAULT` | No custom Registry policy is set (Windows default) |

---

## ⚙️ Requirements

* **Operating System:** Windows 10 or Windows 11
* **Permissions:** Administrator privileges (requested automatically)
* **Dependencies:** None (standalone `.exe`, no installation required)

---

## ⚠️ Registry Warning

> This tool modifies Windows Registry policies (`NC_ShowSharedAccessUI` under `HKLM\SOFTWARE\Policies\Microsoft\Windows\Network Connections`).  
> A system restart may be required for changes to take full effect.

---

## 🛡 Disclaimer

* Use at your own risk.
* Always back up your Registry or create a system restore point before making system changes.
* Intended for **educational and administrative purposes only**.

---

## 👨‍💻 Author

**ejlef** – Educational Windows Utility Developer
