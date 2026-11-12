---
id: swamp_mid
type: encounter_table
category: Encounter Tables
aliases:
  - swamp_mid
  - Swamp  -- Mid Tier
tags:
  - encounter/random
  - terrain/swamp
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Swamp Dwellers
  - Cult of the Hollow Eye
groups: 4
level_min: 5
terrain:
  - swamp
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for swamp terrain, from company level 5, with 4 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Swamp |
| Company level | 5+ |
| Factions | [[Swamp Dwellers]], [[Cult of the Hollow Eye]] |

## Where it is used

- Rolled on **swamp** terrain from company level 5 until level 7 (then [[Swamp — Late Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Marsh crawlers | [[Swamp Dwellers]] | 30 (30%) | 5+ | 2-4 |
| 2 | Bog troll territory | [[Swamp Dwellers]] | 25 (25%) | 6+ | 1-3 |
| 3 | Cultists performing swamp ritual | [[Cult of the Hollow Eye]] | 25 (25%) | 5+ | 3-6 |
| 4 | Witch and crawlers | [[Swamp Dwellers]] | 20 (20%) | 5+ | 2-4 |

### 1. Marsh crawlers

**Faction:** [[Swamp Dwellers]] · **Weight:** 30 · **Company level:** 5+ · **Size:** 2-4 enemies

Always includes:
- 2× [[Marsh Crawler]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

### 2. Bog troll territory

**Faction:** [[Swamp Dwellers]] · **Weight:** 25 · **Company level:** 6+ · **Size:** 1-3 enemies

Always includes:
- 1× [[Bog Troll]]

May include (if the budget allows):
- 1× [[Bog Lurker]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

### 3. Cultists performing swamp ritual

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 25 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Cult Fanatic]]
- 1× [[Cult Acolyte]]

Remaining slots are filled from the [[Cult of the Hollow Eye]] roster (by each unit's spawn weight).

### 4. Witch and crawlers

**Faction:** [[Swamp Dwellers]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 2-4 enemies

Always includes:
- 1× [[Swamp Witch]]
- 1× [[Marsh Crawler]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
