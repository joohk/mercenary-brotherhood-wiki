---
type: combat_sheet
aliases:
  - Saurian Legions abilities
  - Saurian Legions reference
tags:
  - combat-sheet
  - faction/aurelian_legions
  - type/combat_sheet
source:
  - enemies/aurelian_legions.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Saurian Legions
faction_id: aurelian_legions
level_min: 5
tier_max: 5
tier_min: 1
units: 10
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Saurian Legions]]: 10 unit types (tiers 1-5), from company level 5+. They fight as [[How Enemies Behave#Disciplined|Disciplined]] — holds formation, coordinated.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Saurian Legions]].

![[_assets/Units/SlannWarlord.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/SkinkScreen.webp\|40]] | [[Skink Screen]] | 1 | 62 | 4 | 50 / 37 | 0 / 35 | 50 | 10-17 piercing | Slash 4 · Pierce 4 · Blunt 5 | [[Hold the Line (Ability)\|Hold the Line]] |
| ![[_assets/Units/SaurianWarrior.webp\|40]] | [[Saurian Legionary]] | 2 | 112 | 13 | 79 / 68 | 61 / 53 | 51 | 16-27 slashing | Slash 10 · Pierce 19 · Blunt 14 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/SkinkJavelineer.webp\|40]] | [[Skink Javelineer]] | 2 | 75 | 7 | 59 / 47 | 77 / 51 | 64 | 9-17 piercing, ranged | Slash 6 · Pierce 5 · Blunt 7 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/ColdOneRider.webp\|40]] | [[Cold One Rider]] | 3 | 136 | 15 | 98 / 69 | 0 / 63 | 71 | 24-36 piercing | Slash 22 · Pierce 14 · Blunt 9 | [[Gore Charge (Ability)\|Gore Charge]], [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| ![[_assets/Units/SalamanderHandler.webp\|40]] | [[Salamander Handler]] | 3 | 110 | 9 | 60 / 48 | 92 / 49 | 46 | 19-32 piercing, ranged | Slash 8 · Pierce 6 · Blunt 9 | [[Plague Bolt]], [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/SaurianEternityGuard.webp\|40]] | [[Saurian Eternity Guard]] | 3 | 144 | 17 | 99 / 80 | 0 / 69 | 62 | 32-48 slashing | Slash 22 · Pierce 14 · Blunt 9 | [[Shield Bash (Ability)\|Shield Bash]], [[Exploit Opening]] |
| ![[_assets/Units/SaurianTempleGuard.webp\|40]] | [[Saurian Temple Guard]] | 3 | 143 | 21 | 87 / 90 | 0 / 75 | 44 | 23-34 slashing | Slash 25 · Pierce 29 · Blunt 11 | [[Shield Formation]], [[Hold the Line (Ability)\|Hold the Line]] |
| ![[_assets/Units/SaurianOldblood.webp\|40]] | [[Saurian Oldblood]] | 4 | 170 | 19 | 109 / 91 | 0 / 80 | 65 | 39-62 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Shield Formation]], [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/Stegadon.webp\|40]] | [[Stegadon]] | 4 | 264 | 24 | 94 / 58 | 72 / 62 | 38 | 12-22 blunt | Slash 15 · Pierce 20 | [[Gore Charge (Ability)\|Gore Charge]], [[Ground Slam]], [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/SlannWarlord.webp\|40]] | [[Slann Warlord]] | 5 | 194 | 20 | 110 / 100 | 115 / 88 | 60 | 46-75 slashing | Slash 33 · Pierce 22 · Blunt 13 | [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Magic Missile]], [[Arcane Shield (Ability)\|Arcane Shield]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Hold the Line (Ability)\|Hold the Line]] | [[Skink Screen]], [[Saurian Temple Guard]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Flurry (Ability)\|Flurry]] | [[Skink Javelineer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Saurian Legionary]], [[Saurian Eternity Guard]], [[Saurian Oldblood]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Exploit Opening]] | [[Saurian Eternity Guard]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Gore Charge (Ability)\|Gore Charge]] | [[Cold One Rider]], [[Stegadon]] | Enemy, 3 hexes | 1 | 25 | — | 1 | Charge an enemy up to 3 hexes away, dealing 150% weapon damage, stunning them and knocking them back 2 hexes on hit. *150% weapon (+ stun, melee to-hit)* |
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | [[Cold One Rider]] | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Plague Bolt]] | [[Salamander Handler]] | Enemy, 4 hexes | 1 | 12 | 2 turns | — | Hurls a glob of concentrated pestilence that deals minor damage and poisons the target. *5-10 (+ poison)* |
| [[Shield Formation]] | [[Saurian Temple Guard]], [[Saurian Oldblood]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Form a defensive shield wall. You and the allies adjacent when you cast gain +8 melee def, +4 ranged def, -3 initiative while maintained, even if they move away. Drains 4 fatigue/turn. |
| [[Volley (Ability)\|Volley]] | [[Salamander Handler]], [[Stegadon]] | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[Ground Slam]] | [[Stegadon]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Arcane Shield (Ability)\|Arcane Shield]] | [[Slann Warlord]] | Ally, 4 hexes (no line of sight) | 1 | 22 | — | — | Sustained: Conjure a shimmering barrier around yourself or an ally that absorbs damage before HP while you maintain concentration. Drains 5 fatigue/turn. *~27 barrier HP (sustained)* |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Slann Warlord]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Magic Missile]] | [[Slann Warlord]] | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Rally (Ability)\|Rally]] | [[Slann Warlord]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Saurian Eternity Guard]]<br>Possible bonus: [[Slann Warlord]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Cold-Blooded]] | Always: [[Saurian Legionary]], [[Skink Javelineer]], [[Cold One Rider]], [[Salamander Handler]], [[Saurian Eternity Guard]], [[Saurian Temple Guard]], [[Saurian Oldblood]], [[Stegadon]], [[Slann Warlord]]<br>Possible bonus: [[Skink Screen]] | Immune to fear and Shaken. Bleeding damage reduced by 50%. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Saurian Legionary]], [[Saurian Eternity Guard]], [[Saurian Temple Guard]], [[Saurian Oldblood]], [[Slann Warlord]]<br>Possible bonus: [[Skink Screen]] | +5 melee defense, +5 willpower from professional training. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Slann Warlord]]<br>Possible bonus: [[Saurian Eternity Guard]], [[Saurian Oldblood]], [[Stegadon]] | Immune to morale checks and Shaken. |
| [[Fleet-Footed]] | Always: [[Skink Javelineer]]<br>Possible bonus: [[Cold One Rider]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Formation Bonus]] | Always: [[Skink Screen]], [[Saurian Legionary]], [[Saurian Temple Guard]]<br>Possible bonus: [[Salamander Handler]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Fortified (Enemy Passive)\|Fortified]] | Always: [[Salamander Handler]]<br>Possible bonus: [[Saurian Temple Guard]] | Takes 25% less damage from ranged attacks. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Saurian Eternity Guard]], [[Saurian Oldblood]], [[Slann Warlord]]<br>Possible bonus: [[Saurian Legionary]], [[Saurian Temple Guard]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Massive Frame]] | Always: [[Stegadon]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Precise Strikes (Enemy Passive)\|Precise Strikes]] | Always: [[Saurian Oldblood]] | +3 melee attack always. +6 bonus from front arc, +0 from flank/rear. Flank to avoid! |
| [[Predatory Instinct]] | Always: [[Cold One Rider]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Rallying Presence]] | Always: [[Slann Warlord]]<br>Possible bonus: [[Saurian Oldblood]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Reckless Charge]] | Always: [[Cold One Rider]] | +8 initiative, +5 melee attack, -6 melee defense. All-out aggression. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Always: [[Saurian Temple Guard]]<br>Possible bonus: [[Saurian Legionary]], [[Saurian Eternity Guard]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Terrifying]] | Always: [[Stegadon]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Always: [[Stegadon]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Salamander Handler]] | 30% chance to poison the target on hit. |
| [[Crushing Force]] | Possible bonus: [[Stegadon]] | +2 damage min always. +4 bonus vs targets with armor >= 6. Send light units! |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Cold One Rider]], [[Saurian Eternity Guard]], [[Saurian Oldblood]], [[Stegadon]], [[Slann Warlord]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Keen Senses]] | Possible bonus: [[Skink Javelineer]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Magic Resistance]] | Possible bonus: [[Slann Warlord]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Skink Javelineer]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Poison Cloud]] | Possible bonus: [[Salamander Handler]] | Adjacent enemies take 2 poison damage at the start of this unit's turn. |
| [[Stalwart]] | Possible bonus: [[Saurian Temple Guard]] | +10 willpower, +2 armor. Unyielding in the face of danger. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Skink Screen]]*, [[Saurian Legionary]]*, [[Cold One Rider]]*, [[Saurian Eternity Guard]]*, [[Saurian Temple Guard]]*, [[Saurian Oldblood]]*, [[Stegadon]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Skink Javelineer]]*, [[Salamander Handler]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Slann Warlord]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Cleave (Ability)\|Cleave]] | Brute (Champion+), Warlord (Boss) | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
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
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Arch-villains

**[[The Iron Tyrant]]** — *Imperator Ssethek*. From company level 10 · 560 HP · 26 armor · damage 26-36 · resists Slash 30 · Pierce 25 · **Blunt -10**

Escort: 1× [[Saurian Oldblood]], 2× [[Saurian Eternity Guard]], 2× [[Saurian Temple Guard]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Shield Bash (Ability)\|Shield Bash]] | from the start | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Bull Rush (Ability)\|Bull Rush]] | from the start | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Battle Cry (Ability)\|Battle Cry]] | from the start | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Testudo]] | from the start | Self, radius 1 around | 1 | 12 | 5 turns | — | You and the allies beside you lock shields for 2 turns: ranged damage, spells included, is halved, and movement falls by 1. |
| [[Hold the Line (Ability)\|Hold the Line]] | below 40% HP | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[War Horn]] | below 40% HP | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Road — Ambush]], [[Hills — Mid Tier]], [[Plains — Mid Tier]], [[Plains — Late Tier]].

*Generated from `enemies/aurelian_legions.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
