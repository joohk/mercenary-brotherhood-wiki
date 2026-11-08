---
id: skill_skirmisher
type: skill
category: Skills
aliases:
  - Skirmisher
  - skill_skirmisher
tags:
  - skill-group/ranged
  - skill/combat
  - type/skill
source: skills/ranged_skills.json
discovery_source: attack_after_move
discovery_weight: 0.7
max_level: 10
skill_category: combat
skill_group: Ranged
skill_traits: 6
---

A combat skill from the Ranged group, with 10 levels and 6 skill traits.

> Hit and move. Gains XP from attacking in the same turn you moved.

## How to train

**Trained by:** Attack after moving in the same turn.

**Discovery:** Can be discovered on a *attack after move* event; discovery weight 0.7.

**Tutorial offer:** ranged list (#1). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | +3 [[Stats#Melee Attack\|Melee Attack]] | +3 Melee Attack | 20 |
| L2 | +3% [[Stats#Dodge\|Dodge]] | +3 Melee Attack, +3% Dodge | 40 |
| L3 | +2 [[Stats#Melee Attack\|Melee Attack]], +2% [[Stats#Dodge\|Dodge]] | +5 Melee Attack, +5% Dodge | 70 |
| L4 | +2 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Damage Min\|Damage]] | +7 Melee Attack, +5% Dodge, +1 Damage | 110 |
| L5 | +2% [[Stats#Dodge\|Dodge]], +1 to +2 [[Stats#Damage Min\|Damage]] | +7 Melee Attack, +7% Dodge, +2 to +3 Damage | 160 |
| L6 | +2% [[Stats#Dodge\|Dodge]], +1 to +2 [[Stats#Damage Min\|Damage]] | +7 Melee Attack, +9% Dodge, +3 to +5 Damage | 220 |
| L7 | +1 [[Stats#Melee Attack\|Melee Attack]], +2% [[Stats#Dodge\|Dodge]], +1 to +2 [[Stats#Damage Min\|Damage]] | +8 Melee Attack, +11% Dodge, +4 to +7 Damage | 290 |
| L8 | +2% [[Stats#Dodge\|Dodge]], +1 to +3 [[Stats#Damage Min\|Damage]] | +8 Melee Attack, +13% Dodge, +5 to +10 Damage | 360 |
| L9 | +1 [[Stats#Melee Attack\|Melee Attack]], +1% [[Stats#Dodge\|Dodge]], +1 to +3 [[Stats#Damage Min\|Damage]] | +9 Melee Attack, +14% Dodge, +6 to +13 Damage | 440 |
| L10 | +2% [[Stats#Dodge\|Dodge]], +2 to +3 [[Stats#Damage Min\|Damage]] | +9 Melee Attack, +16% Dodge, +8 to +16 Damage | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Evasive (Skill Trait)\|Evasive]] | Common | Passive | 2 | — |
| [[Mobile Striker]] | Common | Passive | 2 | — |
| [[Disengage (Skill Trait, Skirmisher)\|Disengage]] | Uncommon | Passive | 1 | — |
| [[Opportunist Strike (Skill Trait)\|Opportunist Strike]] | Uncommon | Ability | 2 | [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| [[Sprint (Skill Trait)\|Sprint]] | Uncommon | Ability | 2 | [[Sprint (Ability, ability_sprint)\|Sprint]] |
| [[Ghost Step (Skill Trait, Skirmisher)\|Ghost Step]] | Rare | Passive | 2 | — |

## Referenced by

- **Familiar to:** [[Beastmaster]], [[Beggar]], [[Deserter]], [[Forager]], [[Hunter]], [[Outrider]], [[Pathfinder]], [[Rat Catcher]], [[Scavenger]], [[Stalker (Background)|Stalker]], [[Street Urchin]], [[Torch Bearer]], [[Vagabond]]
- **Foreign to:** [[Grave Digger]], [[Guardian]], [[Laborer]], [[Mudfoot]], [[Shield Master]], [[Temple Guard]], [[Undying Sentinel]]
- **Guild signature skill:** [[Hunters' Lodge]], [[Shadow Guild]], [[Wildwardens]]
- **Starting skill of:** [[Beastmaster]], [[Hunter]], [[Outrider]], [[Pathfinder]], [[Stalker (Background)|Stalker]]
- **Trained by hunting at:** [[Ranger Station]]

*Generated from `skills/ranged_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
