---
type: combat_sheet
aliases:
  - Swamp Dwellers abilities
  - Swamp Dwellers reference
tags:
  - combat-sheet
  - faction/swamp_dwellers
  - type/combat_sheet
source:
  - enemies/swamp_dwellers.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Swamp Dwellers
faction_id: swamp_dwellers
level_min: 3
tier_max: 4
tier_min: 1
units: 5
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Swamp Dwellers]]: 5 unit types (tiers 1-4), from company level 3+. They fight as [[How Enemies Behave#Cunning|Cunning]] — intelligent and devious.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Swamp Dwellers]].

![[_assets/Units/SwampHorror.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/BogLurker.webp\|40]] | [[Bog Lurker]] | 1 | 50 | 2 | 50 / 35 | 0 / 33 | 51 | 8-12 slashing | Slash 2 · Pierce 1 · Blunt 2 · Poison 20 | [[Exploit Opening]] |
| ![[_assets/Units/MarshCrawler.webp\|40]] | [[Marsh Crawler]] | 2 | 99 | 10 | 72 / 55 | 0 / 45 | 35 | 13-21 slashing | Slash 20 · Pierce 10 · Poison 20 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/SwampWitch.webp\|40]] | [[Swamp Witch]] | 2 | 66 | 4 | 44 / 36 | 75 / 47 | 50 | 19-32 blunt | Slash 2 · Pierce 2 · Blunt 2 | [[Ice Shard (Ability)\|Ice Shard]], [[Life Drain]] |
| ![[_assets/Units/BogTroll.webp\|40]] | [[Bog Troll]] | 3 | 187 | 12 | 80 / 55 | 0 / 41 | 34 | 28-43 blunt | Blunt 10 · **Fire -30** · Poison 30 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/SwampHorror.webp\|40]] | [[Swamp Horror]] | 4 | 218 | 14 | 100 / 68 | 0 / 54 | 34 | 36-55 blunt | Blunt 30 · **Fire -25** · Poison 40 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Exploit Opening]] | [[Bog Lurker]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Cleave (Ability)\|Cleave]] | [[Marsh Crawler]], [[Bog Troll]], [[Swamp Horror]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Ice Shard (Ability)\|Ice Shard]] | [[Swamp Witch]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Life Drain]] | [[Swamp Witch]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Ground Slam]] | [[Bog Troll]], [[Swamp Horror]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Armored Scales]] | Always: [[Marsh Crawler]] | +3 armor, +3 ranged defense from natural scale plating. |
| [[Bloodless]] | Always: [[Swamp Horror]] | No blood left to spill. Immune to Bleeding. |
| [[Dark Blessing]] | Always: [[Swamp Witch]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Swamp Horror]]<br>Possible bonus: [[Bog Troll]] | Immune to morale checks and Shaken. |
| [[Massive Frame]] | Always: [[Swamp Horror]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Natural Camouflage]] | Always: [[Bog Lurker]] | +3 ranged def always. +10 bonus on forest/swamp/scrub terrain, +0 on open ground. Lure it out! |
| [[Regeneration]] | Always: [[Bog Troll]], [[Swamp Horror]] | Heals 5 HP at the start of each turn. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Always: [[Marsh Crawler]], [[Bog Troll]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Bog Lurker]], [[Swamp Witch]], [[Bog Troll]]<br>Possible bonus: [[Swamp Horror]] | 30% chance to poison the target on hit. |
| [[Ambush]] | Possible bonus: [[Bog Lurker]] | +15 melee attack on first attack of combat. |
| [[Death Throes]] | Possible bonus: [[Swamp Horror]] | Explodes on death, dealing 10 damage to all adjacent units. |
| [[Enrage]] | Possible bonus: [[Marsh Crawler]], [[Bog Troll]] | +30% damage when below 50% HP. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Marsh Crawler]], [[Bog Troll]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Bog Lurker]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Poison Cloud]] | Possible bonus: [[Swamp Witch]] | Adjacent enemies take 2 poison damage at the start of this unit's turn. |
| [[Shadowcloak]] | Possible bonus: [[Swamp Witch]] | +3 ranged def always. +10 bonus at range 4+, +5 at range 2-3, +0 adjacent. Close the distance! |
| [[Terrifying]] | Possible bonus: [[Swamp Horror]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Bog Lurker]]*, [[Marsh Crawler]]*, [[Bog Troll]]*, [[Swamp Horror]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Swamp Witch]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Flurry (Ability)\|Flurry]] | Skirmisher (Elite+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Swamp — Encounter]], [[Shallow Fungal Bog Encounter]], [[Swamp Base Garrison — Shallow]], [[Mid-depth Fungal Bog Encounter]], [[Swamp — Mid Tier]], [[Swamp — Late Tier]].

*Generated from `enemies/swamp_dwellers.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
