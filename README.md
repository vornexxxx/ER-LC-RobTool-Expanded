# 🤖 ERLC Auto-Rob Tool (Expanded & Reworked) 🛠️
<img width="810" height="606" alt="image" src="https://github.com/user-attachments/assets/4c603fcf-76a1-443a-b540-6b2e58e8adc0" />

A modernized, community-driven FULL rework of the original [ER:LC Auto-Rob Tool](https://github.com/IceMinisterq/ERLC-Auto-Rob-Tool).

Built using **.NET 9 (WPF)** and **OpenCV**, this tool focuses on ease of use, reliable detection, and precise timing adjustments.

🎨 **Made by** *[vornex.](https://vornex.cc)*  - with love <3

---

## ✨ Features
*   ⚙️ **Advanced Settings Menu** – Configure wide scan areas, adjustment delays, and custom hotkeys directly from the interface.
*   💾 **Persistent Configuration** – Preferences and hotkeys save automatically to `config.json` on startup.
*   🧠 **Automated Memory Solver** – Uses grayscale template matching to read memory minigame numbers in real-time and automatically inputs the pattern across multiple consecutive rounds.
*   ⏱️ **Live Cooldown & Overlay Support** – Track your active cooldown timers through the main UI or a floating mini-overlay. Supports customizable hotkey displays, corrected robbery slots, and status indicators for all actions.
*   🔔 **Startup Update Checker** – Automatically queries the GitHub API on launch to verify you are running the latest release, prompting you with a download link if an update is found.
*   🔊 **Audio Feedback** – Instant sound effects play when actions begin and when cooldowns finish.

---

## 🧩 Supported Robberies

| Default Hotkey | Action | Description |
|:--:|:--|:--|
| `CTRL + 1` | **Lockpick** | Automatically solves the lockpicking minigame. |
| `CTRL + 2` | **Glass Cutting** | Automates the jewelry store glass cutting sequence. |
| `CTRL + 3` | **ATM** | Automatically solves the ATM firewall minigame and processes withdrawal. |
| `CTRL + 4` | **Crowbar** | Executes crowbar minigame clicks on vehicles. |
| `CTRL + 5` | **Memory** | Automatically reads, remembers, and inputs consecutive memory sequences. |

> 💡 All hotkeys can be rebound to your preference in the Settings menu.

---

## ⚠️  Display Requirements
Because this tool relies on screen coordinate tracking and pixel pattern recognition, your system **must** meet the following display settings for the scanners to align:

1.  **Monitor Resolution:** Set your monitor and Roblox game resolution to **1920x1080**. (An in-app notification will warn you on launch if your screen resolution differs).
2.  **Windows Display Scaling:** Set your Windows DPI scaling to **100%** (Settings -> System -> Display -> Scale & Layout).
3.  **HDR (High Dynamic Range):** **DISABLED**. HDR dynamically alters pixel brightness and contrast, which will cause image matching to fail.
4.  **Roblox Window Mode:** Fullscreen or maximized windowed mode at 1080p.

---

## ▶️ How to Use
1. Extract the folder contents to a directory of your choice.
2. Run `ELRCRobTool.exe`.
3. With the tool running, launch Roblox and enter the game.
4. Use the on-screen buttons or your configured global hotkeys (e.g., `CTRL + 5` for Memory) to initiate automation.
5. Press **Stop Actions** on the interface to cancel any running sequence immediately.

---

## 🐛 Support & Troubleshooting
If you encounter any bugs, display misalignments, or general issues while running the tool, please check the existing reports or [open a new issue](https://github.com/vornexxxx/AutoRob-Tool/issues) on the project's repository page.

---

## ⚠️ Disclaimer
This is a community-driven enhancement, not affiliated with the original author or the developers of ER:LC. Use responsibly and in accordance with the game's terms of service. **The creator (vornex.) assumes absolutely no responsibility for any in-game actions, account suspensions, bans, or consequences that may occur as a result of using this software.** Use entirely at your own risk.
