---
id: plains_jotunblight
type: encounter_table
category: Encounter Tables
aliases:
  - plains_jotunblight
  - Plains  -- Jotunblight Invasion
tags:
  - encounter/random
  - terrain/hills
  - terrain/mountain
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - The Jotunblight
groups: 5
level_min: 8
terrain:
  - plains
  - hills
  - mountain
trigger: random
---

A random encounter table for plains, hills and mountain terrain, from company level 8, with 5 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Plains, Hills, Mountain |
| Company level | 8+ |
| Factions | [[The Jotunblight]] |

## Where it is used

No terrain or site in the data rolls this table directly; what picks it is not stated in the data.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Frost wolf vanguard with hill giant | [[The Jotunblight]] | 40 (35.4%) | 8-10 | 3-5 |
| 2 | Hill giant pair with wolf screen | [[The Jotunblight]] | 30 (26.5%) | 9+ | 3-5 |
| 3 | Stone giant with escort | [[The Jotunblight]] | 20 (17.7%) | 9+ | 2-4 |
| 4 | Frost giant war party | [[The Jotunblight]] | 15 (13.3%) | 10+ | 2-4 |
| 5 | Jotun Warlord's host | [[The Jotunblight]] | 8 (7.1%) | 10+ | 3-5 |

### 1. Frost wolf vanguard with hill giant

*First encounter*

**Faction:** [[The Jotunblight]] · **Weight:** 40 · **Company level:** 8-10 · **Size:** 3-5 enemies

Always includes:
- 2× [[Frost Wolf]]
- 1× [[Mountain Cub]]
- 1× [[Hill Giant]]

Remaining slots are filled from the [[The Jotunblight]] roster (by each unit's spawn weight).

### 2. Hill giant pair with wolf screen

**Faction:** [[The Jotunblight]] · **Weight:** 30 · **Company level:** 9+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Hill Giant]]
- 2× [[Frost Wolf]]

Remaining slots are filled from the [[The Jotunblight]] roster (by each unit's spawn weight).

### 3. Stone giant with escort

*Devastating tank*

**Faction:** [[The Jotunblight]] · **Weight:** 20 · **Company level:** 9+ · **Size:** 2-4 enemies

Always includes:
- 1× [[Stone Giant]]
- 1× [[Hill Giant]]

May include (if the budget allows):
- 1× [[Mountain Cub]]

Remaining slots are filled from the [[The Jotunblight]] roster (by each unit's spawn weight).

### 4. Frost giant war party

*Endgame*

**Faction:** [[The Jotunblight]] · **Weight:** 15 · **Company level:** 10+ · **Size:** 2-4 enemies

Always includes:
- 1× [[Frost Giant]]
- 1× [[Hill Giant]]

May include (if the budget allows):
- 1× [[Jotun Shaman]]

Remaining slots are filled from the [[The Jotunblight]] roster (by each unit's spawn weight).

### 5. Jotun Warlord's host

*Ultimate encounter*

**Faction:** [[The Jotunblight]] · **Weight:** 8 · **Company level:** 10+ · **Size:** 3-5 enemies

Always includes:
- 1× [[Jotun Warlord]]
- 1× [[Frost Giant]]

May include (if the budget allows):
- 1× [[Jotun Shaman]]

Remaining slots are filled from the [[The Jotunblight]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
