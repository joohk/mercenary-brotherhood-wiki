---
id: villain_warlord_ash
type: villain
category: Arch-Villains
aliases:
  - villain_warlord_ash
tags:
  - enemy/tier-5
  - faction/mercenaries
  - type/villain
source: villains/arch_villains.json
armor: 10
faction: Rival Mercenaries
gold: 200
hp: 240
level_min: 6
personality: pragmatic
size: normal
stance: aggressive
threat_cost: 26
tier: 5
title: The Oathbreaker
up: "[[Arch-Villains]]"
xp: 200
---

[[Home]] › [[Bestiary]] › [[Arch-Villains]]

An arch-villain of the [[Rival Mercenaries]] — *The Oathbreaker*. Awakens from company level 6; 240 HP, 10 armor, worth 200 XP and 200 gold.

![[_assets/Units/WarlordAsh.webp|200]]

> A legendary mercenary captain who betrayed his company for power. He now leads a professional army of sellswords, deserters, and opportunists.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 240 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 110 |
| [[Stats#Initiative\|Initiative]] | 58 |
| [[Stats#Melee Attack\|Melee Attack]] | 80 |
| [[Stats#Melee Defense\|Melee Defense]] | 65 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 55 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 60 |
| [[Stats#Armor\|Armor]] | 10 |
| [[Stats#Willpower\|Willpower]] | 90 |
| [[Stats#Vision\|Vision]] | 7 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 20 |
| [[Stats#Damage Min\|Damage]] | 16-26 |

## Combat

|  | Value |
|---|---|
| Title | The Oathbreaker |
| [[Glossary#Numbers used on this wiki\|Tier]] | 5 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 26 |
| XP | 200 |
| Gold | 200 |
| Size | Normal |
| Stance | Aggressive — closes in and fights in melee |
| Personality | Pragmatic |
| AI | [[How Enemies Behave#Elite\|Elite]] (assignment to arch-villains is not stated in the data; no faction uses this profile) |
| Appears from company level | 6 |

## Phases

The fight starts in phase 1. When the villain's HP drops below the threshold, the next phase begins at once.

### Phase 2 — below 50% HP

- **Stats:** +20 [[Stats#Melee Attack|Melee Attack]], +9 to +13 [[Stats#Damage Min|Damage]], +12 [[Stats#Initiative|Initiative]]
- **Gains abilities:** [[Exploit Opening (Ability, ability_exploit_opening)|Exploit Opening]], [[Frenzy (Ability)|Frenzy]], [[Coup de Grace (Ability)|Coup de Grace]]
- **Heals** 10% of max HP
- **Says:** *"You've cost me too many men. Time to handle this myself."*

## Abilities

- [[Rally (Ability)|Rally]]
- [[Command (Ability)|Command]]
- [[Cleave (Ability)|Cleave]]

## Passives

- [[Iron Discipline (Enemy Passive)|Iron Discipline]] — +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns.
- [[Nimble (Enemy Passive)|Nimble]] — +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down.
- [[Unbowed]] — Arch-villains shrug off stuns, roots and knockback 75% of the time.
- [[Unbroken Defiance]] — Each ranged hit, spells included, adds +4 melee and ranged defense for 3 turns. Stacks up to 10 times, and each stack keeps its own clock.

## Escort

Travels and fights with:

- 2× [[Mercenary Knight]]
- 2× [[Mercenary Crossbowman]]
- 1× [[Shield Bearer]]

## Relic drops

Defeating this villain drops a unique relic:

- [[Oathkeeper]]
- [[Throne Guard]]

## On the world map

|  | Value |
|---|---|
| Roam radius | 30 |
| Ambush chance | 12% |
| Settlement corruption chance | 6% |

Units (hexes, per day) are not stated in the data.

## On death

Killing the villain shifts faction power:

| Faction | Power |
|---|---|
| [[Rival Mercenaries]] | -25 |
| [[Deserters]] | +10 |
| [[Bandits]] | +15 |

## Dialogue

> [!quote]- Dialogue
> **On first meeting:** *"A rival company? This is business, nothing personal. Stand down or die."*
>
> **Entering phase 2:** *"You've cost me too many men. Time to handle this myself."*
>
> **When defeated:** *"Should have... taken the deal..."*
>
> **When your company loses:** *"Smart. Live to fight another day. I respect that."*

*Generated from `villains/arch_villains.json`. Edits will be overwritten — put your own notes in Notes/.*
