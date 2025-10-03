# Trash Panda Valley – Mod Organizer 2 Configs

This repository contains the **Mod Organizer 2 configuration files** for the *Trash Panda Valley* Stardew Valley modlist.  
It does **not** include the mods themselves or developer resources — only the configs needed to reproduce categories, separators, and load order.

> 🗂 Repo root is the folder that contains `Trash Panda Valley/` (your MO2 portable install).  
> We intentionally ignore binaries, downloads, logs, and actual mods to keep the repo lean.

---

## Tracked Files

- `Trash Panda Valley/modorganizer.ini` – Global MO2 settings (paths, theme, last profile used)
- `Trash Panda Valley/categories.dat` – Custom separators/categories
- `Trash Panda Valley/profiles/*/modlist.txt` – **Left-pane order + enabled/disabled** state
- `Trash Panda Valley/profiles/*/ini tweaks/` – (optional) per-profile INI tweaks
- `Trash Panda Valley/(Profile_Name).compiler_settings` - Wabbajack Compiler Settings for the List.

> Everything else (mods, downloads, logs, MO2 executables/DLLs) is ignored on purpose.

---

## Ignored (examples)

- `Trash Panda Valley/mods/`, `Trash Panda Valley/downloads/`, `Trash Panda Valley/overwrite/`
- `Trash Panda Valley/logs/`, `Trash Panda Valley/webcache/`, `Trash Panda Valley/crashDumps/`, `Trash Panda Valley/loot/`
- MO2 binaries & support files (e.g., `ModOrganizer.exe`, `QtWebEngineProcess.exe`, `uibase.dll`, `usvfs_*.dll`, etc.)
- `Z - Dev Files/` (docs, art, backups, Wabbajack assets)

See `.gitignore` for the full list.

---

## Setup (Clone/Restore)

1. **Clone** the configs:
   ```bash
   git clone https://github.com/daulvec/Trash-Panda-Valley---Configs.git
