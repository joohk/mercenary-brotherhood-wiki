---
id: skill_flanker
type: skill
category: Skills
aliases:
  - skill_flanker
tags:
  - skill-group/melee
  - skill/combat
  - type/skill
source: skills/melee_skills.json
discovery_source: flanked_hit
discovery_weight: 0.7
max_level: 10
skill_category: combat
skill_group: Melee
skill_traits: 10
up: "[[Melee Skills]]"
---

[[Home]] › [[Your Company]] › [[Melee Skills]]

A combat skill from the Melee group, with 10 levels and 10 skill traits.

> Fight a foe together with a comrade. Your hits on a foe one of your comrades is also beside leave it Pressured: weaker in attack, defense, armor and resistance against everyone for 2 turns. Each level adds to the last.

## How to train

**Trained by:** Hit an enemy that has an ally adjacent.

**Discovery:** Can be discovered on a *flanked hit* event; discovery weight 0.7.

**Tutorial offer:** melee list (#4). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level. Bonuses in *italics* only apply in that situation. *Pressured foe* lists what your hits take away from a Pressured enemy (and for how many turns), as the skill description explains.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | *Vs flanked targets:* +1% [[Stats#Crit Chance\|Crit Chance]]; *Pressured foe:* -3 [[Stats#Melee Defense\|Melee Defense]], +2 turn(s) duration | *Vs flanked targets:* +1% Crit Chance; *Pressured foe:* -3 Melee Defense, +2 turn(s) duration | 20 |
| L2 | *Vs flanked targets:* +1 [[Stats#Damage Max\|Damage Max]]; *Pressured foe:* -2 [[Stats#Melee Attack\|Melee Attack]] | *Vs flanked targets:* +1% Crit Chance, +1 Damage Max; *Pressured foe:* -3 Melee Defense, -2 Melee Attack, +2 turn(s) duration | 40 |
| L3 | *Vs flanked targets:* +1 [[Stats#Armor Pen\|Armor Pen]]; *Pressured foe:* -1 [[Stats#Armor\|Armor]] | *Vs flanked targets:* +1% Crit Chance, +1 Damage Max, +1 Armor Pen; *Pressured foe:* -3 Melee Defense, -2 Melee Attack, -1 Armor, +2 turn(s) duration | 70 |
| L4 | *Vs flanked targets:* +1% [[Stats#Crit Chance\|Crit Chance]]; *Pressured foe:* -3% all resistances | *Vs flanked targets:* +2% Crit Chance, +1 Damage Max, +1 Armor Pen; *Pressured foe:* -3 Melee Defense, -2 Melee Attack, -1 Armor, +2 turn(s) duration, -3% all resistances | 110 |
| L5 | *Pressured foe:* +10 Shared Opening | *Vs flanked targets:* +2% Crit Chance, +1 Damage Max, +1 Armor Pen; *Pressured foe:* -3 Melee Defense, -2 Melee Attack, -1 Armor, +2 turn(s) duration, -3% all resistances, +10 Shared Opening | 160 |
| L6 | *Vs flanked targets:* +1 [[Stats#Damage Min\|Damage]]; *Pressured foe:* -2 [[Stats#Melee Defense\|Melee Defense]], -2 [[Stats#Melee Attack\|Melee Attack]] | *Vs flanked targets:* +2% Crit Chance, +1 to +2 Damage, +1 Armor Pen; *Pressured foe:* -5 Melee Defense, -4 Melee Attack, -1 Armor, +2 turn(s) duration, -3% all resistances, +10 Shared Opening | 220 |
| L7 | *Vs flanked targets:* +2% [[Stats#Crit Chance\|Crit Chance]], +1 [[Stats#Armor Pen\|Armor Pen]]; *Pressured foe:* -2 [[Stats#Armor\|Armor]] | *Vs flanked targets:* +4% Crit Chance, +1 to +2 Damage, +2 Armor Pen; *Pressured foe:* -5 Melee Defense, -4 Melee Attack, -3 Armor, +2 turn(s) duration, -3% all resistances, +10 Shared Opening | 290 |
| L8 | *Vs flanked targets:* +3% resistance bypass; *Pressured foe:* -3 [[Stats#Melee Defense\|Melee Defense]], -4% all resistances | *Vs flanked targets:* +4% Crit Chance, +1 to +2 Damage, +2 Armor Pen, +3% resistance bypass; *Pressured foe:* -8 Melee Defense, -4 Melee Attack, -3 Armor, +2 turn(s) duration, -7% all resistances, +10 Shared Opening | 360 |
| L9 | *Vs flanked targets:* +2% [[Stats#Crit Chance\|Crit Chance]], +1 to +2 [[Stats#Damage Min\|Damage]], +1 [[Stats#Armor Pen\|Armor Pen]] | *Vs flanked targets:* +6% Crit Chance, +2 to +4 Damage, +3 Armor Pen, +3% resistance bypass; *Pressured foe:* -8 Melee Defense, -4 Melee Attack, -3 Armor, +2 turn(s) duration, -7% all resistances, +10 Shared Opening | 440 |
| L10 | *Vs flanked targets:* +1 [[Stats#Damage Max\|Damage Max]], +2% resistance bypass; *Pressured foe:* -2 [[Stats#Melee Attack\|Melee Attack]], -1 [[Stats#Armor\|Armor]], -3% all resistances, +1 turn(s) duration | *Vs flanked targets:* +6% Crit Chance, +2 to +5 Damage, +3 Armor Pen, +5% resistance bypass; *Pressured foe:* -8 Melee Defense, -6 Melee Attack, -4 Armor, +3 turn(s) duration, -10% all resistances, +10 Shared Opening | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Draw Their Eye (Skill Trait)\|Draw Their Eye]] | Common | Ability | 2 | [[Draw Their Eye (Ability)\|Draw Their Eye]] |
| [[Hammer and Anvil (Skill Trait)\|Hammer and Anvil]] | Common | Ability | 2 | [[Hammer and Anvil (Ability)\|Hammer and Anvil]] |
| [[Lingering Pressure]] | Common | Passive | 2 | — |
| [[Opening Strike (Skill Trait)\|Opening Strike]] | Common | Ability | 2 | [[Opening Strike (Ability)\|Opening Strike]] |
| [[Slip Away]] | Common | Passive | 2 | — |
| [[Surround Tactics]] | Common | Passive | 2 | — |
| [[Pack Tactics (Skill Trait)\|Pack Tactics]] | Uncommon | Passive | 2 | — |
| [[Sunder Together (Skill Trait)\|Sunder Together]] | Uncommon | Ability | 2 | [[Sunder Together (Ability)\|Sunder Together]] |
| [[Wolf Pack (Skill Trait)\|Wolf Pack]] | Uncommon | Passive | 2 | — |
| [[All Together Now (Skill Trait)\|All Together Now]] | Rare | Ability | 2 | [[All Together Now (Ability)\|All Together Now]] |

## Referenced by

- **Familiar to:** [[Arcane Prodigy]], [[Enforcer]], [[Herbalist]], [[Saboteur]], [[Scavenger]], [[Witch Hunter (Background)|Witch Hunter]]
- **Foreign to:** [[Champion (Background)|Champion]], [[Executioner (Background)|Executioner]], [[First Blade]], [[Penitent]], [[Templar (Background)|Templar]]
- **Guild signature skill:** [[Blade Circle]], [[Shadow Guild]]

*Generated from `skills/melee_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
