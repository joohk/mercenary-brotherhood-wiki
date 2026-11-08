---
id: skill_counter_fighter
type: skill
category: Skills
aliases:
  - skill_counter_fighter
tags:
  - skill-group/melee
  - skill/combat
  - type/skill
source: skills/melee_skills.json
discovery_source: melee_hit_received
discovery_weight: 0.8
max_level: 10
skill_category: combat
skill_group: Melee
skill_traits: 7
---

A combat skill from the Melee group, with 10 levels and 7 skill traits.

> Every hit you take teaches you something. Gains XP from receiving melee hits.

## How to train

**Trained by:** Get hit by a melee attack.

**Discovery:** Can be discovered on a *melee hit received* event; discovery weight 0.8.

**Tutorial offer:** melee list (#3). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | +3 [[Stats#Melee Defense\|Melee Defense]] | +3 Melee Defense | 20 |
| L2 | +2 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Armor\|Armor]] | +5 Melee Defense, +1 Armor | 40 |
| L3 | +2 [[Stats#Melee Defense\|Melee Defense]], +2 [[Stats#Melee Attack\|Melee Attack]] | +7 Melee Defense, +1 Armor, +2 Melee Attack | 70 |
| L4 | +2 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Armor\|Armor]] | +9 Melee Defense, +2 Armor, +2 Melee Attack | 110 |
| L5 | +2 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Armor\|Armor]] | +9 Melee Defense, +3 Armor, +4 Melee Attack | 160 |
| L6 | +2 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Armor\|Armor]] | +11 Melee Defense, +4 Armor, +5 Melee Attack | 220 |
| L7 | +1 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Armor\|Armor]] | +12 Melee Defense, +5 Armor, +6 Melee Attack | 290 |
| L8 | +1 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Armor\|Armor]] | +13 Melee Defense, +6 Armor, +6 Melee Attack | 360 |
| L9 | +1 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Melee Attack\|Melee Attack]] | +14 Melee Defense, +6 Armor, +7 Melee Attack | 440 |
| L10 | +1 [[Stats#Melee Defense\|Melee Defense]], +1 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Armor\|Armor]] | +15 Melee Defense, +7 Armor, +8 Melee Attack | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Read the Strikes]] | Common | Passive | 2 | — |
| [[Thick Skin (Skill Trait)\|Thick Skin]] | Common | Passive | 2 | — |
| [[Counter Attack]] | Uncommon | Passive | 2 | — |
| [[Perfect Parry]] | Uncommon | Passive | 2 | — |
| [[Punish]] | Uncommon | Passive | 2 | — |
| [[Counter-Crit]] | Rare | Passive | 2 | — |
| [[Iron Jaw]] | Rare | Passive | 2 | — |

## Referenced by

- **Familiar to:** [[Beast Tamer]], [[First Blade]], [[Guardian]], [[Mariner]], [[Shield Master]], [[Warden]]
- **Foreign to:** [[Berserker (Background)|Berserker]], [[Corsair]], [[Feral Champion]], [[Ravager (Background)|Ravager]], [[Tribal Warrior]]
- **Guild signature skill:** [[Blade Circle]]
- **Starting skill of:** [[First Blade]]

*Generated from `skills/melee_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
