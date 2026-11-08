---
id: bandit_archer
type: enemy
category: Enemies
aliases:
  - bandit_archer
tags:
  - enemy/tier-1
  - faction/bandits
  - type/enemy
source: enemies/bandits.json
armor: 1
faction: Bandits
gold: 13
hp: 48
race: Elf
stance: ranged
threat_cost: 2
tier: 1
xp: 20
---

A tier-1 Elf enemy of the [[Bandits]] faction — 48 HP, 1 armor, worth 20 XP and 13 gold.

![[_assets/Units/BanditArcher.webp|160]]

> A cast-out elf with a worn shortbow and a raptor's patience. Keeps to cover, drops arrows into throats across the field, and vanishes before the blade-bandits finish their charge.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 48 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 65 |
| [[Stats#Initiative\|Initiative]] | 62 |
| [[Stats#Melee Attack\|Melee Attack]] | 35 |
| [[Stats#Melee Defense\|Melee Defense]] | 36 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 72 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 50 |
| [[Stats#Armor\|Armor]] | 1 |
| [[Stats#Willpower\|Willpower]] | 42 |
| [[Stats#Vision\|Vision]] | 8 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 15 |
| [[Stats#Damage Min\|Damage]] | 5-8 |
| Ranged damage with weapon | 12-20 (base 5-8 + [[Shortbow]] 7-12) |

## Combat

|  | Value |
|---|---|
| [[Glossary#Numbers used on this wiki\|Tier]] | 1 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 2 |
| XP | 20 |
| Gold | 13 |
| Race | [[Elf]] |
| Variant role | [[Skirmisher (Variant)\|Skirmisher]] (auto-assigned to ranged units) |
| Stance | Ranged — keeps its distance and attacks from range |
| Faction AI | [[How Enemies Behave#Undisciplined\|Undisciplined]] |

> [!info]- Spawn data
> |  | Value |
> |---|---|
> | [[Glossary#Numbers used on this wiki\|Spawn weight]] in the faction pool | 45 |
> | [[Glossary#Numbers used on this wiki\|Potential value]] | 27 |

## Passives

- [[Keen Senses]] — +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain).
- [[Steady Aim (Enemy Passive)|Steady Aim]] — +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement!

**Possible bonus passives:** [[Nimble (Enemy Passive)|Nimble]], [[Evasion]]

## Equipment

- [[Shortbow]]
- [[Leather Armor]]

## Loot

| Item | Chance | Qty |
|---|---|---|
| [[Shortbow]] | 35% | 1 |
| [[Leather Armor]] | 20% | 1 |

## Referenced by

- **Appears in encounters:** [[Plains — Mid Tier]], [[Plains — Random Encounter]], [[Road — Ambush]]
- **Reinforces in encounters:** [[Plains Base Garrison — Shallow]], [[Plains — Bandit Camp]], [[Plains — Random Encounter]], [[Road — Ambush]]

*Generated from `enemies/bandits.json`. Edits will be overwritten — put your own notes in Notes/.*
