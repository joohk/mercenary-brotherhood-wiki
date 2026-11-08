---
id: spec_long_reach
type: specialization
category: Specializations
aliases:
  - spec_long_reach
tags:
  - specialization/weapon_mastery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: spear_kills
points_per_threshold: 1
requires_weapon_tag: spear
spec_category: weapon_mastery
---

A Weapon Mastery specialization. Tracks *Spear Kills* — every 4 → 1 point. Only while wielding a **spear**.

> Keep them at spear's length. Control the distance, control the fight.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Lancer I | Lancer II | Lancer III |
|---|---|---|---|
| [[Stats#Melee Defense\|Melee Defense]] | +4 | +6 | +9 |
| [[Stats#Melee Attack\|Melee Attack]] | +3 | +5 | +8 |
| [[Stats#Damage Min\|Damage]] | +3% | +6% | +10% |
| [[Stats#Dodge\|Dodge]] | — | — | +3% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Spear Kills |
| Threshold | every 4 |
| Points per threshold | 1 |
| Required weapon | Spear |

A unit may choose a specialization every 4 levels. *Weapon Mastery category:* Conditional on weapon equipped, reduced points.

## Referenced by

- **Sponsored by guilds:** [[Hunters' Lodge]]

> [!note]- Developer notes
> *separator:* ── WEAPON MASTERY (8) ── conditional on weapon equipped, reduced points

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
