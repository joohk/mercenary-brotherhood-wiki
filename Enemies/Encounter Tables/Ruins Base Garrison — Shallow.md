---
id: ruins_base_mid
type: encounter_table
category: Encounter Tables
aliases:
  - ruins_base_mid
  - Ruins Base Garrison  -- Shallow
tags:
  - encounter/static
  - terrain/ruins
  - type/encounter_table
source: enemies/encounter_tables_bases.json
factions:
  - Cult of the Hollow Eye
  - The Restless Dead
groups: 2
level_max: 4
level_min: 3
terrain:
  - ruins
trigger: static
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A static encounter table (fought at a fixed location) for ruins terrain, at company levels 3-4, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Ruins |
| Company level | 3-4 |
| Factions | [[Cult of the Hollow Eye]], [[The Restless Dead]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Cultist shrine garrison | [[Cult of the Hollow Eye]] | 50 (50%) | 3-4 | 4-6 |
| 2 | Undead barrow garrison | [[The Restless Dead]] | 50 (50%) | 3-4 | 4-6 |

### 1. Cultist shrine garrison

*Initiates and acolytes around the altar.*

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Cult Initiate]]
- 1× [[Cult Acolyte]]

Remaining slots filled from:
- [[Cult Initiate]] — 28.8%
- [[Cult Torchbearer]] — 20.1%
- [[Cult Chanter]] — 14.4%
- [[Cult Hexer]] — 12.9%
- [[Cult Acolyte]] — 12.9%
- [[Cult Fanatic]] — 10.8%

### 2. Undead barrow garrison

*Skeletons and a ghoul or two among the tombs.*

**Faction:** [[The Restless Dead]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Skeleton]]
- 1× [[Skeleton Archer]]

Remaining slots filled from:
- [[Skeleton]] — 36%
- [[Skeleton Archer]] — 25.2%
- [[Zombie]] — 22.5%
- [[Ghoul]] — 16.2%

## Referenced by

- **Garrisons bases:** [[Cultist Shrine]], [[Undead Barrow]]

*Generated from `enemies/encounter_tables_bases.json`. Edits will be overwritten — put your own notes in Notes/.*
