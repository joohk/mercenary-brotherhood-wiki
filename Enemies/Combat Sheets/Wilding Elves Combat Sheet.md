---
type: combat_sheet
aliases:
  - Wilding Elves abilities
  - Wilding Elves reference
tags:
  - combat-sheet
  - faction/barbarians
  - type/combat_sheet
source:
  - enemies/barbarians.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Wilding Elves
faction_id: barbarians
level_min: 4
tier_max: 4
tier_min: 1
units: 7
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Wilding Elves]]: 7 unit types (tiers 1-4), from company level 4+. They fight as [[How Enemies Behave#Undisciplined|Undisciplined]] — unpredictable, low coordination.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Wilding Elves]].

![[_assets/Units/TribalWarchief.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/TribalRaider.webp\|40]] | [[Wilding Raider]] | 1 | 62 | 1 | 54 / 34 | 0 / 35 | 57 | 11-18 slashing | Slash 2 · Pierce 1 · Blunt 2 | — |
| ![[_assets/Units/ShieldMaiden.webp\|40]] | [[Thorn Warden]] | 2 | 88 | 9 | 75 / 66 | 0 / 55 | 58 | 15-25 slashing | Slash 8 · Pierce 17 · Blunt 9 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/Berserker.webp\|40]] | [[Wilding Berserker]] | 2 | 101 | 3 | 81 / 42 | 0 / 31 | 73 | 19-32 slashing | Slash 2 · Pierce 1 · Blunt 2 | [[Frenzy (Ability)\|Frenzy]] |
| ![[_assets/Units/TribalHunter.webp\|40]] | [[Wilding Huntsman]] | 2 | 69 | 6 | 55 / 44 | 79 / 47 | 64 | 11-18 piercing, ranged | Slash 2 · Pierce 1 · Blunt 2 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/TribalShaman.webp\|40]] | [[Thornwoad Shaman]] | 3 | 88 | 7 | 54 / 48 | 90 / 58 | 57 | 26-41 blunt | Slash 3 · Pierce 2 · Blunt 3 | [[Minor Heal]] |
| ![[_assets/Units/BerserkerChampion.webp\|40]] | [[Wilding Bloodsworn]] | 3 | 131 | 8 | 94 / 55 | 0 / 44 | 74 | 31-46 slashing | Slash 2 · Pierce 1 · Blunt 2 | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]] |
| ![[_assets/Units/TribalWarchief.webp\|40]] | [[Wilding Warchief]] | 4 | 157 | 14 | 107 / 80 | 0 / 66 | 71 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[War Horn]], [[Cleave (Ability)\|Cleave]], [[Rally (Ability)\|Rally]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Wilding Huntsman]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | [[Wilding Berserker]], [[Wilding Bloodsworn]] | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Thorn Warden]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Cleave (Ability)\|Cleave]] | [[Wilding Bloodsworn]], [[Wilding Warchief]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Minor Heal]] | [[Thornwoad Shaman]] | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Rally (Ability)\|Rally]] | [[Wilding Warchief]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[War Horn]] | [[Wilding Warchief]] | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Berserker Rage]] | Always: [[Wilding Berserker]], [[Wilding Bloodsworn]]<br>Possible bonus: [[Wilding Raider]], [[Wilding Warchief]] | +10 melee attack, -8 melee defense. Offense over defense. |
| [[Dark Blessing]] | Always: [[Thornwoad Shaman]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Enrage]] | Always: [[Wilding Berserker]], [[Wilding Bloodsworn]]<br>Possible bonus: [[Wilding Warchief]] | +30% damage when below 50% HP. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Wilding Bloodsworn]], [[Wilding Warchief]]<br>Possible bonus: [[Wilding Berserker]] | Immune to morale checks and Shaken. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Wilding Warchief]]<br>Possible bonus: [[Wilding Bloodsworn]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Wilding Warchief]]<br>Possible bonus: [[Thorn Warden]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Keen Senses]] | Always: [[Wilding Huntsman]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Savage Fury]] | Always: [[Wilding Raider]] | +6 damage max, -2 melee defense. Wild, uncontrolled strikes. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Always: [[Thorn Warden]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Stalwart]] | Always: [[Thorn Warden]] | +10 willpower, +2 armor. Unyielding in the face of danger. |
| [[Blood Frenzy]] | Possible bonus: [[Wilding Bloodsworn]] | +20% damage when any ally has died this combat. |
| [[Feral Speed]] | Possible bonus: [[Wilding Raider]] | +8 initiative from animal instincts. |
| [[Formation Bonus]] | Possible bonus: [[Thorn Warden]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Frenzy (Enemy Passive)\|Frenzy]] | Possible bonus: [[Wilding Bloodsworn]] | +2 melee attack per successful hit in this combat, stacking. |
| [[Intimidating Presence]] | Possible bonus: [[Thornwoad Shaman]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Magic Resistance]] | Possible bonus: [[Thornwoad Shaman]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Wilding Huntsman]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Predatory Instinct]] | Possible bonus: [[Wilding Huntsman]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Rallying Presence]] | Possible bonus: [[Wilding Warchief]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Reckless Charge]] | Possible bonus: [[Wilding Berserker]] | +8 initiative, +5 melee attack, -6 melee defense. All-out aggression. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Thorn Warden]]*, [[Wilding Berserker]]*, [[Wilding Bloodsworn]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Wilding Raider]]*, [[Wilding Huntsman]]*, [[Thornwoad Shaman]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Wilding Warchief]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Battle Cry (Ability)\|Battle Cry]] | Warlord (Elite+) | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Hills — Encounter]], [[Mountain — Encounter]], [[Plains — Random Encounter]], [[Hills Base Garrison — Shallow]], [[Hills — Mid Tier]], [[Plains — Mid Tier]], [[Mountain — Mid Tier]], [[Plains — Late Tier]].

*Generated from `enemies/barbarians.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
