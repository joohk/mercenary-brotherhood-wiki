---
id: plains_late
type: encounter_table
category: Encounter Tables
aliases:
  - plains_late
  - Plains  -- Late Tier
tags:
  - encounter/random
  - terrain/plains
  - terrain/road
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Rival Mercenaries
  - Wilding Elves
  - Greenskin Warband
  - Veteran Company
  - Kesharan Dominion
  - Saurian Legions
  - The Inquisition
  - The Dread Host
  - Deserters
groups: 9
level_min: 8
terrain:
  - plains
  - road
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for plains and road terrain, from company level 8, with 9 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Plains, Road |
| Company level | 8+ |
| Factions | [[Rival Mercenaries]], [[Wilding Elves]], [[Greenskin Warband]], [[Veteran Company]], [[Kesharan Dominion]], [[Saurian Legions]], [[The Inquisition]], [[The Dread Host]], [[Deserters]] |

## Where it is used

- Rolled on **bridge** terrain from company level 8.
- Rolled on **plains** terrain from company level 8.
- Rolled on **road** terrain from company level 8.
- Rolled on **town** terrain from company level 8.

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Rival mercenary company | [[Rival Mercenaries]] | 35 (14.9%) | 8+ | 4-7 |
| 2 | Barbarian war party with champion | [[Wilding Elves]] | 30 (12.8%) | 8+ | 4-7 |
| 3 | Greenskin warband | [[Greenskin Warband]] | 25 (10.6%) | 8+ | 4-7 |
| 4 | Veteran patrol | [[Veteran Company]] | 20 (8.5%) | 8+ | 3-5 |
| 5 | Kesharan war party | [[Kesharan Dominion]] | 25 (10.6%) | 8+ | 5-8 |
| 6 | Saurian cohort | [[Saurian Legions]] | 25 (10.6%) | 8+ | 4-7 |
| 7 | Inquisition crusade | [[The Inquisition]] | 25 (10.6%) | 8+ | 4-7 |
| 8 | Dread Host vanguard | [[The Dread Host]] | 25 (10.6%) | 8+ | 4-7 |
| 9 | Rogue knight's retinue | [[Deserters]] | 25 (10.6%) | 8+ | 4-7 |

### 1. Rival mercenary company

*Full strength*

**Faction:** [[Rival Mercenaries]] · **Weight:** 35 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Sellsword (Enemy)|Sellsword]]
- 1× [[Mercenary Crossbowman]]

May include (if the budget allows):
- 1× [[Mercenary Knight]]

Remaining slots are filled from the [[Rival Mercenaries]] roster (by each unit's spawn weight).

### 2. Barbarian war party with champion

**Faction:** [[Wilding Elves]] · **Weight:** 30 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Wilding Berserker]]
- 1× [[Thorn Warden]]

May include (if the budget allows):
- 1× [[Wilding Bloodsworn]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 3. Greenskin warband

*Full orc assault with an ogre or two and dire wolf war beasts*

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Orc Brute]]

May include (if the budget allows):
- 1× [[Ogre]]
- 1× [[Orc Shaman]]

Remaining slots filled from:
- [[Orc Brute]] — 36%
- [[Orc Grunt]] — 32%
- [[Ogre]] — 14.4%
- [[Ogre Crusher]] — 8%
- [[Dire Wolf]] — 9.6%

### 4. Veteran patrol

**Faction:** [[Veteran Company]] · **Weight:** 20 · **Company level:** 8+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Human Veteran Soldier]]
- 1× [[Elf Veteran Archer]]

Remaining slots are filled from the [[Veteran Company]] roster (by each unit's spawn weight).

### 5. Kesharan war party

*Immortals with slave screen and horse archers*

**Faction:** [[Kesharan Dominion]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 5-8 enemies

Always includes:
- 1× [[Kesharan Immortal]]
- 2× [[Slave Conscript]]

May include (if the budget allows):
- 1× [[Kesharan Horse Archer]]

Remaining slots are filled from the [[Kesharan Dominion]] roster (by each unit's spawn weight).

### 6. Saurian cohort

*Full legion formation with temple guard and salamander*

**Faction:** [[Saurian Legions]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Saurian Temple Guard]]
- 2× [[Saurian Legionary]]

May include (if the budget allows):
- 1× [[Salamander Handler]]

Remaining slots are filled from the [[Saurian Legions]] roster (by each unit's spawn weight).

### 7. Inquisition crusade

*Templars with zealot support*

**Faction:** [[The Inquisition]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Templar Knight]]
- 2× [[Zealot (Enemy)|Zealot]]

May include (if the budget allows):
- 1× [[Battle Cleric (Enemy)|Battle Cleric]]

Remaining slots are filled from the [[The Inquisition]] roster (by each unit's spawn weight).

### 8. Dread Host vanguard

*Dark soldiers with thrall screen*

**Faction:** [[The Dread Host]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Dark Soldier]]
- 2× [[Dread Thrall]]

May include (if the budget allows):
- 1× [[Dread Archer]]

Remaining slots are filled from the [[The Dread Host]] roster (by each unit's spawn weight).

### 9. Rogue knight's retinue

*Well-equipped deserter elites*

**Faction:** [[Deserters]] · **Weight:** 25 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Rogue Knight]]
- 1× [[Deserter Captain]]
- 2× [[Deserter Footman]]

May include (if the budget allows):
- 1× [[Deserter Archer]]

Remaining slots are filled from the [[Deserters]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Rogue Knight's Keep]]

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
