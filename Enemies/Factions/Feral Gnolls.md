---
id: feral_outcasts
type: faction
category: Factions
aliases:
  - feral_outcasts
tags:
  - ai/chaotic
  - faction/feral_outcasts
  - type/faction
source: enemies/feral_outcasts.json
ai_profile: Undisciplined
level_max: 3
level_min: 1
tier_max: 2
tier_min: 0
units: 8
up: "[[Wild Peoples]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Wild Peoples]]

An enemy faction that appears at company levels 1-3 and fights as [[How Enemies Behave#Undisciplined|Undisciplined]] (unpredictable, low coordination): 8 unit types, tiers 0-2.

![[_assets/Units/FeralAlpha.webp|160]]

> Cannibalistic hyena-folk pack hunters who roam the wilderness, tearing apart anything that strays too far from civilization. Found in wilderness areas. Early-game threat slightly tougher than rabble.

## Overview

|  | Value |
|---|---|
| Company level | 1-3 |
| AI profile | [[How Enemies Behave#Undisciplined\|Undisciplined]] — unpredictable, low coordination |
| Vendetta names | Default name pool |

Encounter tables have their own level gates and can field this faction outside its company-level window.

## Roster

|  | Unit | Tier | HP | Armor | MAtk | MDef | RAtk | Dmg | Stance | Threat | XP |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/FeralHurler.webp\|40]] | [[Gnoll Hurler]] | 0 | 35 | 0 | 30 | 22 | 40 | 4-7 (ranged) | Ranged | 1 | 6 |
| ![[_assets/Units/FeralSavage.webp\|40]] | [[Gnoll Savage]] | 0 | 45 | 0 | 48 | 28 | 0 | 6-11 | Aggressive | 1 | 7 |
| ![[_assets/Units/FeralWhelp.webp\|40]] | [[Gnoll Whelp]] | 0 | 22 | 0 | 40 | 28 | 0 | 3-5 | Aggressive | 1 | 5 |
| ![[_assets/Units/FeralBoneRender.webp\|40]] | [[Gnoll Bone-Render]] | 1 | 50 | 1 | 52 | 30 | 0 | 7-12 | Aggressive | 2 | 13 |
| ![[_assets/Units/FeralBrute.webp\|40]] | [[Gnoll Brute]] | 1 | 70 | 2 | 48 | 30 | 0 | 8-14 | Aggressive | 2 | 14 |
| ![[_assets/Units/FeralHexTouched.webp\|40]] | [[Gnoll Hex-Touched]] | 1 | 35 | 0 | 35 | 24 | 0 | 5-9 | Ranged | 2 | 14 |
| ![[_assets/Units/FeralStalker.webp\|40]] | [[Gnoll Stalker]] | 1 | 40 | 1 | 50 | 35 | 0 | 6-11 | Aggressive | 2 | 12 |
| ![[_assets/Units/FeralAlpha.webp\|40]] | [[Gnoll Alpha]] | 2 | 106 | 7 | 75 | 55 | 0 | 13-20 | Aggressive | 4 | 28 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Forest — Encounter]] | Random | 1+ | Forest | 2 |
| [[Hills — Encounter]] | Random | 1+ | Hills | 1 |
| [[Plains — Random Encounter]] | Random | 1+ | Plains, Road | 2 |

## Referenced by

- **Power shifts when these villains die:** [[Gorthak the Beast King]]
- **Slayer properties:** [[Feral Outcasts Bane]]

*Generated from `enemies/feral_outcasts.json`. Edits will be overwritten — put your own notes in Notes/.*
