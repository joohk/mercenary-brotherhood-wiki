---
id: poacher_cache
type: poi
category: Points of Interest
aliases:
  - poacher_cache
tags:
  - poi/respawning
  - type/poi
source: pois/poi_templates.json
active_count: 7
poi_kind: respawning
respawn_days: 10
spacing_tier: minor
up: "[[Points of Interest]]"
---

[[Home]] › [[World]] › [[Points of Interest]]

A respawning point of interest (up to 7 active at once, respawning after 10 days).

![[_assets/PoacherCache.webp|160]]

> A stash of pelts and animal parts left by poachers.

## Details

|  | Value |
|---|---|
| Active at once | 7 |
| Respawns after | 10 days |
| Spacing | Minor |
| Preferred terrain | Forest, Swamp |
| Discovery radius | 4 hexes |
| Encounter chance | 10% |
| Encounter table (level/size stand-in) | [[Plains — Random Encounter]] |
| Enemies drawn from | [[Beasts]] |

> [!note]- Developer notes
> faction_filter is the guarantee -- encounter_table is only a level/size stand-in, since disturbing a pile of pelts must draw ANIMALS, not the cultists and vampires the terrain tables carry. EncounterBuilder tier-caps the beast roster to the company's level.

*Generated from `pois/poi_templates.json`. Edits will be overwritten — put your own notes in Notes/.*
