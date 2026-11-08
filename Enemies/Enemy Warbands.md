---
type: warband_page
tags:
  - type/warband_page
source: enemies/warband_config.json
---

Tuning for the enemy warbands that roam the overland map, move each day, patrol around their bases and start a battle when they reach your company. See also [[Glossary#Warband|Warband]].

> Warbands are the ordinary enemy groups that roam the overland map. They are wandering threats, not persistent characters like Vendettas or arch-villains. Some patrol territory, some clash with rival forces in field battles you can join.

## World rules

|  | Value |
|---|---|
| Map action points per day | 1 |
| Max warbands on the surface | 40 |
| Max warbands underground | 20 |
| Chance of a random warband each day | 25% |
| Spawn distance (min-max) | 6-15 |
| Despawn age (days) | 18 |
| Despawn minimum distance | 30 |
| Max warbands near your company | 4 |
| "Near your company" radius | 8 |
| Ambush reveal radius | 2 |
| Roaming bias toward you (radius) | 15 |

Units for the distances, and how the two despawn values combine, are not stated in the data.

## By base rarity

Enemy bases send out warbands; how often and how far depends on the base's rarity ([[Enemy Bases]]).

| Base rarity | Spawns every (days) | Patrols at once | Patrol radius (hexes) |
|---|---|---|---|
| Common | 10 | 1 | 4 |
| Uncommon | 8 | 1 | 5 |
| Rare | 6 | 1 | 6 |
| Legendary | 5 | 1 | 8 |

## Related

- **Encounters:** [[Encounters]], [[Encounter Tables]]

> [!note]- Developer notes
> Tuning constants for the map warband system. Enemy warbands are visible units on the overland map that move, patrol, and trigger combat on collision.

*Generated from `enemies/warband_config.json`. Edits will be overwritten — put your own notes in Notes/.*
