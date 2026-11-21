---
type: combat_sheet
aliases:
  - Greenskin Warband abilities
  - Greenskin Warband reference
tags:
  - combat-sheet
  - faction/greenskins
  - type/combat_sheet
source:
  - enemies/greenskins.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Greenskin Warband
faction_id: greenskins
level_min: 1
tier_max: 4
tier_min: 1
units: 10
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Greenskin Warband]]: 10 unit types (tiers 1-4), from company level 1+. They fight as [[How Enemies Behave#Undisciplined|Undisciplined]] — unpredictable, low coordination.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Greenskin Warband]].

![[_assets/Units/EnemyOrcAxeman.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/EnemyGoblinArcher.webp\|40]] | [[Goblin Poisoner]] | 1 | 28 | 0 | 30 / 25 | 52 / 30 | 61 | 4-9 piercing, ranged | — | — |
| ![[_assets/Units/GoblinShaman.webp\|40]] | [[Goblin Shaman (Enemy)\|Goblin Shaman]] | 1 | 44 | 0 | 30 / 22 | 50 / 40 | 52 | 13-23 blunt | Slash 2 · Pierce 1 · Blunt 2 | [[Magic Missile]], [[Minor Heal]] |
| ![[_assets/Units/EnemyGoblin.webp\|40]] | [[Goblin Skirmisher]] | 1 | 35 | 1 | 52 / 28 | 0 / 27 | 60 | 10-19 slashing | — | — |
| ![[_assets/Units/EnemyOrcAxeman.webp\|40]] | [[Orc Grunt]] | 1 | 75 | 3 | 58 / 38 | 0 / 35 | 49 | 11-18 slashing | Slash 4 · Pierce 4 · Blunt 5 | — |
| ![[_assets/Units/GoblinWolfrider.webp\|40]] | [[Goblin Wolfrider]] | 2 | 73 | 5 | 73 / 47 | 0 / 40 | 64 | 17-26 slashing | Slash 6 · Pierce 5 · Blunt 7 | [[Opportunist Strike (Ability)\|Opportunist Strike]] |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Orc Brute]] | 2 | 119 | 10 | 77 / 58 | 0 / 45 | 51 | 18-30 slashing | Slash 6 · Pierce 5 · Blunt 7 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Ogre]] | 3 | 207 | 7 | 69 / 41 | 0 / 30 | 46 | 29-49 blunt | Slash 1 · Blunt 1 | [[Toss 'Em]] |
| ![[_assets/Units/OrcShaman.webp\|40]] | [[Orc Shaman]] | 3 | 94 | 8 | 60 / 52 | 85 / 60 | 48 | 27-43 blunt | Slash 3 · Pierce 2 · Blunt 3 | [[Minor Heal]] |
| ![[_assets/Units/OrcBrute.webp\|40]] | [[Ogre Crusher]] | 4 | 276 | 11 | 79 / 55 | 0 / 38 | 50 | 43-69 blunt | Slash 22 · Pierce 14 · Blunt 9 | [[Toss 'Em]] |
| ![[_assets/Units/EnemyOrcAxeman.webp\|40]] | [[Orc Warchief]] | 4 | 172 | 16 | 102 / 84 | 0 / 66 | 55 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[War Horn]], [[Cleave (Ability)\|Cleave]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Magic Missile]] | [[Goblin Shaman (Enemy)\|Goblin Shaman]] | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Minor Heal]] | [[Goblin Shaman (Enemy)\|Goblin Shaman]], [[Orc Shaman]] | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Cleave (Ability)\|Cleave]] | [[Orc Brute]], [[Orc Warchief]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | [[Goblin Wolfrider]] | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Toss 'Em]] | [[Ogre]], [[Ogre Crusher]] | Adjacent ally | 1 | 18 | 2 turns | — | Grab an adjacent small unit — friend or foe — and hurl it up to 4 tiles to an empty space, dealing 5-10 impact damage (reduced by armor). A grabbed ally is lobbed at the enemy's softest line; a grabbed foe is flung clear to break a swarm. Provokes no opportunity attacks. *5-10 impact (armor-reduced)* |
| [[War Horn]] | [[Orc Warchief]] | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Dark Blessing]] | Always: [[Orc Shaman]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Ogre Crusher]], [[Orc Warchief]]<br>Possible bonus: [[Ogre]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Goblin Wolfrider]]<br>Possible bonus: [[Goblin Shaman (Enemy)\|Goblin Shaman]], [[Goblin Skirmisher]] | +8 initiative from animal instincts. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Orc Grunt]], [[Orc Brute]], [[Ogre]], [[Ogre Crusher]], [[Orc Warchief]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Orc Warchief]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Nimble (Enemy Passive)\|Nimble]] | Always: [[Goblin Shaman (Enemy)\|Goblin Shaman]], [[Goblin Skirmisher]]<br>Possible bonus: [[Goblin Poisoner]], [[Goblin Wolfrider]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Pack Tactics (Enemy Passive)\|Pack Tactics]] | Always: [[Goblin Wolfrider]] | +10 hit chance when an ally is adjacent to the target. |
| [[Thick Hide (Enemy Passive)\|Thick Hide]] | Always: [[Orc Brute]], [[Ogre]], [[Ogre Crusher]]<br>Possible bonus: [[Orc Grunt]] | +4 armor from tough, leathery skin. After taking 3 hits, the hide cracks and armor drops to +2. |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Goblin Poisoner]] | 30% chance to poison the target on hit. |
| [[Berserker Rage]] | Possible bonus: [[Orc Brute]], [[Ogre Crusher]], [[Orc Warchief]] | +10 melee attack, -8 melee defense. Offense over defense. |
| [[Enrage]] | Possible bonus: [[Orc Brute]], [[Ogre]], [[Ogre Crusher]], [[Orc Warchief]] | +30% damage when below 50% HP. |
| [[Fleet-Footed]] | Possible bonus: [[Goblin Skirmisher]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Intimidating Presence]] | Possible bonus: [[Orc Shaman]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Predatory Instinct]] | Possible bonus: [[Goblin Wolfrider]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Rallying Presence]] | Possible bonus: [[Orc Warchief]] | Adjacent allies gain +5 willpower on morale checks. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Goblin Skirmisher]]*, [[Orc Brute]]*, [[Ogre]]*, [[Ogre Crusher]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Goblin Poisoner]]*, [[Orc Grunt]]*, [[Goblin Wolfrider]]*, [[Orc Shaman]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Zealot (Variant)\|Zealot]] | [[Goblin Shaman (Enemy)\|Goblin Shaman]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |
| [[Warlord (Variant)\|Warlord]] | [[Orc Warchief]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

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
| [[Rally (Ability)\|Rally]] | Warlord (Champion+) | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+), Warlord (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Smite Undead]] | Zealot (Elite+) | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Arch-villains

**[[Gorthak the Beast King]]** — *Warchief of the Broken Tusk*. From company level 9 · 640 HP · 18 armor · damage 32-46 · resists Slash 20 · **Pierce -10** · Blunt 20

Escort: 1× [[Ogre Crusher]], 2× [[Ogre]], 2× [[Orc Shaman]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Cleave (Ability)\|Cleave]] | from the start | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Bull Rush (Ability)\|Bull Rush]] | from the start | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Skull Leap]] | from the start | Enemy + radius 1, 10 hexes | 1 | 15 | 3 turns | — | Jump up to 9 tiles to land beside a shooter, hurling back everyone around the landing. *18-28 + knockback around the landing* |
| [[Frenzy (Ability)\|Frenzy]] | below 50% HP | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Thunderclap (Ability)\|Thunderclap]] | below 50% HP | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Forest — Encounter]], [[Hills — Encounter]], [[Mountain — Encounter]], [[Plains — Random Encounter]], [[Shallow Cavern Encounter]], [[Shallow Mushroom Forest Encounter]], [[Shallow Stalagmite Field Encounter]], [[Shallow Tunnel Encounter]], [[Warlord's Citadel (Encounter Table)|Warlord's Citadel]], [[Hills Base Garrison — Shallow]], [[Forest — Mid Tier]], [[Hills — Mid Tier]], [[Mountain — Mid Tier]], [[Forest — Late Tier]], [[Plains — Late Tier]].

*Generated from `enemies/greenskins.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
