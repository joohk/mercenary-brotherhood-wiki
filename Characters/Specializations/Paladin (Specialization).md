---
id: spec_paladin
type: specialization
category: Specializations
aliases:
  - Paladin
  - spec_paladin
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - charges_completed
  - holy_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Charges* (every 3) **and** *Holy Kills* (every 4) — both must climb; 2 points per threshold.

> Charge, smite, and shield your kin. Requires completed charges and holy magic both.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Paladin I | Paladin II | Paladin III |
|---|---|---|---|
| [[Stats#Melee Attack\|Melee Attack]] | +3 | +5 | +8 |
| [[Stats#Max HP\|Max HP]] | +6 | +12 | +20 |
| Holy abilities: damage | +8% | +16% | +24% |
| Holy abilities: healing | — | +20% | +35% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Charges, every 3 |
| Tracks | Holy Kills, every 4 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Holy Order]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
