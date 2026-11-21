---
id: rogue_battlemage
type: enemy
category: Enemies
aliases:
  - rogue_battlemage
tags:
  - enemy/tier-2
  - faction/deserters
  - type/enemy
source: enemies/deserters.json
armor: 3
faction: Deserters
gold: 16
hp: 66
stance: ranged
threat_cost: 3
tier: 2
up: "[[Deserters]]"
xp: 22
---

[[Home]] › [[Bestiary]] › [[Enemy Types]] › [[Outlaws & Sellswords]] › [[Deserters]]

A tier-2 enemy of the [[Deserters]] faction — 66 HP, 3 armor, worth 22 XP and 16 gold.

![[_assets/Units/RogueBattleMage.webp|160]]

> A former army spellcaster who deserted alongside the soldiers. Still remembers the incantations drilled into him during training — arcane bolts and protective wards that make this rabble far more dangerous than it should be.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 66 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 77 |
| [[Stats#Initiative\|Initiative]] | 53 |
| [[Stats#Melee Attack\|Melee Attack]] | 44 |
| [[Stats#Melee Defense\|Melee Defense]] | 40 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 0 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 48 |
| [[Stats#Armor\|Armor]] | 3 |
| [[Stats#Willpower\|Willpower]] | 64 |
| [[Stats#Vision\|Vision]] | 5 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 15 |
| [[Stats#Damage Min\|Damage]] | 1-2 |
| Damage with weapon | 13-23 (base 1-2 + [[Hex Staff]] 12-21) |

## Combat

|  | Value |
|---|---|
| [[Glossary#Numbers used on this wiki\|Tier]] | 2 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 3 |
| XP | 22 |
| Gold | 16 |
| Variant role | [[Skirmisher (Variant)\|Skirmisher]] (auto-assigned to ranged units) |
| Stance | Ranged — keeps its distance and attacks from range |
| Damage type | Blunt |
| Faction AI | [[How Enemies Behave#Professional\|Professional]] |
| Combat sheet | [[Deserters Combat Sheet\|all Deserters units and abilities]] |
| Max share of an encounter | 20% |

> [!info]- Spawn data
> |  | Value |
> |---|---|
> | [[Glossary#Numbers used on this wiki\|Spawn weight]] in the faction pool | 25 |
> | [[Glossary#Numbers used on this wiki\|Potential value]] | 28 |

## Resistances

| Damage type | Natural | From gear | Total |
|---|---|---|---|
| [[Stats#Slash Resist\|Slash]] | — | [[Acolyte Robes]] +2 | +2% |
| [[Stats#Pierce Resist\|Pierce]] | — | [[Acolyte Robes]] +2 | +2% |
| [[Stats#Blunt Resist\|Blunt]] | — | [[Acolyte Robes]] +2 | +2% |

*Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%.*

## Abilities

- [[Magic Missile]]
- [[Arcane Shield (Ability)|Arcane Shield]]

## Passives

- [[Disciplined (Enemy Passive)|Disciplined]] — +5 melee defense, +5 willpower from professional training.
- [[Crumbling Resolve]] — Begins the battle steady, but each deserter ally that dies within 3 hexes inflicts -8 willpower permanently and forces an immediate morale check. They came for the loot, not the dying.

**Possible bonus passives:** [[Desperate]]

## Equipment

- [[Hex Staff]]
- [[Focus Wand]]
- [[Acolyte Robes]]
- [[Bone Amulet]]

## Loot

| Item | Chance | Qty |
|---|---|---|
| [[Leather Armor]] | 15% | 1 |

## Referenced by

- **Appears in encounters:** [[Plains — Random Encounter]], [[The Usurper's Castle (Encounter Table)|The Usurper's Castle]]
- **Reinforces in encounters:** [[Plains Base Garrison — Shallow]], [[Plains — Deserter Camp]], [[Plains — Mid Tier]], [[Plains — Random Encounter]], [[Road — Ambush]]

*Generated from `enemies/deserters.json`. Edits will be overwritten — put your own notes in Notes/.*
