---
type: combat_sheet
aliases:
  - Kesharan Dominion abilities
  - Kesharan Dominion reference
tags:
  - combat-sheet
  - faction/kesharan_dominion
  - type/combat_sheet
source:
  - enemies/kesharan_dominion.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Kesharan Dominion
faction_id: kesharan_dominion
level_min: 5
tier_max: 4
tier_min: 1
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Kesharan Dominion]]: 8 unit types (tiers 1-4), from company level 5+. They fight as [[How Enemies Behave#Disciplined|Disciplined]] — holds formation, coordinated.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Kesharan Dominion]].

![[_assets/Units/Satrap.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/SlaveArcher.webp\|40]] | [[Slave Archer]] | 1 | 40 | 0 | 28 / 22 | 48 / 25 | 44 | 8-13 piercing, ranged | Slash 1 · Blunt 1 | — |
| ![[_assets/Units/SlaveConscript.webp\|40]] | [[Slave Conscript]] | 1 | 50 | 1 | 42 / 25 | 0 / 25 | 51 | 10-17 piercing | Slash 1 · Blunt 1 | — |
| ![[_assets/Units/KesharanGuard.webp\|40]] | [[Kesharan Guard]] | 2 | 106 | 11 | 79 / 64 | 0 / 53 | 54 | 15-25 slashing | Slash 10 · Pierce 19 · Blunt 14 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/SlaveDriver.webp\|40]] | [[Slave Driver]] | 2 | 92 | 8 | 73 / 55 | 0 / 48 | 56 | 16-25 slashing | Slash 6 · Pierce 5 · Blunt 7 | [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/EnslavedGiant.webp\|40]] | [[Enslaved Giant]] | 3 | 187 | 12 | 80 / 52 | 0 / 44 | 32 | 25-39 blunt | Slash 10 · Blunt 10 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/KesharanHorseArcher.webp\|40]] | [[Kesharan Horse Archer]] | 3 | 94 | 9 | 69 / 57 | 92 / 64 | 69 | 15-25 piercing, ranged | Slash 8 · Pierce 6 · Blunt 9 | [[Flurry (Ability)\|Flurry]], [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/KesharanImmortal.webp\|40]] | [[Kesharan Immortal]] | 3 | 130 | 15 | 94 / 78 | 0 / 67 | 59 | 24-35 slashing | Slash 13 · Pierce 23 · Blunt 17 | [[Shield Formation]], [[Exploit Opening]] |
| ![[_assets/Units/Satrap.webp\|40]] | [[Satrap]] | 4 | 164 | 18 | 107 / 89 | 0 / 78 | 67 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Exploit Opening]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Rally (Ability)\|Rally]] | [[Slave Driver]], [[Satrap]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Kesharan Guard]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Cleave (Ability)\|Cleave]] | [[Enslaved Giant]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Exploit Opening]] | [[Kesharan Immortal]], [[Satrap]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Flurry (Ability)\|Flurry]] | [[Kesharan Horse Archer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Ground Slam]] | [[Enslaved Giant]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Shield Formation]] | [[Kesharan Immortal]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Form a defensive shield wall. You and the allies adjacent when you cast gain +8 melee def, +4 ranged def, -3 initiative while maintained, even if they move away. Drains 4 fatigue/turn. |
| [[Volley (Ability)\|Volley]] | [[Kesharan Horse Archer]] | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Satrap]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Kesharan Immortal]]<br>Possible bonus: [[Satrap]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Kesharan Guard]], [[Satrap]] | +5 melee defense, +5 willpower from professional training. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Kesharan Immortal]]<br>Possible bonus: [[Enslaved Giant]], [[Satrap]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Kesharan Horse Archer]] | +8 initiative from animal instincts. |
| [[Formation Bonus]] | Always: [[Kesharan Guard]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Giant Stomp]] | Always: [[Enslaved Giant]] | Successful attacks deal 5 splash damage to 1 random adjacent enemy. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Enslaved Giant]]<br>Possible bonus: [[Slave Driver]], [[Kesharan Immortal]], [[Satrap]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Intimidating Presence]] | Always: [[Slave Driver]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Kesharan Immortal]], [[Satrap]]<br>Possible bonus: [[Slave Driver]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Keen Senses]] | Always: [[Kesharan Horse Archer]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Massive Frame]] | Always: [[Enslaved Giant]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Rallying Presence]] | Always: [[Satrap]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Slave-Driven]] | Always: [[Slave Archer]], [[Slave Conscript]] | -10 willpower, +5 melee attack. The taskmaster's whip hurts more than the enemy. |
| [[Enrage]] | Possible bonus: [[Enslaved Giant]] | +30% damage when below 50% HP. |
| [[Evasion]] | Possible bonus: [[Kesharan Horse Archer]] | +6 effective defense from supernatural agility. |
| [[Fleet-Footed]] | Possible bonus: [[Kesharan Horse Archer]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Last Stand (Enemy Passive)\|Last Stand]] | Possible bonus: [[Kesharan Immortal]] | +15 melee attack, +20 willpower when below 25% HP. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Kesharan Horse Archer]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Kesharan Guard]], [[Kesharan Immortal]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Stalwart]] | Possible bonus: [[Kesharan Guard]] | +10 willpower, +2 armor. Unyielding in the face of danger. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Possible bonus: [[Enslaved Giant]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Slave Conscript]]*, [[Kesharan Guard]]*, [[Slave Driver]]*, [[Enslaved Giant]]*, [[Kesharan Immortal]]*, [[Satrap]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Slave Archer]]*, [[Kesharan Horse Archer]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |

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
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Hills — Mid Tier]], [[Plains — Mid Tier]], [[Plains — Late Tier]].

*Generated from `enemies/kesharan_dominion.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
