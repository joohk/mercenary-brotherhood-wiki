---
type: combat_sheet
aliases:
  - Wolf Pack abilities
  - Wolf Pack reference
tags:
  - combat-sheet
  - faction/wolves
  - type/combat_sheet
source:
  - enemies/wolves.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Wolf Pack
faction_id: wolves
level_min: 1
tier_max: 3
tier_min: 1
units: 3
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Wolf Pack (Faction)|Wolf Pack]]: 3 unit types (tiers 1-3), from company levels 1-4. They fight as [[How Enemies Behave#Swarm|Swarm]] — flanks and surrounds.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Wolf Pack (Faction)|Wolf Pack]].

![[_assets/Units/AlphaWolf.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Wolf.webp\|40]] | [[Wolf]] | 1 | 30 | 0 | 48 / 30 | 0 / 25 | 70 | 6-10 piercing | Slash 10 | — |
| ![[_assets/Units/DireWolf.webp\|40]] | [[Dire Wolf]] | 2 | 86 | 6 | 75 / 47 | 0 / 34 | 66 | 14-24 piercing | Slash 10 | [[Gore Charge (Ability)\|Gore Charge]] |
| ![[_assets/Units/AlphaWolf.webp\|40]] | [[Alpha Wolf]] | 3 | 130 | 8 | 89 / 57 | 0 / 44 | 63 | 21-32 piercing | Slash 15 | [[Howl]], [[Gore Charge (Ability)\|Gore Charge]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Gore Charge (Ability)\|Gore Charge]] | [[Dire Wolf]], [[Alpha Wolf]] | Enemy, 3 hexes | 1 | 25 | — | 1 | Charge an enemy up to 3 hexes away, dealing 150% weapon damage, stunning them and knocking them back 2 hexes on hit. *150% weapon (+ stun, melee to-hit)* |
| [[Howl]] | [[Alpha Wolf]] | Self, radius 3 around | 1 | 16 | — | 1 | A terrifying howl that reduces willpower of all enemies within 3 hexes by 15. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Feral Speed]] | Always: [[Dire Wolf]], [[Alpha Wolf]]<br>Possible bonus: [[Wolf]] | +8 initiative from animal instincts. |
| [[Pack Tactics (Enemy Passive)\|Pack Tactics]] | Always: [[Wolf]], [[Dire Wolf]], [[Alpha Wolf]] | +10 hit chance when an ally is adjacent to the target. |
| [[Predatory Instinct]] | Always: [[Alpha Wolf]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Enrage]] | Possible bonus: [[Dire Wolf]], [[Alpha Wolf]] | +30% damage when below 50% HP. |
| [[Fearless (Enemy Passive)\|Fearless]] | Possible bonus: [[Alpha Wolf]] | Immune to morale checks and Shaken. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Dire Wolf]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Intimidating Presence]] | Possible bonus: [[Alpha Wolf]] | Adjacent enemies suffer -5 willpower on morale checks. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Wolf]]*, [[Dire Wolf]]*, [[Alpha Wolf]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Cleave (Ability)\|Cleave]] | Brute (Champion+) | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Forest — Encounter]], [[Forest — Mid Tier]].

Its units also join other factions' groups in: [[Forest — Late Tier]], [[Hills — Encounter]], [[Hills — Mid Tier]], [[Plains — Late Tier]], [[Plains — Random Encounter]].

*Generated from `enemies/wolves.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
