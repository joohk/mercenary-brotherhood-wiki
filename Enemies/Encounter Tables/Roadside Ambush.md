---
id: tutorial_rabble
type: encounter_table
category: Encounter Tables
aliases:
  - tutorial_rabble
tags:
  - encounter/static
  - terrain/plains
  - type/encounter_table
source: enemies/encounter_tables_plains.json
factions:
  - Desperate Rabble
groups: 1
level_min: 1
pool_scale: 0.55
terrain:
  - plains
trigger: static
---

A static encounter table (fought at a fixed location) for plains terrain, from company level 1, with 1 enemy group.

## Overview

|  | Value |
|---|---|
| Trigger | Static — fought at a fixed site (base, lair or dungeon) |
| Terrain | Plains |
| Company level | 1+ |
| Difficulty × | ×0.55 |
| Factions | [[Desperate Rabble]] |

## Where it is used

Used only for the tutorial's opening ambush; no terrain or site rolls it.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | Tutorial Rabble Ambush | [[Desperate Rabble]] | 100 (100%) | 1+ | 4 |

### 1. Tutorial Rabble Ambush

**Faction:** [[Desperate Rabble]] · **Weight:** 100 · **Company level:** 1+ · **Size:** 4 enemies

Always includes:
- 2× [[Starving Thug]]
- 1× [[Cutpurse]]
- 1× [[Stone Thrower]]

Remaining slots filled from:
- [[Starving Thug]] — 100%

> [!note]- Developer notes
> TUTORIAL COLD OPEN -- the ambush the Company-Level-0 tutorial starts inside. Not reachable from any random or POI path: it is looked up BY ID only, from App._start_tutorial_ambush. Kept separate from plains_early deliberately -- that table mixes rabble with eight other factions (two of which the tutorial excludes), so it can never be a reproducible teaching encounter. Tune the opener HERE without touching live plains spawns.
>
> *enemy_groups[0]:* Four rabble, all required, so the opener is the same fight every run. Two thugs to walk into the shield line, a cutpurse that will try to slip around it (the flanking lesson), and ONE stone thrower so 'kill the ranged one first' is discoverable. Deliberately NO rabble_ringleader -- a 48 hp boss in the first fight a player ever sees turns a lesson into a wall; the ringleader belongs in a later fight. filler_enemies is a safety net only: pool_scale is set so the four required enemies consume the budget, but a group with no filler at all can build an EMPTY encounter if the budget maths ever shifts.

*Generated from `enemies/encounter_tables_plains.json`. Edits will be overwritten — put your own notes in Notes/.*
