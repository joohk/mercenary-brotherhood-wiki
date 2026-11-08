---
id: villain_bloodlord_kael
type: villain
category: Arch-Villains
aliases:
  - villain_bloodlord_kael
tags:
  - enemy/tier-5
  - faction/vampires
  - type/villain
source: villains/arch_villains.json
armor: 10
faction: Vampires
gold: 150
hp: 250
level_min: 6
personality: calculating
size: large
stance: aggressive
threat_cost: 25
tier: 5
title: The Undying
xp: 200
---

An arch-villain of the [[Vampires]] — *The Undying*. Awakens from company level 6; 250 HP, 10 armor, worth 200 XP and 150 gold.

![[_assets/Units/BloodlordKael.webp|200]]

> An ancient vampire lord who has ruled the eastern marches for centuries. He views mortals as cattle and mercenaries as entertainment.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 250 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 120 |
| [[Stats#Initiative\|Initiative]] | 65 |
| [[Stats#Melee Attack\|Melee Attack]] | 82 |
| [[Stats#Melee Defense\|Melee Defense]] | 60 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 60 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 55 |
| [[Stats#Armor\|Armor]] | 10 |
| [[Stats#Willpower\|Willpower]] | 95 |
| [[Stats#Vision\|Vision]] | 8 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 22 |
| [[Stats#Damage Min\|Damage]] | 18-30 |

## Combat

|  | Value |
|---|---|
| Title | The Undying |
| [[Glossary#Numbers used on this wiki\|Tier]] | 5 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 25 |
| XP | 200 |
| Gold | 150 |
| Size | Large |
| Stance | Aggressive — closes in and fights in melee |
| Personality | Calculating |
| AI | [[How Enemies Behave#Elite\|Elite]] (assignment to arch-villains is not stated in the data; no faction uses this profile) |
| Appears from company level | 6 |

## Phases

The fight starts in phase 1. When the villain's HP drops below the threshold, the next phase begins at once.

### Phase 2 — below 50% HP

- **Stats:** +15 [[Stats#Initiative|Initiative]], +10 to +16 [[Stats#Damage Min|Damage]], +20 [[Stats#Melee Attack|Melee Attack]]
- **Gains passives:** [[Berserker Rage]]
- **Gains abilities:** [[Shadow Nova]]
- **Heals** 10% of max HP
- **Says:** *"You have drawn blood from me. A rare achievement. It will be your last."*

## Abilities

- [[Life Drain]]
- [[Blood Call]]

## Passives

- [[Drain Life]] — Heals 3 HP on each successful melee hit.
- [[Regeneration]] — Heals 5 HP at the start of each turn.
- [[Unbowed]] — Arch-villains shrug off stuns, roots and knockback 75% of the time.

## Escort

Travels and fights with:

- 2× [[Vampire Knight]]
- 3× [[Thrall Guard]]

## Relic drops

Defeating this villain drops a unique relic:

- [[Heartstone Blade]]

## On the world map

|  | Value |
|---|---|
| Roam radius | 30 |
| Ambush chance | 15% |
| Settlement corruption chance | 5% |

Units (hexes, per day) are not stated in the data.

## On death

Killing the villain shifts faction power:

| Faction | Power |
|---|---|
| [[Vampires]] | -20 |
| [[Demons]] | +5 |
| [[The Restless Dead]] | +10 |

## Dialogue

> [!quote]- Dialogue
> **On first meeting:** *"You smell... promising. Most mortals reek only of fear."*
>
> **Entering phase 2:** *"You have drawn blood from me. A rare achievement. It will be your last."*
>
> **When defeated:** *"Impossible... I have outlived empires..."*
>
> **When your company loses:** *"Run, little mercenary. Tell others what waits in the dark."*

*Generated from `villains/arch_villains.json`. Edits will be overwritten — put your own notes in Notes/.*
