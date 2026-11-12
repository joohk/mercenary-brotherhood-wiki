---
id: faction_clash
type: battle_event
category: Battle Events
aliases:
  - faction_clash
tags:
  - status/retired
  - type/battle_event
source: encounters/battle_events.json
company_level_min: 2
retired: true
up: "[[Battle Events]]"
weight: 0
---

[[Home]] › [[World]] › [[Battle Events]]

A battle event from company level 2 that is never rolled randomly (weight 0).

> [!warning] Retired
> This battle event is marked `_retired` in the game data and may no longer appear in play.
>
> Replaced by overland field battles (systems/field_battle.py) — players now join real two-faction clashes on the world map. weight:0 keeps the setup/reward code reachable for the join while removing it from random battle-event rolls.

> A second warband joins the fray — defeat both factions

## When it happens

This event has weight 0, so it is never picked for a random battle.

## Details

|  | Value |
|---|---|
| Second warband strength | ×0.7 |
| Infighting chance | 60% |
| Reputation needed to be treated as friendly | 10 |

## Terrain

Multiplier on this event's weight when the battle is fought on that terrain.

| Terrain | Weight multiplier |
|---|---|
| Ruins | ×1.5 |
| Plains | ×1.2 |
| Road | ×1.1 |
| Forest | ×0.8 |

*Generated from `encounters/battle_events.json`. Edits will be overwritten — put your own notes in Notes/.*
