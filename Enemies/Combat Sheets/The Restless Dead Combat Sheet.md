---
type: combat_sheet
aliases:
  - The Restless Dead abilities
  - The Restless Dead reference
tags:
  - combat-sheet
  - faction/undead
  - type/combat_sheet
source:
  - enemies/undead.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: The Restless Dead
faction_id: undead
level_min: 1
tier_max: 4
tier_min: 1
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for [[The Restless Dead]]: 8 unit types (tiers 1-4), from company level 1+. They fight as [[How Enemies Behave#Relentless|Relentless]] — fearless, charges without thought.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[The Restless Dead]].

![[_assets/Units/Necromancer.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Zombie.webp\|40]] | [[Zombie]] | 1 | 80 | 3 | 40 / 25 | 0 / 20 | 25 | 6-11 blunt | Slash 1 · Blunt 1 · Poison 30 · Shadow 15 | — |
| ![[_assets/Units/Ghoul.webp\|40]] | [[Ghoul]] | 2 | 73 | 6 | 72 / 47 | 0 / 40 | 57 | 12-20 slashing | Slash 1 · Blunt 1 · Poison 30 · Shadow 15 | [[Frenzy (Ability)\|Frenzy]] |
| ![[_assets/Units/SkeletonWarrior.webp\|40]] | [[Skeleton]] | 2 | 66 | 9 | 66 / 53 | 0 / 45 | 50 | 21-35 slashing | Slash 2 · Pierce 5 · Poison 40 · Shadow 15 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/SkeletonArcher.webp\|40]] | [[Skeleton Archer]] | 2 | 53 | 7 | 55 / 42 | 72 / 45 | 52 | 15-25 piercing, ranged | Slash 2 · Pierce 5 · Poison 40 · Shadow 15 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/CorpseHulk.webp\|40]] | [[Corpse Hulk]] | 3 | 187 | 16 | 77 / 46 | 0 / 38 | 25 | 21-34 blunt | Slash 1 · Blunt 21 · Poison 30 · Shadow 15 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/Revenant.webp\|40]] | [[Revenant]] | 3 | 144 | 14 | 83 / 63 | 0 / 55 | 50 | 35-56 slashing | Slash 22 · Pierce 14 · Blunt 9 · Poison 30 · Shadow 20 | [[Cleave (Ability)\|Cleave]], [[Life Drain]] |
| ![[_assets/Units/Necromancer.webp\|40]] | [[Necromancer]] | 4 | 116 | 7 | 60 / 50 | 90 / 64 | 58 | 31-51 blunt | Slash 4 · Pierce 2 · Blunt 4 | [[Life Drain]], [[Soul Rend (Ability)\|Soul Rend]], [[Mend (Ability)\|Mend]] |
| ![[_assets/Units/Wight.webp\|40]] | [[Wight]] | 4 | 140 | 17 | 96 / 74 | 0 / 66 | 54 | 41-70 slashing | Slash 28 · Pierce 18 · Blunt 12 · Poison 30 · Shadow 30 | [[Life Drain]], [[Cleave (Ability)\|Cleave]], [[Second Wind (Ability)\|Second Wind]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Skeleton Archer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Frenzy (Ability)\|Frenzy]] | [[Ghoul]] | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Skeleton]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Cleave (Ability)\|Cleave]] | [[Corpse Hulk]], [[Revenant]], [[Wight]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Ground Slam]] | [[Corpse Hulk]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Life Drain]] | [[Revenant]], [[Necromancer]], [[Wight]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Mend (Ability)\|Mend]] | [[Necromancer]] | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Second Wind (Ability)\|Second Wind]] | [[Wight]] | Self | 2 | 12 | — | 1 | Dig deep and recover HP through sheer willpower. Costs 2 AP, 1 use per battle. *(only on an injured target)* |
| [[Soul Rend (Ability)\|Soul Rend]] | [[Necromancer]] | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Bone Armor (Enemy Passive)\|Bone Armor]] | Always: [[Skeleton]], [[Skeleton Archer]] | 50% resistance to piercing, 15% to slashing. 25% vulnerable to blunt. |
| [[Dark Blessing]] | Always: [[Necromancer]]<br>Possible bonus: [[Wight]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Drain Life]] | Always: [[Wight]]<br>Possible bonus: [[Ghoul]] | Heals 3 HP on each successful melee hit. |
| [[Enrage]] | Always: [[Revenant]]<br>Possible bonus: [[Ghoul]] | +30% damage when below 50% HP. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Zombie]], [[Corpse Hulk]], [[Revenant]], [[Wight]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Ghoul]] | +8 initiative from animal instincts. |
| [[Massive Frame]] | Always: [[Corpse Hulk]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Tireless (Enemy Passive)\|Tireless]] | Always: [[Zombie]], [[Ghoul]], [[Skeleton]], [[Skeleton Archer]], [[Corpse Hulk]], [[Revenant]], [[Necromancer]], [[Wight]] | Never tires in battle. Attacks and abilities cost no fatigue; only moving tires it. |
| [[Undead Resilience]] | Always: [[Zombie]], [[Ghoul]], [[Skeleton]], [[Skeleton Archer]], [[Corpse Hulk]], [[Revenant]], [[Necromancer]], [[Wight]] | Immune to poison and Bleeding. |
| [[Death Throes]] | Possible bonus: [[Zombie]], [[Corpse Hulk]] | Explodes on death, dealing 10 damage to all adjacent units. |
| [[Formation Bonus]] | Possible bonus: [[Skeleton]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Corpse Hulk]], [[Revenant]], [[Wight]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Last Stand (Enemy Passive)\|Last Stand]] | Possible bonus: [[Revenant]] | +15 melee attack, +20 willpower when below 25% HP. |
| [[Magic Resistance]] | Possible bonus: [[Necromancer]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Regeneration]] | Possible bonus: [[Zombie]], [[Corpse Hulk]], [[Revenant]] | Heals 5 HP at the start of each turn. |
| [[Shadowcloak]] | Possible bonus: [[Necromancer]] | +3 ranged def always. +10 bonus at range 4+, +5 at range 2-3, +0 adjacent. Close the distance! |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Skeleton]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Possible bonus: [[Skeleton Archer]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Terrifying]] | Possible bonus: [[Wight]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Zombie]]*, [[Ghoul]]*, [[Skeleton]]*, [[Corpse Hulk]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Skeleton Archer]]*, [[Necromancer]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warcaster]] | [[Revenant]]* | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]], [[Earthquake]] |
| [[Zealot (Variant)\|Zealot]] | [[Wight]]* | [[Minor Heal]], [[Smite Undead]] | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | [[Martyr's Grace (Ability)\|Martyr's Grace]], [[Bloom of Life (Ability)\|Bloom of Life]] |

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
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Fireball (Ability)\|Fireball]] | Warcaster (Champion+) | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
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
| [[Smite Undead]] | Zealot (Elite+) | Enemy, 3 hexes | 1 | 22 | 2 turns | — | Call down holy wrath on a foe. Deals triple damage against undead enemies. *20-35 (3x vs undead)* |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Stone Shards]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Sunburst (Ability)\|Sunburst]] | Zealot (Champion+) | Enemy, 4 hexes | 1 | 22 | 2 turns | — | A radiant lance of sunfire scours the target. Deals holy damage scaled by willpower; +50% damage vs demons and undead. *10-16 holy (+50% vs demons/undead)* |
| [[Telekinetic Crush]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 24 | 3 turns | — | Slam an enemy with a wall of psionic force. Deals 20-30 force damage (scaled by spell power) and roots them in place. *20-30 force (+ root, scales with Magic Power)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Ruins — Early]], [[Mid-depth Dark Ruins Encounter]], [[Ruins Base Garrison — Shallow]], [[Ruins — Mid Tier]], [[Deep Dark Ruins Encounter]], [[Ruins — Late Tier]].

*Generated from `enemies/undead.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
