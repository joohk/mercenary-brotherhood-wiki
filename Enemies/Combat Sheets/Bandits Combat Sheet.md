---
type: combat_sheet
aliases:
  - Bandits abilities
  - Bandits reference
tags:
  - combat-sheet
  - faction/bandits
  - type/combat_sheet
source:
  - enemies/bandits.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Bandits
faction_id: bandits
level_min: 1
tier_max: 2
tier_min: 1
units: 7
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Bandits]]: 7 unit types (tiers 1-2), from company level 1+. They fight as [[How Enemies Behave#Undisciplined|Undisciplined]] — unpredictable, low coordination.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Bandits]].

![[_assets/Units/BanditCaptain.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/BanditCutthroat.webp\|40]] | [[Bandit Cutthroat]] | 1 | 62 | 3 | 72 / 50 | 0 / 49 | 60 | 15-25 slashing | Slash 4 · Pierce 4 · Blunt 5 | — |
| ![[_assets/Units/BanditArcher.webp\|40]] | [[Elf Bandit Archer]] | 1 | 48 | 1 | 35 / 36 | 72 / 50 | 62 | 13-21 piercing, ranged | Slash 4 · Pierce 4 · Blunt 5 | — |
| ![[_assets/Units/BanditHedgeWitch.webp\|40]] | [[Goblin Bandit Shaman]] | 1 | 46 | 0 | 28 / 30 | 0 / 46 | 58 | 10-19 slashing | Slash 1 · Blunt 1 | [[Minor Heal]], [[Curse (Ability)\|Curse]] |
| ![[_assets/Units/HalflingCutpurse.webp\|40]] | [[Halfling Cutpurse]] | 1 | 44 | 1 | 55 / 56 | 48 / 53 | 66 | 12-22 slashing | Slash 4 · Pierce 4 · Blunt 5 | [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| ![[_assets/Units/BanditRaider.webp\|40]] | [[Orc Bandit Raider]] | 1 | 88 | 6 | 66 / 40 | 0 / 38 | 44 | 13-22 slashing | Slash 4 · Pierce 4 · Blunt 5 | — |
| ![[_assets/Units/BanditRaider.webp\|40]] | [[Orc Thug]] | 1 | 98 | 6 | 61 / 35 | 0 / 38 | 50 | 14-24 slashing | Slash 4 · Pierce 4 · Blunt 5 | — |
| ![[_assets/Units/BanditCaptain.webp\|40]] | [[Bandit Captain]] | 2 | 125 | 11 | 82 / 64 | 0 / 56 | 56 | 16-28 slashing | Slash 10 · Pierce 19 · Blunt 14 | [[Shield Bash (Ability)\|Shield Bash]], [[Rally (Ability)\|Rally]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Curse (Ability)\|Curse]] | [[Goblin Bandit Shaman]] | Enemy, 4 hexes | 1 | 12 | 3 turns | — | Hex an enemy with dark power, reducing their attack stats for 3 turns. |
| [[Minor Heal]] | [[Goblin Bandit Shaman]] | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | [[Halfling Cutpurse]] | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Rally (Ability)\|Rally]] | [[Bandit Captain]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Bandit Captain]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Bandit Captain]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Brutal Strength]] | Always: [[Orc Thug]] | +2 damage always. First melee hit each turn deals +5 bonus damage. |
| [[Desperate]] | Always: [[Goblin Bandit Shaman]] | +5 melee attack, -5 melee defense, -10 willpower. Nothing left to lose. |
| [[Evasion]] | Always: [[Halfling Cutpurse]]<br>Possible bonus: [[Elf Bandit Archer]] | +6 effective defense from supernatural agility. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Bandit Cutthroat]], [[Orc Bandit Raider]]<br>Possible bonus: [[Bandit Cutthroat]], [[Orc Bandit Raider]], [[Bandit Captain]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Keen Senses]] | Always: [[Elf Bandit Archer]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Nimble (Enemy Passive)\|Nimble]] | Always: [[Halfling Cutpurse]]<br>Possible bonus: [[Elf Bandit Archer]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Rallying Presence]] | Always: [[Bandit Captain]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Always: [[Elf Bandit Archer]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Wiry (Enemy Passive)\|Wiry]] | Always: [[Goblin Bandit Shaman]] | +5 initiative, +4 melee defense. Lean and quick. |
| [[Fleet-Footed]] | Possible bonus: [[Halfling Cutpurse]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Possible bonus: [[Bandit Captain]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Bandit Captain]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Venomous (Enemy Passive)\|Venomous]] | Possible bonus: [[Goblin Bandit Shaman]] | 30% chance to poison the target on hit. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Bandit Cutthroat]]*, [[Halfling Cutpurse]]*, [[Orc Bandit Raider]]*, [[Orc Thug]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Elf Bandit Archer]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Zealot (Variant)\|Zealot]] | [[Goblin Bandit Shaman]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |
| [[Warlord (Variant)\|Warlord]] | [[Bandit Captain]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Arcane Shield (Ability)\|Arcane Shield]] | Zealot (Champion+) | Ally, 4 hexes (no line of sight) | 1 | 22 | — | — | Sustained: Conjure a shimmering barrier around yourself or an ally that absorbs damage before HP while you maintain concentration. Drains 5 fatigue/turn. *~27 barrier HP (sustained)* |
| [[Battle Cry (Ability)\|Battle Cry]] | Warlord (Elite+) | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Bloom of Life (Ability)\|Bloom of Life]] | Zealot (Boss) | Ally + radius 2, 4 hexes (no line of sight) | 2 | 22 | 4 turns | — | Burst a flower of healing light. Heals all allies in radius 2 for 14 HP each (scales with willpower and magic power). An ally carrying your healing over time also receives all of its remaining healing at once, plus 25%. *(only on an injured target)* *Heals 14 HP to allies in radius 2; harvests your healing over time (+25%)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Cleave (Ability)\|Cleave]] | Brute (Champion+), Warlord (Boss) | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Flurry (Ability)\|Flurry]] | Skirmisher (Elite+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Martyr's Grace (Ability)\|Martyr's Grace]] | Zealot (Boss) | Ally, 3 hexes | 1 | 15 | 3 turns | — | Take 50% of an ally's incoming damage this turn. Holy casters protect their flock. |
| [[Mend (Ability)\|Mend]] | Zealot (Champion+) | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Smite Undead]] | Zealot (Elite+) | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Where you meet them

Leads groups in: [[Forest — Encounter]], [[Plains — Random Encounter]], [[Ruins — Early]], [[Plains Base Garrison — Shallow]], [[Plains — Bandit Camp]], [[Road — Ambush]], [[Plains — Mid Tier]].

*Generated from `enemies/bandits.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
