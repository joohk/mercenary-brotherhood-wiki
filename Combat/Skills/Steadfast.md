---
id: skill_steadfast
type: skill
category: Skills
aliases:
  - skill_steadfast
tags:
  - skill-group/defense
  - skill/combat
  - type/skill
source: skills/defense_skills.json
discovery_source: morale_pass
discovery_weight: 0.5
max_level: 10
skill_category: combat
skill_group: Defense
skill_traits: 7
---

A combat skill from the Defense group, with 10 levels and 7 skill traits.

> You've stared death down and didn't blink. Gains XP from passing morale checks.

## How to train

**Trained by:** Pass a morale check.

**Discovery:** Can be discovered on a *morale pass* event; discovery weight 0.5.

**Tutorial offer:** default list (#4), magic list (#2), melee list (#7), support list (#3). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | +5 [[Stats#Willpower\|Willpower]] | +5 Willpower | 10 |
| L2 | +5 [[Stats#Willpower\|Willpower]], +3 [[Stats#Max HP\|Max HP]] | +10 Willpower, +3 Max HP | 25 |
| L3 | +4 [[Stats#Willpower\|Willpower]], +3 [[Stats#Max HP\|Max HP]] | +14 Willpower, +6 Max HP | 45 |
| L4 | +4 [[Stats#Willpower\|Willpower]], +3 [[Stats#Max HP\|Max HP]] | +18 Willpower, +9 Max HP | 70 |
| L5 | +3 [[Stats#Willpower\|Willpower]], +3 [[Stats#Max HP\|Max HP]] | +21 Willpower, +12 Max HP | 100 |
| L6 | +3 [[Stats#Willpower\|Willpower]], +2 [[Stats#Max HP\|Max HP]] | +24 Willpower, +14 Max HP | 140 |
| L7 | +3 [[Stats#Willpower\|Willpower]], +2 [[Stats#Max HP\|Max HP]] | +27 Willpower, +16 Max HP | 200 |
| L8 | +2 [[Stats#Willpower\|Willpower]], +2 [[Stats#Max HP\|Max HP]] | +29 Willpower, +18 Max HP | 280 |
| L9 | +2 [[Stats#Willpower\|Willpower]], +2 [[Stats#Max HP\|Max HP]] | +31 Willpower, +20 Max HP | 440 |
| L10 | +2 [[Stats#Willpower\|Willpower]], +2 [[Stats#Max HP\|Max HP]] | +33 Willpower, +22 Max HP | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Iron Will (Skill Trait, Steadfast)\|Iron Will]] | Common | Passive | 2 | — |
| [[Stoic (Skill Trait)\|Stoic]] | Common | Passive | 2 | — |
| [[Inspiring Presence (Skill Trait)\|Inspiring Presence]] | Uncommon | Passive | 2 | — |
| [[Rally (Skill Trait)\|Rally]] | Uncommon | Ability | 1 | [[Rally (Ability)\|Rally]] |
| [[Defiant]] | Rare | Passive | 2 | — |
| [[Unbowed Will]] | Rare | Passive | 2 | — |
| [[Unbreakable Will (Skill Trait)\|Unbreakable Will]] | Rare | Passive | 1 | — |

## Referenced by

- **Familiar to:** [[Acolyte]], [[Acolyte Militant]], [[Grave Digger]], [[Grave Tender]], [[Militia]], [[Pilgrim]], [[Shepherd]], [[Temple Guard]]
- **Foreign to:** [[Deserter]], [[Pit Slave]], [[Poacher]], [[Street Urchin]]
- **Guild signature skill:** [[Fighters' Guild]], [[Holy Order]]

*Generated from `skills/defense_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
