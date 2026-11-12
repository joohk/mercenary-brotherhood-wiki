---
id: spec_battle_cleric
type: specialization
category: Specializations
aliases:
  - Battle Cleric
  - spec_battle_cleric
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - melee_finishing_blows
  - healing_done
points_per_threshold: 2
spec_category: battlemage
up: "[[Specializations]]"
---

[[Home]] › [[Your Company]] › [[Specializations]]

A Battlemage specialization. Tracks *Melee Kills* (every 5) **and** *HP Healed* (every 15) — both must climb; 2 points per threshold.

> One hand mends, the other ends. Faith swings both ways — you must fight and heal to walk this path.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Battle Cleric I | Battle Cleric II | Battle Cleric III |
|---|---|---|---|
| [[Stats#Melee Attack\|Melee Attack]] | +3 | +5 | +8 |
| [[Stats#Willpower\|Willpower]] | +3 | +5 | +8 |
| Holy abilities: healing | +15% | +30% | +45% |
| Holy abilities: damage | +5% | +10% | +15% |
| [[Stats#Max HP\|Max HP]] | — | +6 | +12 |

## How it's earned

|  | Value |
|---|---|
| Tracks | Melee Kills, every 5 |
| Tracks | HP Healed, every 15 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Holy Order]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
