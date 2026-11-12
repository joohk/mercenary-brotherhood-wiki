---
id: usurper_castle
type: encounter_table
category: Encounter Tables
aliases:
  - The Usurper's Castle
  - usurper_castle
tags:
  - encounter/static
  - terrain/castle
  - type/encounter_table
source: enemies/encounter_tables_other.json
factions:
  - Deserters
groups: 1
level_min: 1
terrain:
  - castle
trigger: static
up: "[[Encounter Tables]]"
---

[[Home]] › [[Bestiary]] › [[Encounter Tables]]

A static encounter table (fought at a fixed location) for castle terrain, from company level 1, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Castle |
| Company level | 1+ |
| Factions | [[Deserters]] |

## Where it is used

Used by fixed sites (bases, dungeons or points of interest) — see *Referenced by* below.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Deserters group | [[Deserters]] | 100 (100%) | 1+ | 22 |

### 1. Deserters group

**Faction:** [[Deserters]] · **Weight:** 100 · **Company level:** 1+ · **Size:** 22 enemies

Always includes:
- 1× [[Deserter Captain]]
- 2× [[Rogue Knight]]
- 2× [[Rogue Battlemage]]
- 2× [[Deserter Sergeant]]
- 5× [[Deserter Archer]]
- 4× [[Deserter Swordsman]]
- 4× [[Deserter Footman]]
- 2× [[Deserter Militia]]

Remaining slots are filled from the [[Deserters]] roster (by each unit's spawn weight).

## Referenced by

- **Garrisons bases:** [[The Usurper's Castle (Enemy Base)|The Usurper's Castle]]

> [!note]- Developer notes
> Castle siege garrison — deserter usurper army. All enemies are is_required so the full garrison spawns regardless of pool budget or the filler cap. Static-only; only reachable via The Usurper's Castle legendary enemy base.

*Generated from `enemies/encounter_tables_other.json`. Edits will be overwritten — put your own notes in Notes/.*
