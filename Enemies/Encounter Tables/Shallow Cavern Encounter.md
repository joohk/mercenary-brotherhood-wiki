---
id: cavern_shallow
type: encounter_table
category: Encounter Tables
aliases:
  - cavern_shallow
tags:
  - encounter/random
  - terrain/cavern
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Ratkin Swarm
  - Greenskin Warband
groups: 3
level_min: 1
terrain:
  - cavern
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for cavern terrain, from company level 1, with 3 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Cavern |
| Company level | 1+ |
| Factions | [[Ratkin Swarm]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **cavern** terrain from company level 1 until level 3 (then [[Mid-depth Cavern Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Ratkin Swarm group | [[Ratkin Swarm]] | 40 (47.1%) | 1-4 | 4-8 |
| 2 | Greenskin Warband group | [[Greenskin Warband]] | 30 (35.3%) | 1-4 | 3-6 |
| 3 | Ratkin Swarm group | [[Ratkin Swarm]] | 15 (17.6%) | 3-5 | 5-10 |

### 1. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 40 · **Company level:** 1-4 · **Size:** 4-8 enemies

Always includes:
- 2× [[Ratkin Scrapper]]
- 1× [[Ratkin Slinger]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 43.5%
- [[Ratkin Slinger]] — 21.7%
- [[Ratkin Tunneler]] — 17.4%
- [[Ratkin Brute]] — 8.7%
- [[Ratkin Plague Shaman]] — 8.7%

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

### 3. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 15 · **Company level:** 3-5 · **Size:** 5-10 enemies

Always includes:
- 1× [[Ratkin Chieftain]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 43.5%
- [[Ratkin Slinger]] — 21.7%
- [[Ratkin Tunneler]] — 17.4%
- [[Ratkin Brute]] — 8.7%
- [[Ratkin Plague Shaman]] — 8.7%

## Referenced by

- **Defends dungeons:** [[Abandoned Mine Shaft]], [[Ratkin Nest]]
- **Garrisons bases:** [[Ratkin Warren]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
