---
id: eastern_empire
type: faction
category: Factions
aliases:
  - eastern_empire
tags:
  - ai/disciplined
  - faction/eastern_empire
  - type/faction
source: enemies/eastern_empire.json
ai_profile: Disciplined
level_min: 3
tier_max: 5
tier_min: 1
units: 11
---

An enemy faction that appears from company level 3 and fights as [[How Enemies Behave#Disciplined|Disciplined]] (holds formation, coordinated): 11 unit types, tiers 1-5.

![[_assets/Units/Daimyo.webp|160]]

> A disciplined feudal army of civilized ratkin from across the sea. Their highly-ordered society is the polar opposite of the feral Ratkin Swarm. Ashigaru foot soldiers form the bulk of their forces, supported by elite samurai-rats and shadowy shinobi. Highly organized, honor-bound, with iron resolve.

## Overview

|  | Value |
|---|---|
| Company level | 3+ |
| AI profile | [[How Enemies Behave#Disciplined\|Disciplined]] — holds formation, coordinated |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/AshigaruSpearman.webp\|40]] | [[Ratkin Ashigaru]] | 1 | 52 | 3 | 52 | 39 | 0 | 7-13 | Defensive | 2 | 12 |
| ![[_assets/Units/AshigaruArcher.webp\|40]] | [[Ratkin Bowman]] | 1 | 42 | 1 | 32 | 32 | 60 | 9-15 (ranged) | Ranged | 2 | 14 |
| ![[_assets/Units/AshigaruSergeant.webp\|40]] | [[Ratkin Ashigaru-Kashira]] | 2 | 88 | 9 | 77 | 64 | 0 | 14-22 | Aggressive | 3 | 22 |
| ![[_assets/Units/AshigaruGunner.webp\|40]] | [[Ratkin Tanegashima Gunner]] | 2 | 59 | 6 | 44 | 42 | 81 | 12-21 (ranged) | Ranged | 3 | 20 |
| ![[_assets/Units/Ronin.webp\|40]] | [[Ratkin Ronin]] | 3 | 103 | 10 | 97 | 70 | 0 | 21-32 | Aggressive | 7 | 40 |
| ![[_assets/Units/Samurai.webp\|40]] | [[Ratkin Samurai]] | 3 | 110 | 13 | 94 | 72 | 0 | 20-31 | Aggressive | 6 | 38 |
| ![[_assets/Units/Shinobi.webp\|40]] | [[Ratkin Shinobi]] | 3 | 71 | 7 | 91 | 63 | 79 | 18-27 | Aggressive | 5 | 35 |
| ![[_assets/Units/SamuraiArcher.webp\|40]] | [[Ratkin Yabusame]] | 3 | 92 | 10 | 74 | 62 | 99 | 11-19 (ranged) | Ranged | 5 | 32 |
| ![[_assets/Units/Hatamoto.webp\|40]] | [[Ratkin Hatamoto]] | 4 | 140 | 17 | 110 | 84 | 0 | 34-55 | Aggressive | 10 | 58 |
| ![[_assets/Units/WarriorMonk.webp\|40]] | [[Ratkin Sohei]] | 4 | 126 | 12 | 102 | 75 | 0 | 23-38 | Aggressive | 8 | 48 |
| ![[_assets/Units/Daimyo.webp\|40]] | [[Ratkin Daimyo]] | 5 | 169 | 20 | 119 | 90 | 0 | 42-66 | Aggressive | 14 | 72 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Plains — Eastern Empire Patrol]] | Random | 3+ | Plains, Road | 9 |

## Referenced by

- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Crime Lord]], [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Eastern Empire Bane]]

*Generated from `enemies/eastern_empire.json`. Edits will be overwritten — put your own notes in Notes/.*
