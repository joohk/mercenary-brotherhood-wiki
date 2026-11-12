---
id: villain_beast_king
type: villain
category: Arch-Villains
aliases:
  - villain_beast_king
tags:
  - enemy/tier-5
  - faction/greenskins
  - type/villain
source: villains/arch_villains.json
armor: 8
faction: Greenskin Warband
gold: 130
hp: 320
level_min: 6
personality: savage
size: large
stance: aggressive
threat_cost: 30
tier: 5
title: Warchief of the Broken Tusk
up: "[[Arch-Villains]]"
xp: 210
---

[[Home]] › [[Bestiary]] › [[Arch-Villains]]

An arch-villain of the [[Greenskin Warband]] — *Warchief of the Broken Tusk*. Awakens from company level 6; 320 HP, 8 armor, worth 210 XP and 130 gold.

![[_assets/Units/BeastKing.webp|200]]

> A massive orc warlord who united the greenskin tribes through sheer brutality. He fights with a bone axe torn from a creature no one can name.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 320 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 100 |
| [[Stats#Initiative\|Initiative]] | 40 |
| [[Stats#Melee Attack\|Melee Attack]] | 85 |
| [[Stats#Melee Defense\|Melee Defense]] | 52 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 0 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 40 |
| [[Stats#Armor\|Armor]] | 8 |
| [[Stats#Willpower\|Willpower]] | 88 |
| [[Stats#Vision\|Vision]] | 5 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 20 |
| [[Stats#Damage Min\|Damage]] | 22-36 |

## Combat

|  | Value |
|---|---|
| Title | Warchief of the Broken Tusk |
| [[Glossary#Numbers used on this wiki\|Tier]] | 5 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 30 |
| XP | 210 |
| Gold | 130 |
| Size | Large |
| Stance | Aggressive — closes in and fights in melee |
| Personality | Savage |
| AI | [[How Enemies Behave#Elite\|Elite]] (assignment to arch-villains is not stated in the data; no faction uses this profile) |
| Appears from company level | 6 |

## Phases

The fight starts in phase 1. When the villain's HP drops below the threshold, the next phase begins at once.

### Phase 2 — below 50% HP

- **Stats:** +16 to +24 [[Stats#Damage Min|Damage]], +20 [[Stats#Melee Attack|Melee Attack]], +12 [[Stats#Initiative|Initiative]]
- **Gains passives:** [[Berserker Rage]]
- **Gains abilities:** [[Frenzy (Ability)|Frenzy]], [[Thunderclap (Ability)|Thunderclap]]
- **Heals** 10% of max HP
- **Says:** *"GORTHAK NOT DIE! GORTHAK STRONGER!"*

## Abilities

- [[Cleave (Ability)|Cleave]]
- [[Bull Rush (Ability)|Bull Rush]]
- [[Skull Leap]]

## Passives

- [[Heavy Blows (Enemy Passive)|Heavy Blows]] — +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets.
- [[Fearless (Enemy Passive)|Fearless]] — Immune to morale checks and Shaken.
- [[Unbowed]] — Arch-villains shrug off stuns, roots and knockback 75% of the time.

## Escort

Travels and fights with:

- 2× [[Orc Brute]]
- 3× [[Goblin Skirmisher]]

## Relic drops

Defeating this villain drops a unique relic:

- [[Fang of Ruin]]

## On the world map

|  | Value |
|---|---|
| Roam radius | 40 |
| Ambush chance | 20% |
| Settlement corruption chance | 3% |

Units (hexes, per day) are not stated in the data.

## On death

Killing the villain shifts faction power:

| Faction | Power |
|---|---|
| [[Greenskin Warband]] | -30 |
| [[Wilding Elves]] | +10 |
| [[Feral Gnolls]] | +10 |

## Dialogue

> [!quote]- Dialogue
> **On first meeting:** *"SMALL THINGS! GORTHAK BREAKS YOU!"*
>
> **Entering phase 2:** *"GORTHAK NOT DIE! GORTHAK STRONGER!"*
>
> **When defeated:** *"Gorthak... tired..."*
>
> **When your company loses:** *"RUN! RUN AND TELL! GORTHAK COMES!"*

*Generated from `villains/arch_villains.json`. Edits will be overwritten — put your own notes in Notes/.*
