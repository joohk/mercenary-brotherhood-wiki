---
id: tunnel_shallow
type: encounter_table
category: Encounter Tables
aliases:
  - tunnel_shallow
tags:
  - encounter/random
  - terrain/tunnel
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Ratkin Swarm
  - Greenskin Warband
groups: 2
level_min: 1
terrain:
  - tunnel
trigger: random
---

A random encounter table for tunnel terrain, from company level 1, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Tunnel |
| Company level | 1+ |
| Factions | [[Ratkin Swarm]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **tunnel** terrain from company level 1 until level 2 (then [[Mid-depth Tunnel Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Ratkin Swarm group | [[Ratkin Swarm]] | 45 (56.2%) | 1-4 | 3-6 |
| 2 | Greenskin Warband group | [[Greenskin Warband]] | 35 (43.8%) | 1-4 | 3-5 |

### 1. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 45 · **Company level:** 1-4 · **Size:** 3-6 enemies

Remaining slots filled from:
- [[Ratkin Scrapper]] — 40.9%
- [[Ratkin Tunneler]] — 27.3%
- [[Ratkin Slinger]] — 22.7%
- [[Ratkin Plague Shaman]] — 9.1%

### 2. Greenskin Warband group

**Faction:** [[Greenskin Warband]] · **Weight:** 35 · **Company level:** 1-4 · **Size:** 3-5 enemies

Always includes:
- 2× [[Goblin Skirmisher]]
- 1× [[Goblin Poisoner]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 58%
- [[Goblin Poisoner]] — 31.2%
- [[Goblin Shaman (Enemy)|Goblin Shaman]] — 10.7%

## Referenced by

- **Defends dungeons:** [[Collapsed Tunnel]]
- **Garrisons bases:** [[Goblin Tunnels (Underground Enemy Base)|Goblin Tunnels]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
