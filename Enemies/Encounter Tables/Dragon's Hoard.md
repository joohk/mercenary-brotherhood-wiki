---
id: dragon_hoard_lair
type: encounter_table
category: Encounter Tables
aliases:
  - dragon_hoard_lair
tags:
  - encounter/static
  - terrain/mountain
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Beasts
groups: 1
level_min: 9
pool_scale: 2
terrain:
  - mountain
trigger: static
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A static encounter table (fought at a fixed location) for mountain terrain, from company level 9, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Mountain |
| Company level | 9+ |
| Difficulty × | ×2 |
| Factions | [[Beasts]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Great wyrm's lair | [[Beasts]] | 100 (100%) | 9+ | 2-4 |

### 1. Great wyrm's lair

*Wyverns and manticores guard the hoard (no dragon enemy defined yet)*

**Faction:** [[Beasts]] · **Weight:** 100 · **Company level:** 9+ · **Size:** 2-4 enemies

Always includes:
- 1× [[Wyvern]]
- 1× [[Manticore]]

Remaining slots are filled from the [[Beasts]] roster (by each unit's spawn weight).

## Referenced by

- **Monster lair kind:** [[Monster Lair]]

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
