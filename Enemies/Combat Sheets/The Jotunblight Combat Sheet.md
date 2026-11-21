---
type: combat_sheet
aliases:
  - The Jotunblight abilities
  - The Jotunblight reference
tags:
  - combat-sheet
  - faction/jotunblight
  - type/combat_sheet
source:
  - enemies/jotunblight.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: The Jotunblight
faction_id: jotunblight
level_min: 5
tier_max: 5
tier_min: 2
units: 7
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for [[The Jotunblight]]: 7 unit types (tiers 2-5), from company level 5+. They fight as [[How Enemies Behave#Cunning|Cunning]] — intelligent and devious.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[The Jotunblight]].

![[_assets/Units/JotunWarlord.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Wolf.webp\|40]] | [[Frost Wolf]] | 2 | 77 | 4 | 66 / 42 | 0 / 40 | 68 | 7-11 piercing | Slash 10 · Pierce 10 · Blunt 10 · **Fire -20** · Cold 40 | [[Gore Charge (Ability)\|Gore Charge]] |
| ![[_assets/Units/MountainCub.webp\|40]] | [[Mountain Cub]] | 2 | 121 | 9 | 61 / 42 | 70 / 42 | 42 | 9-13 blunt | Slash 10 · Pierce 10 · Blunt 10 | [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/HillGiant.webp\|40]] | [[Hill Giant]] | 4 | 281 | 12 | 96 / 56 | 0 / 42 | 30 | 40-60 blunt | Slash 15 · Pierce 15 · Blunt 15 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/StoneGiant.webp\|40]] | [[Stone Giant]] | 4 | 312 | 19 | 92 / 68 | 0 / 54 | 26 | 40-60 blunt | — | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/FrostGiant.webp\|40]] | [[Frost Giant]] | 5 | 309 | 18 | 109 / 78 | 0 / 62 | 40 | 50-75 slashing | Slash 20 · Pierce 20 · Blunt 20 · **Fire -25** · Cold 50 | [[Frost Slam]], [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/JotunShaman.webp\|40]] | [[Jotun Shaman]] | 5 | 211 | 11 | 79 / 59 | 109 / 65 | 44 | 20-32 blunt | Slash 15 · Pierce 15 · Blunt 15 · Cold 30 · Lightning 25 | [[Fireball (Ability)\|Fireball]], [[Ice Shard (Ability)\|Ice Shard]], [[Mend (Ability)\|Mend]], [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/JotunWarlord.webp\|40]] | [[Jotun Warlord]] | 5 | 406 | 22 | 116 / 84 | 0 / 69 | 38 | 52-79 blunt | Slash 20 · Pierce 20 · Blunt 20 · **Fire -20** · Cold 50 | [[War Horn]], [[Ground Slam]], [[Cleave (Ability)\|Cleave]], [[Battle Cry (Ability)\|Battle Cry]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Gore Charge (Ability)\|Gore Charge]] | [[Frost Wolf]] | Enemy, 3 hexes | 1 | 25 | — | 1 | Charge an enemy up to 3 hexes away, dealing 150% weapon damage, stunning them and knocking them back 2 hexes on hit. *150% weapon (+ stun, melee to-hit)* |
| [[Volley (Ability)\|Volley]] | [[Mountain Cub]] | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[Cleave (Ability)\|Cleave]] | [[Hill Giant]], [[Stone Giant]], [[Frost Giant]], [[Jotun Warlord]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Ground Slam]] | [[Hill Giant]], [[Stone Giant]], [[Frost Giant]], [[Jotun Warlord]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Jotun Warlord]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Fireball (Ability)\|Fireball]] | [[Jotun Shaman]] | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Frost Slam]] | [[Frost Giant]] | Adjacent enemy | 1 | 24 | — | 1 | A freezing strike that deals 20-30 cold damage and roots the target in place on hit. *20-30 (+ root, melee to-hit)* |
| [[Ice Shard (Ability)\|Ice Shard]] | [[Jotun Shaman]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Mend (Ability)\|Mend]] | [[Jotun Shaman]] | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Rally (Ability)\|Rally]] | [[Jotun Shaman]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[War Horn]] | [[Jotun Warlord]] | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Bloodless]] | Always: [[Stone Giant]] | No blood left to spill. Immune to Bleeding. |
| [[Cold-Blooded]] | Always: [[Frost Wolf]], [[Frost Giant]], [[Jotun Shaman]]<br>Possible bonus: [[Jotun Warlord]] | Immune to fear and Shaken. Bleeding damage reduced by 50%. |
| [[Dark Blessing]] | Always: [[Jotun Shaman]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Jotun Warlord]]<br>Possible bonus: [[Hill Giant]], [[Stone Giant]], [[Frost Giant]], [[Jotun Shaman]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Frost Wolf]] | +8 initiative from animal instincts. |
| [[Frost Aura (Enemy Passive)\|Frost Aura]] | Always: [[Frost Giant]] | 20% chance to reduce melee attacker's initiative by 10 for 1 turn. |
| [[Giant Stomp]] | Always: [[Hill Giant]], [[Stone Giant]], [[Jotun Warlord]]<br>Possible bonus: [[Frost Giant]] | Successful attacks deal 5 splash damage to 1 random adjacent enemy. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Mountain Cub]], [[Hill Giant]], [[Stone Giant]], [[Frost Giant]], [[Jotun Warlord]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Massive Frame]] | Always: [[Hill Giant]], [[Frost Giant]], [[Jotun Warlord]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Pack Tactics (Enemy Passive)\|Pack Tactics]] | Always: [[Frost Wolf]] | +10 hit chance when an ally is adjacent to the target. |
| [[Rallying Presence]] | Always: [[Jotun Warlord]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Stone Flesh]] | Always: [[Stone Giant]] | +3 armor always, -5 initiative. 25% resistance to slashing and piercing. 25% vulnerable to blunt. Shrugs off stuns and roots 50% of the time. Use maces! |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Always: [[Mountain Cub]]<br>Possible bonus: [[Frost Wolf]], [[Hill Giant]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |
| [[Crushing Force]] | Possible bonus: [[Stone Giant]], [[Frost Giant]] | +2 damage min always. +4 bonus vs targets with armor >= 6. Send light units! |
| [[Enrage]] | Possible bonus: [[Hill Giant]], [[Jotun Warlord]] | +30% damage when below 50% HP. |
| [[Fortified (Enemy Passive)\|Fortified]] | Possible bonus: [[Stone Giant]] | Takes 25% less damage from ranged attacks. |
| [[Intimidating Presence]] | Possible bonus: [[Jotun Shaman]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Possible bonus: [[Jotun Warlord]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Magic Resistance]] | Possible bonus: [[Jotun Shaman]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Predatory Instinct]] | Possible bonus: [[Frost Wolf]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Possible bonus: [[Mountain Cub]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Frost Wolf]]*, [[Hill Giant]]*, [[Stone Giant]]*, [[Frost Giant]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Mountain Cub]]*, [[Jotun Shaman]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Jotun Warlord]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Flurry (Ability)\|Flurry]] | Skirmisher (Elite+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+), Warlord (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Plains — Jotunblight Invasion]].

*Generated from `enemies/jotunblight.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
