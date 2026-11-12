---
id: mountain_mid
type: encounter_table
category: Encounter Tables
aliases:
  - mountain_mid
  - Mountain  -- Mid Tier
tags:
  - encounter/random
  - terrain/mountain
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Wilding Elves
  - Beasts
  - Greenskin Warband
groups: 4
level_min: 6
terrain:
  - mountain
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for mountain terrain, from company level 6, with 4 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Mountain |
| Company level | 6+ |
| Factions | [[Wilding Elves]], [[Beasts]], [[Greenskin Warband]] |

## Where it is used

- Rolled on **mountain** terrain from company level 6.

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Barbarian elite warband | [[Wilding Elves]] | 35 (36.8%) | 6+ | 4-7 |
| 2 | Troll lair | [[Beasts]] | 20 (21.1%) | 6+ | 1-3 |
| 3 | Wyvern nesting ground | [[Beasts]] | 15 (15.8%) | 8+ | 1-2 |
| 4 | Orc stronghold | [[Greenskin Warband]] | 25 (26.3%) | 6+ | 4-7 |

### 1. Barbarian elite warband

**Faction:** [[Wilding Elves]] · **Weight:** 35 · **Company level:** 6+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Wilding Berserker]]
- 1× [[Thornwoad Shaman]]

May include (if the budget allows):
- 1× [[Wilding Bloodsworn]]

Remaining slots are filled from the [[Wilding Elves]] roster (by each unit's spawn weight).

### 2. Troll lair

**Faction:** [[Beasts]] · **Weight:** 20 · **Company level:** 6+ · **Size:** 1-3 enemies

Always includes:
- 1× [[Cave Troll]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 3. Wyvern nesting ground

**Faction:** [[Beasts]] · **Weight:** 15 · **Company level:** 8+ · **Size:** 1-2 enemies

Always includes:
- 1× [[Wyvern]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

### 4. Orc stronghold

*Ogre crushers guard the warlord's hold*

**Faction:** [[Greenskin Warband]] · **Weight:** 25 · **Company level:** 6+ · **Size:** 4-7 enemies

Always includes:
- 2× [[Orc Brute]]
- 1× [[Orc Shaman]]

May include (if the budget allows):
- 1× [[Ogre Crusher]]

Remaining slots filled from:
- [[Orc Brute]] — 52.6%
- [[Ogre]] — 28.9%
- [[Ogre Crusher]] — 18.4%

## Referenced by

- **Garrisons bases:** [[Barbarian Chieftain's Hold]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
