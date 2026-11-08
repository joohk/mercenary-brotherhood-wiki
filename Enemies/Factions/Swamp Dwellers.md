---
id: swamp_dwellers
type: faction
category: Factions
aliases:
  - swamp_dwellers
tags:
  - ai/cunning
  - faction/swamp_dwellers
  - type/faction
source: enemies/swamp_dwellers.json
ai_profile: Cunning
level_min: 3
tier_max: 4
tier_min: 1
units: 5
---

An enemy faction that appears from company level 3 and fights as [[How Enemies Behave#Cunning|Cunning]] (intelligent and devious): 5 unit types, tiers 1-4.

![[_assets/Units/SwampHorror.webp|160]]

> Creatures and outcasts lurking in bogs and marshes. Poisonous, durable, and hard to pin down. Found in swamp terrain.

## Overview

|  | Value |
|---|---|
| Company level | 3+ |
| AI profile | [[How Enemies Behave#Cunning\|Cunning]] — intelligent and devious |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/BogLurker.webp\|40]] | [[Bog Lurker]] | 1 | 50 | 2 | 50 | 35 | 0 | 7-11 | Aggressive | 2 | 10 |
| ![[_assets/Units/MarshCrawler.webp\|40]] | [[Marsh Crawler]] | 2 | 99 | 10 | 72 | 55 | 0 | 13-21 | Aggressive | 4 | 20 |
| ![[_assets/Units/SwampWitch.webp\|40]] | [[Swamp Witch]] | 2 | 59 | 4 | 44 | 36 | 75 | 8-14 (ranged) | Ranged | 4 | 22 |
| ![[_assets/Units/BogTroll.webp\|40]] | [[Bog Troll]] | 3 | 187 | 12 | 80 | 55 | 0 | 28-43 | Aggressive | 8 | 40 |
| ![[_assets/Units/SwampHorror.webp\|40]] | [[Swamp Horror]] | 4 | 218 | 14 | 100 | 68 | 0 | 36-55 | Aggressive | 10 | 55 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Swamp — Encounter]] | Random | 1+ | Swamp | 2 |
| [[Shallow Fungal Bog Encounter]] | Random | 2+ | Fungal Bog | 1 |
| [[Swamp Base Garrison — Shallow]] | Static | 3-4 | Swamp | 1 |
| [[Mid-depth Fungal Bog Encounter]] | Random | 5+ | Fungal Bog | 1 |
| [[Swamp — Mid Tier]] | Random | 5+ | Swamp | 3 |
| [[Swamp — Late Tier]] | Random | 8+ | Swamp | 2 |

## Referenced by

- **Bases held:** [[Swamp Horror's Lair]], [[Swamp Witch's Hut]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Swamp Dwellers Bane]]

*Generated from `enemies/swamp_dwellers.json`. Edits will be overwritten — put your own notes in Notes/.*
