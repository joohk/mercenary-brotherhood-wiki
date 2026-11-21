---
type: combat_sheet
aliases:
  - Beasts abilities
  - Beasts reference
tags:
  - combat-sheet
  - faction/beasts
  - type/combat_sheet
source:
  - enemies/beasts.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Beasts
faction_id: beasts
level_min: 1
tier_max: 4
tier_min: 1
units: 7
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Beasts]]: 7 unit types (tiers 1-4), from company level 1+. They fight as [[How Enemies Behave#Swarm|Swarm]] — flanks and surrounds.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Beasts]].

![[_assets/Units/Manticore.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/GiantSpider.webp\|40]] | [[Spider Broodling]] | 1 | 22 | 0 | 55 / 40 | 0 / 30 | 68 | 5-9 piercing | Slash 10 | — |
| ![[_assets/Units/Boar.webp\|40]] | [[Wild Boar]] | 1 | 45 | 2 | 50 / 30 | 0 / 27 | 50 | 7-12 piercing | Slash 10 | — |
| ![[_assets/Units/Bear.webp\|40]] | [[Bear]] | 2 | 132 | 8 | 75 / 53 | 0 / 40 | 44 | 16-25 slashing | Slash 15 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/GiantSpider.webp\|40]] | [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]] | 2 | 66 | 6 | 72 / 47 | 0 / 37 | 61 | 12-20 piercing | Slash 15 | [[Web Shot]] |
| ![[_assets/Units/CaveTroll.webp\|40]] | [[Cave Troll]] | 3 | 201 | 14 | 83 / 52 | 0 / 38 | 32 | 30-46 blunt | Slash 10 · Pierce 10 | [[Ground Slam]] |
| ![[_assets/Units/Wyvern.webp\|40]] | [[Wyvern]] | 3 | 123 | 10 | 89 / 63 | 0 / 55 | 63 | 18-30 slashing | Slash 10 · Fire 20 | [[Fire Breath]] |
| ![[_assets/Units/Manticore.webp\|40]] | [[Manticore]] | 4 | 203 | 13 | 102 / 74 | 88 / 62 | 60 | 34-53 slashing | Slash 15 | [[Gore Charge (Ability)\|Gore Charge]], [[Fire Breath]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Cleave (Ability)\|Cleave]] | [[Bear]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Web Shot]] | [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]] | Enemy, 3 hexes | 1 | 10 | 2 turns | 2 | Fire a strand of sticky web at a ranged target, rooting them in place for their next turn. 2 uses per battle. |
| [[Fire Breath]] | [[Wyvern]], [[Manticore]] | Cone, 1 hex | 1 | 22 | 4 turns | — | Exhale draconic flame at an adjacent enemy. Burns the targeted hex and the three hexes immediately behind it. Hits allies caught in the blast. Ignores armor. *18-26 per target (4-hex fan, ignores armor, burning)* |
| [[Ground Slam]] | [[Cave Troll]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Gore Charge (Ability)\|Gore Charge]] | [[Manticore]] | Enemy, 3 hexes | 1 | 25 | — | 1 | Charge an enemy up to 3 hexes away, dealing 150% weapon damage, stunning them and knocking them back 2 hexes on hit. *150% weapon (+ stun, melee to-hit)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Enrage]] | Always: [[Wild Boar]]<br>Possible bonus: [[Bear]], [[Cave Troll]], [[Wyvern]], [[Manticore]] | +30% damage when below 50% HP. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Manticore]]<br>Possible bonus: [[Bear]], [[Cave Troll]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Wyvern]], [[Manticore]] | +8 initiative from animal instincts. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Bear]]<br>Possible bonus: [[Cave Troll]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Massive Frame]] | Always: [[Cave Troll]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Regeneration]] | Always: [[Cave Troll]] | Heals 5 HP at the start of each turn. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Always: [[Bear]], [[Manticore]]<br>Possible bonus: [[Wild Boar]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Spider Broodling]], [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]], [[Wyvern]]<br>Possible bonus: [[Manticore]] | 30% chance to poison the target on hit. |
| [[Web Spinner]] | Always: [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]] | 20% chance to root target for 1 turn on hit. |
| [[Chitinous Plates]] | Possible bonus: [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]] | +5 armor, -3 initiative from insectoid exoskeleton. |
| [[Evasion]] | Possible bonus: [[Wyvern]] | +6 effective defense from supernatural agility. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Spider Broodling]], [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Terrifying]] | Possible bonus: [[Wyvern]], [[Manticore]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Spider Broodling]]*, [[Wild Boar]]*, [[Bear]]*, [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]]*, [[Cave Troll]]*, [[Wyvern]]*, [[Manticore]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Boar Nesting Ground (Encounter Table)|Boar Nesting Ground]], [[Dungeon — Boss Encounter]], [[Forest — Encounter]], [[Hills — Encounter]], [[Mountain — Encounter]], [[Brood Hollow]], [[Bear Den]], [[Forest — Mid Tier]], [[Giant Spider Nest (Encounter Table)|Giant Spider Nest]], [[Hills — Mid Tier]], [[Mountain — Mid Tier]], [[Troll Cave (Encounter Table)|Troll Cave]], [[Wyvern Roost (Encounter Table)|Wyvern Roost]], [[Forest — Late Tier]], [[Dragon's Hoard]].

*Generated from `enemies/beasts.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
