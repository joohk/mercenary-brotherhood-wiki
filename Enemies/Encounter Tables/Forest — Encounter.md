---
id: forest_early
type: encounter_table
category: Encounter Tables
aliases:
  - forest_early
  - Forest  -- Encounter
tags:
  - encounter/random
  - terrain/forest
  - type/encounter_table
source: enemies/encounter_tables_forest.json
factions:
  - Wolf Pack
  - Bandits
  - Beasts
  - Ratkin Swarm
  - Feral Gnolls
  - Greenskin Warband
groups: 9
level_min: 1
terrain:
  - forest
trigger: random
---

A random encounter table for forest terrain, from company level 1, with 9 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Forest |
| Company level | 1+ |
| Factions | [[Wolf Pack (Faction)\|Wolf Pack]], [[Bandits]], [[Beasts]], [[Ratkin Swarm]], [[Feral Gnolls]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **forest** terrain from company level 1 until level 3 (then [[Forest — Mid Tier]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Wolf Pack group | [[Wolf Pack (Faction)\|Wolf Pack]] | 60 (27.3%) | 1+ | 3-6 |
| 2 | Wolf Pack group | [[Wolf Pack (Faction)\|Wolf Pack]] | 25 (11.4%) | 3+ | 2-5 |
| 3 | Bandits group | [[Bandits]] | 15 (6.8%) | 1+ | 2-4 |
| 4 | Wild boar encounter | [[Beasts]] | 30 (13.6%) | 1+ | 2-4 |
| 5 | Ratkin foragers | [[Ratkin Swarm]] | 20 (9.1%) | 1-3 | 3-6 |
| 6 | Ratkin raiding party | [[Ratkin Swarm]] | 10 (4.5%) | 1-3 | 3-6 |
| 7 | Feral ambush | [[Feral Gnolls]] | 20 (9.1%) | 1-3 | 3-5 |
| 8 | Gnoll hex-touched ritual | [[Feral Gnolls]] | 15 (6.8%) | 1-3 | 3-5 |
| 9 | Goblin tunnel raiders | [[Greenskin Warband]] | 25 (11.4%) | 1+ | 3-6 |

### 1. Wolf Pack group

**Faction:** [[Wolf Pack (Faction)|Wolf Pack]] · **Weight:** 60 · **Company level:** 1+ · **Size:** 3-6 enemies

Always includes:
- 3× [[Wolf]]

Remaining slots are filled from the [[Wolf Pack (Faction)|Wolf Pack]] roster (by each unit's spawn weight).

### 2. Wolf Pack group

**Faction:** [[Wolf Pack (Faction)|Wolf Pack]] · **Weight:** 25 · **Company level:** 3+ · **Size:** 2-5 enemies

Always includes:
- 2× [[Wolf]]
- 1× [[Dire Wolf]]

Remaining slots are filled from the [[Wolf Pack (Faction)|Wolf Pack]] roster (by each unit's spawn weight).

### 3. Bandits group

**Faction:** [[Bandits]] · **Weight:** 15 · **Company level:** 1+ · **Size:** 2-4 enemies

Always includes:
- 2× [[Orc Bandit Raider]]

Remaining slots are filled from the [[Bandits]] roster (by each unit's spawn weight).

### 4. Wild boar encounter

**Faction:** [[Beasts]] · **Weight:** 30 · **Company level:** 1+ · **Size:** 2-4 enemies

Always includes:
- 2× [[Wild Boar]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 5. Ratkin foragers

*Early game swarm*

**Faction:** [[Ratkin Swarm]] · **Weight:** 20 · **Company level:** 1-3 · **Size:** 3-6 enemies

Always includes:
- 2× [[Ratkin Scrapper]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 36.4%
- [[Ratkin Tunneler]] — 22.7%
- [[Ratkin Slinger]] — 18.2%
- [[Ratkin Brute]] — 13.6%
- [[Ratkin Plague Shaman]] — 9.1%

### 6. Ratkin raiding party

*Led by a brute with scrapper escorts*

**Faction:** [[Ratkin Swarm]] · **Weight:** 10 · **Company level:** 1-3 · **Size:** 3-6 enemies

Always includes:
- 1× [[Ratkin Brute]]
- 1× [[Ratkin Scrapper]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 31.8%
- [[Ratkin Tunneler]] — 22.7%
- [[Ratkin Slinger]] — 18.2%
- [[Ratkin Alchemist]] — 10.9%
- [[Ratkin Plague Shaman]] — 9.1%
- [[Ratkin Brute]] — 7.3%

### 7. Feral ambush

*Wild men lurking in trees*

**Faction:** [[Feral Gnolls]] · **Weight:** 20 · **Company level:** 1-3 · **Size:** 3-5 enemies

Always includes:
- 1× [[Gnoll Savage]]

May include (if the budget allows):
- 1× [[Gnoll Stalker]]

Remaining slots filled from:
- [[Gnoll Savage]] — 26.1%
- [[Gnoll Whelp]] — 26.1%
- [[Gnoll Stalker]] — 21.7%
- [[Gnoll Bone-Render]] — 17.4%
- [[Gnoll Hex-Touched]] — 8.7%

### 8. Gnoll hex-touched ritual

*A glowing-eyed shaman-spawn flanked by bone-renders; kill it fast*

**Faction:** [[Feral Gnolls]] · **Weight:** 15 · **Company level:** 1-3 · **Size:** 3-5 enemies

Always includes:
- 1× [[Gnoll Hex-Touched]]
- 2× [[Gnoll Savage]]

May include (if the budget allows):
- 1× [[Gnoll Bone-Render]]

Remaining slots filled from:
- [[Gnoll Savage]] — 42.1%
- [[Gnoll Bone-Render]] — 26.3%
- [[Gnoll Stalker]] — 21.1%
- [[Gnoll Hex-Touched]] — 10.5%

### 9. Goblin tunnel raiders

*Goblins ambushing from the undergrowth*

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 1+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Goblin Skirmisher]]

May include (if the budget allows):
- 1× [[Goblin Poisoner]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 70%
- [[Goblin Poisoner]] — 30%

## Referenced by

- **Garrisons bases:** [[Goblin Tunnels (Enemy Base)|Goblin Tunnels]], [[Wolf Den]]

*Generated from `enemies/encounter_tables_forest.json`. Edits will be overwritten — put your own notes in Notes/.*
