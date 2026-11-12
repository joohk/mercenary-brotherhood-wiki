---
id: forest_mid
type: encounter_table
category: Encounter Tables
aliases:
  - forest_mid
  - Forest  -- Mid Tier
tags:
  - encounter/random
  - terrain/forest
  - type/encounter_table
source: enemies/encounter_tables_forest.json
factions:
  - Beasts
  - Wolf Pack
  - Greenskin Warband
  - Cult of the Hollow Eye
  - The Inquisition
groups: 6
level_min: 4
terrain:
  - forest
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for forest terrain, from company level 4, with 6 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Forest |
| Company level | 4+ |
| Factions | [[Beasts]], [[Wolf Pack (Faction)\|Wolf Pack]], [[Greenskin Warband]], [[Cult of the Hollow Eye]], [[The Inquisition]] |

## Where it is used

- Rolled on **forest** terrain from company level 4 until level 6 (then [[Forest — Late Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Spider nest | [[Beasts]] | 35 (24.1%) | 5+ | 3-6 |
| 2 | Bear encounter | [[Beasts]] | 20 (13.8%) | 4+ | 1-2 |
| 3 | Alpha wolf pack | [[Wolf Pack (Faction)\|Wolf Pack]] | 25 (17.2%) | 5+ | 3-6 |
| 4 | Greenskin forest camp | [[Greenskin Warband]] | 25 (17.2%) | 4+ | 3-6 |
| 5 | Cultist ritual site | [[Cult of the Hollow Eye]] | 20 (13.8%) | 5+ | 4-6 |
| 6 | Inquisition witch hunt | [[The Inquisition]] | 20 (13.8%) | 4+ | 4-7 |

### 1. Spider nest

**Faction:** [[Beasts]] · **Weight:** 35 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 3× [[Giant Spider (Enemy, Beasts)|Giant Spider (Beasts)]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 2. Bear encounter

**Faction:** [[Beasts]] · **Weight:** 20 · **Company level:** 4+ · **Size:** 1-2 enemies

Always includes:
- 1× [[Bear]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 3. Alpha wolf pack

**Faction:** [[Wolf Pack (Faction)|Wolf Pack]] · **Weight:** 25 · **Company level:** 5+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Wolf]]
- 1× [[Dire Wolf]]

May include (if the budget allows):
- 1× [[Alpha Wolf]]

Remaining slots are filled from the [[Wolf Pack (Faction)|Wolf Pack]] roster (by each unit's spawn weight).

### 4. Greenskin forest camp

*A lumbering ogre among the goblins, wolves lurk at the edges*

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 4+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Goblin Skirmisher]]
- 1× [[Goblin Poisoner]]

May include (if the budget allows):
- 1× [[Ogre]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 48.3%
- [[Goblin Poisoner]] — 27.6%
- [[Ogre]] — 10.3%
- [[Wolf]] — 13.8%

### 5. Cultist ritual site

*Fanatic leads with chanter and torchbearer support*

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 20 · **Company level:** 5+ · **Size:** 4-6 enemies

Always includes:
- 1× [[Cult Initiate]]
- 1× [[Cult Chanter]]

May include (if the budget allows):
- 1× [[Cult Torchbearer]]
- 1× [[Cult Fanatic]]

Remaining slots are filled from the [[Cult of the Hollow Eye]] roster (by each unit's spawn weight).

### 6. Inquisition witch hunt

*Zealots searching the woods*

**Faction:** [[The Inquisition]] · **Weight:** 20 · **Company level:** 4+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Witch Finder]]
- 2× [[Zealot (Enemy)|Zealot]]

Remaining slots are filled from the [[The Inquisition]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_forest.json`. Edits will be overwritten — put your own notes in Notes/.*
