---
id: skill_flanking
type: skill
category: Skills
aliases:
  - skill_flanking
tags:
  - skill-group/melee
  - skill/combat
  - type/skill
source: skills/melee_skills.json
discovery_source: side_arc_hit
discovery_weight: 0.6
max_level: 10
skill_category: combat
skill_group: Melee
skill_traits: 11
---

A combat skill from the Melee group, with 10 levels and 11 skill traits.

> You read a foe's guard and step outside it. Every bonus here applies only on a melee attack that lands in the target's side arc.

## How to train

**Trained by:** Land a melee hit in an enemy's side arc.

**Discovery:** Can be discovered on a *side arc hit* event; discovery weight 0.6.

## Progression

Bonuses are **cumulative**: each level adds its gains on top of every earlier level (the *Total so far* column). *Uses to next level* is how many qualifying actions it takes to reach the following level. Bonuses in *italics* only apply in that situation.

| Level | Gains this level | Total so far | Uses to next level |
|---|---|---|---|
| L1 | *Side-arc hits:* +4 [[Stats#Melee Attack\|Melee Attack]] | *Side-arc hits:* +4 Melee Attack | 20 |
| L2 | *Side-arc hits:* +3 [[Stats#Melee Attack\|Melee Attack]], +1% [[Stats#Crit Chance\|Crit Chance]] | *Side-arc hits:* +7 Melee Attack, +1% Crit Chance | 40 |
| L3 | *Side-arc hits:* +2 [[Stats#Melee Attack\|Melee Attack]], +1 [[Stats#Damage Min\|Damage]] | *Side-arc hits:* +9 Melee Attack, +1% Crit Chance, +1 Damage | 70 |
| L4 | *Side-arc hits:* +2% [[Stats#Crit Chance\|Crit Chance]], +2 [[Stats#Damage Max\|Damage Max]] | *Side-arc hits:* +9 Melee Attack, +3% Crit Chance, +1 to +3 Damage | 110 |
| L5 | *Side-arc hits:* +2 [[Stats#Melee Attack\|Melee Attack]], +2 [[Stats#Armor Pen\|Armor Pen]] | *Side-arc hits:* +11 Melee Attack, +3% Crit Chance, +1 to +3 Damage, +2 Armor Pen | 160 |
| L6 | *Side-arc hits:* +2% [[Stats#Crit Chance\|Crit Chance]], +1 to +2 [[Stats#Damage Min\|Damage]] | *Side-arc hits:* +11 Melee Attack, +5% Crit Chance, +2 to +5 Damage, +2 Armor Pen | 220 |
| L7 | *Side-arc hits:* +2 [[Stats#Melee Attack\|Melee Attack]], +1% [[Stats#Crit Chance\|Crit Chance]], +2 [[Stats#Damage Max\|Damage Max]] | *Side-arc hits:* +13 Melee Attack, +6% Crit Chance, +2 to +7 Damage, +2 Armor Pen | 290 |
| L8 | *Side-arc hits:* +3 [[Stats#Armor Pen\|Armor Pen]], +1 to +2 [[Stats#Damage Min\|Damage]] | *Side-arc hits:* +13 Melee Attack, +6% Crit Chance, +3 to +9 Damage, +5 Armor Pen | 360 |
| L9 | *Side-arc hits:* +2 [[Stats#Melee Attack\|Melee Attack]], +2% [[Stats#Crit Chance\|Crit Chance]], +3 [[Stats#Damage Max\|Damage Max]] | *Side-arc hits:* +15 Melee Attack, +8% Crit Chance, +3 to +12 Damage, +5 Armor Pen | 440 |
| L10 | *Side-arc hits:* +3% [[Stats#Crit Chance\|Crit Chance]], +2 to +3 [[Stats#Damage Min\|Damage]] | *Side-arc hits:* +15 Melee Attack, +11% Crit Chance, +5 to +15 Damage, +5 Armor Pen | max |

## Skill traits

Each level-up offers a skill trait from this list: 60% of the time the offer upgrades a skill trait you already own, 40% of the time it is a new one (base weights 60 / 40).

| Skill trait | Rarity | Type | Ranks | Grants |
|---|---|---|---|---|
| [[Circle the Prey (Skill Trait)\|Circle the Prey]] | Common | Ability | 2 | [[Circle the Prey (Ability)\|Circle the Prey]] |
| [[Off Angle]] | Common | Passive | 2 | — |
| [[Blindside (Skill Trait)\|Blindside]] | Uncommon | Ability | 2 | [[Blindside (Ability)\|Blindside]] |
| [[Expose the Flank (Skill Trait)\|Expose the Flank]] | Uncommon | Ability | 2 | [[Expose the Flank (Ability)\|Expose the Flank]] |
| [[No Safe Side]] | Uncommon | Passive | 2 | — |
| [[Pack Tactics (Skill Trait)\|Pack Tactics]] | Uncommon | Passive | 2 | — |
| [[Pivot Strike (Skill Trait)\|Pivot Strike]] | Uncommon | Ability | 2 | [[Pivot Strike (Ability)\|Pivot Strike]] |
| [[Vulture]] | Uncommon | Passive | 2 | — |
| [[Cut the Strings]] | Rare | Passive | 2 | — |
| [[Encircled (Skill Trait)\|Encircled]] | Rare | Passive | 2 | — |
| [[Two Fronts (Skill Trait)\|Two Fronts]] | Rare | Ability | 2 | [[Two Fronts (Ability)\|Two Fronts]] |

## Referenced by

- **Familiar to:** [[Duelist (Background)|Duelist]], [[Runecarver]], [[Shadow Mage]], [[Street Urchin]]
- **Foreign to:** [[Crusader (Background)|Crusader]], [[Executioner (Background)|Executioner]], [[Geomancer (Background)|Geomancer]], [[Pathfinder]], [[War Priest]], [[Warden]]

*Generated from `skills/melee_skills.json`. Edits will be overwritten — put your own notes in Notes/.*
