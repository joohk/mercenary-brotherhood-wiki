---
id: cultists
type: faction
category: Factions
aliases:
  - cultists
tags:
  - ai/cunning
  - faction/cultists
  - type/faction
source: enemies/cultists.json
ai_profile: Cunning
level_min: 1
tier_max: 4
tier_min: 0
units: 14
---

An enemy faction that appears from company level 1 and fights as [[How Enemies Behave#Cunning|Cunning]] (intelligent and devious): 14 unit types, tiers 0-4.

![[_assets/Units/Cultist.webp|160]]

> Fanatical worshippers of a nameless dark power. Low skill but terrifyingly high resolve. Favor crude bludgeons and cleavers over proper swords. Found in ruins, forests, and swamps.

## Overview

|  | Value |
|---|---|
| Company level | 1+ |
| AI profile | [[How Enemies Behave#Cunning\|Cunning]] — intelligent and devious |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/CultWretch.webp\|40]] | [[Cult Wretch]] | 0 | 25 | 0 | 45 | 22 | 0 | 5-9 | Aggressive | 1 | 5 |
| ![[_assets/Units/VoidHound.webp\|40]] | [[Void Hound]] | 0 | 22 | 0 | 45 | 28 | 0 | 5-9 | Aggressive | 1 | 7 |
| ![[_assets/Units/CultChanter.webp\|40]] | [[Cult Chanter]] | 1 | 32 | 1 | 35 | 28 | 10 | 4-7 | Defensive | 2 | 12 |
| ![[_assets/Units/CultHexer.webp\|40]] | [[Cult Hexer]] | 1 | 30 | 0 | 30 | 24 | 50 | — | Ranged | 2 | 12 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Initiate]] | 1 | 35 | 1 | 52 | 30 | 0 | 5-9 | Aggressive | 1 | 10 |
| ![[_assets/Units/CultTorchbearer.webp\|40]] | [[Cult Torchbearer]] | 1 | 30 | 0 | 32 | 24 | 45 | 3-6 (ranged) | Ranged | 1 | 8 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Acolyte]] | 2 | 53 | 4 | 46 | 40 | 72 | 7-13 (ranged) | Ranged | 3 | 18 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Fanatic]] | 2 | 92 | 6 | 75 | 47 | 0 | 17-28 | Aggressive | 3 | 22 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Neophyte Summoner]] | 2 | 57 | 2 | 40 | 33 | 66 | 9-17 (ranged) | Ranged | 4 | 22 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Abomination]] | 3 | 172 | 13 | 85 | 57 | 0 | 21-33 | Aggressive | 7 | 40 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Assassin]] | 3 | 79 | 9 | 92 | 69 | 0 | 17-26 | Aggressive | 5 | 32 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Cult Summoner]] | 3 | 83 | 5 | 48 | 39 | 83 | 15-25 (ranged) | Ranged | 6 | 36 |
| ![[_assets/Units/Cultist.webp\|40]] | [[Dark Priest]] | 3 | 86 | 8 | 57 | 52 | 89 | 10-18 (ranged) | Ranged | 6 | 38 |
| ![[_assets/Units/Cultist.webp\|40]] | [[High Priest]] | 4 | 125 | 11 | 66 | 60 | 104 | 14-21 (ranged) | Ranged | 9 | 58 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Arch-villains

- [[Plague Bishop Malachar]] — *Voice of the Hollow Eye*, from company level 6

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 6 |
| [[Mid-depth Crystal Cave Encounter]] | Random | 3+ | Crystal Cave | 1 |
| [[Mid-depth Dark Ruins Encounter]] | Random | 3+ | Dark Ruins | 1 |
| [[Road — Ambush]] | Random | 3+ | Road | 1 |
| [[Ruins Base Garrison — Shallow]] | Static | 3-4 | Ruins | 1 |
| [[Forest — Mid Tier]] | Random | 4+ | Forest | 1 |
| [[Ruins — Mid Tier]] | Random | 5+ | Ruins | 1 |
| [[Swamp — Mid Tier]] | Random | 5+ | Swamp | 1 |
| [[Forest — Late Tier]] | Random | 7+ | Forest | 2 |
| [[Ruins — Late Tier]] | Random | 8+ | Ruins | 1 |
| [[Swamp — Late Tier]] | Random | 8+ | Swamp | 1 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Mordecai, Sybaris, Thaelen, Nyx, Ashara, Verek, Lilura, Calyx, Obsidian, Morrigan, Thalor, Sevrin, Lucrezia, Corvid, Umbra. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Cultist Shrine]], [[Dark Temple]]
- **Dungeons held:** [[Crystal Vault]], [[Dark Sanctum]], [[Forsaken Chapel]], [[Sunken Temple]], [[Witch Sanctum]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Crime Lord]]
- **Power shifts when these villains die:** [[The Void Herald]], [[The Witch Queen]]
- **Slayer properties:** [[Cultists Bane]]

*Generated from `enemies/cultists.json`. Edits will be overwritten — put your own notes in Notes/.*
