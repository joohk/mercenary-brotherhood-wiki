---
id: veterans
type: faction
category: Factions
aliases:
  - veterans
tags:
  - ai/professional
  - faction/veterans
  - type/faction
source: enemies/veterans.json
ai_profile: Professional
level_min: 7
tier_max: 4
tier_min: 3
units: 5
---

An enemy faction that appears from company level 7 and fights as [[How Enemies Behave#Professional|Professional]] (skilled and pragmatic): 5 unit types, tiers 3-4.

![[_assets/Units/OrcVeteranSergeant.webp|160]]

> Disciplined, well-armored, high damage; mid-to-late game threat. A multiracial professional unit: human veterans form the core shield line, elves serve as precision archers, orcs command as sergeants, halflings as scouts/skirmishers, and goblins as engineer-sappers. Each unit is a single race so the faction reads as a proper mixed-race military.

## Overview

|  | Value |
|---|---|
| Company level | 7+ |
| AI profile | [[How Enemies Behave#Professional\|Professional]] — skilled and pragmatic |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/ElfVeteranArcher.webp\|40]] | [[Elf Veteran Archer]] | 3 | 90 | 8 | 71 | 66 | 103 | 27-44 (ranged) | Ranged | 5 | 28 |
| ![[_assets/Units/GoblinSapperVeteran.webp\|40]] | [[Goblin Sapper-Veteran]] | 3 | 83 | 9 | 67 | 63 | 83 | 25-41 (ranged) | Ranged | 5 | 26 |
| ![[_assets/Units/HalflingScoutVeteran.webp\|40]] | [[Halfling Scout-Veteran]] | 3 | 78 | 8 | 86 | 86 | 63 | 27-41 | Aggressive | 5 | 26 |
| ![[_assets/Units/VeteranSoldier.webp\|40]] | [[Human Veteran Soldier]] | 3 | 115 | 14 | 89 | 75 | 0 | 30-49 | Aggressive | 6 | 30 |
| ![[_assets/Units/OrcVeteranSergeant.webp\|40]] | [[Orc Veteran Sergeant]] | 4 | 166 | 19 | 108 | 89 | 0 | 45-73 | Aggressive | 10 | 55 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Ruins — Mid Tier]] | Random | 5+ | Ruins | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Referenced by

- **Slayer properties:** [[Veterans Bane]]

*Generated from `enemies/veterans.json`. Edits will be overwritten — put your own notes in Notes/.*
