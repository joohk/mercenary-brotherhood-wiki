---
id: swamp_late
type: encounter_table
category: Encounter Tables
aliases:
  - swamp_late
  - Swamp  -- Late Tier
tags:
  - encounter/random
  - terrain/swamp
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Swamp Dwellers
  - Cult of the Hollow Eye
groups: 3
level_min: 8
terrain:
  - swamp
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for swamp terrain, from company level 8, with 3 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Swamp |
| Company level | 8+ |
| Factions | [[Swamp Dwellers]], [[Cult of the Hollow Eye]] |

## Where it is used

- Rolled on **swamp** terrain from company level 8.

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Swamp horror emerges | [[Swamp Dwellers]] | 30 (35.3%) | 8+ | 3-5 |
| 2 | Cult sacrifice site | [[Cult of the Hollow Eye]] | 35 (41.2%) | 8+ | 4-7 |
| 3 | Bog troll pack | [[Swamp Dwellers]] | 20 (23.5%) | 8+ | 2-3 |

### 1. Swamp horror emerges

**Faction:** [[Swamp Dwellers]] · **Weight:** 30 · **Company level:** 8+ · **Size:** 3-5 enemies

Always includes:
- 1× [[Swamp Horror]]
- 1× [[Marsh Crawler]]

May include (if the budget allows):
- 1× [[Bog Lurker]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

### 2. Cult sacrifice site

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 35 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Cult Abomination]]
- 1× [[Dark Priest]]
- 2× [[Cult Fanatic]]

Remaining slots are filled from the [[Cult of the Hollow Eye]] roster (by each unit's spawn weight).

### 3. Bog troll pack

**Faction:** [[Swamp Dwellers]] · **Weight:** 20 · **Company level:** 8+ · **Size:** 2-3 enemies

Always includes:
- 2× [[Bog Troll]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Swamp Horror's Lair]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
