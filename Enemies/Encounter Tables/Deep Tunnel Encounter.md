---
id: tunnel_deep
type: encounter_table
category: Encounter Tables
aliases:
  - tunnel_deep
tags:
  - encounter/random
  - terrain/tunnel
  - type/encounter_table
source: enemies/underground_encounter_tables.json
factions:
  - The Umbral Court
  - Demons
groups: 2
level_min: 6
terrain:
  - tunnel
trigger: random
---

A random encounter table for tunnel terrain, from company level 6, with 2 enemy groups.

## Overview

|  | Value |
|---|---|
| Trigger | Random — rolled while travelling |
| Terrain | Tunnel |
| Company level | 6+ |
| Factions | [[The Umbral Court]], [[Demons]] |

## Where it is used

- Rolled on **tunnel** terrain from company level 6.

See [[Encounters]] for the full terrain progression.

## Groups

When this table is rolled, one group is picked by weight among the groups allowed at your company level; the share in brackets is out of all groups in the table.

| # | Group | Faction | Weight | Company level | Size |
|---|---|---|---|---|---|
| 1 | The Umbral Court group | [[The Umbral Court]] | 40 (57.1%) | 6+ | 3-6 |
| 2 | Demons group | [[Demons]] | 30 (42.9%) | 6+ | 3-5 |

### 1. The Umbral Court group

**Faction:** [[The Umbral Court]] · **Weight:** 40 · **Company level:** 6+ · **Size:** 3-6 enemies

Always includes:
- 2× [[Umbral Swordsman]]

Remaining slots filled from:
- [[Umbral Swordsman]] — 27.6%
- [[Umbral Archer]] — 20.7%
- [[Giant Spider (Enemy, Umbral Court)|Giant Spider (The Umbral Court)]] — 17.2%
- [[Umbral Blademaster]] — 12.4%
- [[Umbral Shadowcaster]] — 10.3%
- [[Court Spider]] — 8.3%
- [[Umbral Matriarch]] — 3.4%

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
