---
id: brood_hollow_lair
type: encounter_table
category: Encounter Tables
aliases:
  - brood_hollow_lair
tags:
  - encounter/static
  - terrain/forest
  - type/encounter_table
source: enemies/encounter_tables_forest.json
factions:
  - Beasts
groups: 1
level_min: 2
terrain:
  - forest
trigger: static
---

A static encounter table (fought at a fixed location) for forest terrain, from company level 2, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Forest |
| Company level | 2+ |
| Factions | [[Beasts]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Broodling swarm. spawn_weight is 0, so the filler weight must be explicit | [[Beasts]] | 100 (100%) | 2+ | 4-10 |

### 1. Broodling swarm. spawn_weight is 0, so the filler weight must be explicit

**Faction:** [[Beasts]] · **Weight:** 100 · **Company level:** 2+ · **Size:** 4-10 enemies

Always includes:
- 4× [[Spider Broodling]]

Remaining slots filled from:
- [[Spider Broodling]] — 100%

## Referenced by

- **Monster lair kind:** [[Monster Lair]]

*Generated from `enemies/encounter_tables_forest.json`. Edits will be overwritten — put your own notes in Notes/.*
