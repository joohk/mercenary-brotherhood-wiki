---
id: mushroom_shallow
type: encounter_table
category: Encounter Tables
aliases:
  - mushroom_shallow
tags:
  - encounter/random
  - terrain/mushroom_forest
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Ratkin Swarm
  - Greenskin Warband
groups: 2
level_min: 1
terrain:
  - mushroom_forest
trigger: random
---

A random encounter table for mushroom forest terrain, from company level 1, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Mushroom Forest |
| Company level | 1+ |
| Factions | [[Ratkin Swarm]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **mushroom forest** terrain from company level 1 until level 3 (then [[Mid-depth Mushroom Forest Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Ratkin Swarm group | [[Ratkin Swarm]] | 50 (66.7%) | 1-4 | 4-8 |
| 2 | Greenskin Warband group | [[Greenskin Warband]] | 25 (33.3%) | 1-3 | 3-6 |

### 1. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 50 · **Company level:** 1-4 · **Size:** 4-8 enemies

Always includes:
- 1× [[Ratkin Alchemist]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 43.5%
- [[Ratkin Slinger]] — 21.7%
- [[Ratkin Tunneler]] — 17.4%
- [[Ratkin Brute]] — 8.7%
- [[Ratkin Plague Shaman]] — 8.7%

### 2. Greenskin Warband group

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 1-3 · **Size:** 3-6 enemies

Always includes:
- 1× [[Goblin Poisoner]]
- 2× [[Goblin Skirmisher]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 53.6%
- [[Goblin Poisoner]] — 35.7%
- [[Goblin Shaman (Enemy)|Goblin Shaman]] — 10.7%

## Referenced by

- **Defends dungeons:** [[Fungal Grotto]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
