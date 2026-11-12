---
id: swamp_early
type: encounter_table
category: Encounter Tables
aliases:
  - swamp_early
  - Swamp  -- Encounter
tags:
  - encounter/random
  - terrain/swamp
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Swamp Dwellers
  - Ratkin Swarm
groups: 3
level_min: 1
terrain:
  - swamp
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for swamp terrain, from company level 1, with 3 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Swamp |
| Company level | 1+ |
| Factions | [[Swamp Dwellers]], [[Ratkin Swarm]] |

## Where it is used

- Rolled on **swamp** terrain from company level 1 until level 4 (then [[Swamp — Mid Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Bog lurker ambush | [[Swamp Dwellers]] | 40 (44.4%) | 3+ | 3-6 |
| 2 | Swamp witch with lurkers | [[Swamp Dwellers]] | 30 (33.3%) | 4+ | 3-5 |
| 3 | Ratkin warren | [[Ratkin Swarm]] | 20 (22.2%) | 1+ | 3-5 |

### 1. Bog lurker ambush

**Faction:** [[Swamp Dwellers]] · **Weight:** 40 · **Company level:** 3+ · **Size:** 3-6 enemies

Always includes:
- 3× [[Bog Lurker]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

### 2. Swamp witch with lurkers

**Faction:** [[Swamp Dwellers]] · **Weight:** 30 · **Company level:** 4+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Bog Lurker]]
- 1× [[Swamp Witch]]

Remaining slots are filled from the [[Swamp Dwellers]] roster (by each unit's spawn weight).

### 3. Ratkin warren

*Swamp-dwelling rat-folk*

**Faction:** [[Ratkin Swarm]] · **Weight:** 20 · **Company level:** 1+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Ratkin Scrapper]]

May include (if the budget allows):
- 1× [[Ratkin Brute]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 35%
- [[Ratkin Tunneler]] — 25%
- [[Ratkin Slinger]] — 20%
- [[Ratkin Brute]] — 15%
- [[Ratkin Alchemist]] — 5%

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
