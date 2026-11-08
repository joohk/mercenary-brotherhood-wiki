---
id: duergar
type: faction
category: Factions
aliases:
  - duergar
tags:
  - ai/disciplined
  - faction/duergar
  - type/faction
source: enemies/duergar.json
ai_profile: Disciplined
level_min: 3
tier_max: 5
tier_min: 2
units: 11
---

An enemy faction that appears from company level 3 and fights as [[How Enemies Behave#Disciplined|Disciplined]] (holds formation, coordinated): 11 unit types, tiers 2-5.

![[_assets/Units/DuergarLord.webp|160]]

> Grey-skinned evil dwarves from the deep underground. Relentless, disciplined, and cruel. They forge dark iron and fight with warhammers and crossbows. Slavers who view surface-dwellers as chattel. Mid-to-late game faction.

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
| ![[_assets/Units/DuergarCrossbowman.webp\|40]] | [[Duergar Crossbowman]] | 2 | 79 | 8 | 53 | 47 | 75 | 13-21 (ranged) | Ranged | 3 | 20 |
| ![[_assets/Units/DuergarSlaveSoldier.webp\|40]] | [[Duergar Slave Soldier]] | 2 | 92 | 9 | 68 | 55 | 0 | 15-23 | Defensive | 3 | 18 |
| ![[_assets/Units/CopperGolem.webp\|40]] | [[Copper Golem]] | 3 | 300 | 21 | 80 | 48 | 0 | 47-69 | Aggressive | 9 | 48 |
| ![[_assets/Units/DuergarDarkSmith.webp\|40]] | [[Duergar Dark Smith]] | 3 | 94 | 10 | 62 | 55 | 85 | 12-18 | Ranged | 6 | 38 |
| ![[_assets/Units/DuergarIronguard.webp\|40]] | [[Duergar Ironguard]] | 3 | 130 | 15 | 85 | 78 | 0 | 30-47 | Defensive | 5 | 32 |
| ![[_assets/Units/DuergarStonekeeper.webp\|40]] | [[Duergar Stonekeeper]] | 3 | 109 | 9 | 57 | 55 | 71 | 21-33 | Ranged | 6 | 40 |
| ![[_assets/Units/DuergarTaskmaster.webp\|40]] | [[Duergar Taskmaster]] | 3 | 115 | 12 | 83 | 67 | 0 | 20-31 | Aggressive | 5 | 35 |
| ![[_assets/Units/DuergarWarpriest.webp\|40]] | [[Duergar Warpriest]] | 4 | 156 | 17 | 100 | 84 | 0 | 37-59 | Aggressive | 8 | 52 |
| ![[_assets/Units/IronGolem.webp\|40]] | [[Iron Golem]] | 4 | 450 | 26 | 96 | 55 | 0 | 72-103 | Aggressive | 13 | 70 |
| ![[_assets/Units/DuergarLord.webp\|40]] | [[Duergar Lord]] | 5 | 195 | 20 | 112 | 96 | 0 | 45-72 | Defensive | 12 | 72 |
| ![[_assets/Units/MithrilGolem.webp\|40]] | [[Mithril Golem]] | 5 | 600 | 32 | 112 | 62 | 0 | 102-140 | Aggressive | 19 | 100 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Hills — Encounter]] | Random | 1+ | Hills | 4 |
| [[Mountain — Encounter]] | Random | 1+ | Mountain | 4 |
| [[Mid-depth Crystal Cave Encounter]] | Random | 3+ | Crystal Cave | 1 |
| [[Mid-depth Dark Ruins Encounter]] | Random | 3+ | Dark Ruins | 1 |
| [[Mid-depth Tunnel Encounter]] | Random | 3+ | Tunnel | 3 |
| [[Mid-depth Cavern Encounter]] | Random | 4+ | Cavern | 3 |
| [[Mid-depth Mushroom Forest Encounter]] | Random | 4+ | Mushroom Forest | 1 |
| [[Mid-depth Stalagmite Encounter]] | Random | 4+ | Stalagmite Field | 1 |
| [[Mountains — Duergar Raid]] | Random | 5+ | Mountain, Hills | 5 |
| [[Deep Cavern Encounter]] | Random | 7+ | Cavern | 1 |

## Referenced by

- **Bases held:** [[Duergar Mining Camp]], [[Duergar Slave Fortress]]
- **Dungeons held:** [[Duergar Forge Complex]], [[Duergar Outpost]], [[Throne of the Deep King]]
- **Possible enemy in chains:** [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Duergar Bane]]

*Generated from `enemies/duergar.json`. Edits will be overwritten — put your own notes in Notes/.*
