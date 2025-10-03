# Trash Panda Valley – Mod Organizer 2 Configs

This repository contains the **Mod Organizer 2 configuration files** for the *Trash Panda Valley* Stardew Valley modlist.  
It does **not** include the mods themselves or developer resources — only the configs needed to reproduce categories, separators, and load order.

---

## 📂 Repository Contents
- `Trash Panda Valley/modorganizer.ini` – Global MO2 settings (paths, theme, last profile used).
- `Trash Panda Valley/categories.dat` – Custom separators and categories for organizing mods.
- `Trash Panda Valley/profiles/*/modlist.txt` – Left pane load order + enabled/disabled state.
- `Trash Panda Valley/profiles/*/ini tweaks/` – Any per-profile ini tweaks.

---

## 🚫 Ignored Files
To keep the repo lightweight, the following are not tracked:
- `mods/` – Installed mods (can be redownloaded).
- `downloads/` – Archive downloads.
- `logs/`, `webcache/`, `overwrite/`, `crashDumps/`, `loot/` – Runtime / cache files.
- `Z - Dev Files/` – Readme drafts, art, backups, Wabbajack files, etc.

---

## 🔧 How to Use
1. Clone this repository into your working directory.
   ```bash
   git clone https://github.com/daulvec/Trash-Panda-Valley---Configs.git
