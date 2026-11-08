---
id: aurelian_legions
type: faction
category: Factions
aliases:
  - aurelian_legions
tags:
  - ai/disciplined
  - faction/aurelian_legions
  - type/faction
source: enemies/aurelian_legions.json
ai_profile: Disciplined
level_min: 5
tier_max: 5
tier_min: 1
units: 10
---

An enemy faction that appears from company level 5 and fights as [[How Enemies Behave#Disciplined|Disciplined]] (holds formation, coordinated): 10 unit types, tiers 1-5.

![[_assets/Units/SlannWarlord.webp|160]]

> A disciplined professional army of lizardmen and their bred war-beasts, modelled after the Roman Empire but with scaled legionaries, javelin-hurling skinks, and exotic dinosaur units. Cold-blooded patience combined with iron formations.

## Overview

|  | Value |
|---|---|
| Company level | 5+ |
| AI profile | [[How Enemies Behave#Disciplined\|Disciplined]] — holds formation, coordinated |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/SkinkScreen.webp\|40]] | [[Skink Screen]] | 1 | 62 | 4 | 50 | 37 | 0 | 7-13 | Defensive | 2 | 10 |
| ![[_assets/Units/SaurianWarrior.webp\|40]] | [[Saurian Legionary]] | 2 | 112 | 13 | 79 | 68 | 61 | 15-24 | Aggressive | 3 | 26 |
| ![[_assets/Units/SkinkJavelineer.webp\|40]] | [[Skink Javelineer]] | 2 | 75 | 7 | 59 | 47 | 77 | 9-17 (ranged) | Ranged | 2 | 16 |
| ![[_assets/Units/ColdOneRider.webp\|40]] | [[Cold One Rider]] | 3 | 136 | 15 | 98 | 69 | 0 | 20-32 | Aggressive | 7 | 42 |
| ![[_assets/Units/SalamanderHandler.webp\|40]] | [[Salamander Handler]] | 3 | 110 | 9 | 60 | 48 | 92 | 19-32 (ranged) | Ranged | 6 | 36 |
| ![[_assets/Units/SaurianEternityGuard.webp\|40]] | [[Saurian Eternity Guard]] | 3 | 144 | 17 | 99 | 80 | 0 | 29-46 | Aggressive | 7 | 44 |
| ![[_assets/Units/SaurianTempleGuard.webp\|40]] | [[Saurian Temple Guard]] | 3 | 143 | 21 | 87 | 90 | 0 | 20-31 | Defensive | 6 | 38 |
| ![[_assets/Units/SaurianOldblood.webp\|40]] | [[Saurian Oldblood]] | 4 | 170 | 19 | 109 | 91 | 0 | 35-56 | Aggressive | 9 | 55 |
| ![[_assets/Units/Stegadon.webp\|40]] | [[Stegadon]] | 4 | 264 | 24 | 94 | 58 | 72 | 12-22 | Aggressive | 11 | 62 |
| ![[_assets/Units/SlannWarlord.webp\|40]] | [[Slann Warlord]] | 5 | 194 | 20 | 110 | 100 | 115 | 42-66 | Aggressive | 14 | 78 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Arch-villains

- [[The Iron Tyrant]] — *Imperator Ssethek*, from company level 7

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Road — Ambush]] | Random | 3+ | Road | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Referenced by

- **Possible enemy in chains:** [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Aurelian Legions Bane]]

*Generated from `enemies/aurelian_legions.json`. Edits will be overwritten — put your own notes in Notes/.*
