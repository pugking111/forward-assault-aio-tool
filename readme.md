# 🎮 Forward Assault AIO Tool

A powerful all-in-one desktop utility for Forward Assault Remix, designed to simplify account management, credit editing, stat customization, and more — all packed into a modern, themed UI.

---

## 🚀 Features

- 💰 **Credit Management**
  - Add credits manually or on a loop
  - Set custom or target credit values
  - Cooldown timing options for safe execution

- 📊 **Stat Editor**
  - Modify kills, deaths, headshots, assists, wins/losses, and playtime
  - Built-in input validation to avoid game-breaking values

- ⚙️ **Settings & Themes**
  - Choose from built-in themes
  - Toggle between dark and light modes
  - Save credentials (AES encrypted)
  - Reset to default with one click

- 📦 **Auto-Update Support**
  - On launch, checks for updates via GitHub
  - Downloads and launches new version installer if available

- 🖥️ **System Tray Mode**
  - Run in the background and reopen anytime from the system tray
  - Quick access to check credits and quit

---

## 🛠 Installation

> This tool is Windows-only.

1. [Download the latest `.exe` installer](https://github.com/pugking111/forward-assault-aio-tool/releases/latest)
2. Run the installer and follow setup instructions.
3. Launch the app and enjoy!

---

## 🔄 Auto-Update System

This app checks `version.json` hosted in this repository to determine whether a new version is available. If found, it downloads the latest `.exe` installer and prompts the user to install it.

**version.json format:**
```json
{
  "version": "1.0.2",
  "download_url": "https://github.com/pugking111/forward-assault-aio-tool/releases/latest/download/ForwardAssaultSetup_v1.0.2.exe"
}
