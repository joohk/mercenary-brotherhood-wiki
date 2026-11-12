---
type: guide
tags:
  - guide/mechanics
source: game code (main_gui.py, engine/game_state.py)
---

Where the game keeps its saves, what is in them, and how to edit one safely.

## Where they are

| Setup | Folder |
|---|---|
| Windows | `%APPDATA%\MercenaryBrotherhood\saves\` |
| Mac via CrossOver | `~/Library/Application Support/CrossOver/Bottles/<bottle>/drive_c/users/crossover/AppData/Roaming/MercenaryBrotherhood/saves/` |

The parent `MercenaryBrotherhood` folder also holds `settings.json`, `logs/`, `custom_portraits/` and a second starter mod in `mods/`.

On a Mac, press **Cmd+Shift+G** in Finder and paste the CrossOver path, with your bottle's name in place of `<bottle>`.

## What the files are

| File | What it is |
|---|---|
| `save_1.json`, `save_2.json`, … | Manual save slots |
| `quicksave.json` | The F5 quicksave |
| `autosave.json`, `autosave_1.json`, `autosave_2.json` | The latest autosave and two rotating backups |
| `*.meta.json` | Small summaries shown in the load menu |
| `*.v<N>.bak` | Copies the game makes before upgrading an old save to a new format |
| `steam_autocloud.vdf` | Marks the folder as synced by Steam Cloud |

**Continue** loads whichever save was written most recently.

## Format

Saves are **plain JSON**, with no compression and no checksum, so any text editor or script can read them. They are large (about 15 MB) because the whole world map is stored inside.

- Each mercenary's traits, skills and learned abilities are entries under `effect_manager` → `unit_effects` → their unit ID.
- A spell taught at the [[Magic Academy]] is one entry with an `effect_id` of `trained_<ability id>_<first 8 characters of the unit ID>`. Deleting that entry removes the spell.
- Each academy's current stock is under `arcane_training_catalogs`.

## Editing safely

1. Quit the game first, or the next autosave will overwrite your edit.
2. Copy the `saves` folder somewhere else and edit the copy.
3. Keep the original formatting. The game writes compact JSON (`separators=(",", ":")`). Reading and re-writing the file the same way in Python reproduces it byte for byte, which is an easy way to confirm you changed only what you meant to.
4. Edit the save you play from, and its autosave if it's newer.
5. Copy the edited files back. If Steam reports a sync conflict on launch, choose the **local** files.
