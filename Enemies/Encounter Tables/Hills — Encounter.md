---
id: hills_early
type: encounter_table
category: Encounter Tables
aliases:
  - hills_early
  - Hills  -- Encounter
tags:
  - encounter/random
  - terrain/hills
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Wilding Elves
  - Greenskin Warband
  - Beasts
  - Feral Gnolls
  - Duergar
groups: 9
level_min: 1
terrain:
  - hills
trigger: random
---

A random encounter table for hills terrain, from company level 1, with 9 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Hills |
| Company level | 1+ |
| Factions | [[Wilding Elves]], [[Greenskin Warband]], [[Beasts]], [[Feral Gnolls]], [[Duergar]] |

## Where it is used

- Rolled on **hills** terrain from company level 1 until level 4 (then [[Hills — Mid Tier]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Barbarian scouts | [[Wilding Elves]] | 40 (16.7%) | 2+ | 3-5 |
| 2 | Wilding hunting party | [[Wilding Elves]] | 25 (10.4%) | 3+ | 3-5 |
| 3 | Greenskin foothills camp | [[Greenskin Warband]] | 35 (14.6%) | 1+ | 3-6 |
| 4 | Wild beasts | [[Beasts]] | 25 (10.4%) | 1+ | 2-4 |
| 5 | Feral cave dwellers | [[Feral Gnolls]] | 20 (8.3%) | 1-3 | 3-5 |
| 6 | Duergar slaver raiding party | [[Duergar]] | 30 (12.5%) | 3+ | 4-7 |
| 7 | Dark iron crossbow line | [[Duergar]] | 22 (9.2%) | 3+ | 4-6 |
| 8 | Ironguard patrol | [[Duergar]] | 25 (10.4%) | 3+ | 4-7 |
| 9 | Forge raiders | [[Duergar]] | 18 (7.5%) | 4+ | 4-7 |

### 1. Barbarian scouts

**Faction:** [[Wilding Elves]] · **Weight:** 40 · **Company level:** 2+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Wilding Raider]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 2. Wilding hunting party

*Raiders with a huntsman picking off stragglers (full warband variety arrives at Lv4+)*

**Faction:** [[Wilding Elves]] · **Weight:** 25 · **Company level:** 3+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Wilding Raider]]
- 1× [[Wilding Huntsman]]

Remaining slots filled from:
- [[Wilding Raider]] — 70.6%
- [[Wilding Huntsman]] — 29.4%

### 3. Greenskin foothills camp

*Wolves kept as camp guards*

**Faction:** [[Greenskin Warband]] · **Weight:** 35 · **Company level:** 1+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Orc Grunt]]
- 1× [[Goblin Skirmisher]]

Remaining slots filled from:
- [[Orc Grunt]] — 48%
- [[Goblin Skirmisher]] — 40%
- [[Wolf]] — 12%

### 4. Wild beasts

**Faction:** [[Beasts]] · **Weight:** 25 · **Company level:** 1+ · **Size:** 2-4 enemies

Always includes:
- 2× [[Wild Boar]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 5. Feral cave dwellers

*Outcasts holed up in the hills*

**Faction:** [[Feral Gnolls]] · **Weight:** 20 · **Company level:** 1-3 · **Size:** 3-5 enemies

Always includes:
- 1× [[Gnoll Brute]]
- 1× [[Gnoll Savage]]

Remaining slots filled from:
- [[Gnoll Savage]] — 27.3%
- [[Gnoll Whelp]] — 22.7%
- [[Gnoll Brute]] — 18.2%
- [[Gnoll Bone-Render]] — 22.7%
- [[Gnoll Hex-Touched]] — 9.1%

### 6. Duergar slaver raiding party

*Grey dwarves surfaced to take captives, driven by a taskmaster*

**Faction:** [[Duergar]] · **Weight:** 30 · **Company level:** 3+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]
- 1× [[Duergar Taskmaster]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 57.1%
- [[Duergar Crossbowman]] — 28.6%
- [[Duergar Ironguard]] — 14.3%

### 7. Dark iron crossbow line

*Methodical bolt fire behind a shield screen*

**Faction:** [[Duergar]] · **Weight:** 22 · **Company level:** 3+ · **Size:** 4-6 enemies · **Ranged units:** at most 50%

Always includes:
- 2× [[Duergar Crossbowman]]
- 1× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Crossbowman]] — 43.5%
- [[Duergar Slave Soldier]] — 43.5%
- [[Duergar Ironguard]] — 13%

### 8. Ironguard patrol

*A dark-iron shield wall anchored by a tower-shield veteran*

**Faction:** [[Duergar]] · **Weight:** 25 · **Company level:** 3+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Duergar Ironguard]]
- 2× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 52.4%
- [[Duergar Crossbowman]] — 28.6%
- [[Duergar Ironguard]] — 19%

### 9. Forge raiders

*A dark-smith hurls molten iron behind an ironguard van (Lv4+)*

**Faction:** [[Duergar]] · **Weight:** 18 · **Company level:** 4+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Duergar Dark Smith]]
- 1× [[Duergar Ironguard]]
- 1× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 45%
- [[Duergar Crossbowman]] — 35%
- [[Duergar Ironguard]] — 20%

## Referenced by

- **Garrisons bases:** [[Barbarian Outpost]], [[Greenskin Warren]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
