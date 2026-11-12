---
id: deserters
type: faction
category: Factions
aliases:
  - deserters
tags:
  - ai/professional
  - faction/deserters
  - type/faction
source: enemies/deserters.json
ai_profile: Professional
level_min: 2
tier_max: 3
tier_min: 1
units: 8
up: "[[Outlaws & Sellswords]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Outlaws & Sellswords]]

An enemy faction that appears from company level 2 and fights as [[How Enemies Behave#Professional|Professional]] (skilled and pragmatic): 8 unit types, tiers 1-3.

![[_assets/Units/DeserterCaptain.webp|160]]

> Soldiers who abandoned their posts and turned to banditry. Better equipped than common bandits but broken in morale. Found on roads and plains.

## Overview

|  | Value |
|---|---|
| Company level | 2+ |
| AI profile | [[How Enemies Behave#Professional\|Professional]] — skilled and pragmatic |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/DeserterFootman.webp\|40]] | [[Deserter Footman]] | 1 | 60 | 4 | 56 | 42 | 0 | 10-17 | Aggressive | 2 | 12 |
| ![[_assets/Units/DeserterMilitia.webp\|40]] | [[Deserter Militia]] | 1 | 55 | 3 | 51 | 38 | 0 | 10-17 | Aggressive | 2 | 10 |
| ![[_assets/Units/DeserterSwordsman.webp\|40]] | [[Deserter Swordsman]] | 1 | 60 | 2 | 61 | 42 | 0 | 11-17 | Aggressive | 2 | 16 |
| ![[_assets/Units/DeserterArcher.webp\|40]] | [[Deserter Archer]] | 2 | 66 | 7 | 55 | 47 | 75 | 10-16 (ranged) | Ranged | 3 | 18 |
| ![[_assets/Units/DeserterSergeant.webp\|40]] | [[Deserter Sergeant]] | 2 | 106 | 10 | 77 | 62 | 0 | 14-22 | Aggressive | 4 | 25 |
| ![[_assets/Units/RogueBattleMage.webp\|40]] | [[Rogue Battlemage]] | 2 | 61 | 3 | 44 | 40 | 0 | 7-12 (ranged) | Ranged | 3 | 22 |
| ![[_assets/Units/DeserterCaptain.webp\|40]] | [[Deserter Captain]] | 3 | 123 | 14 | 87 | 71 | 0 | 28-44 | Aggressive | 7 | 38 |
| ![[_assets/Units/RogueKnight.webp\|40]] | [[Rogue Knight]] | 3 | 130 | 15 | 90 | 74 | 0 | 19-30 | Aggressive | 6 | 35 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 6 |
| [[The Usurper's Castle (Encounter Table)\|The Usurper's Castle]] | Static | 1+ | Castle | 1 |
| [[Plains Base Garrison — Shallow]] | Static | 3-4 | Plains | 1 |
| [[Road — Ambush]] | Random | 3+ | Road | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Plains — Deserter Camp]] | Static | 5-7 | Plains | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Referenced by

- **Bases held:** [[Deserter Fort]], [[Deserter Hideout]], [[Rogue Knight's Keep]], [[The Usurper's Castle (Enemy Base)|The Usurper's Castle]]
- **Dungeons held:** [[Deserter Bunker]], [[Old War Camp]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Crime Lord]], [[The Marauding Army]], [[The Uprising]]
- **Power shifts when these villains die:** [[The Iron Tyrant]], [[The Shadow Weaver]], [[Warlord Ash]]
- **Slayer properties:** [[Deserters Bane]]

*Generated from `enemies/deserters.json`. Edits will be overwritten — put your own notes in Notes/.*
