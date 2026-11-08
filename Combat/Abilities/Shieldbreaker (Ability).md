---
id: ability_shieldbreaker
type: ability
category: Abilities
aliases:
  - Shieldbreaker
  - ability_shieldbreaker
tags:
  - ability/melee
  - type/ability
source: abilities/combat_abilities.json
ap_cost: 1
cooldown_turns: 2
fatigue_cost: 14
range: 1
requires_los: true
source_type: Skill
target_type: enemy
uses_per_battle: 2
---

A 1-AP melee ability targeting an adjacent enemy, usable twice per battle.

> Target the enemy's guard. Deals 50% damage and reduces their melee defense by 10 for 3 turns.

## Stats

|  | Value |
|---|---|
| Action Points | 1 |
| Fatigue | 14 |
| Cooldown | 2 turns |
| Uses per battle | 2 |
| Range | 1 hex |
| Target | Enemy |
| Line of sight | Required |

*Tags:* melee, mace, debuff

## Requirements

- Requires a mace equipped

## Effects

- Target: -10 [[Stats#Melee Defense|Melee Defense]] for 3 turns

## Referenced by

- **Available through skill:** [[Mace Fighting]]
- **Empowered by magic properties:** [[Shieldbreaker Mastery]]
- **Granted by skill traits:** [[Shieldbreaker (Skill Trait)|Shieldbreaker]]

*Generated from `abilities/combat_abilities.json`. Edits will be overwritten — put your own notes in Notes/.*
