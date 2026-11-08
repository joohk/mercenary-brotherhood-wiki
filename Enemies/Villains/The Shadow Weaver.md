---
id: villain_shadow_weaver
type: villain
category: Arch-Villains
aliases:
  - villain_shadow_weaver
tags:
  - enemy/tier-5
  - faction/umbral_court
  - type/villain
source: villains/arch_villains.json
armor: 5
faction: The Umbral Court
gold: 170
hp: 180
level_min: 7
personality: cold
size: normal
stance: aggressive
threat_cost: 24
tier: 5
title: Vaelith of the Deep Dark
xp: 220
---

An arch-villain of [[The Umbral Court]] — *Vaelith of the Deep Dark*. Awakens from company level 7; 180 HP, 5 armor, worth 220 XP and 170 gold.

![[_assets/Units/ShadowWeaver.webp|200]]

> A dark elf spymistress who commands a web of assassins and informants. She prefers to kill silently but is lethal in open combat.

## Stats

| Stat | Value |
|---|---|
| [[Stats#Max HP\|Max HP]] | 180 |
| [[Stats#Max Fatigue\|Max Fatigue]] | 120 |
| [[Stats#Initiative\|Initiative]] | 78 |
| [[Stats#Melee Attack\|Melee Attack]] | 80 |
| [[Stats#Melee Defense\|Melee Defense]] | 65 |
| [[Stats#Ranged Attack\|Ranged Attack]] | 60 |
| [[Stats#Ranged Defense\|Ranged Defense]] | 62 |
| [[Stats#Armor\|Armor]] | 5 |
| [[Stats#Willpower\|Willpower]] | 85 |
| [[Stats#Vision\|Vision]] | 9 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | 22 |
| [[Stats#Damage Min\|Damage]] | 16-26 |
| Ranged Range | 4 |

## Combat

|  | Value |
|---|---|
| Title | Vaelith of the Deep Dark |
| [[Glossary#Numbers used on this wiki\|Tier]] | 5 |
| [[Glossary#Numbers used on this wiki\|Threat cost]] | 24 |
| XP | 220 |
| Gold | 170 |
| Size | Normal |
| Stance | Aggressive — closes in and fights in melee |
| Personality | Cold |
| AI | [[How Enemies Behave#Elite\|Elite]] (assignment to arch-villains is not stated in the data; no faction uses this profile) |
| Appears from company level | 7 |

## Phases

The fight starts in phase 1. When the villain's HP drops below the threshold, the next phase begins at once.

### Phase 2 — below 45% HP

- **Stats:** +20 [[Stats#Initiative|Initiative]], +22 [[Stats#Melee Attack|Melee Attack]], +9 to +14 [[Stats#Damage Min|Damage]]
- **Gains passives:** [[Evasion]]
- **Gains abilities:** [[Frenzy (Ability)|Frenzy]], [[Soul Rend (Ability)|Soul Rend]]
- **Heals** 10% of max HP
- **Says:** *"Enough games. I will end this personally."*

## Abilities

- [[Opportunist Strike (Ability)|Opportunist Strike]]
- [[Exploit Opening (Ability, ability_exploit_opening)|Exploit Opening]]
- [[Shadow Nova]]
- [[Shadow Stalk]]

## Passives

- [[Shadowcloak]] — +3 ranged def always. +10 bonus at range 4+, +5 at range 2-3, +0 adjacent. Close the distance!
- [[Nimble (Enemy Passive)|Nimble]] — +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down.
- [[Unbowed]] — Arch-villains shrug off stuns, roots and knockback 75% of the time.

## Escort

Travels and fights with:

- 2× [[Umbral Blademaster]]
- 2× [[Umbral Archer]]

## Relic drops

Defeating this villain drops a unique relic:

- [[Shadow Mantle]]
- [[Warpblade]]

## On the world map

|  | Value |
|---|---|
| Roam radius | 35 |
| Ambush chance | 25% |
| Settlement corruption chance | 4% |

Units (hexes, per day) are not stated in the data.

## On death

Killing the villain shifts faction power:

| Faction | Power |
|---|---|
| [[The Umbral Court]] | -20 |
| [[Deserters]] | +5 |
| [[Bandits]] | +15 |

## Dialogue

> [!quote]- Dialogue
> **On first meeting:** *"You found me. Impressive. It will not save you."*
>
> **Entering phase 2:** *"Enough games. I will end this personally."*
>
> **When defeated:** *"How... did you see me..."*
>
> **When your company loses:** *"Consider this a warning. The next time, you will not see the blade."*

*Generated from `villains/arch_villains.json`. Edits will be overwritten — put your own notes in Notes/.*
