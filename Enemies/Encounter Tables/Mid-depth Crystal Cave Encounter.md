---
id: crystal_mid
type: encounter_table
category: Encounter Tables
aliases:
  - crystal_mid
tags:
  - encounter/random
  - terrain/crystal_cave
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - Duergar
  - Cult of the Hollow Eye
groups: 2
level_min: 3
terrain:
  - crystal_cave
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for crystal cave terrain, from company level 3, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Crystal Cave |
| Company level | 3+ |
| Factions | [[Duergar]], [[Cult of the Hollow Eye]] |

## Where it is used

- Rolled on **crystal cave** terrain from company level 3 until level 5 (then [[Deep Crystal Cave Encounter]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Duergar group | [[Duergar]] | 35 (53.8%) | 3+ | 3-6 |
| 2 | Cult of the Hollow Eye group | [[Cult of the Hollow Eye]] | 30 (46.2%) | 3+ | 3-5 |

### 1. Duergar group

**Faction:** [[Duergar]] · **Weight:** 35 · **Company level:** 3+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 44.4%
- [[Duergar Crossbowman]] — 28.2%
- [[Duergar Ironguard]] — 16.1%
- [[Duergar Taskmaster]] — 6.5%
- [[Copper Golem]] — 4.8%

### 2. Cult of the Hollow Eye group

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 30 · **Company level:** 3+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Cult Fanatic]]

Remaining slots filled from:
- [[Cult Fanatic]] — 25.7%
- [[Cult Initiate]] — 20%
- [[Cult Acolyte]] — 17.1%
- [[Cult Assassin]] — 12.6%
- [[Dark Priest]] — 10.3%
- [[Cult Summoner]] — 8.6%
- [[Cult Abomination]] — 5.7%

## Referenced by

- **Defends dungeons:** [[Crystal Vault]]

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
