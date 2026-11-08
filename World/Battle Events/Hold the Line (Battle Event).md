---
id: hold_the_line
type: battle_event
category: Battle Events
aliases:
  - Hold the Line
  - hold_the_line
tags:
  - type/battle_event
source: encounters/battle_events.json
company_level_min: 3
weight: 15
---

A battle event from company level 3 (weight 15).

> Survive the onslaught until reinforcements arrive

## When it happens

Each random or warband battle has a 20% chance to turn into a battle event; every battle without one adds 5%, up to 60% extra. The event is then picked by [[Glossary#Numbers used on this wiki|weight]] among those available at your company level: this one has weight 15 of 55 in total (27.27% when all are available).

## Details

|  | Value |
|---|---|
| Enemy count | ×1.8 |
| Turns to hold | 8-10 |
| Reward for holding | 75 gold |
| Reputation for holding | +5 |
| Reputation if you retreat | -5 |

## Terrain

Multiplier on this event's weight when the battle is fought on that terrain.

| Terrain | Weight multiplier |
|---|---|
| Ruins | ×1.5 |
| Bridge | ×1.3 |
| Mountain | ×1.2 |
| Plains | ×0.8 |

## Allies

Allied units that fight alongside you.

### Allied Soldier

Fights aggressively. Equipment: [[Iron Sword]], [[Leather Armor]].

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 50 |
| [[Stats#Melee Attack\|Melee Attack]] | 50 |
| [[Stats#Melee Defense\|Melee Defense]] | 45 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 35 |
| [[Stats#Armor\|Armor]] | 4 |
| [[Stats#Initiative\|Initiative]] | 45 |
| Action Points | 2 |
| [[Stats#Willpower\|Willpower]] | 55 |
| [[Stats#Vision\|Vision]] | 5 |
| [[Stats#Damage Min\|Damage]] | 7-12 |

*Generated from `encounters/battle_events.json`. Edits will be overwritten — put your own notes in Notes/.*
