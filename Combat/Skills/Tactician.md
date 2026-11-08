---
id: skill_tactician
type: skill
category: Skills
aliases:
  - skill_tactician
tags:
  - skill-group/utility
  - skill/combat
  - type/skill
source: skills/utility_skills.json
discovery_source: use_ability
discovery_weight: 0.5
max_level: 10
skill_category: combat
skill_group: Utility
skill_traits: 6
---

A combat skill from the Utility group, with 10 levels and 6 skill traits.

> Every battle is a chess match. Gains XP from using active abilities.

## How to train

**Trained by:** Use an active ability in combat.

**Discovery:** Can be discovered on a *use ability* event; discovery weight 0.5.

**Tutorial offer:** magic list (#1), support list (#1). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | +5 [[Stats#Max Fatigue\|Max Fatigue]] | +5 Max Fatigue | 15 |
| L2 | +4 [[Stats#Max Fatigue\|Max Fatigue]], +3 [[Stats#Willpower\|Willpower]] | +9 Max Fatigue, +3 Willpower | 30 |
| L3 | +4 [[Stats#Max Fatigue\|Max Fatigue]], +3 [[Stats#Willpower\|Willpower]] | +13 Max Fatigue, +6 Willpower | 55 |
| L4 | +3 [[Stats#Max Fatigue\|Max Fatigue]], +2 [[Stats#Willpower\|Willpower]] | +16 Max Fatigue, +8 Willpower | 85 |
| L5 | +3 [[Stats#Max Fatigue\|Max Fatigue]], +2 [[Stats#Willpower\|Willpower]] | +19 Max Fatigue, +10 Willpower | 125 |
| L6 | +3 [[Stats#Max Fatigue\|Max Fatigue]], +2 [[Stats#Willpower\|Willpower]] | +22 Max Fatigue, +12 Willpower | 180 |
| L7 | +2 [[Stats#Max Fatigue\|Max Fatigue]], +2 [[Stats#Willpower\|Willpower]] | +24 Max Fatigue, +14 Willpower | 250 |
| L8 | +2 [[Stats#Max Fatigue\|Max Fatigue]], +2 [[Stats#Willpower\|Willpower]] | +26 Max Fatigue, +16 Willpower | 335 |
| L9 | +2 [[Stats#Max Fatigue\|Max Fatigue]], +1 [[Stats#Willpower\|Willpower]] | +28 Max Fatigue, +17 Willpower | 440 |
| L10 | +2 [[Stats#Max Fatigue\|Max Fatigue]], +1 [[Stats#Willpower\|Willpower]] | +30 Max Fatigue, +18 Willpower | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Anticipate]] | Common | Passive | 2 | — |
| [[Calm Under Pressure]] | Common | Passive | 2 | — |
| [[Efficient]] | Common | Passive | 2 | — |
| [[Battle Cry (Skill Trait, Tactician)\|Battle Cry]] | Uncommon | Ability | 1 | [[Battle Cry (Ability)\|Battle Cry]] |
| [[Command (Skill Trait)\|Command]] | Uncommon | Ability | 2 | [[Command (Ability)\|Command]] |
| [[Mastermind]] | Rare | Passive | 2 | — |

## Referenced by

- **Familiar to:** [[Minstrel]], [[Outrider]], [[Royal Exile]], [[Scroll Scribe]], [[Venom Adept]], [[Warchief]]
- **Foreign to:** [[Beggar]], [[Deserter]], [[Forager]], [[Fungus Farmer]], [[Pit Slave]], [[Shaman]], [[Shepherd]], [[Tanner]], [[Vagabond]]
- **Guild signature skill:** [[Arcane Conclave (Guild)|Arcane Conclave]], [[Blade Circle]], [[Hunters' Lodge]]
- **Starting skill of:** [[Royal Exile]], [[Warchief]]

*Generated from `skills/utility_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
