---
type: encounters_page
tags:
  - type/encounters_page
source: encounters/encounter_config.json
---

How random fights are chosen: each terrain rolls a different encounter table as your company levels up, and the chance of an encounter depends on depth underground and on nearby settlement security.

## Terrain progression

For each terrain, the table with the highest starting level your company has reached is used. Terrain not listed here falls back to the hex's own default table.

| Terrain | Table by company level |
|---|---|
| Bridge | Lv 1: [[Plains — Random Encounter]] → Lv 3: [[Road — Ambush]] → Lv 5: [[Plains — Mid Tier]] → Lv 8: [[Plains — Late Tier]] |
| Cavern | Lv 1: [[Shallow Cavern Encounter]] → Lv 4: [[Mid-depth Cavern Encounter]] → Lv 7: [[Deep Cavern Encounter]] |
| Crystal Cave | Lv 3: [[Mid-depth Crystal Cave Encounter]] → Lv 6: [[Deep Crystal Cave Encounter]] |
| Dark Ruins | Lv 3: [[Mid-depth Dark Ruins Encounter]] → Lv 6: [[Deep Dark Ruins Encounter]] |
| Forest | Lv 1: [[Forest — Encounter]] → Lv 4: [[Forest — Mid Tier]] → Lv 7: [[Forest — Late Tier]] |
| Fungal Bog | Lv 2: [[Shallow Fungal Bog Encounter]] → Lv 5: [[Mid-depth Fungal Bog Encounter]] |
| Hills | Lv 1: [[Hills — Encounter]] → Lv 5: [[Hills — Mid Tier]] |
| Mountain | Lv 1: [[Mountain — Encounter]] → Lv 6: [[Mountain — Mid Tier]] |
| Mushroom Forest | Lv 1: [[Shallow Mushroom Forest Encounter]] → Lv 4: [[Mid-depth Mushroom Forest Encounter]] |
| Plains | Lv 1: [[Plains — Random Encounter]] → Lv 5: [[Plains — Mid Tier]] → Lv 8: [[Plains — Late Tier]] |
| Road | Lv 1: [[Plains — Random Encounter]] → Lv 3: [[Road — Ambush]] → Lv 5: [[Plains — Mid Tier]] → Lv 8: [[Plains — Late Tier]] |
| Ruins | Lv 1: [[Ruins — Early]] → Lv 5: [[Ruins — Mid Tier]] → Lv 8: [[Ruins — Late Tier]] |
| Stalagmite Field | Lv 1: [[Shallow Stalagmite Field Encounter]] → Lv 4: [[Mid-depth Stalagmite Encounter]] → Lv 7: [[Deep Stalagmite Encounter]] |
| Swamp | Lv 1: [[Swamp — Encounter]] → Lv 5: [[Swamp — Mid Tier]] → Lv 8: [[Swamp — Late Tier]] |
| Town | Lv 1: [[Plains — Random Encounter]] → Lv 3: [[Road — Ambush]] → Lv 5: [[Plains — Mid Tier]] → Lv 8: [[Plains — Late Tier]] |
| Tunnel | Lv 1: [[Shallow Tunnel Encounter]] → Lv 3: [[Mid-depth Tunnel Encounter]] → Lv 6: [[Deep Tunnel Encounter]] |

## Underground depth

Underground, the chance of an encounter is multiplied by the depth zone:

| Depth zone | Encounter chance |
|---|---|
| Shallow | ×1 |
| Mid | ×1.3 |
| Deep | ×1.6 |

## Settlement security

Near settlements, the encounter chance depends on the settlement's security; the first row it meets applies:

| Security | Encounter chance |
|---|---|
| 70 or more | ×1 |
| 40 or more | ×1.15 |
| 20 or more | ×1.3 |
| lower | ×1.5 |

## Table types

- **Random tables** are rolled while travelling, per the terrain progression above.
- **Static tables** hold the garrison of a fixed site — an enemy base, dungeon or lair — and are listed on those pages. A base filters the table down to its own faction's groups.
- Tables that no terrain or site uses directly (what picks them is not stated in the data): [[Forest — Umbral Court Raid]], [[Mountains — Duergar Raid]], [[Plains — Eastern Empire Patrol]], [[Plains — Jotunblight Invasion]], [[Roadside Ambush]].

All tables: [[Encounter Tables]].

## Related

- **See also:** [[Enemy Warbands]], [[How Enemies Behave]]

> [!note]- Developer notes
> Encounter configuration: terrain-based table progression and settlement security modifiers. Loaded by EncounterTrigger at runtime for designer tuning.
>
> *depth_zone_multipliers:* Encounter chance multiplier by underground depth zone.
>
> *security_thresholds:* Settlement security level thresholds and their encounter chance multipliers. Evaluated top-down: the first threshold the security level meets or exceeds is used. Below all thresholds uses the fallback multiplier.
>
> *terrain_tables:* Maps terrain_type to a list of [company_level_min, encounter_table_id]. The highest entry whose min is satisfied is selected. Terrain types not listed fall back to the hex default.

*Generated from `encounters/encounter_config.json`. Edits will be overwritten — put your own notes in Notes/.*
