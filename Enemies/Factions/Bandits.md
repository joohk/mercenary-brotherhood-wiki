---
id: bandits
type: faction
category: Factions
aliases:
  - bandits
tags:
  - ai/chaotic
  - faction/bandits
  - type/faction
source: enemies/bandits.json
ai_profile: Undisciplined
level_min: 1
tier_max: 2
tier_min: 1
units: 7
up: "[[Outlaws & Sellswords]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Outlaws & Sellswords]]

An enemy faction that appears from company level 1 and fights as [[How Enemies Behave#Undisciplined|Undisciplined]] (unpredictable, low coordination): 7 unit types, tiers 1-2.

![[_assets/Units/BanditCaptain.webp|160]]

> The most common early-game enemy faction. A motley crew drawn from the common races: orcs form the muscle up front, elves pick off targets from range, goblins fill the magical/support role, halflings cut purses and throats, and a human captain (or ex-soldier) usually holds the crew together. Each bandit unit is a single race so every tile fits one archetype cleanly.

## Overview

|  | Value |
|---|---|
| Company level | 1+ |
| AI profile | [[How Enemies Behave#Undisciplined\|Undisciplined]] — unpredictable, low coordination |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/BanditCutthroat.webp\|40]] | [[Bandit Cutthroat]] | 1 | 62 | 3 | 72 | 50 | 0 | 13-22 | Aggressive | 2 | 18 |
| ![[_assets/Units/BanditArcher.webp\|40]] | [[Elf Bandit Archer]] | 1 | 48 | 1 | 35 | 36 | 72 | 12-20 (ranged) | Ranged | 2 | 20 |
| ![[_assets/Units/BanditHedgeWitch.webp\|40]] | [[Goblin Bandit Shaman]] | 1 | 36 | 0 | 28 | 30 | 0 | 6-12 | Defensive | 2 | 15 |
| ![[_assets/Units/HalflingCutpurse.webp\|40]] | [[Halfling Cutpurse]] | 1 | 44 | 1 | 55 | 56 | 48 | 8-15 | Aggressive | 2 | 15 |
| ![[_assets/Units/BanditRaider.webp\|40]] | [[Orc Bandit Raider]] | 1 | 88 | 6 | 66 | 40 | 0 | 11-19 | Aggressive | 4 | 16 |
| ![[_assets/Units/BanditRaider.webp\|40]] | [[Orc Thug]] | 1 | 98 | 6 | 61 | 35 | 0 | 12-21 | Aggressive | 4 | 14 |
| ![[_assets/Units/BanditCaptain.webp\|40]] | [[Bandit Captain]] | 2 | 125 | 11 | 82 | 64 | 0 | 15-25 | Aggressive | 4 | 45 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Forest — Encounter]] | Random | 1+ | Forest | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 6 |
| [[Ruins — Early]] | Random | 2-4 | Ruins | 1 |
| [[Plains Base Garrison — Shallow]] | Static | 3-4 | Plains | 1 |
| [[Plains — Bandit Camp]] | Static | 3-5 | Plains | 1 |
| [[Road — Ambush]] | Random | 3+ | Road | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 2 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Harrow, Grimjaw, Blackthorn, Vex, Sallow, Cutler, Dross, Fenn, Rask, Gorge, Mace, Scab, Blight, Tallow, Crag. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Bandit Camp]], [[Bandit Fortress]], [[Roadside Ambush Point]]
- **Dungeons held:** [[Bandit Cellar]], [[Iron Keep]], [[Ruined Watchtower]]
- **Points of interest:** [[Bandit Toll]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Crime Lord]], [[The Marauding Army]], [[The Uprising]]
- **Power shifts when these villains die:** [[The Shadow Weaver]], [[Warlord Ash]]
- **Seeded vendetta in:** [[Veteran Band]]
- **Slayer properties:** [[Bandits Bane]]

*Generated from `enemies/bandits.json`. Edits will be overwritten — put your own notes in Notes/.*
