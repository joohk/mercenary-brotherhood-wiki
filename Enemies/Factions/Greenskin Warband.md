---
id: greenskins
type: faction
category: Factions
aliases:
  - greenskins
tags:
  - ai/chaotic
  - faction/greenskins
  - type/faction
source: enemies/greenskins.json
ai_profile: Undisciplined
level_min: 1
tier_max: 4
tier_min: 1
units: 10
up: "[[Wild Peoples]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Wild Peoples]]

An enemy faction that appears from company level 1 and fights as [[How Enemies Behave#Undisciplined|Undisciplined]] (unpredictable, low coordination): 10 unit types, tiers 1-4.

![[_assets/Units/EnemyOrcAxeman.webp|160]]

> Organized orc and goblin raiding parties. Goblins are fast and fragile; orcs are slow and brutal. Found across plains, forests, and hills.

## Overview

|  | Value |
|---|---|
| Company level | 1+ |
| AI profile | [[How Enemies Behave#Undisciplined\|Undisciplined]] — unpredictable, low coordination |
| Faction AI tweaks | Coordination 40%, Focus fire 40% |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/EnemyGoblinArcher.webp\|40]] | [[Goblin Poisoner]] | 1 | 28 | 0 | 30 | 25 | 52 | 4-8 (ranged) | Ranged | 2 | 10 |
| ![[_assets/Units/GoblinShaman.webp\|40]] | [[Goblin Shaman (Enemy)\|Goblin Shaman]] | 1 | 30 | 0 | 30 | 22 | 50 | 7-12 (ranged) | Defensive | 2 | 12 |
| ![[_assets/Units/EnemyGoblin.webp\|40]] | [[Goblin Skirmisher]] | 1 | 35 | 1 | 52 | 28 | 0 | 6-12 | Aggressive | 1 | 8 |
| ![[_assets/Units/EnemyOrcAxeman.webp\|40]] | [[Orc Grunt]] | 1 | 75 | 3 | 58 | 38 | 0 | 10-16 | Aggressive | 2 | 14 |
| ![[_assets/Units/GoblinWolfrider.webp\|40]] | [[Goblin Wolfrider]] | 2 | 73 | 5 | 73 | 47 | 0 | 16-24 | Aggressive | 3 | 20 |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Orc Brute]] | 2 | 119 | 10 | 77 | 58 | 0 | 17-28 | Aggressive | 4 | 25 |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Ogre]] | 3 | 207 | 7 | 69 | 41 | 0 | 29-47 | Aggressive | 7 | 45 |
| ![[_assets/Units/EnemyGoblinArcher.webp\|40]] | [[Orc Shaman]] | 3 | 94 | 8 | 60 | 52 | 85 | 9-17 (ranged) | Ranged | 6 | 35 |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Ogre Crusher]] | 4 | 276 | 11 | 79 | 55 | 0 | 43-67 | Aggressive | 10 | 60 |
| ![[_assets/Units/EnemyOrcAxeman.webp\|40]] | [[Orc Warchief]] | 4 | 172 | 16 | 102 | 84 | 0 | 34-55 | Aggressive | 9 | 55 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Arch-villains

- [[Gorthak the Beast King]] — *Warchief of the Broken Tusk*, from company level 6

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Forest — Encounter]] | Random | 1+ | Forest | 1 |
| [[Hills — Encounter]] | Random | 1+ | Hills | 1 |
| [[Mountain — Encounter]] | Random | 1+ | Mountain | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 5 |
| [[Shallow Cavern Encounter]] | Random | 1+ | Cavern | 1 |
| [[Shallow Mushroom Forest Encounter]] | Random | 1+ | Mushroom Forest | 1 |
| [[Shallow Stalagmite Field Encounter]] | Random | 1+ | Stalagmite Field | 1 |
| [[Shallow Tunnel Encounter]] | Random | 1+ | Tunnel | 1 |
| [[Warlord's Citadel (Encounter Table)\|Warlord's Citadel]] | Static | 1+ | Castle | 1 |
| [[Hills Base Garrison — Shallow]] | Static | 3-4 | Hills | 1 |
| [[Forest — Mid Tier]] | Random | 4+ | Forest | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Mountain — Mid Tier]] | Random | 6+ | Mountain | 1 |
| [[Forest — Late Tier]] | Random | 7+ | Forest | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Grokka, Snagtooth, Mugrot, Skullcleava, Borgash, Thrakk, Grubfist, Wortgut, Nazgob, Skulg, Krusha, Dakka, Rotgob, Gnashteef, Bugrot. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Goblin Tunnels (Enemy Base)|Goblin Tunnels]], [[Goblin Tunnels (Underground Enemy Base)|Goblin Tunnels]], [[Greenskin Warren]], [[Orc Stockade]], [[Orc Warchief's Stronghold]], [[Warlord's Citadel (Enemy Base)|Warlord's Citadel]]
- **Dungeons held:** [[Abandoned Mine Shaft]], [[Collapsed Mine]], [[Collapsed Tunnel]], [[Goblin Warrens]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[Hunt the Vendetta]], [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Greenskins Bane]]

*Generated from `enemies/greenskins.json`. Edits will be overwritten — put your own notes in Notes/.*
