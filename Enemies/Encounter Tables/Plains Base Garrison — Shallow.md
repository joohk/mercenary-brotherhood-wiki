---
id: plains_base_mid
type: encounter_table
category: Encounter Tables
aliases:
  - plains_base_mid
  - Plains Base Garrison  -- Shallow
tags:
  - encounter/static
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_bases.json
factions:
  - Rival Mercenaries
  - Bandits
  - Deserters
groups: 3
level_max: 4
level_min: 3
terrain:
  - plains
trigger: static
---

A static encounter table (fought at a fixed location) for plains terrain, at company levels 3-4, with 3 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Plains |
| Company level | 3-4 |
| Factions | [[Rival Mercenaries]], [[Bandits]], [[Deserters]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Mercenary lodge garrison | [[Rival Mercenaries]] | 50 (33.3%) | 3-4 | 4-6 |
| 2 | Bandit fortress garrison | [[Bandits]] | 50 (33.3%) | 3-4 | 4-6 |
| 3 | Deserter fort garrison | [[Deserters]] | 50 (33.3%) | 3-4 | 4-6 |

### 1. Mercenary lodge garrison

*Disciplined sellswords behind shield-bearers.*

**Faction:** [[Rival Mercenaries]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Sellsword (Enemy)|Sellsword]]
- 1× [[Shield Bearer]]

Remaining slots filled from:
- [[Sellsword (Enemy)|Sellsword]] — 39.1%
- [[Mercenary Crossbowman]] — 26.1%
- [[Shield Bearer]] — 21.7%
- [[Mercenary Mage]] — 13%

### 2. Bandit fortress garrison

*Raiders and cutthroats under a captain.*

**Faction:** [[Bandits]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Bandit Cutthroat]]
- 1× [[Bandit Captain]]

Remaining slots filled from:
- [[Bandit Cutthroat]] — 30.3%
- [[Orc Bandit Raider]] — 22.7%
- [[Elf Bandit Archer]] — 22.7%
- [[Orc Thug]] — 15.2%
- [[Goblin Bandit Shaman]] — 9.1%

### 3. Deserter fort garrison

*Ex-soldiers holding a defensive line.*

**Faction:** [[Deserters]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Deserter Swordsman]]
- 1× [[Deserter Sergeant]]

Remaining slots filled from:
- [[Deserter Footman]] — 27.6%
- [[Deserter Swordsman]] — 23.6%
- [[Deserter Militia]] — 19.7%
- [[Deserter Archer]] — 19.7%
- [[Rogue Battlemage]] — 9.4%

## Referenced by

- **Garrisons bases:** [[Bandit Fortress]], [[Deserter Fort]], [[Mercenary Lodge]]

*Generated from `enemies/encounter_tables_bases.json`. Edits will be overwritten — put your own notes in Notes/.*
