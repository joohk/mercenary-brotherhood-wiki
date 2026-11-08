---
id: villain_iron_tyrant
type: villain
category: Arch-Villains
aliases:
  - villain_iron_tyrant
tags:
  - enemy/tier-5
  - faction/aurelian_legions
  - type/villain
source: villains/arch_villains.json
armor: 16
faction: Saurian Legions
gold: 180
hp: 280
level_min: 7
personality: authoritarian
size: normal
stance: defensive
threat_cost: 28
tier: 5
title: Imperator Ssethek
xp: 220
---

An arch-villain of the [[Saurian Legions]] — *Imperator Ssethek*. Awakens from company level 7; 280 HP, 16 armor, worth 220 XP and 180 gold.

![[_assets/Units/IronTyrant.webp|200]]

> A renegade saurian oldblood who carved out his own empire with discipline and brutality. His legions march in perfect formation even when the scales have rotted from their bones.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 280 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 110 |
| [[Stats#Initiative\|Initiative]] | 48 |
| [[Stats#Melee Attack\|Melee Attack]] | 78 |
| [[Stats#Melee Defense\|Melee Defense]] | 72 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 0 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 65 |
| [[Stats#Armor\|Armor]] | 16 |
| [[Stats#Willpower\|Willpower]] | 98 |
| [[Stats#Vision\|Vision]] | 6 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 18 |
| [[Stats#Damage Min\|Damage]] | 16-26 |

## Combat

|  | Value |
|---|---|
| Title | Imperator Ssethek |
| [[Glossary#Numbers used on this wiki\|Tier]] | 5 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 28 |
| XP | 220 |
| Gold | 180 |
| Size | Normal |
| Stance | Defensive — holds its ground and protects its allies |
| Personality | Authoritarian |
| AI | [[How Enemies Behave#Elite\|Elite]] (assignment to arch-villains is not stated in the data; no faction uses this profile) |
| Appears from company level | 7 |

## Phases

The fight starts in phase 1. When the villain's HP drops below the threshold, the next phase begins at once.

### Phase 2 — below 40% HP

- **Stats:** +10 [[Stats#Armor|Armor]], +20 [[Stats#Melee Defense|Melee Defense]], +20 [[Stats#Willpower|Willpower]], +8 to +12 [[Stats#Damage Min|Damage]]
- **Gains abilities:** [[Hold the Line (Ability)|Hold the Line]], [[War Horn]]
- **Heals** 10% of max HP
- **Says:** *"You fight well. But discipline always defeats passion."*

## Abilities

- [[Shield Bash (Ability)|Shield Bash]]
- [[Bull Rush (Ability)|Bull Rush]]
- [[Battle Cry (Ability)|Battle Cry]]
- [[Testudo]]

## Passives

- [[Iron Discipline (Enemy Passive)|Iron Discipline]] — +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns.
- [[Formation Bonus]] — +6 melee defense when adjacent to 2 or more allies.
- [[Unbowed]] — Arch-villains shrug off stuns, roots and knockback 75% of the time.

## Escort

Travels and fights with:

- 2× [[Saurian Legionary]]
- 1× [[Saurian Temple Guard]]
- 1× [[Saurian Oldblood]]

## Relic drops

Defeating this villain drops a unique relic:

- [[Ironblood Cuirass]]
- [[The Unbreakable Ward]]

## On the world map

|  | Value |
|---|---|
| Roam radius | 25 |
| Ambush chance | 8% |
| Settlement corruption chance | 8% |

Units (hexes, per day) are not stated in the data.

## On death

Killing the villain shifts faction power:

| Faction | Power |
|---|---|
| [[Saurian Legions]] | -25 |
| [[Deserters]] | +10 |
| [[Rival Mercenaries]] | +10 |

## Dialogue

> [!quote]- Dialogue
> **On first meeting:** *"Another band of sellswords. You will kneel, or you will break."*
>
> **Entering phase 2:** *"You fight well. But discipline always defeats passion."*
>
> **When defeated:** *"Order prevails. As it always does."*
>
> **When your company loses:** *"Retreat is not defeat. Remember that when you return."*

*Generated from `villains/arch_villains.json`. Edits will be overwritten — put your own notes in Notes/.*
