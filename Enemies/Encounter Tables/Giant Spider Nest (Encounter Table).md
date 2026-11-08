---
id: spider_nest_lair
type: encounter_table
category: Encounter Tables
aliases:
  - Giant Spider Nest
  - spider_nest_lair
tags:
  - encounter/static
  - terrain/forest
  - type/encounter_table
source: enemies/encounter_tables_forest.json
factions:
  - Beasts
groups: 1
level_min: 5
pool_scale: 1.2
terrain:
  - forest
trigger: static
---

A static encounter table (fought at a fixed location) for forest terrain, from company level 5, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Forest |
| Company level | 5+ |
| Difficulty × | ×1.2 |
| Factions | [[Beasts]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Spider colony | [[Beasts]] | 100 (100%) | 5+ | 3-6 |

### 1. Spider colony

**Faction:** [[Beasts]] · **Weight:** 100 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 3× [[Giant Spider (Enemy, Beasts)|Giant Spider (Beasts)]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Giant Spider Nest (Enemy Base)|Giant Spider Nest]]
- **Monster lair kind:** [[Monster Lair]]

*Generated from `enemies/encounter_tables_forest.json`. Edits will be overwritten — put your own notes in Notes/.*
