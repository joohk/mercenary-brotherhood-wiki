---
type: combat_sheet
aliases:
  - The Inquisition abilities
  - The Inquisition reference
tags:
  - combat-sheet
  - faction/inquisition
  - type/combat_sheet
source:
  - enemies/inquisition.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: The Inquisition
faction_id: inquisition
level_min: 5
tier_max: 5
tier_min: 1
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for [[The Inquisition]]: 8 unit types (tiers 1-5), from company level 5+. They fight as [[How Enemies Behave#Disciplined|Disciplined]] — holds formation, coordinated.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[The Inquisition]].

![[_assets/Units/GrandInquisitor.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Flagellant.webp\|40]] | [[Flagellant]] | 1 | 45 | 0 | 55 / 25 | 0 / 20 | 57 | 9-15 blunt | Slash 1 · Blunt 1 | [[Frenzy (Ability)\|Frenzy]] |
| ![[_assets/Units/Zealot.webp\|40]] | [[Zealot (Enemy)\|Zealot]] | 1 | 55 | 2 | 52 / 35 | 0 / 30 | 53 | 10-17 slashing | Slash 4 · Pierce 4 · Blunt 5 | [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/BattleCleric.webp\|40]] | [[Battle Cleric (Enemy)\|Battle Cleric]] | 2 | 92 | 9 | 72 / 58 | 0 / 51 | 50 | 15-25 slashing | Slash 8 · Pierce 7 · Blunt 12 | [[Mend (Ability)\|Mend]], [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/WitchFinder.webp\|40]] | [[Witch Finder]] | 2 | 73 | 7 | 55 / 47 | 79 / 51 | 55 | 16-26 piercing, ranged | Slash 8 · Pierce 7 · Blunt 11 | [[Exploit Opening]] |
| ![[_assets/Units/Purifier.webp\|40]] | [[Purifier]] | 3 | 79 | 8 | 57 / 48 | 89 / 53 | 52 | 10-19 blunt, ranged | Slash 1 · Blunt 1 | [[Fireball (Ability)\|Fireball]] |
| ![[_assets/Units/TemplarKnight.webp\|40]] | [[Templar Knight]] | 3 | 123 | 14 | 92 / 75 | 0 / 64 | 59 | 23-34 slashing | Slash 25 · Pierce 29 · Blunt 11 | [[Shield Bash (Ability)\|Shield Bash]], [[Exploit Opening]] |
| ![[_assets/Units/Paladin.webp\|40]] | [[Paladin (Enemy)\|Paladin]] | 4 | 156 | 17 | 104 / 89 | 0 / 78 | 67 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Shield Bash (Ability)\|Shield Bash]], [[Second Wind (Ability)\|Second Wind]] |
| ![[_assets/Units/GrandInquisitor.webp\|40]] | [[Grand Inquisitor]] | 5 | 179 | 19 | 114 / 96 | 0 / 85 | 70 | 52-78 blunt | Slash 33 · Pierce 22 · Blunt 13 | [[Fireball (Ability)\|Fireball]], [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Smite Undead]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Cleave (Ability)\|Cleave]] | [[Zealot (Enemy)\|Zealot]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Frenzy (Ability)\|Frenzy]] | [[Flagellant]] | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Exploit Opening]] | [[Witch Finder]], [[Templar Knight]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Mend (Ability)\|Mend]] | [[Battle Cleric (Enemy)\|Battle Cleric]] | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Battle Cleric (Enemy)\|Battle Cleric]], [[Templar Knight]], [[Paladin (Enemy)\|Paladin]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Fireball (Ability)\|Fireball]] | [[Purifier]], [[Grand Inquisitor]] | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Rally (Ability)\|Rally]] | [[Paladin (Enemy)\|Paladin]], [[Grand Inquisitor]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Second Wind (Ability)\|Second Wind]] | [[Paladin (Enemy)\|Paladin]] | Self | 2 | 12 | — | 1 | Dig deep and recover HP through sheer willpower. Costs 2 AP, 1 use per battle. *(only on an injured target)* |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Grand Inquisitor]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Smite Undead]] | [[Grand Inquisitor]] | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Templar Knight]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Bloodlust (Enemy Passive)\|Bloodlust]] | Always: [[Flagellant]] | +5 melee attack, +3 damage min, -5 willpower. Craves violence but panics when outmatched. |
| [[Fanatical Zeal]] | Always: [[Flagellant]], [[Purifier]], [[Grand Inquisitor]]<br>Possible bonus: [[Zealot (Enemy)\|Zealot]] | +20 willpower, -5 melee defense. Religious fervor overrides self-preservation. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Paladin (Enemy)\|Paladin]], [[Grand Inquisitor]]<br>Possible bonus: [[Purifier]], [[Templar Knight]] | Immune to morale checks and Shaken. |
| [[Fire Aura]] | Always: [[Purifier]], [[Grand Inquisitor]] | 25% chance to burn melee attackers. |
| [[Holy Fervor]] | Always: [[Zealot (Enemy)\|Zealot]], [[Battle Cleric (Enemy)\|Battle Cleric]], [[Witch Finder]], [[Templar Knight]], [[Paladin (Enemy)\|Paladin]] | +10 willpower, +3 melee attack, -3 ranged defense. Faith-driven aggression. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Paladin (Enemy)\|Paladin]]<br>Possible bonus: [[Templar Knight]], [[Grand Inquisitor]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Keen Senses]] | Always: [[Witch Finder]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Always: [[Templar Knight]]<br>Possible bonus: [[Battle Cleric (Enemy)\|Battle Cleric]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Stalwart]] | Always: [[Battle Cleric (Enemy)\|Battle Cleric]] | +10 willpower, +2 armor. Unyielding in the face of danger. |
| [[Terrifying]] | Always: [[Grand Inquisitor]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |
| [[Ambush]] | Possible bonus: [[Witch Finder]] | +15 melee attack on first attack of combat. |
| [[Berserker Rage]] | Possible bonus: [[Zealot (Enemy)\|Zealot]] | +10 melee attack, -8 melee defense. Offense over defense. |
| [[Dark Blessing]] | Possible bonus: [[Battle Cleric (Enemy)\|Battle Cleric]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Death Throes]] | Possible bonus: [[Purifier]] | Explodes on death, dealing 10 damage to all adjacent units. |
| [[Enrage]] | Possible bonus: [[Flagellant]], [[Purifier]] | +30% damage when below 50% HP. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Templar Knight]], [[Paladin (Enemy)\|Paladin]], [[Grand Inquisitor]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Last Stand (Enemy Passive)\|Last Stand]] | Possible bonus: [[Flagellant]] | +15 melee attack, +20 willpower when below 25% HP. |
| [[Magic Resistance]] | Possible bonus: [[Grand Inquisitor]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Witch Finder]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Rallying Presence]] | Possible bonus: [[Paladin (Enemy)\|Paladin]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Undying Will]] | Possible bonus: [[Paladin (Enemy)\|Paladin]] | The first time HP would reach 0, survive with 1 HP instead. Once per combat. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Flagellant]]*, [[Zealot (Enemy)\|Zealot]]*, [[Templar Knight]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Witch Finder]]*, [[Purifier]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warcaster]] | [[Grand Inquisitor]]* | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]], [[Earthquake]] |
| [[Zealot (Variant)\|Zealot]] | [[Battle Cleric (Enemy)\|Battle Cleric]]*, [[Paladin (Enemy)\|Paladin]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Arcane Shield (Ability)\|Arcane Shield]] | Zealot (Champion+) | Ally, 4 hexes (no line of sight) | 1 | 22 | — | — | Sustained: Conjure a shimmering barrier around yourself or an ally that absorbs damage before HP while you maintain concentration. Drains 5 fatigue/turn. *~27 barrier HP (sustained)* |
| [[Bloom of Life (Ability)\|Bloom of Life]] | Zealot (Boss) | Ally + radius 2, 4 hexes (no line of sight) | 2 | 22 | 4 turns | — | Burst a flower of healing light. Heals all allies in radius 2 for 14 HP each (scales with willpower and magic power). An ally carrying your healing over time also receives all of its remaining healing at once, plus 25%. *(only on an injured target)* *Heals 14 HP to allies in radius 2; harvests your healing over time (+25%)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Earthquake]] | Warcaster (Boss) | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |
| [[Eldritch Blast]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Flurry (Ability)\|Flurry]] | Skirmisher (Elite+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Ice Shard (Ability)\|Ice Shard]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | Warcaster (Champion+) | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Magic Missile]] | Warcaster (Elite+) | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Martyr's Grace (Ability)\|Martyr's Grace]] | Zealot (Boss) | Ally, 3 hexes | 1 | 15 | 3 turns | — | Take 50% of an ally's incoming damage this turn. Holy casters protect their flock. |
| [[Minor Heal]] | Zealot (Elite+) | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Plague Bolt]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 12 | 2 turns | — | Hurls a glob of concentrated pestilence that deals minor damage and poisons the target. *5-10 (+ poison)* |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Soul Rend (Ability)\|Soul Rend]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Stone Shards]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Telekinetic Crush]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 24 | 3 turns | — | Slam an enemy with a wall of psionic force. Deals 20-30 force damage (scaled by spell power) and roots them in place. *20-30 force (+ root, scales with Magic Power)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Forest — Mid Tier]], [[Plains — Mid Tier]], [[Ruins — Mid Tier]], [[Forest — Late Tier]], [[Plains — Late Tier]].

*Generated from `enemies/inquisition.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
