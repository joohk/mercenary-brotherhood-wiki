---
id: ratkin_swarm
type: faction
category: Factions
aliases:
  - ratkin_swarm
tags:
  - ai/swarm
  - faction/ratkin_swarm
  - type/faction
source: enemies/ratkin_swarm.json
ai_profile: Swarm
level_max: 2
level_min: 1
tier_max: 2
tier_min: 0
units: 7
---

An enemy faction that appears at company levels 1-2 and fights as [[How Enemies Behave#Swarm|Swarm]] (flanks and surrounds): 7 unit types, tiers 0-2.

![[_assets/Units/RatkinChieftain.webp|160]]

> Intelligent rat-folk who attack in overwhelming numbers. Individually weak but fast and numerous. Found infesting ruins, dark forests, and swamps. Early-game swarm faction.

## Overview

|  | Value |
|---|---|
| Company level | 1-2 |
| AI profile | [[How Enemies Behave#Swarm\|Swarm]] — flanks and surrounds |
| Faction AI tweaks | Goes after healers and casters 30% |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Ratkin.webp\|40]] | [[Ratkin Scrapper]] | 0 | 28 | 0 | 46 | 25 | 0 | 6-12 | Aggressive | 1 | 6 |
| ![[_assets/Units/RatkinSlinger.webp\|40]] | [[Ratkin Slinger]] | 0 | 22 | 0 | 25 | 20 | 42 | 3-6 (ranged) | Ranged | 1 | 6 |
| ![[_assets/Units/RatkinTunneller.webp\|40]] | [[Ratkin Tunneler]] | 0 | 24 | 0 | 45 | 22 | 0 | 5-10 | Aggressive | 1 | 7 |
| ![[_assets/Units/RatkinAlchemist.webp\|40]] | [[Ratkin Alchemist]] | 1 | 30 | 0 | 28 | 22 | 52 | 5-9 (ranged) | Ranged | 2 | 12 |
| ![[_assets/Units/RatkinBrute.webp\|40]] | [[Ratkin Brute]] | 1 | 50 | 2 | 48 | 32 | 0 | 6-10 | Aggressive | 2 | 10 |
| ![[_assets/Units/RatkinPlagueShaman.webp\|40]] | [[Ratkin Plague Shaman]] | 1 | 28 | 0 | 25 | 20 | 0 | 8-14 (ranged) | Ranged | 2 | 14 |
| ![[_assets/Units/RatkinChieftain.webp\|40]] | [[Ratkin Chieftain]] | 2 | 86 | 8 | 73 | 53 | 0 | 14-22 | Aggressive | 4 | 25 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Forest — Encounter]] | Random | 1+ | Forest | 2 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 2 |
| [[Shallow Cavern Encounter]] | Random | 1+ | Cavern | 2 |
| [[Shallow Mushroom Forest Encounter]] | Random | 1+ | Mushroom Forest | 1 |
| [[Shallow Stalagmite Field Encounter]] | Random | 1+ | Stalagmite Field | 1 |
| [[Shallow Tunnel Encounter]] | Random | 1+ | Tunnel | 1 |
| [[Swamp — Encounter]] | Random | 1+ | Swamp | 1 |
| [[Ruins — Early]] | Random | 2-4 | Ruins | 2 |
| [[Shallow Fungal Bog Encounter]] | Random | 2+ | Fungal Bog | 1 |
| [[Mid-depth Cavern Encounter]] | Random | 4+ | Cavern | 1 |

## Referenced by

- **Bases held:** [[Ratkin Warren]]
- **Dungeons held:** [[Fungal Grotto]], [[Ratkin Nest]]
- **Possible enemy in chains:** [[Hunt the Vendetta]], [[The Crime Lord]]
- **Slayer properties:** [[Ratkin Swarm Bane]]

*Generated from `enemies/ratkin_swarm.json`. Edits will be overwritten — put your own notes in Notes/.*
