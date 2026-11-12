---
id: inquisition
type: faction
category: Factions
aliases:
  - inquisition
tags:
  - ai/disciplined
  - faction/inquisition
  - type/faction
source: enemies/inquisition.json
ai_profile: Disciplined
level_min: 5
tier_max: 5
tier_min: 1
units: 8
up: "[[Armies & Orders]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Armies & Orders]]

An enemy faction that appears from company level 5 and fights as [[How Enemies Behave#Disciplined|Disciplined]] (holds formation, coordinated): 8 unit types, tiers 1-5.

![[_assets/Units/GrandInquisitor.webp|160]]

> A fanatical religious order that seeks to purify the world through fire and holy wrath. Zealots and flagellants form the bulk of their forces, supported by armored Templar Knights, Battle Clerics, and the dreaded Purifiers. Mid-to-late game faction.

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
| ![[_assets/Units/Flagellant.webp\|40]] | [[Flagellant]] | 1 | 45 | 0 | 55 | 25 | 0 | 8-14 | Aggressive | 1 | 9 |
| ![[_assets/Units/Zealot.webp\|40]] | [[Zealot (Enemy)\|Zealot]] | 1 | 55 | 2 | 52 | 35 | 0 | 8-14 | Aggressive | 2 | 12 |
| ![[_assets/Units/BattleCleric.webp\|40]] | [[Battle Cleric (Enemy)\|Battle Cleric]] | 2 | 92 | 9 | 72 | 58 | 0 | 14-22 | Defensive | 4 | 24 |
| ![[_assets/Units/WitchFinder.webp\|40]] | [[Witch Finder]] | 2 | 73 | 7 | 55 | 47 | 79 | 16-26 (ranged) | Ranged | 3 | 20 |
| ![[_assets/Units/Purifier.webp\|40]] | [[Purifier]] | 3 | 79 | 8 | 57 | 48 | 89 | 10-19 (ranged) | Ranged | 5 | 32 |
| ![[_assets/Units/TemplarKnight.webp\|40]] | [[Templar Knight]] | 3 | 123 | 14 | 92 | 75 | 0 | 20-31 | Aggressive | 6 | 38 |
| ![[_assets/Units/Paladin.webp\|40]] | [[Paladin (Enemy)\|Paladin]] | 4 | 156 | 17 | 104 | 89 | 0 | 34-55 | Aggressive | 9 | 55 |
| ![[_assets/Units/GrandInquisitor.webp\|40]] | [[Grand Inquisitor]] | 5 | 179 | 19 | 114 | 96 | 0 | 45-72 | Aggressive | 14 | 75 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Forest — Mid Tier]] | Random | 4+ | Forest | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Ruins — Mid Tier]] | Random | 5+ | Ruins | 1 |
| [[Forest — Late Tier]] | Random | 7+ | Forest | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Referenced by

- **Slayer properties:** [[Inquisition Bane]]

*Generated from `enemies/inquisition.json`. Edits will be overwritten — put your own notes in Notes/.*
