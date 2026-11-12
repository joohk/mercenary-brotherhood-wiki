---
id: rabble
type: faction
category: Factions
aliases:
  - rabble
tags:
  - ai/chaotic
  - faction/rabble
  - type/faction
source: enemies/rabble.json
ai_profile: Undisciplined
level_max: 2
level_min: 1
tier_max: 1
tier_min: 0
units: 5
up: "[[Outlaws & Sellswords]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Outlaws & Sellswords]]

An enemy faction that appears at company levels 1-2 and fights as [[How Enemies Behave#Undisciplined|Undisciplined]] (unpredictable, low coordination): 5 unit types, tiers 0-1.

![[_assets/Units/RabbleRingleader.webp|160]]

> Very early-game fodder. Starving farmers and vagrants driven to raiding. 2 thugs ≈ 1 trained soldier. Appears only at low company levels.

## Overview

|  | Value |
|---|---|
| Company level | 1-2 |
| AI profile | [[How Enemies Behave#Undisciplined\|Undisciplined]] — unpredictable, low coordination |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/RabbleCutpurse.webp\|40]] | [[Cutpurse]] | 0 | 22 | 0 | 38 | 36 | 0 | 4-9 | Aggressive | 1 | 7 |
| ![[_assets/Units/StarvingThug.webp\|40]] | [[Starving Thug]] | 0 | 25 | 0 | 48 | 25 | 0 | 6-11 | Aggressive | 1 | 6 |
| ![[_assets/Units/RabbleStoneThrower.webp\|40]] | [[Stone Thrower]] | 0 | 19 | 0 | 20 | 18 | 42 | 6-11 (ranged) | Ranged | 1 | 5 |
| ![[_assets/Units/RabbleRingleader.webp\|40]] | [[Rabble Ringleader]] | 1 | 48 | 2 | 55 | 32 | 0 | 12-20 | Aggressive | 2 | 12 |
| ![[_assets/Units/RabbleTorchbearer.webp\|40]] | [[Torchbearer]] | 1 | 26 | 0 | 25 | 22 | 42 | 4-8 (ranged) | Ranged | 1 | 8 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 5 |
| [[Roadside Ambush]] | Static | 1+ | Plains | 1 |

## Referenced by

- **Bases held:** [[Rabble Encampment]]
- **Slayer properties:** [[Rabble Bane]]

*Generated from `enemies/rabble.json`. Edits will be overwritten — put your own notes in Notes/.*
