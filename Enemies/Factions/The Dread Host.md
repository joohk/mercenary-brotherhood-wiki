---
id: dread_host
type: faction
category: Factions
aliases:
  - dread_host
tags:
  - ai/mindless
  - faction/dread_host
  - type/faction
source: enemies/dread_host.json
ai_profile: Relentless
level_min: 5
tier_max: 5
tier_min: 1
units: 8
---

An enemy faction that appears from company level 5 and fights as [[How Enemies Behave#Relentless|Relentless]] (fearless, charges without thought): 8 unit types, tiers 1-5.

![[_assets/Units/LichCommander.webp|160]]

> An evil empire combining necromancy with dark knights and war mages. Powerful undead summons pad their ranks while living soldiers form the elite core. Late-game faction.

## Overview

|  | Value |
|---|---|
| Company level | 5+ |
| AI profile | [[How Enemies Behave#Relentless\|Relentless]] — fearless, charges without thought |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/DreadThrall.webp\|40]] | [[Dread Thrall]] | 1 | 55 | 2 | 45 | 28 | 0 | 6-10 | Aggressive | 1 | 8 |
| ![[_assets/Units/DarkSoldier.webp\|40]] | [[Dark Soldier]] | 2 | 106 | 11 | 77 | 64 | 0 | 14-22 | Aggressive | 4 | 25 |
| ![[_assets/Units/DreadArcher.webp\|40]] | [[Dread Archer]] | 2 | 59 | 4 | 46 | 36 | 75 | 19-31 (ranged) | Ranged | 3 | 16 |
| ![[_assets/Units/DreadKnight.webp\|40]] | [[Dread Knight]] | 3 | 137 | 16 | 94 | 80 | 0 | 28-44 | Aggressive | 7 | 42 |
| ![[_assets/Units/WarNecromancer.webp\|40]] | [[War Necromancer]] | 3 | 86 | 8 | 57 | 48 | 92 | 20-33 (ranged) | Ranged | 6 | 38 |
| ![[_assets/Units/BoneColossus.webp\|40]] | [[Bone Colossus]] | 4 | 218 | 14 | 90 | 62 | 0 | 38-59 | Aggressive | 9 | 52 |
| ![[_assets/Units/DarkGeneral.webp\|40]] | [[Dark General]] | 4 | 172 | 18 | 109 | 92 | 0 | 34-55 | Aggressive | 11 | 62 |
| ![[_assets/Units/LichCommander.webp\|40]] | [[Lich Commander]] | 5 | 146 | 12 | 75 | 62 | 116 | 29-46 | Ranged | 14 | 78 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 2 |
| [[Deep Crystal Cave Encounter]] | Random | 6+ | Crystal Cave | 1 |
| [[Deep Stalagmite Encounter]] | Random | 7+ | Stalagmite Field | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |
| [[Ruins — Late Tier]] | Random | 8+ | Ruins | 1 |

## Referenced by

- **Slayer properties:** [[Dread Host Bane]]

*Generated from `enemies/dread_host.json`. Edits will be overwritten — put your own notes in Notes/.*
