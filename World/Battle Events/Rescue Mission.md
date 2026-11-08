---
id: rescue_mission
type: battle_event
category: Battle Events
aliases:
  - rescue_mission
tags:
  - status/retired
  - type/battle_event
source: encounters/battle_events.json
company_level_min: 1
retired: true
weight: 0
---

A battle event from company level 1 that is never rolled randomly (weight 0).

> [!warning] Retired
> This battle event is marked `_retired` in the game data and may no longer appear in play.
>
> Replaced by overland field battles (systems/field_battle.py) — defending NPCs/patrols/merchants now happens by joining a real world-map battle. weight:0 keeps the setup/reward code reachable for the join while removing it from random battle-event rolls.

> Protect the captives and keep them alive

## When it happens

This event has weight 0, so it is never picked for a random battle.

## Details

|  | Value |
|---|---|
| Captives | 2-4 |
| Chance captives are armed | 50% |
| Base reward | 50 gold |
| Gold per surviving civilian | 10 |
| Reputation per surviving civilian | +2 |
| Reputation per surviving soldier | +3 |
| Reputation on failure | -5 |
| Chance a survivor offers to join | 25% |

## Terrain

Multiplier on this event's weight when the battle is fought on that terrain.

| Terrain | Weight multiplier |
|---|---|
| Road | ×1.5 |
| Bridge | ×1.4 |
| Plains | ×1.3 |
| Forest | ×0.9 |

*Generated from `encounters/battle_events.json`. Edits will be overwritten — put your own notes in Notes/.*
