---
id: plains_mid
type: encounter_table
category: Encounter Tables
aliases:
  - plains_mid
  - Plains  -- Mid Tier
tags:
  - encounter/random
  - terrain/plains
  - terrain/road
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Bandits
  - Veteran Company
  - Deserters
  - Rival Mercenaries
  - Wilding Elves
  - Kesharan Dominion
  - Saurian Legions
  - The Inquisition
groups: 9
level_min: 5
terrain:
  - plains
  - road
trigger: random
---

A random encounter table for plains and road terrain, from company level 5, with 9 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Plains, Road |
| Company level | 5+ |
| Factions | [[Bandits]], [[Veteran Company]], [[Deserters]], [[Rival Mercenaries]], [[Wilding Elves]], [[Kesharan Dominion]], [[Saurian Legions]], [[The Inquisition]] |

## Where it is used

- Rolled on **bridge** terrain from company level 5 until level 7 (then [[Plains — Late Tier]]).
- Rolled on **plains** terrain from company level 5 until level 7 (then [[Plains — Late Tier]]).
- Rolled on **road** terrain from company level 5 until level 7 (then [[Plains — Late Tier]]).
- Rolled on **town** terrain from company level 5 until level 7 (then [[Plains — Late Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Bandits group | [[Bandits]] | 50 (20.8%) | 5+ | 3-6 |
| 2 | Veteran Company group | [[Veteran Company]] | 30 (12.5%) | 7+ | 2-5 |
| 3 | Bandits group | [[Bandits]] | 20 (8.3%) | 5+ | 4-7 |
| 4 | Deserter band with sergeant | [[Deserters]] | 30 (12.5%) | 5+ | 3-6 |
| 5 | Mercenary company patrol | [[Rival Mercenaries]] | 25 (10.4%) | 6+ | 3-5 |
| 6 | Barbarian raiding party | [[Wilding Elves]] | 25 (10.4%) | 5+ | 3-6 |
| 7 | Kesharan slave column | [[Kesharan Dominion]] | 20 (8.3%) | 5+ | 4-7 |
| 8 | Saurian legion patrol | [[Saurian Legions]] | 20 (8.3%) | 5+ | 3-6 |
| 9 | Inquisition zealot procession | [[The Inquisition]] | 20 (8.3%) | 5+ | 4-7 |

### 1. Bandits group

**Faction:** [[Bandits]] · **Weight:** 50 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Orc Bandit Raider]]

May include (if the budget allows):
- 1× [[Bandit Captain]]

Remaining slots are filled from the [[Bandits]] roster (by each unit's spawn weight).

### 2. Veteran Company group

**Faction:** [[Veteran Company]] · **Weight:** 30 · **Company level:** 7+ · **Size:** 2-5 enemies

Always includes:
- 2× [[Human Veteran Soldier]]

Remaining slots are filled from the [[Veteran Company]] roster (by each unit's spawn weight).

### 3. Bandits group

**Faction:** [[Bandits]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 4-7 enemies

Always includes:
- 3× [[Orc Bandit Raider]]
- 2× [[Elf Bandit Archer]]

Remaining slots are filled from the [[Bandits]] roster (by each unit's spawn weight).

### 4. Deserter band with sergeant

**Faction:** [[Deserters]] · **Weight:** 30 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Deserter Footman]]
- 1× [[Deserter Sergeant]]

Remaining slots filled from:
- [[Deserter Footman]] — 36%
- [[Deserter Militia]] — 20%
- [[Deserter Swordsman]] — 14.4%
- [[Deserter Archer]] — 20%
- [[Rogue Battlemage]] — 9.6%

### 5. Mercenary company patrol

**Faction:** [[Rival Mercenaries]] · **Weight:** 25 · **Company level:** 6+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Sellsword (Enemy)|Sellsword]]

May include (if the budget allows):
- 1× [[Shield Bearer]]

Remaining slots filled from:
- [[Sellsword (Enemy)|Sellsword]] — 54.9%
- [[Mercenary Crossbowman]] — 30.5%
- [[Mercenary Mage]] — 14.6%

### 6. Barbarian raiding party

**Faction:** [[Wilding Elves]] · **Weight:** 25 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Wilding Raider]]

May include (if the budget allows):
- 1× [[Wilding Berserker]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 7. Kesharan slave column

*Slaves herded by a driver*

**Faction:** [[Kesharan Dominion]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 4-7 enemies

Always includes:
- 3× [[Slave Conscript]]
- 1× [[Slave Driver]]

Remaining slots are filled from the [[Kesharan Dominion]] roster (by each unit's spawn weight).

### 8. Saurian legion patrol

*Saurian warriors with skink screen*

**Faction:** [[Saurian Legions]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Saurian Legionary]]
- 1× [[Skink Screen]]

Remaining slots are filled from the [[Saurian Legions]] roster (by each unit's spawn weight).

### 9. Inquisition zealot procession

**Faction:** [[The Inquisition]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Zealot (Enemy)|Zealot]]
- 1× [[Flagellant]]

May include (if the budget allows):
- 1× [[Witch Finder]]

Remaining slots are filled from the [[The Inquisition]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
