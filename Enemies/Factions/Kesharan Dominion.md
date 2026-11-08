---
id: kesharan_dominion
type: faction
category: Factions
aliases:
  - kesharan_dominion
tags:
  - ai/disciplined
  - faction/kesharan_dominion
  - type/faction
source: enemies/kesharan_dominion.json
ai_profile: Disciplined
level_min: 5
tier_max: 4
tier_min: 1
units: 8
---

An enemy faction that appears from company level 5 and fights as [[How Enemies Behave#Disciplined|Disciplined]] (holds formation, coordinated): 8 unit types, tiers 1-4.

![[_assets/Units/Satrap.webp|160]]

> A vast slave empire modelled after ancient Persia. Relies on masses of expendable slaves screened by elite Immortal guards. Enslaved giants provide devastating heavy support. Mid-to-late game faction.

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
| ![[_assets/Units/SlaveArcher.webp\|40]] | [[Slave Archer]] | 1 | 40 | 0 | 28 | 22 | 48 | 7-12 (ranged) | Ranged | 1 | 8 |
| ![[_assets/Units/SlaveConscript.webp\|40]] | [[Slave Conscript]] | 1 | 50 | 1 | 42 | 25 | 0 | 7-13 | Aggressive | 1 | 8 |
| ![[_assets/Units/KesharanGuard.webp\|40]] | [[Kesharan Guard]] | 2 | 106 | 11 | 79 | 64 | 0 | 14-22 | Aggressive | 4 | 25 |
| ![[_assets/Units/SlaveDriver.webp\|40]] | [[Slave Driver]] | 2 | 92 | 8 | 73 | 55 | 0 | 15-22 | Aggressive | 3 | 20 |
| ![[_assets/Units/EnslavedGiant.webp\|40]] | [[Enslaved Giant]] | 3 | 187 | 12 | 80 | 52 | 0 | 25-39 | Aggressive | 8 | 45 |
| ![[_assets/Units/KesharanHorseArcher.webp\|40]] | [[Kesharan Horse Archer]] | 3 | 94 | 9 | 69 | 57 | 92 | 13-22 (ranged) | Ranged | 5 | 32 |
| ![[_assets/Units/KesharanImmortal.webp\|40]] | [[Kesharan Immortal]] | 3 | 130 | 15 | 94 | 78 | 0 | 21-32 | Aggressive | 7 | 40 |
| ![[_assets/Units/Satrap.webp\|40]] | [[Satrap]] | 4 | 164 | 18 | 107 | 89 | 0 | 34-55 | Aggressive | 10 | 58 |

*Dmg is the unit's base damage plus its main weapon's damage ("ranged" when that weapon is a ranged one); see each unit's page for the breakdown.*

## Encounter tables

| Table | Trigger | Company level | Terrain | Groups |
|---|---|---|---|---|
| [[Dungeon — Boss Encounter]] | Static | 1+ | Dungeon | 1 |
| [[Hills — Mid Tier]] | Random | 5+ | Hills | 1 |
| [[Plains — Mid Tier]] | Random | 5+ | Plains, Road | 1 |
| [[Plains — Late Tier]] | Random | 8+ | Plains, Road | 1 |

## Referenced by

- **Possible enemy in chains:** [[The Marauding Army]], [[The Uprising]]
- **Slayer properties:** [[Kesharan Dominion Bane]]

*Generated from `enemies/kesharan_dominion.json`. Edits will be overwritten — put your own notes in Notes/.*
