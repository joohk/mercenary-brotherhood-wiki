---
id: wolves
type: faction
category: Factions
aliases:
  - Wolf Pack
  - wolves
tags:
  - ai/swarm
  - faction/wolves
  - type/faction
source: enemies/wolves.json
ai_profile: Swarm
animal: true
level_max: 4
level_min: 1
tier_max: 3
tier_min: 1
units: 3
up: "[[Wild Beasts]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Wild Beasts]]

An enemy faction that appears at company levels 1-4 and fights as [[How Enemies Behave#Swarm|Swarm]] (flanks and surrounds): 3 unit types, tiers 1-3.

![[_assets/Units/AlphaWolf.webp|160]]

> Fast, low armor, pack hunters found in forests

## Overview

|  | Value |
|---|---|
| Company level | 1-4 |
| AI profile | [[How Enemies Behave#Swarm\|Swarm]] — flanks and surrounds |
| Animals | Yes |
| Vendetta names | Own name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Wolf.webp\|40]] | [[Wolf]] | 1 | 30 | 0 | 48 | 30 | 0 | 6-10 | Aggressive | 2 | 8 |
| ![[_assets/Units/DireWolf.webp\|40]] | [[Dire Wolf]] | 2 | 86 | 6 | 75 | 47 | 0 | 14-24 | Aggressive | 4 | 18 |
| ![[_assets/Units/AlphaWolf.webp\|40]] | [[Alpha Wolf]] | 3 | 130 | 8 | 89 | 57 | 0 | 21-32 | Aggressive | 6 | 35 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Forest — Encounter]] | Random | 1+ | Forest | 2 |
| [[Forest — Mid Tier]] | Random | 4+ | Forest | 1 |

Its units also join other factions' groups in: [[Forest — Late Tier]], [[Hills — Encounter]], [[Hills — Mid Tier]], [[Plains — Late Tier]], [[Plains — Random Encounter]].

## Vendetta names

Vendettas that rise from this faction draw their first name from: Greymane, Shadowfang, Ironpelt, Stormhowl, Bloodmaw, Nightstalk, Frostbite, Ashclaw, Bonegnaw, Duskrunner, Razorfang, Thornpelt, Dirge, Emberclaw, Windsnap. See [[Vendetta]].

## Referenced by

- **Bases held:** [[Wolf Den]]
- **Slayer properties:** [[Wolves Bane]]

*Generated from `enemies/wolves.json`. Edits will be overwritten — put your own notes in Notes/.*
