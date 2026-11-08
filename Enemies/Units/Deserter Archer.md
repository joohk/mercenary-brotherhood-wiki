---
id: deserter_archer
type: enemy
category: Enemies
aliases:
  - deserter_archer
tags:
  - enemy/tier-2
  - faction/deserters
  - type/enemy
source: enemies/deserters.json
armor: 7
faction: Deserters
gold: 12
hp: 66
stance: ranged
threat_cost: 3
tier: 2
xp: 18
---

A tier-2 enemy of the [[Deserters]] faction — 66 HP, 7 armor, worth 18 XP and 12 gold.

![[_assets/Units/DeserterArcher.webp|160]]

> A former army bowman who kept his weapon when he fled. Still remembers how to use it.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 66 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 77 |
| [[Stats#Initiative\|Initiative]] | 57 |
| [[Stats#Melee Attack\|Melee Attack]] | 55 |
| [[Stats#Melee Defense\|Melee Defense]] | 47 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 75 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 48 |
| [[Stats#Armor\|Armor]] | 7 |
| [[Stats#Willpower\|Willpower]] | 46 |
| [[Stats#Vision\|Vision]] | 6 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 18 |
| [[Stats#Damage Min\|Damage]] | 9-13 |
| Ranged damage with weapon | 10-16 (base 0 + [[Longbow]] 10-16) |

## Combat

|  | Value |
|---|---|
| [[Glossary#Numbers used on this wiki\|Tier]] | 2 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 3 |
| XP | 18 |
| Gold | 12 |
| Variant role | [[Skirmisher (Variant)\|Skirmisher]] (auto-assigned to ranged units) |
| Stance | Ranged — keeps its distance and attacks from range |
| Faction AI | [[How Enemies Behave#Professional\|Professional]] |

> [!info]- Spawn data
> |  | Value |
> |---|---|
> | [[Glossary#Numbers used on this wiki\|Spawn weight]] in the faction pool | 60 |
> | [[Glossary#Numbers used on this wiki\|Potential value]] | 22 |

## Abilities

- [[Flurry (Ability)|Flurry]]

## Passives

- [[Keen Senses]] — +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain).
- [[Crumbling Resolve]] — Begins the battle steady, but each deserter ally that dies within 3 hexes inflicts -8 willpower permanently and forces an immediate morale check. They came for the loot, not the dying.

**Possible bonus passives:** [[Nimble (Enemy Passive)|Nimble]]

## Equipment

- [[Longbow]]
- [[Studded Leather]]
- [[Polished Trinket]]

## Loot

| Item | Chance | Qty |
|---|---|---|
| [[Longbow]] | 18% | 1 |
| [[Studded Leather]] | 12% | 1 |

## Referenced by

- **Appears in encounters:** [[Plains — Late Tier]], [[Plains — Random Encounter]], [[Road — Ambush]], [[The Usurper's Castle (Encounter Table)|The Usurper's Castle]]
- **Reinforces in encounters:** [[Plains Base Garrison — Shallow]], [[Plains — Deserter Camp]], [[Plains — Mid Tier]], [[Plains — Random Encounter]], [[Road — Ambush]]

*Generated from `enemies/deserters.json`. Edits will be overwritten — put your own notes in Notes/.*
