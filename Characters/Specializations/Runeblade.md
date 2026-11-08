---
id: spec_runeblade
type: specialization
category: Specializations
aliases:
  - spec_runeblade
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - turns_in_melee_contact
  - stone_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Turns in Melee* (every 20) **and** *Stone Kills* (every 4) — both must climb; 2 points per threshold.

> A frontline warded in living stone. Requires holding the melee line and stone magic both.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Runeblade I | Runeblade II | Runeblade III |
|---|---|---|---|
| [[Stats#Melee Defense\|Melee Defense]] | +3 | +5 | +8 |
| [[Stats#Max HP\|Max HP]] | +5 | +10 | +15 |
| Stone abilities: damage | +8% | +16% | +24% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Turns in Melee, every 20 |
| Tracks | Stone Kills, every 4 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Arcane Conclave (Guild)|Arcane Conclave]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
