---
id: tunnel_mid
type: encounter_table
category: Encounter Tables
aliases:
  - tunnel_mid
tags:
  - encounter/random
  - terrain/tunnel
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Duergar
  - The Umbral Court
groups: 4
level_min: 3
terrain:
  - tunnel
trigger: random
---

A random encounter table for tunnel terrain, from company level 3, with 4 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Tunnel |
| Company level | 3+ |
| Factions | [[Duergar]], [[The Umbral Court]] |

## Where it is used

- Rolled on **tunnel** terrain from company level 3 until level 5 (then [[Deep Tunnel Encounter]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Duergar group | [[Duergar]] | 40 (45.5%) | 3+ | 3-6 |
| 2 | Foundry war-construct escort | [[Duergar]] | 8 (9.1%) | 5+ | 3-5 |
| 3 | Mithril war-construct vanguard | [[Duergar]] | 5 (5.7%) | 8+ | 3-5 |
| 4 | The Umbral Court group | [[The Umbral Court]] | 35 (39.8%) | 3+ | 3-5 |

### 1. Duergar group

**Faction:** [[Duergar]] · **Weight:** 40 · **Company level:** 3+ · **Size:** 3-6 enemies

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

**Faction:** [[The Umbral Court]] · **Weight:** 35 · **Company level:** 3+ · **Size:** 3-5 enemies

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

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
