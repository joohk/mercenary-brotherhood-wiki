---
id: road_ambush
type: encounter_table
category: Encounter Tables
aliases:
  - road_ambush
  - Road  -- Ambush
tags:
  - encounter/random
  - terrain/road
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Deserters
  - Bandits
  - Cult of the Hollow Eye
  - Saurian Legions
groups: 4
level_min: 3
terrain:
  - road
trigger: random
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A random encounter table for road terrain, from company level 3, with 4 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Road |
| Company level | 3+ |
| Factions | [[Deserters]], [[Bandits]], [[Cult of the Hollow Eye]], [[Saurian Legions]] |

## Where it is used

- Rolled on **bridge** terrain from company level 3 until level 4 (then [[Plains — Mid Tier]]).
- Rolled on **road** terrain from company level 3 until level 4 (then [[Plains — Mid Tier]]).
- Rolled on **town** terrain from company level 3 until level 4 (then [[Plains — Mid Tier]]).

See [[Encounters]] for the full terrain progression. Fixed sites also use it — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Deserter ambush | [[Deserters]] | 40 (36.4%) | 3+ | 3-6 |
| 2 | Bandit highway robbery | [[Bandits]] | 35 (31.8%) | 3+ | 3-6 |
| 3 | Cultist waylay | [[Cult of the Hollow Eye]] | 20 (18.2%) | 4+ | 4-6 |
| 4 | Saurian legion checkpoint | [[Saurian Legions]] | 15 (13.6%) | 5+ | 3-5 |

### 1. Deserter ambush

**Faction:** [[Deserters]] · **Weight:** 40 · **Company level:** 3+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Deserter Footman]]
- 1× [[Deserter Archer]]

Remaining slots filled from:
- [[Deserter Footman]] — 36%
- [[Deserter Militia]] — 20%
- [[Deserter Swordsman]] — 14.4%
- [[Deserter Archer]] — 20%
- [[Rogue Battlemage]] — 9.6%

### 2. Bandit highway robbery

**Faction:** [[Bandits]] · **Weight:** 35 · **Company level:** 3+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Orc Bandit Raider]]
- 1× [[Elf Bandit Archer]]

Remaining slots filled from:
- [[Orc Bandit Raider]] — 38.5%
- [[Orc Thug]] — 15.4%
- [[Bandit Cutthroat]] — 13.8%
- [[Elf Bandit Archer]] — 23.1%
- [[Goblin Bandit Shaman]] — 9.2%

### 3. Cultist waylay

*Hounds rush ahead while torchbearers provide ranged cover*

**Faction:** [[Cult of the Hollow Eye]] · **Weight:** 20 · **Company level:** 4+ · **Size:** 4-6 enemies

Always includes:
- 1× [[Cult Initiate]]
- 1× [[Void Hound]]
- 1× [[Cult Torchbearer]]

May include (if the budget allows):
- 1× [[Cult Acolyte]]

Remaining slots are filled from the [[Cult of the Hollow Eye]] roster (by each unit's spawn weight).

### 4. Saurian legion checkpoint

*Saurian warriors blocking the road*

**Faction:** [[Saurian Legions]] · **Weight:** 15 · **Company level:** 5+ · **Size:** 3-5 enemies

Always includes:
- 2× [[Saurian Legionary]]

May include (if the budget allows):
- 1× [[Skink Javelineer]]

Remaining slots are filled from the [[Saurian Legions]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[Roadside Ambush Point]]

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
