---
id: fungalbog_shallow
type: encounter_table
category: Encounter Tables
aliases:
  - fungalbog_shallow
tags:
  - encounter/random
  - terrain/fungal_bog
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Ratkin Swarm
  - Swamp Dwellers
groups: 2
level_min: 2
terrain:
  - fungal_bog
trigger: random
---

A random encounter table for fungal bog terrain, from company level 2, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Fungal Bog |
| Company level | 2+ |
| Factions | [[Ratkin Swarm]], [[Swamp Dwellers]] |

## Where it is used

- Rolled on **fungal bog** terrain from company level 2 until level 4 (then [[Mid-depth Fungal Bog Encounter]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Ratkin Swarm group | [[Ratkin Swarm]] | 35 (50%) | 2-5 | 4-8 |
| 2 | Swamp Dwellers group | [[Swamp Dwellers]] | 35 (50%) | 3-5 | 3-6 |

### 1. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 35 · **Company level:** 2-5 · **Size:** 4-8 enemies

Remaining slots filled from:
- [[Ratkin Scrapper]] — 39.1%
- [[Ratkin Tunneler]] — 21.7%
- [[Ratkin Slinger]] — 17.4%
- [[Ratkin Brute]] — 13%
- [[Ratkin Plague Shaman]] — 8.7%

### 2. Swamp Dwellers group

**Faction:** [[Swamp Dwellers]] · **Weight:** 35 · **Company level:** 3-5 · **Size:** 3-6 enemies

Always includes:
- 2× [[Bog Lurker]]

Remaining slots filled from:
- [[Bog Lurker]] — 40%
- [[Marsh Crawler]] — 32%
- [[Swamp Witch]] — 20%
- [[Bog Troll]] — 8%

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
