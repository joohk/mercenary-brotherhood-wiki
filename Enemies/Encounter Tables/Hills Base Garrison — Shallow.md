---
id: hills_base_mid
type: encounter_table
category: Encounter Tables
aliases:
  - hills_base_mid
  - Hills Base Garrison  -- Shallow
tags:
  - encounter/static
  - terrain/hills
  - type/encounter_table
source: enemies/encounter_tables_bases.json
factions:
  - Wilding Elves
  - Greenskin Warband
groups: 2
level_max: 4
level_min: 3
terrain:
  - hills
trigger: static
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A static encounter table (fought at a fixed location) for hills terrain, at company levels 3-4, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Hills |
| Company level | 3-4 |
| Factions | [[Wilding Elves]], [[Greenskin Warband]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Barbarian war camp garrison | [[Wilding Elves]] | 50 (50%) | 3-4 | 4-6 |
| 2 | Orc stockade garrison | [[Greenskin Warband]] | 50 (50%) | 3-4 | 4-7 |

### 1. Barbarian war camp garrison

*Raiders and shield-maidens, a berserker or two.*

**Faction:** [[Wilding Elves]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-6 enemies

Always includes:
- 2× [[Wilding Raider]]
- 1× [[Thorn Warden]]

Remaining slots filled from:
- [[Wilding Raider]] — 35.4%
- [[Wilding Huntsman]] — 26.5%
- [[Thorn Warden]] — 22.1%
- [[Wilding Berserker]] — 15.9%

### 2. Orc stockade garrison

*Goblin sentries and orc brutes on the walls.*

**Faction:** [[Greenskin Warband]] · **Weight:** 50 · **Company level:** 3-4 · **Size:** 4-7 enemies

Always includes:
- 2× [[Orc Grunt]]
- 1× [[Orc Brute]]

Remaining slots filled from:
- [[Goblin Skirmisher]] — 29.2%
- [[Orc Grunt]] — 25%
- [[Goblin Poisoner]] — 18.3%
- [[Orc Brute]] — 15%
- [[Goblin Wolfrider]] — 12.5%

## Referenced by

- **Garrisons bases:** [[Barbarian War Camp]], [[Orc Stockade]]

*Generated from `enemies/encounter_tables_bases.json`. Edits will be overwritten — put your own notes in Notes/.*
