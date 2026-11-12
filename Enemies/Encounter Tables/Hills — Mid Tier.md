---
id: hills_mid
type: encounter_table
category: Encounter Tables
aliases:
  - hills_mid
  - Hills  -- Mid Tier
tags:
  - encounter/random
  - terrain/hills
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Wilding Elves
  - Greenskin Warband
  - Beasts
  - Deserters
  - Kesharan Dominion
  - Saurian Legions
groups: 6
level_min: 5
terrain:
  - hills
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for hills terrain, from company level 5, with 6 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Hills |
| Company level | 5+ |
| Factions | [[Wilding Elves]], [[Greenskin Warband]], [[Beasts]], [[Deserters]], [[Kesharan Dominion]], [[Saurian Legions]] |

## Where it is used

- Rolled on **hills** terrain from company level 5.

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Barbarian war party | [[Wilding Elves]] | 35 (25%) | 5+ | 3-6 |
| 2 | Orc raiding force | [[Greenskin Warband]] | 30 (21.4%) | 5+ | 3-6 |
| 3 | Cave troll territory | [[Beasts]] | 15 (10.7%) | 7+ | 1-2 |
| 4 | Deserter hideout | [[Deserters]] | 20 (14.3%) | 5+ | 3-5 |
| 5 | Kesharan patrol | [[Kesharan Dominion]] | 20 (14.3%) | 5+ | 4-7 |
| 6 | Saurian skink scouts | [[Saurian Legions]] | 20 (14.3%) | 5+ | 3-6 |

### 1. Barbarian war party

**Faction:** [[Wilding Elves]] · **Weight:** 35 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Wilding Raider]]
- 1× [[Wilding Berserker]]

May include (if the budget allows):
- 1× [[Wilding Huntsman]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 2. Orc raiding force

*Dire wolves run alongside the brutes*

**Faction:** [[Greenskin Warband]] · **Weight:** 30 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Orc Brute]]

May include (if the budget allows):
- 1× [[Ogre]]
- 1× [[Goblin Wolfrider]]

Remaining slots filled from:
- [[Orc Brute]] — 41.7%
- [[Goblin Wolfrider]] — 27.8%
- [[Ogre]] — 16.7%
- [[Dire Wolf]] — 13.9%

### 3. Cave troll territory

**Faction:** [[Beasts]] · **Weight:** 15 · **Company level:** 7+ · **Size:** 1-2 enemies

Always includes:
- 1× [[Cave Troll]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 4. Deserter hideout

**Faction:** [[Deserters]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Deserter Footman]]

May include (if the budget allows):
- 1× [[Deserter Sergeant]]

Remaining slots are filled from the [[Deserters]] roster (by each unit's spawn weight).

### 5. Kesharan patrol

*Dominion scouts in the hills*

**Faction:** [[Kesharan Dominion]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Kesharan Guard]]
- 2× [[Slave Conscript]]

Remaining slots are filled from the [[Kesharan Dominion]] roster (by each unit's spawn weight).

### 6. Saurian skink scouts

*Forward reconnaissance*

**Faction:** [[Saurian Legions]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 1× [[Skink Javelineer]]
- 2× [[Skink Screen]]

Remaining slots are filled from the [[Saurian Legions]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Orc Warchief's Stronghold]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
