---
type: combat_sheet
aliases:
  - Veteran Company abilities
  - Veteran Company reference
tags:
  - combat-sheet
  - faction/veterans
  - type/combat_sheet
source:
  - enemies/veterans.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Veteran Company
faction_id: veterans
level_min: 7
tier_max: 4
tier_min: 3
units: 5
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Veteran Company]]: 5 unit types (tiers 3-4), from company level 7+. They fight as [[How Enemies Behave#Professional|Professional]] — skilled and pragmatic.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Veteran Company]].

![[_assets/Units/OrcVeteranSergeant.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/ElfVeteranArcher.webp\|40]] | [[Elf Veteran Archer]] | 3 | 90 | 8 | 71 / 66 | 103 / 71 | 69 | 29-47 piercing, ranged | Slash 10 · Pierce 8 · Blunt 15 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/GoblinSapperVeteran.webp\|40]] | [[Goblin Sapper-Veteran]] | 3 | 83 | 9 | 67 / 63 | 83 / 57 | 71 | 25-41 piercing, ranged | Slash 8 · Pierce 6 · Blunt 9 | [[Fireball (Ability)\|Fireball]] |
| ![[_assets/Units/HalflingScoutVeteran.webp\|40]] | [[Halfling Scout-Veteran]] | 3 | 78 | 8 | 86 / 86 | 63 / 72 | 78 | 29-44 slashing | Slash 8 · Pierce 6 · Blunt 9 | [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| ![[_assets/Units/VeteranSoldier.webp\|40]] | [[Human Veteran Soldier]] | 3 | 115 | 14 | 89 / 75 | 0 / 61 | 57 | 33-52 slashing | Slash 13 · Pierce 23 · Blunt 17 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/OrcVeteranSergeant.webp\|40]] | [[Orc Veteran Sergeant]] | 4 | 166 | 19 | 108 / 89 | 0 / 78 | 54 | 49-79 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Shield Bash (Ability)\|Shield Bash]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Fireball (Ability)\|Fireball]] | [[Goblin Sapper-Veteran]] | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Flurry (Ability)\|Flurry]] | [[Elf Veteran Archer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | [[Halfling Scout-Veteran]] | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Human Veteran Soldier]], [[Orc Veteran Sergeant]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Rally (Ability)\|Rally]] | [[Orc Veteran Sergeant]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle Scars]] | Always: [[Elf Veteran Archer]], [[Goblin Sapper-Veteran]], [[Halfling Scout-Veteran]], [[Human Veteran Soldier]], [[Orc Veteran Sergeant]] | Each fallen veteran ally permanently grants this unit +3 melee defense, +3 ranged defense, and +2 willpower. Stacks up to 5 times. Hardened by loss. |
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Human Veteran Soldier]]<br>Possible bonus: [[Elf Veteran Archer]], [[Halfling Scout-Veteran]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Elf Veteran Archer]], [[Goblin Sapper-Veteran]], [[Halfling Scout-Veteran]], [[Human Veteran Soldier]], [[Orc Veteran Sergeant]] | +5 melee defense, +5 willpower from professional training. |
| [[Evasion]] | Always: [[Halfling Scout-Veteran]]<br>Possible bonus: [[Elf Veteran Archer]] | +6 effective defense from supernatural agility. |
| [[Fleet-Footed]] | Always: [[Halfling Scout-Veteran]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Formation Bonus]] | Always: [[Human Veteran Soldier]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Orc Veteran Sergeant]]<br>Possible bonus: [[Human Veteran Soldier]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Keen Senses]] | Always: [[Elf Veteran Archer]]<br>Possible bonus: [[Halfling Scout-Veteran]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Rallying Presence]] | Always: [[Orc Veteran Sergeant]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Always: [[Elf Veteran Archer]]<br>Possible bonus: [[Goblin Sapper-Veteran]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Goblin Sapper-Veteran]] | 30% chance to poison the target on hit. |
| [[Wiry (Enemy Passive)\|Wiry]] | Always: [[Goblin Sapper-Veteran]] | +5 initiative, +4 melee defense. Lean and quick. |
| [[Brutal Strength]] | Possible bonus: [[Orc Veteran Sergeant]] | +2 damage always. First melee hit each turn deals +5 bonus damage. |
| [[Fearless (Enemy Passive)\|Fearless]] | Possible bonus: [[Orc Veteran Sergeant]] | Immune to morale checks and Shaken. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Human Veteran Soldier]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Elf Veteran Archer]], [[Goblin Sapper-Veteran]], [[Halfling Scout-Veteran]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Poison Cloud]] | Possible bonus: [[Goblin Sapper-Veteran]] | Adjacent enemies take 2 poison damage at the start of this unit's turn. |
| [[Precise Strikes (Enemy Passive)\|Precise Strikes]] | Possible bonus: [[Human Veteran Soldier]] | +3 melee attack always. +6 bonus from front arc, +0 from flank/rear. Flank to avoid! |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Human Veteran Soldier]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Elf Veteran Archer]]*, [[Goblin Sapper-Veteran]]*, [[Halfling Scout-Veteran]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Orc Veteran Sergeant]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Battle Cry (Ability)\|Battle Cry]] | Warlord (Elite+) | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Cleave (Ability)\|Cleave]] | Brute (Champion+), Warlord (Boss) | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Plains — Mid Tier]], [[Ruins — Mid Tier]], [[Plains — Late Tier]].

*Generated from `enemies/veterans.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
