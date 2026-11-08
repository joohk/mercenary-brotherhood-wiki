---
id: ruins_early
type: encounter_table
category: Encounter Tables
aliases:
  - ruins_early
  - Ruins  -- Early
tags:
  - encounter/random
  - terrain/ruins
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - The Restless Dead
  - Bandits
  - Ratkin Swarm
groups: 8
level_max: 4
level_min: 2
terrain:
  - ruins
trigger: random
---

A random encounter table for ruins terrain, at company levels 2-4, with 8 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Ruins |
| Company level | 2-4 |
| Factions | [[The Restless Dead]], [[Bandits]], [[Ratkin Swarm]] |

## Where it is used

- Rolled on **ruins** terrain from company level 1 until level 4 (then [[Ruins — Mid Tier]]).

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | The Restless Dead group | [[The Restless Dead]] | 70 (26.9%) | 2-4 | 3-5 |
| 2 | Shambling dead | [[The Restless Dead]] | 35 (13.5%) | 2-4 | 2-4 |
| 3 | Bone archers | [[The Restless Dead]] | 30 (11.5%) | 2-4 | 3-5 |
| 4 | Ghoul pack | [[The Restless Dead]] | 25 (9.6%) | 3-4 | 2-4 |
| 5 | Risen mob | [[The Restless Dead]] | 30 (11.5%) | 2-4 | 4-6 |
| 6 | Bandits group | [[Bandits]] | 30 (11.5%) | 2-4 | 2-4 |
| 7 | Ratkin nest | [[Ratkin Swarm]] | 25 (9.6%) | 2-4 | 4-7 |
| 8 | Ratkin tunnel breach | [[Ratkin Swarm]] | 15 (5.8%) | 2-4 | 3-6 |

### 1. The Restless Dead group

**Faction:** [[The Restless Dead]] · **Weight:** 70 · **Company level:** 2-4 · **Size:** 3-5 enemies

Always includes:
- 2× [[Skeleton]]
- 1× [[Skeleton Archer]]

Remaining slots filled from:
- [[Skeleton]] — 80%
- [[Skeleton Archer]] — 20%

### 2. Shambling dead

*Slow zombies that soak hits and burst on death*

**Faction:** [[The Restless Dead]] · **Weight:** 35 · **Company level:** 2-4 · **Size:** 2-4 enemies

Always includes:
- 2× [[Zombie]]

Remaining slots filled from:
- [[Zombie]] — 66.7%
- [[Skeleton]] — 33.3%

### 3. Bone archers

*Skeletal bowmen behind a skeleton shield line*

**Faction:** [[The Restless Dead]] · **Weight:** 30 · **Company level:** 2-4 · **Size:** 3-5 enemies · **Ranged units:** at most 60%

Always includes:
- 2× [[Skeleton Archer]]
- 1× [[Skeleton]]

Remaining slots filled from:
- [[Skeleton]] — 47.6%
- [[Skeleton Archer]] — 33.3%
- [[Zombie]] — 19%

### 4. Ghoul pack

*Fast, feral undead that close the distance and frenzy*

**Faction:** [[The Restless Dead]] · **Weight:** 25 · **Company level:** 3-4 · **Size:** 2-4 enemies

Always includes:
- 2× [[Ghoul]]

Remaining slots filled from:
- [[Ghoul]] — 47.6%
- [[Zombie]] — 28.6%
- [[Skeleton]] — 23.8%

### 5. Risen mob

*A mixed press of skeletons and shambling zombies, a bowman loosing over their heads*

**Faction:** [[The Restless Dead]] · **Weight:** 30 · **Company level:** 2-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Skeleton]]
- 2× [[Zombie]]
- 1× [[Skeleton Archer]]

Remaining slots filled from:
- [[Skeleton]] — 40%
- [[Zombie]] — 40%
- [[Skeleton Archer]] — 20%

### 6. Bandits group

**Faction:** [[Bandits]] · **Weight:** 30 · **Company level:** 2-4 · **Size:** 2-4 enemies

Always includes:
- 2× [[Orc Bandit Raider]]

Remaining slots are filled from the [[Bandits]] roster (by each unit's spawn weight).

### 7. Ratkin nest

*Infesting old ruins*

**Faction:** [[Ratkin Swarm]] · **Weight:** 25 · **Company level:** 2-4 · **Size:** 4-7 enemies

Always includes:
- 2× [[Ratkin Scrapper]]
- 1× [[Ratkin Slinger]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 40%
- [[Ratkin Tunneler]] — 25%
- [[Ratkin Slinger]] — 20%
- [[Ratkin Brute]] — 15%

### 8. Ratkin tunnel breach

*Tunnelers flanking from multiple directions*

**Faction:** [[Ratkin Swarm]] · **Weight:** 15 · **Company level:** 2-4 · **Size:** 3-6 enemies

Always includes:
- 1× [[Ratkin Tunneler]]
- 1× [[Ratkin Scrapper]]

Remaining slots filled from:
- [[Ratkin Scrapper]] — 50%
- [[Ratkin Tunneler]] — 30%
- [[Ratkin Slinger]] — 20%

Ambush wave (arrives during the battle):
- 2× [[Ratkin Tunneler]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
