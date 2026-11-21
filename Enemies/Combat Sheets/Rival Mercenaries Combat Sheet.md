---
type: combat_sheet
aliases:
  - Rival Mercenaries abilities
  - Rival Mercenaries reference
tags:
  - combat-sheet
  - faction/mercenaries
  - type/combat_sheet
source:
  - enemies/mercenaries.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Rival Mercenaries
faction_id: mercenaries
level_min: 3
tier_max: 4
tier_min: 2
units: 7
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Rival Mercenaries]]: 7 unit types (tiers 2-4), from company level 3+. They fight as [[How Enemies Behave#Professional|Professional]] — skilled and pragmatic.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Rival Mercenaries]].

![[_assets/Units/MercenaryCaptain.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/MercenaryCrossbowman.webp\|40]] | [[Mercenary Crossbowman]] | 2 | 73 | 7 | 57 / 51 | 79 / 51 | 52 | 14-21 piercing, ranged | Slash 6 · Pierce 5 · Blunt 7 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/MercenaryMage.webp\|40]] | [[Mercenary Mage]] | 2 | 72 | 4 | 46 / 44 | 0 / 50 | 55 | 13-23 blunt | Slash 2 · Pierce 2 · Blunt 2 | [[Fireball (Ability)\|Fireball]], [[Minor Heal]] |
| ![[_assets/Units/Sellsword.webp\|40]] | [[Sellsword (Enemy)\|Sellsword]] | 2 | 99 | 9 | 75 / 62 | 0 / 51 | 56 | 16-27 slashing | Slash 8 · Pierce 17 · Blunt 9 | [[Exploit Opening]] |
| ![[_assets/Units/ShieldBearer.webp\|40]] | [[Shield Bearer]] | 2 | 112 | 12 | 68 / 73 | 0 / 62 | 47 | 15-25 slashing | Slash 19 · Pierce 20 · Blunt 17 | [[Shield Formation]], [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/MercenaryKnight.webp\|40]] | [[Mercenary Knight]] | 3 | 130 | 16 | 92 / 75 | 0 / 64 | 52 | 22-33 slashing | Slash 25 · Pierce 29 · Blunt 11 | [[Cleave (Ability)\|Cleave]], [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/Pikeman.webp\|40]] | [[Pikeman]] | 3 | 101 | 12 | 87 / 69 | 0 / 57 | 56 | 22-33 piercing | Slash 22 · Pierce 14 · Blunt 9 | [[Hold the Line (Ability)\|Hold the Line]], [[Exploit Opening]] |
| ![[_assets/Units/MercenaryCaptain.webp\|40]] | [[Mercenary Captain]] | 4 | 156 | 18 | 107 / 86 | 0 / 74 | 70 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Second Wind (Ability)\|Second Wind]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Exploit Opening]] | [[Sellsword (Enemy)\|Sellsword]], [[Pikeman]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fireball (Ability)\|Fireball]] | [[Mercenary Mage]] | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Flurry (Ability)\|Flurry]] | [[Mercenary Crossbowman]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Minor Heal]] | [[Mercenary Mage]] | Ally, 4 hexes (no line of sight) | 1 | 14 | 1 turn | — | Channel a small pulse of divine energy to mend an ally's wounds, or your own. *(only on an injured target)* *Heals 8 HP* |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Shield Bearer]], [[Mercenary Knight]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Shield Formation]] | [[Shield Bearer]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Form a defensive shield wall. You and the allies adjacent when you cast gain +8 melee def, +4 ranged def, -3 initiative while maintained, even if they move away. Drains 4 fatigue/turn. |
| [[Cleave (Ability)\|Cleave]] | [[Mercenary Knight]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Hold the Line (Ability)\|Hold the Line]] | [[Pikeman]] | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Mercenary Captain]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Rally (Ability)\|Rally]] | [[Mercenary Captain]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Second Wind (Ability)\|Second Wind]] | [[Mercenary Captain]] | Self | 2 | 12 | — | 1 | Dig deep and recover HP through sheer willpower. Costs 2 AP, 1 use per battle. *(only on an injured target)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Mercenary Knight]]<br>Possible bonus: [[Mercenary Mage]], [[Sellsword (Enemy)\|Sellsword]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Mercenary Mage]], [[Sellsword (Enemy)\|Sellsword]], [[Mercenary Knight]], [[Pikeman]], [[Mercenary Captain]] | +5 melee defense, +5 willpower from professional training. |
| [[Formation Bonus]] | Always: [[Shield Bearer]], [[Pikeman]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Mercenary Captain]]<br>Possible bonus: [[Shield Bearer]], [[Mercenary Knight]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Precise Strikes (Enemy Passive)\|Precise Strikes]] | Always: [[Mercenary Captain]]<br>Possible bonus: [[Sellsword (Enemy)\|Sellsword]], [[Pikeman]] | +3 melee attack always. +6 bonus from front arc, +0 from flank/rear. Flank to avoid! |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Always: [[Shield Bearer]]<br>Possible bonus: [[Mercenary Knight]], [[Pikeman]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Always: [[Mercenary Crossbowman]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Fearless (Enemy Passive)\|Fearless]] | Possible bonus: [[Mercenary Captain]] | Immune to morale checks and Shaken. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Mercenary Knight]], [[Mercenary Captain]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Keen Senses]] | Possible bonus: [[Mercenary Crossbowman]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Mercenary Crossbowman]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Rallying Presence]] | Possible bonus: [[Mercenary Captain]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Stalwart]] | Possible bonus: [[Shield Bearer]] | +10 willpower, +2 armor. Unyielding in the face of danger. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Sellsword (Enemy)\|Sellsword]]*, [[Shield Bearer]]*, [[Mercenary Knight]]*, [[Pikeman]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Mercenary Crossbowman]]*, [[Mercenary Mage]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Mercenary Captain]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

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
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Arch-villains

**[[Warlord Ash]]** — *The Oathbreaker*. From company level 9 · 480 HP · 20 armor · damage 26-36 · resists Slash 25 · Pierce 15

Escort: 1× [[Mercenary Captain]], 2× [[Mercenary Knight]], 2× [[Pikeman]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Rally (Ability)\|Rally]] | from the start | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Command (Ability)\|Command]] | from the start | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Cleave (Ability)\|Cleave]] | from the start | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Exploit Opening]] | below 50% HP | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Frenzy (Ability)\|Frenzy]] | below 50% HP | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | below 50% HP | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Plains — Random Encounter]], [[Plains Base Garrison — Shallow]], [[Plains — Mid Tier]], [[Plains — Late Tier]].

*Generated from `enemies/mercenaries.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
