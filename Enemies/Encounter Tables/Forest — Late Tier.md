---
id: forest_late
type: encounter_table
category: Encounter Tables
aliases:
  - forest_late
  - Forest  -- Late Tier
tags:
  - encounter/random
  - terrain/forest
  - type/encounter_table
source: enemies/encounter_tables_forest.json
factions:
  - Beasts
  - Greenskin Warband
  - Cult of the Hollow Eye
  - Vampires
  - The Inquisition
  - The Umbral Court
groups: 8
level_min: 7
pool_scale: 1.4
terrain:
  - forest
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for forest terrain, from company level 7, with 8 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Forest |
| Company level | 7+ |
| Difficulty × | ×1.4 |
| Factions | [[Beasts]], [[Greenskin Warband]], [[Cult of the Hollow Eye]], [[Vampires]], [[The Inquisition]], [[The Umbral Court]] |

## Where it is used

- Rolled on **forest** terrain from company level 7.

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Wyvern hunting ground | [[Beasts]] | 20 (12.3%) | 7+ | 3-6 |
| 2 | Cave troll lair | [[Beasts]] | 15 (9.3%) | 8+ | 4-7 |
| 3 | Full greenskin warband | [[Greenskin Warband]] | 30 (18.5%) | 7+ | 4-7 |
| 4 | Cult abomination patrol | [[Cult of the Hollow Eye]] | 25 (15.4%) | 7+ | 3-6 |
| 5 | Deep-forest summoning grove | [[Cult of the Hollow Eye]] | 10 (6.2%) | 5+ | 4-6 |
| 6 | Vampire hunting party in the deep forest | [[Vampires]] | 20 (12.3%) | 7+ | 3-6 |
| 7 | Inquisition purification force | [[The Inquisition]] | 20 (12.3%) | 7+ | 5-8 |
| 8 | Umbral Court surface raid | [[The Umbral Court]] | 22 (13.6%) | 8+ | 4-7 |

### 1. Wyvern hunting ground

*Wyvern with pack of wolves*

**Faction:** [[Beasts]] · **Weight:** 20 · **Company level:** 7+ · **Size:** 3-6 enemies

Always includes:
- 1× [[Wyvern]]

May include (if the budget allows):
- 2× [[Dire Wolf]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 2. Cave troll lair

*Troll with wolves and boar*

**Faction:** [[Beasts]] · **Weight:** 15 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Cave Troll]]
- 2× [[Dire Wolf]]

May include (if the budget allows):
- 1× [[Wild Boar]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 3. Full greenskin warband

*Ogres anchor the line, dire wolves run with the pack*

**Faction:** [[Greenskin Warband]] · **Weight:** 30 · **Company level:** 7+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Orc Brute]]
- 1× [[Goblin Wolfrider]]

May include (if the budget allows):
- 1× [[Ogre]]
- 1× [[Orc Shaman]]

Remaining slots filled from:
- [[Orc Brute]] — 38.1%
- [[Goblin Wolfrider]] — 25.4%
- [[Ogre]] — 15.3%
- [[Ogre Crusher]] — 8.5%
- [[Dire Wolf]] — 12.7%

### 4. Cult abomination patrol

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 25 · **Company level:** 7+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Cult Fanatic]]
- 1× [[Cult Abomination]]

Remaining slots are filled from the [[Cult of the Hollow Eye]] roster (by each unit's spawn weight).

### 5. Deep-forest summoning grove

*The summoner drags demons from the veil; focus-fire mid-channel*

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 10 · **Company level:** 5+ · **Size:** 4-6 enemies

Always includes:
- 1× [[Cult Summoner]]
- 1× [[Cult Fanatic]]
- 1× [[Cult Torchbearer]]

Remaining slots filled from:
- [[Cult Acolyte]] — 40%
- [[Cult Hexer]] — 33.3%
- [[Void Hound]] — 26.7%

### 6. Vampire hunting party in the deep forest

**Faction:** [[Vampires]] · **Weight:** 20 · **Company level:** 7+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Thrall Militia]]
- 1× [[Vampire Nightblade]]

Remaining slots are filled from the [[Vampires]] roster (by each unit's spawn weight).

### 7. Inquisition purification force

*Burning the forest clean*

**Faction:** [[The Inquisition]] · **Weight:** 20 · **Company level:** 7+ · **Size:** 5-8 enemies

Always includes:
- 1× [[Purifier]]
- 1× [[Templar Knight]]
- 2× [[Zealot (Enemy)|Zealot]]

Remaining slots are filled from the [[The Inquisition]] roster (by each unit's spawn weight).

### 8. Umbral Court surface raid

*Thralls and spiders in the deep forest*

**Faction:** [[The Umbral Court]] · **Weight:** 22 · **Company level:** 8+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Thrall Slave]]
- 1× [[Court Spider]]
- 1× [[Umbral Swordsman]]

Remaining slots are filled from the [[The Umbral Court]] roster (by each unit's spawn weight).

*Generated from `enemies/encounter_tables_forest.json`. Edits will be overwritten — put your own notes in Notes/.*
