---
id: ability_armor_crush
type: ability
category: Abilities
aliases:
  - Armor Crush
  - ability_armor_crush
tags:
  - ability/melee
  - type/ability
source: abilities/combat_abilities.json
ap_cost: 1
cooldown_turns: 2
fatigue_cost: 16
range: 1
requires_los: true
source_type: Skill
target_type: enemy
uses_per_battle: 2
---

A 1-AP melee ability targeting an adjacent enemy, usable twice per battle.

> A targeted blow to the armor plating. Reduces target armor by 4 for the rest of the battle.

## Stats

|  | Value |
|---|---|
| Action Points | 1 |
| Fatigue | 16 |
| Cooldown | 2 turns |
| Uses per battle | 2 |
| Range | 1 hex |
| Target | Enemy |
| Line of sight | Required |

*Tags:* melee, hammer, armor break

## Requirements

- Requires a hammer equipped

## Effects

- Target: -4 [[Stats#Armor|Armor]]

## Referenced by

- **Available through skill:** [[Hammer Fighting]]
- **Empowered by magic properties:** [[Armor Crush Mastery]]
- **Granted by skill traits:** [[Armor Crush (Skill Trait)|Armor Crush]]

*Generated from `abilities/combat_abilities.json`. Edits will be overwritten — put your own notes in Notes/.*
