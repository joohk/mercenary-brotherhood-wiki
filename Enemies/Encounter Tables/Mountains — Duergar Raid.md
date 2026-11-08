---
id: mountain_duergar
type: encounter_table
category: Encounter Tables
aliases:
  - mountain_duergar
  - Mountains  -- Duergar Raid
tags:
  - encounter/random
  - terrain/hills
  - terrain/mountain
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Duergar
groups: 5
level_min: 5
pool_scale: 1.3
terrain:
  - mountain
  - hills
trigger: random
---

A random encounter table for mountain and hills terrain, from company level 5, with 5 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Mountain, Hills |
| Company level | 5+ |
| Difficulty × | ×1.3 |
| Factions | [[Duergar]] |

## Where it is used

No terrain or site in the data rolls this table directly; what picks it is not stated in the data.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Duergar slave patrol | [[Duergar]] | 45 (34.6%) | 5-6 | 4-7 |
| 2 | Duergar raiding party with taskmaster | [[Duergar]] | 30 (23.1%) | 6+ | 4-7 |
| 3 | Duergar war party with ironguard and dark smith | [[Duergar]] | 25 (19.2%) | 7+ | 4-7 |
| 4 | Duergar full assault with warpriest | [[Duergar]] | 20 (15.4%) | 8+ | 5-8 |
| 5 | Duergar lord's retinue | [[Duergar]] | 10 (7.7%) | 9+ | 4-7 |

### 1. Duergar slave patrol

*Early encounter with this faction*

**Faction:** [[Duergar]] · **Weight:** 45 · **Company level:** 5-6 · **Size:** 4-7 enemies

Always includes:
- 3× [[Duergar Slave Soldier]]
- 1× [[Duergar Crossbowman]]

Remaining slots are filled from the [[Duergar]] roster (by each unit's spawn weight).

### 2. Duergar raiding party with taskmaster

**Faction:** [[Duergar]] · **Weight:** 30 · **Company level:** 6+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]
- 1× [[Duergar Crossbowman]]
- 1× [[Duergar Taskmaster]]

Remaining slots are filled from the [[Duergar]] roster (by each unit's spawn weight).

### 3. Duergar war party with ironguard and dark smith

**Faction:** [[Duergar]] · **Weight:** 25 · **Company level:** 7+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Ironguard]]
- 1× [[Duergar Dark Smith]]
- 1× [[Duergar Crossbowman]]

May include (if the budget allows):
- 1× [[Duergar Stonekeeper]]

Remaining slots are filled from the [[Duergar]] roster (by each unit's spawn weight).

### 4. Duergar full assault with warpriest

*Late game*

**Faction:** [[Duergar]] · **Weight:** 20 · **Company level:** 8+ · **Size:** 5-8 enemies

Always includes:
- 2× [[Duergar Ironguard]]
- 1× [[Duergar Warpriest]]
- 1× [[Duergar Crossbowman]]

Remaining slots are filled from the [[Duergar]] roster (by each unit's spawn weight).

### 5. Duergar lord's retinue

*Endgame*

**Faction:** [[Duergar]] · **Weight:** 10 · **Company level:** 9+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Duergar Lord]]
- 2× [[Duergar Ironguard]]

May include (if the budget allows):
- 1× [[Duergar Warpriest]]

Remaining slots are filled from the [[Duergar]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
