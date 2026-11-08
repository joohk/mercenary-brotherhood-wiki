---
id: undead
type: faction
category: Factions
aliases:
  - undead
tags:
  - ai/mindless
  - faction/undead
  - type/faction
source: enemies/undead.json
ai_profile: Relentless
level_min: 1
tier_max: 4
tier_min: 1
units: 8
---

An enemy faction that appears from company level 1 and fights as [[How Enemies Behave#Relentless|Relentless]] (fearless, charges without thought): 8 unit types, tiers 1-4.

![[_assets/Units/Necromancer.webp|160]]

> Slow but high armor and resolve; found in ruins and dungeons

## Overview

|  | Value |
|---|---|
| Company level | 1+ |
| AI profile | [[How Enemies Behave#Relentless\|Relentless]] — fearless, charges without thought |
| Faction AI tweaks | Goes after healers and casters 0% |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Zombie.webp\|40]] | [[Zombie]] | 1 | 80 | 3 | 40 | 25 | 0 | 6-11 | Aggressive | 2 | 10 |
| ![[_assets/Units/Ghoul.webp\|40]] | [[Ghoul]] | 2 | 73 | 6 | 72 | 47 | 0 | 12-20 | Aggressive | 3 | 18 |
| ![[_assets/Units/SkeletonWarrior.webp\|40]] | [[Skeleton]] | 2 | 66 | 9 | 66 | 53 | 0 | 19-32 | Aggressive | 3 | 15 |
| ![[_assets/Units/SkeletonArcher.webp\|40]] | [[Skeleton Archer]] | 2 | 53 | 7 | 55 | 42 | 72 | 14-24 (ranged) | Ranged | 3 | 15 |
| ![[_assets/Units/CorpseHulk.webp\|40]] | [[Corpse Hulk]] | 3 | 187 | 16 | 77 | 46 | 0 | 21-34 | Aggressive | 6 | 35 |
| ![[_assets/Units/Revenant.webp\|40]] | [[Revenant]] | 3 | 144 | 14 | 83 | 63 | 0 | 32-53 | Aggressive | 6 | 40 |
| ![[_assets/Units/Necromancer.webp\|40]] | [[Necromancer]] | 4 | 109 | 7 | 60 | 50 | 90 | 22-38 (ranged) | Ranged | 8 | 60 |
| ![[_assets/Units/Wight.webp\|40]] | [[Wight]] | 4 | 140 | 17 | 96 | 74 | 0 | 38-65 | Aggressive | 8 | 55 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 2 |
| [[Ruins — Early]] | Random | 2-4 | Ruins | 5 |
| [[Mid-depth Dark Ruins Encounter]] | Random | 3+ | Dark Ruins | 1 |
| [[Ruins Base Garrison — Shallow]] | Static | 3-4 | Ruins | 1 |
| [[Ruins — Mid Tier]] | Random | 5+ | Ruins | 2 |
| [[Deep Dark Ruins Encounter]] | Random | 6+ | Dark Ruins | 1 |
| [[Ruins — Late Tier]] | Random | 8+ | Ruins | 1 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Valthor, Drethis, Malachar, Ossevain, Nekrul, Graveth, Morwyn, Dustal, Krevas, Ashborn, Rothar, Boneval, Cryptis, Skelorn, Ghul. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Necromancer's Tower]], [[Undead Barrow]], [[Undead Crypt]]
- **Dungeons held:** [[Barrow Mounds]], [[Catacomb Depths]], [[Crumbling Ruins]], [[The Deep Tomb]], [[The Plague Pits]], [[Warlord Tomb]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Uprising]]
- **Power shifts when these villains die:** [[Bloodlord Kael]], [[Plague Bishop Malachar]]
- **Slayer properties:** [[Undead Bane (Magic Property, vs Undead Faction)|Undead Bane]]

*Generated from `enemies/undead.json`. Edits will be overwritten — put your own notes in Notes/.*
