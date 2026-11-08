---
id: crystal_deep
type: encounter_table
category: Encounter Tables
aliases:
  - crystal_deep
tags:
  - encounter/random
  - terrain/crystal_cave
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - The Dread Host
  - Demons
groups: 2
level_min: 6
terrain:
  - crystal_cave
trigger: random
---

A random encounter table for crystal cave terrain, from company level 6, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Crystal Cave |
| Company level | 6+ |
| Factions | [[The Dread Host]], [[Demons]] |

## Where it is used

- Rolled on **crystal cave** terrain from company level 6.

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | The Dread Host group | [[The Dread Host]] | 35 (53.8%) | 6+ | 3-6 |
| 2 | Demons group | [[Demons]] | 30 (46.2%) | 6+ | 3-5 |

### 1. The Dread Host group

**Faction:** [[The Dread Host]] · **Weight:** 35 · **Company level:** 6+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Dark Soldier]]
- 1× [[Dread Knight]]

Remaining slots filled from:
- [[Dark Soldier]] — 25%
- [[Dread Thrall]] — 18.8%
- [[Dread Archer]] — 17.5%
- [[Dread Knight]] — 13.8%
- [[War Necromancer]] — 11.3%
- [[Bone Colossus]] — 6.2%
- [[Dark General]] — 5%
- [[Lich Commander]] — 2.5%

### 2. Demons group

**Faction:** [[Demons]] · **Weight:** 30 · **Company level:** 6+ · **Size:** 3-5 enemies

Always includes:
- 1× [[Lesser Demon]]
- 1× [[Imp]]

Remaining slots filled from:
- [[Imp]] — 27.6%
- [[Hellhound]] — 24.1%
- [[Lesser Demon]] — 19.3%
- [[Corrupted Knight]] — 15.2%
- [[Demon Brute]] — 10.3%
- [[Arch Demon]] — 3.4%

*Generated from `enemies/underground_encounter_tables.json`. Edits will be overwritten — put your own notes in Notes/.*
