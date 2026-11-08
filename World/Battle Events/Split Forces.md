---
id: split_forces
type: battle_event
category: Battle Events
aliases:
  - split_forces
tags:
  - type/battle_event
source: encounters/battle_events.json
company_level_min: 3
weight: 15
---

A battle event from company level 3 (weight 15).

> Your squad has been divided — reunite and survive

## When it happens

Each random or warband battle has a 20% chance to turn into a battle event; every battle without one adds 5%, up to 60% extra. The event is then picked by [[Glossary#Numbers used on this wiki|weight]] among those available at your company level: this one has weight 15 of 55 in total (27.27% when all are available).

## Details

|  | Value |
|---|---|
| Needs a squad of at least | 4 units |

## Terrain

Multiplier on this event's weight when the battle is fought on that terrain.

| Terrain | Weight multiplier |
|---|---|
| Forest | ×1.3 |
| Mountain | ×1.2 |
| Swamp | ×1.1 |

*Generated from `encounters/battle_events.json`. Edits will be overwritten — put your own notes in Notes/.*
