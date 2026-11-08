---
id: spec_blade_laureate
type: specialization
category: Specializations
aliases:
  - spec_blade_laureate
tags:
  - specialization/weapon_mastery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: sword_kills
points_per_threshold: 1
requires_weapon_tag: sword
spec_category: weapon_mastery
---

A Weapon Mastery specialization. Tracks *Sword Kills* — every 4 → 1 point. Only while wielding a **sword**.

> The sword becomes an extension of will itself.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Blademaster I | Blademaster II | Blademaster III |
|---|---|---|---|
| [[Stats#Melee Attack\|Melee Attack]] | +4 | +6 | +10 |
| [[Stats#Damage Min\|Damage]] | +3% | +6% | +10% |
| [[Stats#Dodge\|Dodge]] | +2% | +4% | +6% |
| [[Stats#Initiative\|Initiative]] | — | — | +3 |

## How it's earned

|  | Value |
|---|---|
| Tracks | Sword Kills |
| Threshold | every 4 |
| Points per threshold | 1 |
| Required weapon | Sword |

A unit may choose a specialization every 4 levels. *Weapon Mastery category:* Conditional on weapon equipped, reduced points.

## Referenced by

- **Sponsored by guilds:** [[Blade Circle]]

> [!note]- Developer notes
> *separator:* ── WEAPON MASTERY (8) ── conditional on weapon equipped, reduced points

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
