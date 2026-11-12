---
id: barbarians
type: faction
category: Factions
aliases:
  - barbarians
tags:
  - ai/chaotic
  - faction/barbarians
  - type/faction
source: enemies/barbarians.json
ai_profile: Undisciplined
level_min: 4
tier_max: 4
tier_min: 1
units: 7
up: "[[Wild Peoples]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Wild Peoples]]

An enemy faction that appears from company level 4 and fights as [[How Enemies Behave#Undisciplined|Undisciplined]] (unpredictable, low coordination): 7 unit types, tiers 1-4.

![[_assets/Units/TribalWarchief.webp|160]]

> Savage forest-elf raiders who burn with the same fury as the old human barbarians they replaced. Painted in woad, crowned in bone, their warbands descend on travellers from deep glades. Similar aggression/rage identity with elven initiative and vision. Favour aggression over armour. Found in forests, hills, and wild frontier.

## Overview

|  | Value |
|---|---|
| Company level | 4+ |
| AI profile | [[How Enemies Behave#Undisciplined\|Undisciplined]] — unpredictable, low coordination |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/TribalRaider.webp\|40]] | [[Wilding Raider]] | 1 | 62 | 1 | 54 | 34 | 0 | 10-16 | Aggressive | 3 | 12 |
| ![[_assets/Units/ShieldMaiden.webp\|40]] | [[Thorn Warden]] | 2 | 88 | 9 | 75 | 66 | 0 | 14-22 | Defensive | 3 | 20 |
| ![[_assets/Units/Berserker.webp\|40]] | [[Wilding Berserker]] | 2 | 101 | 3 | 81 | 42 | 0 | 18-30 | Aggressive | 4 | 24 |
| ![[_assets/Units/TribalHunter.webp\|40]] | [[Wilding Huntsman]] | 2 | 69 | 6 | 55 | 44 | 79 | 10-16 (ranged) | Ranged | 3 | 18 |
| ![[_assets/Units/TribalShaman.webp\|40]] | [[Thornwoad Shaman]] | 3 | 76 | 7 | 54 | 48 | 90 | 9-17 (ranged) | Ranged | 5 | 32 |
| ![[_assets/Units/BerserkerChampion.webp\|40]] | [[Wilding Bloodsworn]] | 3 | 131 | 8 | 94 | 55 | 0 | 28-44 | Aggressive | 7 | 40 |
| ![[_assets/Units/TribalWarchief.webp\|40]] | [[Wilding Warchief]] | 4 | 157 | 14 | 107 | 80 | 0 | 34-55 | Aggressive | 9 | 52 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Hills — Encounter]] | Random | 1+ | Hills | 2 |
| [[Mountain — Encounter]] | Random | 1+ | Mountain | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 1 |
| [[Hills Base Garrison — Shallow]] | Static | 3-4 | Hills | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Mountain — Mid Tier]] | Random | 6+ | Mountain | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Vendetta names

Vendettas that rise from this faction draw their first name from: Ulfgar, Thrain, Brynhild, Kael, Gunvor, Skarr, Thyra, Volgar, Draga, Helvir, Ragn, Sven, Torv, Yrsa, Bjorn. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Barbarian Chieftain's Hold]], [[Barbarian Outpost]], [[Barbarian War Camp]]
- **Dungeons held:** [[The Blood Pit]]
- **Possible enemy in chains:** [[Faction Ambush Survival]], [[The Marauding Army]], [[The Uprising]]
- **Power shifts when these villains die:** [[Gorthak the Beast King]]
- **Slayer properties:** [[Barbarians Bane]]

*Generated from `enemies/barbarians.json`. Edits will be overwritten — put your own notes in Notes/.*
