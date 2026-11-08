---
id: boar_den
type: encounter_table
category: Encounter Tables
aliases:
  - Boar Nesting Ground
  - boar_den
tags:
  - encounter/static
  - terrain/forest
  - terrain/hills
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Beasts
groups: 1
level_min: 1
terrain:
  - forest
  - plains
  - hills
trigger: static
---

A static encounter table (fought at a fixed location) for forest, plains and hills terrain, from company level 1, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Forest, Plains, Hills |
| Company level | 1+ |
| Factions | [[Beasts]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Aggressive boar pack | [[Beasts]] | 100 (100%) | 1+ | 2-5 |

### 1. Aggressive boar pack

**Faction:** [[Beasts]] · **Weight:** 100 · **Company level:** 1+ · **Size:** 2-5 enemies

Always includes:
- 2× [[Wild Boar]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Boar Nesting Ground (Enemy Base)|Boar Nesting Ground]], [[Boar Warren]]
- **Monster lair kind:** [[Monster Lair]]
- **Used by points of interest:** [[Monster Lair]]

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
