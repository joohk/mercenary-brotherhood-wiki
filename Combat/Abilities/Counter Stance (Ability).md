---
id: ability_riposte_strike
type: ability
category: Abilities
aliases:
  - Counter Stance
  - ability_riposte_strike
tags:
  - type/ability
source: abilities/combat_abilities.json
ap_cost: 1
cooldown_turns: 2
fatigue_cost: 10
range: 0
requires_los: false
source_type: Skill
target_type: self
---

A 1-AP ability used on yourself.

> Take a guarded sword stance. Each time an enemy misses you in melee you gain a charge of +5 Melee Attack and +10% melee damage, up to 3. Your next attack uses every charge, then they are spent. Sustained: drains fatigue each turn.

## Stats

|  | Value |
|---|---|
| Action Points | 1 |
| Fatigue | 10 |
| Cooldown | 2 turns |
| Uses per battle | Unlimited |
| Range | Self |
| Target | Self |
| Line of sight | Not required |
| Damage | Per charge: +5 melee atk, +10% melee dmg (max 3, sustained) |

*Tags:* sword, stance, sustained, buff

## Requirements

- Requires a sword equipped

## Referenced by

- **Available through skill:** [[Swordsmanship]]
- **Empowered by magic properties:** [[Counter Stance Mastery]]
- **Granted by skill traits:** [[Counter Stance (Skill Trait)|Counter Stance]]

*Generated from `abilities/combat_abilities.json`. Edits will be overwritten — put your own notes in Notes/.*
