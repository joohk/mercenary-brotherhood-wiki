---
id: stalagmite_mid
type: encounter_table
category: Encounter Tables
aliases:
  - stalagmite_mid
tags:
  - encounter/random
  - terrain/stalagmite_field
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Duergar
  - The Umbral Court
groups: 2
level_min: 4
terrain:
  - stalagmite_field
trigger: random
---

A random encounter table for stalagmite field terrain, from company level 4, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Stalagmite Field |
| Company level | 4+ |
| Factions | [[Duergar]], [[The Umbral Court]] |

## Where it is used

- Rolled on **stalagmite field** terrain from company level 4 until level 6 (then [[Deep Stalagmite Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Duergar group | [[Duergar]] | 35 (50%) | 4+ | 4-7 |
| 2 | The Umbral Court group | [[The Umbral Court]] | 35 (50%) | 4+ | 4-6 |

### 1. Duergar group

**Faction:** [[Duergar]] · **Weight:** 35 · **Company level:** 4+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 44.4%
- [[Duergar Crossbowman]] — 28.2%
- [[Duergar Ironguard]] — 16.1%
- [[Duergar Taskmaster]] — 6.5%
- [[Copper Golem]] — 4.8%

### 2. The Umbral Court group

**Faction:** [[The Umbral Court]] · **Weight:** 35 · **Company level:** 4+ · **Size:** 4-6 enemies

Always includes:
- 1× [[Umbral Swordsman]]
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

## Referenced by

- **Defends dungeons:** [[Spider Lair]]
- **Garrisons bases:** [[Umbral Patrol Camp]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
