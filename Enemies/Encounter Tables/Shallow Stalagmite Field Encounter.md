---
id: stalagmite_shallow
type: encounter_table
category: Encounter Tables
aliases:
  - stalagmite_shallow
tags:
  - encounter/random
  - terrain/stalagmite_field
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Ratkin Swarm
  - Greenskin Warband
groups: 2
level_min: 1
terrain:
  - stalagmite_field
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for stalagmite field terrain, from company level 1, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Stalagmite Field |
| Company level | 1+ |
| Factions | [[Ratkin Swarm]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **stalagmite field** terrain from company level 1 until level 3 (then [[Mid-depth Stalagmite Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Ratkin Swarm group | [[Ratkin Swarm]] | 40 (57.1%) | 1-4 | 4-7 |
| 2 | Greenskin Warband group | [[Greenskin Warband]] | 30 (42.9%) | 1-4 | 3-6 |

### 1. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 40 · **Company level:** 1-4 · **Size:** 4-7 enemies

Remaining slots filled from:
- [[Ratkin Scrapper]] — 40.9%
- [[Ratkin Tunneler]] — 27.3%
- [[Ratkin Slinger]] — 22.7%
- [[Ratkin Plague Shaman]] — 9.1%

### 2. Greenskin Warband group

**Faction:** [[Greenskin Warband]] · **Weight:** 30 · **Company level:** 1-4 · **Size:** 3-6 enemies

Always includes:
- 2× [[Goblin Skirmisher]]
- 1× [[Orc Grunt]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 43.8%
- [[Orc Grunt]] — 29.2%
- [[Goblin Poisoner]] — 18.2%
- [[Goblin Shaman (Enemy)|Goblin Shaman]] — 8.8%

## Referenced by

- **Garrisons bases:** [[Cave Beast Den]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
