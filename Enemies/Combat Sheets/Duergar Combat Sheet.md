---
type: combat_sheet
aliases:
  - Duergar abilities
  - Duergar reference
tags:
  - combat-sheet
  - faction/duergar
  - type/combat_sheet
source:
  - enemies/duergar.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Duergar
faction_id: duergar
level_min: 3
tier_max: 5
tier_min: 2
units: 11
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Duergar]]: 11 unit types (tiers 2-5), from company level 3+. They fight as [[How Enemies Behave#Disciplined|Disciplined]] — holds formation, coordinated.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Duergar]].

![[_assets/Units/DuergarLord.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/DuergarCrossbowman.webp\|40]] | [[Duergar Crossbowman]] | 2 | 79 | 8 | 53 / 47 | 75 / 42 | 56 | 13-21 piercing, ranged | Slash 17 · Pierce 8 · Blunt 14 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/DuergarSlaveSoldier.webp\|40]] | [[Duergar Slave Soldier]] | 2 | 92 | 9 | 68 / 55 | 0 / 45 | 52 | 15-25 blunt | Slash 17 · Pierce 8 · Blunt 14 | — |
| ![[_assets/Units/CopperGolem.webp\|40]] | [[Copper Golem]] | 3 | 300 | 21 | 80 / 48 | 0 / 44 | 34 | 47-69 blunt | Slash 30 · Pierce 35 · **Blunt -15** | [[Crushing Slam]] |
| ![[_assets/Units/DuergarDarkSmith.webp\|40]] | [[Duergar Dark Smith]] | 3 | 94 | 10 | 62 / 55 | 85 / 53 | 46 | 13-19 blunt | Slash 22 · Pierce 14 · Blunt 9 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/DuergarIronguard.webp\|40]] | [[Duergar Ironguard]] | 3 | 130 | 15 | 85 / 78 | 0 / 67 | 58 | 34-52 blunt | Slash 25 · Pierce 29 · Blunt 11 | [[Shield Formation]], [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/DuergarStonekeeper.webp\|40]] | [[Duergar Stonekeeper]] | 3 | 109 | 9 | 57 / 55 | 71 / 58 | 44 | 23-35 blunt | Slash 22 · Pierce 14 · Blunt 9 | [[Stone Shards]], [[Stoneskin (Ability)\|Stoneskin]], [[Tremor]] |
| ![[_assets/Units/DuergarTaskmaster.webp\|40]] | [[Duergar Taskmaster]] | 3 | 115 | 12 | 83 / 67 | 0 / 55 | 53 | 22-33 blunt | Slash 22 · Pierce 14 · Blunt 9 | [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/DuergarWarpriest.webp\|40]] | [[Duergar Warpriest]] | 4 | 156 | 17 | 100 / 84 | 0 / 72 | 58 | 41-64 blunt | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Mend (Ability)\|Mend]] |
| ![[_assets/Units/IronGolem.webp\|40]] | [[Iron Golem]] | 4 | 450 | 26 | 96 / 55 | 0 / 48 | 31 | 72-103 blunt | Slash 40 · Pierce 45 · **Blunt -15** | [[Sundering Sweep]] |
| ![[_assets/Units/DuergarLord.webp\|40]] | [[Duergar Lord]] | 5 | 195 | 20 | 112 / 96 | 0 / 81 | 65 | 52-78 blunt | Slash 33 · Pierce 22 · Blunt 13 | [[War Horn]], [[Shield Formation]], [[Second Wind (Ability)\|Second Wind]] |
| ![[_assets/Units/MithrilGolem.webp\|40]] | [[Mithril Golem]] | 5 | 600 | 32 | 112 / 62 | 0 / 55 | 30 | 102-140 blunt | Slash 60 · Pierce 50 · **Blunt -10** | [[Sundering Sweep]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Duergar Crossbowman]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Cleave (Ability)\|Cleave]] | [[Duergar Dark Smith]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Crushing Slam]] | [[Copper Golem]] | Adjacent enemy | 1 | 0 | 2 turns | — | A piston-driven hammer blow that smashes a single enemy for heavy damage and hurls them back 2 tiles. |
| [[Rally (Ability)\|Rally]] | [[Duergar Taskmaster]], [[Duergar Warpriest]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Duergar Ironguard]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Shield Formation]] | [[Duergar Ironguard]], [[Duergar Lord]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Form a defensive shield wall. You and the allies adjacent when you cast gain +8 melee def, +4 ranged def, -3 initiative while maintained, even if they move away. Drains 4 fatigue/turn. |
| [[Stone Shards]] | [[Duergar Stonekeeper]] | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Stoneskin (Ability)\|Stoneskin]] | [[Duergar Stonekeeper]] | Ally, 3 hexes (no line of sight) | 1 | 22 | — | — | Sustained: encase an ally in living stone. +4 armor and +10% physical resistance while you hold it. Drains 5 fatigue/turn. |
| [[Tremor]] | [[Duergar Stonekeeper]] | Self, radius 2 around | 1 | 28 | 3 turns | — | Slam the ground. Every enemy within 2 takes 8-14 blunt damage and 1 Fracture, and has a 30% chance to be stunned. *8-14 blunt damage to enemies within 2, 1 Fracture each, 30% stun* |
| [[Mend (Ability)\|Mend]] | [[Duergar Warpriest]] | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Sundering Sweep]] | [[Iron Golem]], [[Mithril Golem]] | Area (radius 1), 1 hex | 1 | 0 | 3 turns | — | A wide arcing swing that batters every adjacent enemy for heavy damage and knocks them all back 2 tiles. |
| [[Second Wind (Ability)\|Second Wind]] | [[Duergar Lord]] | Self | 2 | 12 | — | 1 | Dig deep and recover HP through sheer willpower. Costs 2 AP, 1 use per battle. *(only on an injured target)* |
| [[War Horn]] | [[Duergar Lord]] | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Anchor the Line]] | Always: [[Duergar Slave Soldier]], [[Duergar Ironguard]], [[Duergar Taskmaster]], [[Duergar Warpriest]], [[Duergar Lord]] | Holds position rather than chasing. Ranged allies adjacent to this unit fire from inside the line — see Artillery Anchor. |
| [[Artillery Anchor]] | Always: [[Duergar Crossbowman]], [[Duergar Dark Smith]], [[Duergar Stonekeeper]] | +12 ranged attack and +5 ranged defense while adjacent to a Duergar ally with Anchor the Line. Fires safely from behind the shield wall. |
| [[Construct]] | Always: [[Copper Golem]], [[Iron Golem]], [[Mithril Golem]] | Metal and forge-sorcery, not flesh. Immune to Bleeding. |
| [[Dark Blessing]] | Always: [[Duergar Warpriest]]<br>Possible bonus: [[Duergar Lord]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Dark Iron Armor]] | Always: [[Copper Golem]], [[Duergar Dark Smith]], [[Duergar Ironguard]], [[Duergar Stonekeeper]], [[Duergar Warpriest]], [[Iron Golem]], [[Duergar Lord]], [[Mithril Golem]]<br>Possible bonus: [[Duergar Crossbowman]], [[Duergar Taskmaster]] | +3 armor, +5 melee defense. Fire and magic attacks ignore 2 armor and corrode -1 armor per hit. Corrodes: -1 armor every 3 turns. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Copper Golem]], [[Iron Golem]], [[Duergar Lord]], [[Mithril Golem]]<br>Possible bonus: [[Duergar Warpriest]] | Immune to morale checks and Shaken. |
| [[Fire Aura]] | Always: [[Duergar Dark Smith]] | 25% chance to burn melee attackers. |
| [[Formation Bonus]] | Always: [[Duergar Slave Soldier]], [[Duergar Ironguard]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Intimidating Presence]] | Always: [[Duergar Taskmaster]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Duergar Taskmaster]], [[Duergar Lord]]<br>Possible bonus: [[Copper Golem]], [[Duergar Ironguard]], [[Duergar Stonekeeper]], [[Duergar Warpriest]], [[Iron Golem]], [[Mithril Golem]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Rallying Presence]] | Always: [[Duergar Lord]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Slave-Driven]] | Always: [[Duergar Slave Soldier]] | -10 willpower, +5 melee attack. The taskmaster's whip hurts more than the enemy. |
| [[Stalwart]] | Always: [[Copper Golem]], [[Duergar Stonekeeper]], [[Duergar Warpriest]], [[Iron Golem]], [[Mithril Golem]]<br>Possible bonus: [[Duergar Ironguard]] | +10 willpower, +2 armor. Unyielding in the face of danger. |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Always: [[Duergar Crossbowman]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Thorns]] | Always: [[Mithril Golem]]<br>Possible bonus: [[Duergar Dark Smith]] | Melee attackers take 3 damage on hit. |
| [[Tireless (Enemy Passive)\|Tireless]] | Always: [[Copper Golem]], [[Iron Golem]], [[Mithril Golem]] | Never tires in battle. Attacks and abilities cost no fatigue; only moving tires it. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Possible bonus: [[Duergar Slave Soldier]] | +5 melee defense, +5 willpower from professional training. |
| [[Enrage]] | Possible bonus: [[Duergar Dark Smith]] | +30% damage when below 50% HP. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Duergar Dark Smith]], [[Duergar Taskmaster]], [[Duergar Warpriest]], [[Iron Golem]], [[Duergar Lord]], [[Mithril Golem]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Duergar Ironguard]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Terrifying]] | Possible bonus: [[Duergar Lord]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Duergar Slave Soldier]]*, [[Copper Golem]]*, [[Duergar Ironguard]]*, [[Iron Golem]]*, [[Mithril Golem]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Duergar Crossbowman]]*, [[Duergar Dark Smith]]*, [[Duergar Stonekeeper]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Zealot (Variant)\|Zealot]] | [[Duergar Warpriest]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |
| [[Warlord (Variant)\|Warlord]] | [[Duergar Taskmaster]], [[Duergar Lord]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

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
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Martyr's Grace (Ability)\|Martyr's Grace]] | Zealot (Boss) | Ally, 3 hexes | 1 | 15 | 3 turns | — | Take 50% of an ally's incoming damage this turn. Holy casters protect their flock. |
| [[Minor Heal]] | Zealot (Elite+) | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Smite Undead]] | Zealot (Elite+) | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Where you meet them

Leads groups in: [[Hills — Encounter]], [[Mountain — Encounter]], [[Mid-depth Crystal Cave Encounter]], [[Mid-depth Dark Ruins Encounter]], [[Mid-depth Tunnel Encounter]], [[Mid-depth Cavern Encounter]], [[Mid-depth Mushroom Forest Encounter]], [[Mid-depth Stalagmite Encounter]], [[Mountains — Duergar Raid]], [[Deep Cavern Encounter]].

*Generated from `enemies/duergar.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
