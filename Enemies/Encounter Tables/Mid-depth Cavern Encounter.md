---
id: cavern_mid
type: encounter_table
category: Encounter Tables
aliases:
  - cavern_mid
tags:
  - encounter/random
  - terrain/cavern
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Duergar
  - The Umbral Court
  - Ratkin Swarm
groups: 5
level_min: 4
terrain:
  - cavern
trigger: random
---

A random encounter table for cavern terrain, from company level 4, with 5 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Cavern |
| Company level | 4+ |
| Factions | [[Duergar]], [[The Umbral Court]], [[Ratkin Swarm]] |

## Where it is used

- Rolled on **cavern** terrain from company level 4 until level 6 (then [[Deep Cavern Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Duergar group | [[Duergar]] | 40 (40.8%) | 4+ | 4-7 |
| 2 | Foundry war-construct escort | [[Duergar]] | 8 (8.2%) | 5+ | 3-5 |
| 3 | Mithril war-construct vanguard | [[Duergar]] | 5 (5.1%) | 8+ | 3-5 |
| 4 | The Umbral Court group | [[The Umbral Court]] | 30 (30.6%) | 4+ | 4-6 |
| 5 | Ratkin Swarm group | [[Ratkin Swarm]] | 15 (15.3%) | 4+ | 6-10 |

### 1. Duergar group

**Faction:** [[Duergar]] · **Weight:** 40 · **Company level:** 4+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 44.4%
- [[Duergar Crossbowman]] — 28.2%
- [[Duergar Ironguard]] — 16.1%
- [[Duergar Taskmaster]] — 6.5%
- [[Copper Golem]] — 4.8%

### 2. Foundry war-construct escort

*Duergar handlers marching a golem up from the deep forges (Lv5+)*

**Faction:** [[Duergar]] · **Weight:** 8 · **Company level:** 5+ · **Size:** 3-5 enemies

Always includes:
- 1× [[Iron Golem]]
- 1× [[Duergar Crossbowman]]

Remaining slots filled from:
- [[Duergar Ironguard]] — 36.1%
- [[Duergar Crossbowman]] — 30.1%
- [[Copper Golem]] — 21.7%
- [[Duergar Taskmaster]] — 12%

### 3. Mithril war-construct vanguard

*The duergar deploy their masterwork golem only for the gravest wars (Lv8+)*

**Faction:** [[Duergar]] · **Weight:** 5 · **Company level:** 8+ · **Size:** 3-5 enemies

Always includes:
- 1× [[Mithril Golem]]
- 1× [[Duergar Crossbowman]]

Remaining slots filled from:
- [[Duergar Ironguard]] — 32.6%
- [[Duergar Crossbowman]] — 23.9%
- [[Iron Golem]] — 17.4%
- [[Duergar Warpriest]] — 13%
- [[Copper Golem]] — 13%

### 4. The Umbral Court group

**Faction:** [[The Umbral Court]] · **Weight:** 30 · **Company level:** 4+ · **Size:** 4-6 enemies

Always includes:
- 2× [[Thrall Slave]]

Remaining slots filled from:
- [[Thrall Slave]] — 23.3%
- [[Court Spider]] — 18.1%
- [[Thrall Archer]] — 15.5%
- [[Thrall Taskmaster]] — 13%
- [[Umbral Swordsman]] — 11.4%
- [[Umbral Archer]] — 9.3%
- [[Giant Spider (Enemy, Umbral Court)|Giant Spider (The Umbral Court)]] — 6.2%
- [[Umbral Shadowcaster]] — 3.1%

### 5. Ratkin Swarm group

**Faction:** [[Ratkin Swarm]] · **Weight:** 15 · **Company level:** 4+ · **Size:** 6-10 enemies

Always includes:
- 1× [[Ratkin Brute]]
- 1× [[Ratkin Chieftain]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 42.9%
- [[Ratkin Tunneler]] — 23.8%
- [[Ratkin Slinger]] — 19%
- [[Ratkin Brute]] — 14.3%

## Referenced by

- **Defends dungeons:** [[Duergar Outpost]]
- **Garrisons bases:** [[Duergar Mining Camp]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
