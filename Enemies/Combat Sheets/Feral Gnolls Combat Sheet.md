---
type: combat_sheet
aliases:
  - Feral Gnolls abilities
  - Feral Gnolls reference
tags:
  - combat-sheet
  - faction/feral_outcasts
  - type/combat_sheet
source:
  - enemies/feral_outcasts.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Feral Gnolls
faction_id: feral_outcasts
level_min: 1
tier_max: 2
tier_min: 0
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Feral Gnolls]]: 8 unit types (tiers 0-2), from company levels 1-3. They fight as [[How Enemies Behave#Undisciplined|Undisciplined]] — unpredictable, low coordination.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Feral Gnolls]].

![[_assets/Units/FeralAlpha.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/FeralHurler.webp\|40]] | [[Gnoll Hurler]] | 0 | 35 | 0 | 30 / 22 | 40 / 30 | 50 | 4-7 blunt, ranged | Slash 2 · Pierce 1 · Blunt 2 | — |
| ![[_assets/Units/FeralSavage.webp\|40]] | [[Gnoll Savage]] | 0 | 45 | 0 | 48 / 28 | 0 / 27 | 53 | 6-12 blunt | Slash 2 · Pierce 1 · Blunt 2 | — |
| ![[_assets/Units/FeralWhelp.webp\|40]] | [[Gnoll Whelp]] | 0 | 22 | 0 | 40 / 28 | 0 / 31 | 62 | 3-5 piercing | Slash 2 · Pierce 1 · Blunt 2 | [[Leap]] |
| ![[_assets/Units/FeralBoneRender.webp\|40]] | [[Gnoll Bone-Render]] | 1 | 50 | 1 | 52 / 30 | 0 / 30 | 48 | 8-13 slashing | Slash 2 · Pierce 1 · Blunt 2 | [[Rending Chop (Ability)\|Rending Chop]] |
| ![[_assets/Units/FeralBrute.webp\|40]] | [[Gnoll Brute]] | 1 | 70 | 2 | 48 / 30 | 0 / 30 | 39 | 8-16 blunt | Slash 2 · Pierce 1 · Blunt 2 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/FeralHexTouched.webp\|40]] | [[Gnoll Hex-Touched]] | 1 | 40 | 0 | 35 / 24 | 0 / 32 | 48 | 5-10 blunt | Slash 2 · Pierce 1 · Blunt 2 | [[Blood Bolt]], [[Life Drain]] |
| ![[_assets/Units/FeralStalker.webp\|40]] | [[Gnoll Stalker]] | 1 | 40 | 1 | 50 / 35 | 0 / 35 | 59 | 6-12 slashing | Slash 2 · Pierce 1 · Blunt 2 | [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| ![[_assets/Units/FeralAlpha.webp\|40]] | [[Gnoll Alpha]] | 2 | 106 | 7 | 75 / 55 | 0 / 45 | 56 | 14-22 slashing | Slash 2 · Pierce 1 · Blunt 2 | [[Howl]], [[Cleave (Ability)\|Cleave]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Leap]] | [[Gnoll Whelp]] | Empty hex, 2 hexes (no line of sight) | 0 | 12 | 2 turns | — | Spring up to 2 hexes without triggering opportunity attacks — used to flank, vault past the front line at a backline target, or break free and retreat. Bounds up onto raised ground and clears low walls and obstacles in the path. |
| [[Blood Bolt]] | [[Gnoll Hex-Touched]] | Enemy, 4 hexes | 1 | 10 | 1 turn | — | Hurl a bolt of crystallized blood at an enemy. Costs 5% of your max HP to cast. *15-28 (ignores armor, costs 5% of max HP)* |
| [[Cleave (Ability)\|Cleave]] | [[Gnoll Brute]], [[Gnoll Alpha]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Life Drain]] | [[Gnoll Hex-Touched]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | [[Gnoll Stalker]] | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Rending Chop (Ability)\|Rending Chop]] | [[Gnoll Bone-Render]] | Adjacent enemy | 1 | 14 | 3 turns | — | A savage downward strike that tears flesh. Inflicts Bleeding: 5 damage per tick for 3 ticks. |
| [[Howl]] | [[Gnoll Alpha]] | Self, radius 3 around | 1 | 16 | — | 1 | A terrifying howl that reduces willpower of all enemies within 3 hexes by 15. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Bloodlust (Enemy Passive)\|Bloodlust]] | Always: [[Gnoll Savage]], [[Gnoll Bone-Render]], [[Gnoll Hex-Touched]] | +5 melee attack, +3 damage min, -5 willpower. Craves violence but panics when outmatched. |
| [[Desperate]] | Always: [[Gnoll Hurler]]<br>Possible bonus: [[Gnoll Hex-Touched]] | +5 melee attack, -5 melee defense, -10 willpower. Nothing left to lose. |
| [[Enrage]] | Always: [[Gnoll Brute]], [[Gnoll Alpha]] | +30% damage when below 50% HP. |
| [[Feral Speed]] | Always: [[Gnoll Stalker]], [[Gnoll Alpha]]<br>Possible bonus: [[Gnoll Savage]], [[Gnoll Whelp]] | +8 initiative from animal instincts. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Gnoll Brute]]<br>Possible bonus: [[Gnoll Alpha]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Pack Tactics (Enemy Passive)\|Pack Tactics]] | Always: [[Gnoll Whelp]]<br>Possible bonus: [[Gnoll Alpha]] | +10 hit chance when an ally is adjacent to the target. |
| [[Predatory Instinct]] | Always: [[Gnoll Stalker]]<br>Possible bonus: [[Gnoll Bone-Render]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Brutal Strength]] | Possible bonus: [[Gnoll Bone-Render]] | +2 damage always. First melee hit each turn deals +5 bonus damage. |
| [[Evasion]] | Possible bonus: [[Gnoll Whelp]], [[Gnoll Stalker]] | +6 effective defense from supernatural agility. |
| [[Fearless (Enemy Passive)\|Fearless]] | Possible bonus: [[Gnoll Alpha]] | Immune to morale checks and Shaken. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Gnoll Stalker]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Possible bonus: [[Gnoll Brute]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Gnoll Savage]]*, [[Gnoll Whelp]]*, [[Gnoll Bone-Render]]*, [[Gnoll Brute]]*, [[Gnoll Stalker]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Gnoll Hurler]]*, [[Gnoll Hex-Touched]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Gnoll Alpha]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

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
| [[Flurry (Ability)\|Flurry]] | Skirmisher (Elite+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Rally (Ability)\|Rally]] | Warlord (Champion+) | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+), Warlord (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Forest — Encounter]], [[Hills — Encounter]], [[Plains — Random Encounter]].

*Generated from `enemies/feral_outcasts.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
