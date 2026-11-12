---
id: plains_captain
type: encounter_table
category: Encounter Tables
aliases:
  - plains_captain
  - Plains  -- Bandit Camp
tags:
  - encounter/static
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Bandits
groups: 1
level_max: 5
level_min: 3
pool_scale: 1.4
terrain:
  - plains
trigger: static
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A static encounter table (fought at a fixed location) for plains terrain, at company levels 3-5, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Plains |
| Company level | 3-5 |
| Difficulty × | ×1.4 |
| Factions | [[Bandits]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Bandits group | [[Bandits]] | 100 (100%) | 3-5 | 4-6 |

### 1. Bandits group

**Faction:** [[Bandits]] · **Weight:** 100 · **Company level:** 3-5 · **Size:** 4-6 enemies

Always includes:
- 1× [[Bandit Captain]]
- 2× [[Orc Bandit Raider]]

Remaining slots filled from:
- [[Orc Bandit Raider]] — 37.6%
- [[Orc Thug]] — 15%
- [[Bandit Cutthroat]] — 13.5%
- [[Elf Bandit Archer]] — 22.6%
- [[Goblin Bandit Shaman]] — 11.3%

## Referenced by

- **Garrisons bases:** [[Bandit Camp]]

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
