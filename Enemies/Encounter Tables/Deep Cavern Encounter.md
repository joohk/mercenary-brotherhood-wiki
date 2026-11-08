---
id: cavern_deep
type: encounter_table
category: Encounter Tables
aliases:
  - cavern_deep
tags:
  - encounter/random
  - terrain/cavern
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - The Umbral Court
  - Demons
  - Duergar
groups: 3
level_min: 7
terrain:
  - cavern
trigger: random
---

A random encounter table for cavern terrain, from company level 7, with 3 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Cavern |
| Company level | 7+ |
| Factions | [[The Umbral Court]], [[Demons]], [[Duergar]] |

## Where it is used

- Rolled on **cavern** terrain from company level 7.

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | The Umbral Court group | [[The Umbral Court]] | 30 (37.5%) | 7+ | 4-7 |
| 2 | Demons group | [[Demons]] | 30 (37.5%) | 7+ | 3-6 |
| 3 | Duergar group | [[Duergar]] | 20 (25%) | 9+ | 4-7 |

### 1. The Umbral Court group

**Faction:** [[The Umbral Court]] · **Weight:** 30 · **Company level:** 7+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Umbral Blademaster]]

Remaining slots filled from:
- [[Umbral Swordsman]] — 27.6%
- [[Umbral Archer]] — 20.7%
- [[Giant Spider (Enemy, Umbral Court)|Giant Spider (The Umbral Court)]] — 17.2%
- [[Umbral Blademaster]] — 12.4%
- [[Umbral Shadowcaster]] — 10.3%
- [[Court Spider]] — 8.3%
- [[Umbral Matriarch]] — 3.4%

### 2. Demons group

**Faction:** [[Demons]] · **Weight:** 30 · **Company level:** 7+ · **Size:** 3-6 enemies

Always includes:
- 1× [[Lesser Demon]]
- 1× [[Imp]]

Remaining slots filled from:
- [[Imp]] — 27.6%
- [[Hellhound]] — 24.1%
- [[Lesser Demon]] — 19.3%
- [[Corrupted Knight]] — 15.2%
- [[Demon Brute]] — 10.3%
- [[Arch Demon]] — 3.4%

### 3. Duergar group

**Faction:** [[Duergar]] · **Weight:** 20 · **Company level:** 9+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Duergar Lord]]

Remaining slots filled from:
- [[Duergar Ironguard]] — 35.3%
- [[Duergar Crossbowman]] — 29.4%
- [[Iron Golem]] — 21.2%
- [[Duergar Warpriest]] — 14.1%

## Referenced by

- **Defends dungeons:** [[Duergar Forge Complex]], [[The Deep Tomb]], [[Throne of the Deep King]]
- **Garrisons bases:** [[Demon Incursion Point]], [[Duergar Slave Fortress]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
