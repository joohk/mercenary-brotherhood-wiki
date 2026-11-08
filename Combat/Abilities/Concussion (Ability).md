---
id: ability_concussion
type: ability
category: Abilities
aliases:
  - Concussion
  - ability_concussion
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

> A targeted blow to the head. Deals normal damage and reduces target melee attack by 10 and initiative by 10 for 3 turns.

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

*Tags:* melee, mace, debuff

## Requirements

- Requires a mace equipped

## Effects

- Target: -10 [[Stats#Melee Attack|Melee Attack]] for 3 turns
- Target: -10 [[Stats#Initiative|Initiative]] for 3 turns

## Referenced by

- **Available through skill:** [[Mace Fighting]]
- **Empowered by magic properties:** [[Concussion Mastery]]
- **Granted by skill traits:** [[Concussion (Skill Trait)|Concussion]]

*Generated from `abilities/combat_abilities.json`. Edits will be overwritten — put your own notes in Notes/.*
