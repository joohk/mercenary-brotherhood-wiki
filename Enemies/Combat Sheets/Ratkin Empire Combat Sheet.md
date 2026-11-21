---
type: combat_sheet
aliases:
  - Ratkin Empire abilities
  - Ratkin Empire reference
tags:
  - combat-sheet
  - faction/eastern_empire
  - type/combat_sheet
source:
  - enemies/eastern_empire.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Ratkin Empire
faction_id: eastern_empire
level_min: 3
tier_max: 5
tier_min: 1
units: 11
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Ratkin Empire]]: 11 unit types (tiers 1-5), from company level 3+. They fight as [[How Enemies Behave#Disciplined|Disciplined]] — holds formation, coordinated.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Ratkin Empire]].

![[_assets/Units/Daimyo.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/AshigaruSpearman.webp\|40]] | [[Ratkin Ashigaru]] | 1 | 52 | 3 | 52 / 39 | 0 / 37 | 54 | 10-17 piercing | Slash 4 · Pierce 4 · Blunt 5 | [[Hold the Line (Ability)\|Hold the Line]] |
| ![[_assets/Units/AshigaruArcher.webp\|40]] | [[Ratkin Bowman]] | 1 | 42 | 1 | 32 / 32 | 60 / 40 | 56 | 10-16 piercing, ranged | Slash 1 · Pierce 1 · Blunt 4 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/AshigaruSergeant.webp\|40]] | [[Ratkin Ashigaru-Kashira]] | 2 | 88 | 9 | 77 / 64 | 0 / 53 | 63 | 15-25 slashing | Slash 8 · Pierce 7 · Blunt 12 | [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/AshigaruGunner.webp\|40]] | [[Ratkin Tanegashima Gunner]] | 2 | 59 | 6 | 44 / 42 | 81 / 47 | 52 | 12-21 piercing, ranged | Slash 6 · Pierce 5 · Blunt 7 | [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/Ronin.webp\|40]] | [[Ratkin Ronin]] | 3 | 103 | 10 | 97 / 70 | 0 / 59 | 77 | 24-35 slashing | Slash 8 · Pierce 6 · Blunt 9 | [[Frenzy (Ability)\|Frenzy]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/Samurai.webp\|40]] | [[Ratkin Samurai]] | 3 | 110 | 13 | 94 / 72 | 0 / 62 | 74 | 23-34 slashing | Slash 10 · Pierce 8 · Blunt 15 | [[Exploit Opening]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/Shinobi.webp\|40]] | [[Ratkin Shinobi]] | 3 | 71 | 7 | 91 / 63 | 79 / 58 | 83 | 22-35 slashing | Slash 3 · Pierce 3 · Blunt 3 | [[Shadow Step (Ability)\|Shadow Step]], [[Exploit Opening]] |
| ![[_assets/Units/SamuraiArcher.webp\|40]] | [[Ratkin Yabusame]] | 3 | 92 | 10 | 74 / 62 | 99 / 63 | 69 | 12-21 piercing, ranged | Slash 8 · Pierce 6 · Blunt 9 | [[Flurry (Ability)\|Flurry]], [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/Hatamoto.webp\|40]] | [[Ratkin Hatamoto]] | 4 | 140 | 17 | 110 / 84 | 0 / 72 | 79 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Exploit Opening]], [[Battle Cry (Ability)\|Battle Cry]] |
| ![[_assets/Units/WarriorMonk.webp\|40]] | [[Ratkin Sohei]] | 4 | 126 | 12 | 102 / 75 | 0 / 66 | 76 | 27-44 piercing | Slash 12 · Pierce 11 · Blunt 18 | [[Frenzy (Ability)\|Frenzy]], [[Second Wind (Ability)\|Second Wind]] |
| ![[_assets/Units/Daimyo.webp\|40]] | [[Ratkin Daimyo]] | 5 | 169 | 20 | 119 / 90 | 0 / 78 | 80 | 46-75 slashing | Slash 33 · Pierce 22 · Blunt 13 | [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Exploit Opening]], [[War Horn]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Ratkin Bowman]], [[Ratkin Yabusame]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Hold the Line (Ability)\|Hold the Line]] | [[Ratkin Ashigaru]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Rally (Ability)\|Rally]] | [[Ratkin Ashigaru-Kashira]], [[Ratkin Hatamoto]], [[Ratkin Daimyo]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Volley (Ability)\|Volley]] | [[Ratkin Tanegashima Gunner]], [[Ratkin Yabusame]] | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[Cleave (Ability)\|Cleave]] | [[Ratkin Ronin]], [[Ratkin Samurai]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Exploit Opening]] | [[Ratkin Samurai]], [[Ratkin Shinobi]], [[Ratkin Hatamoto]], [[Ratkin Daimyo]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Frenzy (Ability)\|Frenzy]] | [[Ratkin Ronin]], [[Ratkin Sohei]] | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Shadow Step (Ability)\|Shadow Step]] | [[Ratkin Shinobi]] | Empty hex, 3 hexes (no line of sight) | 0 | 16 | 2 turns | 2 | Vanish into shadow and reappear up to 3 hexes away. Cannot be used if rooted. Free action. |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Ratkin Hatamoto]], [[Ratkin Daimyo]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Second Wind (Ability)\|Second Wind]] | [[Ratkin Sohei]] | Self | 2 | 12 | — | 1 | Dig deep and recover HP through sheer willpower. Costs 2 AP, 1 use per battle. *(only on an injured target)* |
| [[War Horn]] | [[Ratkin Daimyo]] | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Ambush]] | Always: [[Ratkin Shinobi]] | +15 melee attack on first attack of combat. |
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Ratkin Sohei]]<br>Possible bonus: [[Ratkin Daimyo]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Ratkin Ashigaru-Kashira]]<br>Possible bonus: [[Ratkin Ashigaru]] | +5 melee defense, +5 willpower from professional training. |
| [[Disciplined March]] | Always: [[Ratkin Ashigaru]], [[Ratkin Ashigaru-Kashira]], [[Ratkin Samurai]], [[Ratkin Hatamoto]], [[Ratkin Sohei]] | At turn start, if 2+ allies with this passive are adjacent, gain +1 AP for this turn — the line shifts in unison. Lost when isolated from the column. |
| [[Evasion]] | Always: [[Ratkin Ronin]], [[Ratkin Shinobi]]<br>Possible bonus: [[Ratkin Samurai]], [[Ratkin Hatamoto]] | +6 effective defense from supernatural agility. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Ratkin Sohei]], [[Ratkin Daimyo]]<br>Possible bonus: [[Ratkin Samurai]], [[Ratkin Hatamoto]] | Immune to morale checks and Shaken. |
| [[Formation Bonus]] | Always: [[Ratkin Ashigaru]], [[Ratkin Ashigaru-Kashira]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Ratkin Hatamoto]]<br>Possible bonus: [[Ratkin Ronin]], [[Ratkin Samurai]], [[Ratkin Sohei]], [[Ratkin Daimyo]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Ratkin Samurai]], [[Ratkin Yabusame]], [[Ratkin Hatamoto]], [[Ratkin Sohei]], [[Ratkin Daimyo]]<br>Possible bonus: [[Ratkin Ashigaru-Kashira]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Keen Senses]] | Always: [[Ratkin Bowman]]<br>Possible bonus: [[Ratkin Yabusame]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Precise Strikes (Enemy Passive)\|Precise Strikes]] | Always: [[Ratkin Ronin]], [[Ratkin Samurai]], [[Ratkin Hatamoto]], [[Ratkin Daimyo]] | +3 melee attack always. +6 bonus from front arc, +0 from flank/rear. Flank to avoid! |
| [[Rallying Presence]] | Always: [[Ratkin Daimyo]]<br>Possible bonus: [[Ratkin Hatamoto]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Shadowy]] | Always: [[Ratkin Shinobi]] | 20% miss chance for ranged attacks from beyond 5 hexes. |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Always: [[Ratkin Tanegashima Gunner]], [[Ratkin Yabusame]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Berserker Rage]] | Possible bonus: [[Ratkin Ronin]] | +10 melee attack, -8 melee defense. Offense over defense. |
| [[Enrage]] | Possible bonus: [[Ratkin Ronin]] | +30% damage when below 50% HP. |
| [[Fleet-Footed]] | Possible bonus: [[Ratkin Shinobi]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Fortified (Enemy Passive)\|Fortified]] | Possible bonus: [[Ratkin Tanegashima Gunner]] | Takes 25% less damage from ranged attacks. |
| [[Last Stand (Enemy Passive)\|Last Stand]] | Possible bonus: [[Ratkin Sohei]] | +15 melee attack, +20 willpower when below 25% HP. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Ratkin Bowman]], [[Ratkin Shinobi]], [[Ratkin Yabusame]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Venomous (Enemy Passive)\|Venomous]] | Possible bonus: [[Ratkin Shinobi]] | 30% chance to poison the target on hit. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Ratkin Ashigaru]]*, [[Ratkin Ronin]]*, [[Ratkin Samurai]]*, [[Ratkin Shinobi]]*, [[Ratkin Hatamoto]]*, [[Ratkin Daimyo]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Ratkin Bowman]]*, [[Ratkin Tanegashima Gunner]]*, [[Ratkin Yabusame]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Zealot (Variant)\|Zealot]] | [[Ratkin Sohei]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |
| [[Warlord (Variant)\|Warlord]] | [[Ratkin Ashigaru-Kashira]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Arcane Shield (Ability)\|Arcane Shield]] | Zealot (Champion+) | Ally, 4 hexes (no line of sight) | 1 | 22 | — | — | Sustained: Conjure a shimmering barrier around yourself or an ally that absorbs damage before HP while you maintain concentration. Drains 5 fatigue/turn. *~27 barrier HP (sustained)* |
| [[Bloom of Life (Ability)\|Bloom of Life]] | Zealot (Boss) | Ally + radius 2, 4 hexes (no line of sight) | 2 | 22 | 4 turns | — | Burst a flower of healing light. Heals all allies in radius 2 for 14 HP each (scales with willpower and magic power). An ally carrying your healing over time also receives all of its remaining healing at once, plus 25%. *(only on an injured target)* *Heals 14 HP to allies in radius 2; harvests your healing over time (+25%)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Martyr's Grace (Ability)\|Martyr's Grace]] | Zealot (Boss) | Ally, 3 hexes | 1 | 15 | 3 turns | — | Take 50% of an ally's incoming damage this turn. Holy casters protect their flock. |
| [[Mend (Ability)\|Mend]] | Zealot (Champion+) | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Minor Heal]] | Zealot (Elite+) | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+), Warlord (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Smite Undead]] | Zealot (Elite+) | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Plains — Eastern Empire Patrol]].

*Generated from `enemies/eastern_empire.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
