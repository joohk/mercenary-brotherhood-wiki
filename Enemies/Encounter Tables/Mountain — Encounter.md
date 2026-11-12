---
id: mountain_early
type: encounter_table
category: Encounter Tables
aliases:
  - mountain_early
  - Mountain  -- Encounter
tags:
  - encounter/random
  - terrain/mountain
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Wilding Elves
  - Beasts
  - Greenskin Warband
  - Duergar
groups: 8
level_min: 1
terrain:
  - mountain
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for mountain terrain, from company level 1, with 8 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Mountain |
| Company level | 1+ |
| Factions | [[Wilding Elves]], [[Beasts]], [[Greenskin Warband]], [[Duergar]] |

## Where it is used

- Rolled on **mountain** terrain from company level 1 until level 5 (then [[Mountain — Mid Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Barbarian highland camp | [[Wilding Elves]] | 40 (18.6%) | 2+ | 3-6 |
| 2 | Mountain beasts | [[Beasts]] | 30 (14%) | 1+ | 2-4 |
| 3 | Mountain beasts | [[Beasts]] | 20 (9.3%) | 4+ | 1-2 |
| 4 | Greenskin cave dwellers | [[Greenskin Warband]] | 25 (11.6%) | 1+ | 3-5 |
| 5 | Duergar slaver raiding party | [[Duergar]] | 32 (14.9%) | 3+ | 4-7 |
| 6 | Dark iron crossbow line | [[Duergar]] | 22 (10.2%) | 3+ | 4-6 |
| 7 | Ironguard shield wall | [[Duergar]] | 28 (13%) | 3+ | 4-7 |
| 8 | Stonekeeper delving | [[Duergar]] | 18 (8.4%) | 4+ | 4-7 |

### 1. Barbarian highland camp

**Faction:** [[Wilding Elves]] · **Weight:** 40 · **Company level:** 2+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Wilding Raider]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 2. Mountain beasts

*Wild boar pack at low levels*

**Faction:** [[Beasts]] · **Weight:** 30 · **Company level:** 1+ · **Size:** 2-4 enemies

Always includes:
- 2× [[Wild Boar]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 3. Mountain beasts

*Bear territory (mid+)*

**Faction:** [[Beasts]] · **Weight:** 20 · **Company level:** 4+ · **Size:** 1-2 enemies

Always includes:
- 1× [[Bear]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 4. Greenskin cave dwellers

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 1+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Orc Grunt]]

May include (if the budget allows):
- 1× [[Goblin Poisoner]]

Remaining slots are filled from the [[Greenskin Warband]] roster (by each unit's spawn weight).

### 5. Duergar slaver raiding party

*Grey dwarves emerge from mountain delvings to take captives*

**Faction:** [[Duergar]] · **Weight:** 32 · **Company level:** 3+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Slave Soldier]]
- 1× [[Duergar Taskmaster]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 54.5%
- [[Duergar Crossbowman]] — 27.3%
- [[Duergar Ironguard]] — 18.2%

### 6. Dark iron crossbow line

*Bolt fire from the high crags behind a shield screen*

**Faction:** [[Duergar]] · **Weight:** 22 · **Company level:** 3+ · **Size:** 4-6 enemies · **Ranged units:** at most 50%

Always includes:
- 2× [[Duergar Crossbowman]]
- 1× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Crossbowman]] — 41.7%
- [[Duergar Slave Soldier]] — 41.7%
- [[Duergar Ironguard]] — 16.7%

### 7. Ironguard shield wall

*Duergar fight hardest on their own stone; tower-shield veterans anchor the line*

**Faction:** [[Duergar]] · **Weight:** 28 · **Company level:** 3+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Duergar Ironguard]]
- 1× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 47.6%
- [[Duergar Crossbowman]] — 28.6%
- [[Duergar Ironguard]] — 23.8%

### 8. Stonekeeper delving

*A geomancer cracks the ground beneath the company, screened by ironguard (Lv4+)*

**Faction:** [[Duergar]] · **Weight:** 18 · **Company level:** 4+ · **Size:** 4-7 enemies

Always includes:
- 1× [[Duergar Stonekeeper]]
- 1× [[Duergar Ironguard]]
- 1× [[Duergar Slave Soldier]]

Remaining slots filled from:
- [[Duergar Slave Soldier]] — 42.9%
- [[Duergar Crossbowman]] — 33.3%
- [[Duergar Ironguard]] — 23.8%

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
