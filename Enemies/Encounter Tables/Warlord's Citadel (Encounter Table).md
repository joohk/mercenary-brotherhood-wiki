---
id: greenskin_citadel
type: encounter_table
category: Encounter Tables
aliases:
  - Warlord's Citadel
  - greenskin_citadel
tags:
  - encounter/static
  - terrain/castle
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Greenskin Warband
groups: 1
level_min: 1
terrain:
  - castle
trigger: static
---

A static encounter table (fought at a fixed location) for castle terrain, from company level 1, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Castle |
| Company level | 1+ |
| Factions | [[Greenskin Warband]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Greenskin Warband group | [[Greenskin Warband]] | 100 (100%) | 1+ | 22 |

### 1. Greenskin Warband group

**Faction:** [[Greenskin Warband]] · **Weight:** 100 · **Company level:** 1+ · **Size:** 22 enemies

Always includes:
- 1× [[Orc Warchief]]
- 1× [[Ogre Crusher]]
- 1× [[Ogre]]
- 3× [[Orc Brute]]
- 2× [[Orc Shaman]]
- 1× [[Goblin Shaman (Enemy)|Goblin Shaman]]
- 4× [[Orc Grunt]]
- 2× [[Goblin Wolfrider]]
- 4× [[Goblin Poisoner]]
- 3× [[Goblin Skirmisher]]

Remaining slots are filled from the [[Greenskin Warband]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Warlord's Citadel (Enemy Base)|Warlord's Citadel]]

> [!note]- Developer notes
> Castle siege garrison — greenskin warhost. All enemies are is_required so the full garrison spawns regardless of pool budget or the filler cap (a castle map needs ~22 defenders to feel besieged). Static-only; only reachable via the Warlord's Citadel legendary enemy base.

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
