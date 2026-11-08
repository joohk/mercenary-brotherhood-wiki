---
id: plains_mid_captain
type: encounter_table
category: Encounter Tables
aliases:
  - plains_mid_captain
  - Plains  -- Deserter Camp
tags:
  - encounter/static
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Deserters
groups: 1
level_max: 7
level_min: 5
pool_scale: 1.5
terrain:
  - plains
trigger: static
---

A static encounter table (fought at a fixed location) for plains terrain, at company levels 5-7, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Plains |
| Company level | 5-7 |
| Difficulty × | ×1.5 |
| Factions | [[Deserters]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Deserters group | [[Deserters]] | 100 (100%) | 5-7 | 4-6 |

### 1. Deserters group

**Faction:** [[Deserters]] · **Weight:** 100 · **Company level:** 5-7 · **Size:** 4-6 enemies

Always includes:
- 1× [[Deserter Captain]]
- 1× [[Deserter Sergeant]]
- 1× [[Deserter Swordsman]]

Remaining slots filled from:
- [[Deserter Swordsman]] — 31.5%
- [[Deserter Footman]] — 23.6%
- [[Deserter Archer]] — 19.7%
- [[Deserter Militia]] — 15.7%
- [[Rogue Battlemage]] — 9.4%

## Referenced by

- **Garrisons bases:** [[Deserter Hideout]]

> [!note]- Developer notes
> Bridges the L3-L8 captain-camp gap. Tier 3 boss + tier 2 elites + tier 1-2 fillers so a fresh L5 company has a clear escalation target above plains_captain.

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
