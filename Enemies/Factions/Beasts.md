---
id: beasts
type: faction
category: Factions
aliases:
  - beasts
tags:
  - ai/swarm
  - faction/beasts
  - type/faction
source: enemies/beasts.json
ai_profile: Swarm
animal: true
level_min: 1
tier_max: 4
tier_min: 1
units: 7
up: "[[Wild Beasts]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Wild Beasts]]

An enemy faction that appears from company level 1 and fights as [[How Enemies Behave#Swarm|Swarm]] (flanks and surrounds): 7 unit types, tiers 1-4.

![[_assets/Units/Manticore.webp|160]]

> Dangerous wildlife beyond common wolves. No loot (animals), but high XP. Found in forests, hills, mountains, and swamps.

## Overview

|  | Value |
|---|---|
| Company level | 1+ |
| AI profile | [[How Enemies Behave#Swarm\|Swarm]] — flanks and surrounds |
| Faction AI tweaks | Goes after healers and casters 20% |
| Animals | Yes |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/GiantSpider.webp\|40]] | [[Spider Broodling]] | 1 | 22 | 0 | 55 | 40 | 0 | 5-9 | Aggressive | 1 | 5 |
| ![[_assets/Units/Boar.webp\|40]] | [[Wild Boar]] | 1 | 45 | 2 | 50 | 30 | 0 | 7-12 | Aggressive | 2 | 10 |
| ![[_assets/Units/Bear.webp\|40]] | [[Bear]] | 2 | 132 | 8 | 75 | 53 | 0 | 16-25 | Aggressive | 5 | 24 |
| ![[_assets/Units/GiantSpider.webp\|40]] | [[Giant Spider (Enemy, Beasts)\|Giant Spider]] | 2 | 66 | 6 | 72 | 47 | 0 | 12-20 | Aggressive | 3 | 18 |
| ![[_assets/Units/CaveTroll.webp\|40]] | [[Cave Troll]] | 3 | 201 | 14 | 83 | 52 | 0 | 30-46 | Aggressive | 8 | 42 |
| ![[_assets/Units/Wyvern.webp\|40]] | [[Wyvern]] | 3 | 123 | 10 | 89 | 63 | 0 | 18-30 | Aggressive | 7 | 38 |
| ![[_assets/Units/Manticore.webp\|40]] | [[Manticore]] | 4 | 203 | 13 | 102 | 74 | 88 | 34-53 | Aggressive | 10 | 55 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Boar Nesting Ground (Encounter Table)\|Boar Nesting Ground]] | Static | 1+ | Forest, Plains, Hills | 1 |
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Forest — Encounter]] | Random | 1+ | Forest | 1 |
| [[Hills — Encounter]] | Random | 1+ | Hills | 1 |
| [[Mountain — Encounter]] | Random | 1+ | Mountain | 2 |
| [[Brood Hollow]] | Static | 2+ | Forest | 1 |
| [[Bear Den]] | Static | 3+ | Forest | 1 |
| [[Forest — Mid Tier]] | Random | 4+ | Forest | 2 |
| [[Giant Spider Nest (Encounter Table)\|Giant Spider Nest]] | Static | 5+ | Forest | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Mountain — Mid Tier]] | Random | 6+ | Mountain | 2 |
| [[Troll Cave (Encounter Table)\|Troll Cave]] | Static | 6+ | Mountain, Hills | 1 |
| [[Wyvern Roost (Encounter Table)\|Wyvern Roost]] | Static | 6+ | Mountain | 1 |
| [[Forest — Late Tier]] | Random | 7+ | Forest | 2 |
| [[Dragon's Hoard]] | Static | 9+ | Mountain | 1 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Goreclaw, Thornback, Venomfang, Ironskin, Darkhorn, Cindermaw, Stonehide, Blight, Dreadfang, Rottusk, Ashscale, Bonecrusher, Gorge, Mistveil, Razorwing. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Boar Nesting Ground (Enemy Base)|Boar Nesting Ground]], [[Boar Warren]], [[Cave Beast Den]], [[Giant Spider Nest (Enemy Base)|Giant Spider Nest]], [[Troll Cave (Enemy Base)|Troll Cave]], [[Wyvern Roost (Enemy Base)|Wyvern Roost]]
- **Points of interest:** [[Poacher's Cache]]
- **Quest target of:** [[Slay the Wyvern]]
- **Slayer properties:** [[Beasts Bane]]

*Generated from `enemies/beasts.json`. Edits will be overwritten — put your own notes in Notes/.*
