---
id: skill_battle_hardened
type: skill
category: Skills
aliases:
  - Battle Hardened
  - skill_battle_hardened
tags:
  - skill-group/defense
  - skill/combat
  - type/skill
source: skills/defense_skills.json
discovery_source: hit_received
discovery_weight: 1
max_level: 10
skill_category: combat
skill_group: Defense
skill_traits: 7
---

A combat skill from the Defense group, with 10 levels and 7 skill traits.

> Surviving enough fights builds resilience that borders on supernatural. Increases max HP and willpower.

## How to train

**Trained by:** Take damage in combat.

**Discovery:** Can be discovered on a *hit received* event; discovery weight 1.

**Tutorial offer:** default list (#2), magic list (#4), melee list (#2), ranged list (#6), support list (#5). In the tutorial's guaranteed first level-up, units whose gear does not already suggest a skill are offered skills from these ordered lists.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | +6 [[Stats#Max HP\|Max HP]], +4 [[Stats#Willpower\|Willpower]] | +6 Max HP, +4 Willpower | 20 |
| L2 | +7 [[Stats#Max HP\|Max HP]], +5 [[Stats#Willpower\|Willpower]] | +13 Max HP, +9 Willpower | 35 |
| L3 | +6 [[Stats#Max HP\|Max HP]], +4 [[Stats#Willpower\|Willpower]] | +19 Max HP, +13 Willpower | 55 |
| L4 | +8 [[Stats#Max HP\|Max HP]], +5 [[Stats#Willpower\|Willpower]] | +27 Max HP, +18 Willpower | 85 |
| L5 | +7 [[Stats#Max HP\|Max HP]], +5 [[Stats#Willpower\|Willpower]] | +34 Max HP, +23 Willpower | 125 |
| L6 | +6 [[Stats#Max HP\|Max HP]], +4 [[Stats#Willpower\|Willpower]] | +40 Max HP, +27 Willpower | 180 |
| L7 | +6 [[Stats#Max HP\|Max HP]], +3 [[Stats#Willpower\|Willpower]] | +46 Max HP, +30 Willpower | 250 |
| L8 | +5 [[Stats#Max HP\|Max HP]], +3 [[Stats#Willpower\|Willpower]] | +51 Max HP, +33 Willpower | 335 |
| L9 | +4 [[Stats#Max HP\|Max HP]], +2 [[Stats#Willpower\|Willpower]] | +55 Max HP, +35 Willpower | 440 |
| L10 | +4 [[Stats#Max HP\|Max HP]], +2 [[Stats#Willpower\|Willpower]] | +59 Max HP, +37 Willpower | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Grit]] | Common | Passive | 2 | — |
| [[Thick Hide (Skill Trait)\|Thick Hide]] | Common | Passive | 2 | — |
| [[Bloodied Fury]] | Uncommon | Passive | 2 | — |
| [[Second Wind (Skill Trait)\|Second Wind]] | Uncommon | Ability | 2 | [[Second Wind (Ability)\|Second Wind]] |
| [[Veteran's Pace]] | Uncommon | Passive | 2 | — |
| [[Undying (Skill Trait, Battle Hardened)\|Undying]] | Rare | Passive | 2 | — |
| [[War Veteran]] | Rare | Passive | 2 | — |

## Referenced by

- **Familiar to:** [[Arcane Prodigy]], [[Beast Tamer]], [[Beastmaster]], [[Blood Initiate]], [[Blood Shaman]], [[Cultist]], [[Enforcer]], [[Farmhand]], [[Feral Champion]], [[Fungus Farmer]], [[Geomancer (Background)|Geomancer]], [[Gladiator (Background)|Gladiator]], [[Mind Shaper]], [[Penitent]], [[Pit Fighter]], [[Pit Slave]], [[Raider]], [[Ravager (Background)|Ravager]], [[Royal Exile]], [[Runecarver]], [[Tinkerer]], [[Tribal Warrior]], [[Void Touched]], [[War Mage]], [[War Priest]], [[Warchief]], [[Zealot (Background)|Zealot]]
- **Foreign to:** [[Grand Master]], [[Master Archer]], [[Saboteur]], [[Scout]], [[Thief (Background)|Thief]]
- **Guild signature skill:** [[Fighters' Guild]]
- **Starting skill of:** [[Arcane Prodigy]], [[Beast Tamer]], [[Beastmaster]], [[Blood Shaman]], [[Cultist]], [[Enforcer]], [[Feral Champion]], [[Geomancer (Background)|Geomancer]], [[Mind Shaper]], [[Penitent]], [[Pit Fighter]], [[Ravager (Background)|Ravager]], [[Royal Exile]], [[Runecarver]], [[Tribal Warrior]], [[Void Touched]], [[War Mage]], [[War Priest]], [[Warchief]], [[Zealot (Background)|Zealot]]
- **Taught at:** [[Hermit Trainer]]

*Generated from `skills/defense_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
