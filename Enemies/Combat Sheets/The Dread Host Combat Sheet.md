---
type: combat_sheet
aliases:
  - The Dread Host abilities
  - The Dread Host reference
tags:
  - combat-sheet
  - faction/dread_host
  - type/combat_sheet
source:
  - enemies/dread_host.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: The Dread Host
faction_id: dread_host
level_min: 5
tier_max: 5
tier_min: 1
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for [[The Dread Host]]: 8 unit types (tiers 1-5), from company level 5+. They fight as [[How Enemies Behave#Relentless|Relentless]] — fearless, charges without thought.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[The Dread Host]].

![[_assets/Units/LichCommander.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/DreadThrall.webp\|40]] | [[Dread Thrall]] | 1 | 55 | 2 | 45 / 28 | 0 / 22 | 30 | 6-10 blunt | Slash 1 · Blunt 1 · Poison 30 · Shadow 20 | — |
| ![[_assets/Units/DarkSoldier.webp\|40]] | [[Dark Soldier]] | 2 | 106 | 11 | 77 / 64 | 0 / 53 | 52 | 15-25 slashing | Slash 8 · Pierce 7 · Blunt 12 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/DreadArcher.webp\|40]] | [[Dread Archer]] | 2 | 59 | 4 | 46 / 36 | 75 / 37 | 38 | 20-33 piercing, ranged | Slash 1 · Blunt 1 · Poison 30 · Shadow 20 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/DreadKnight.webp\|40]] | [[Dread Knight]] | 3 | 137 | 16 | 94 / 80 | 0 / 69 | 61 | 31-46 slashing | Slash 22 · Pierce 14 · Blunt 9 · Poison 25 · Shadow 25 | [[Cleave (Ability)\|Cleave]], [[Life Drain]] |
| ![[_assets/Units/WarNecromancer.webp\|40]] | [[War Necromancer]] | 3 | 90 | 8 | 57 / 48 | 92 / 60 | 48 | 27-42 blunt | Slash 3 · Pierce 2 · Blunt 3 | [[Life Drain]], [[Soul Rend (Ability)\|Soul Rend]] |
| ![[_assets/Units/BoneColossus.webp\|40]] | [[Bone Colossus]] | 4 | 218 | 14 | 90 / 62 | 0 / 54 | 30 | 38-59 blunt | Poison 40 · Shadow 30 | [[Ground Slam]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/DarkGeneral.webp\|40]] | [[Dark General]] | 4 | 172 | 18 | 109 / 92 | 0 / 78 | 67 | 38-61 slashing | Slash 28 · Pierce 18 · Blunt 12 | [[Rally (Ability)\|Rally]], [[Battle Cry (Ability)\|Battle Cry]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/LichCommander.webp\|40]] | [[Lich Commander]] | 5 | 146 | 12 | 75 / 62 | 116 / 78 | 52 | 39-64 blunt | Slash 4 · Pierce 3 · Blunt 4 · Cold 20 · Poison 40 · Shadow 30 | [[Soul Rend (Ability)\|Soul Rend]], [[Ice Shard (Ability)\|Ice Shard]], [[Arcane Shield (Ability)\|Arcane Shield]], [[Life Drain]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Dread Archer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Dark Soldier]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Cleave (Ability)\|Cleave]] | [[Dread Knight]], [[Bone Colossus]], [[Dark General]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Life Drain]] | [[Dread Knight]], [[War Necromancer]], [[Lich Commander]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Soul Rend (Ability)\|Soul Rend]] | [[War Necromancer]], [[Lich Commander]] | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Battle Cry (Ability)\|Battle Cry]] | [[Dark General]] | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Ground Slam]] | [[Bone Colossus]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Rally (Ability)\|Rally]] | [[Dark General]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Arcane Shield (Ability)\|Arcane Shield]] | [[Lich Commander]] | Ally, 4 hexes (no line of sight) | 1 | 22 | — | — | Sustained: Conjure a shimmering barrier around yourself or an ally that absorbs damage before HP while you maintain concentration. Drains 5 fatigue/turn. *~27 barrier HP (sustained)* |
| [[Ice Shard (Ability)\|Ice Shard]] | [[Lich Commander]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Dark Soldier]]<br>Possible bonus: [[Dread Knight]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Bone Armor (Enemy Passive)\|Bone Armor]] | Always: [[Dread Thrall]], [[Dread Archer]], [[Bone Colossus]] | 50% resistance to piercing, 15% to slashing. 25% vulnerable to blunt. |
| [[Dark Blessing]] | Always: [[War Necromancer]], [[Lich Commander]]<br>Possible bonus: [[Dread Knight]], [[Dark General]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Dark Soldier]] | +5 melee defense, +5 willpower from professional training. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Dread Thrall]], [[Dread Archer]], [[Dread Knight]], [[Bone Colossus]], [[Dark General]], [[Lich Commander]]<br>Possible bonus: [[War Necromancer]] | Immune to morale checks and Shaken. |
| [[Formation Bonus]] | Always: [[Dark Soldier]]<br>Possible bonus: [[Dread Thrall]] | +6 melee defense when adjacent to 2 or more allies. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Dread Knight]]<br>Possible bonus: [[Bone Colossus]], [[Dark General]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Always: [[Dark General]]<br>Possible bonus: [[Dark Soldier]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Magic Resistance]] | Always: [[War Necromancer]], [[Lich Commander]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Massive Frame]] | Always: [[Bone Colossus]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Rallying Presence]] | Always: [[Dark General]] | Adjacent allies gain +5 willpower on morale checks. |
| [[Tireless (Enemy Passive)\|Tireless]] | Always: [[Dread Thrall]], [[Dread Archer]], [[Dread Knight]], [[Bone Colossus]], [[Dark General]], [[Lich Commander]] | Never tires in battle. Attacks and abilities cost no fatigue; only moving tires it. |
| [[Undead Resilience]] | Always: [[Dread Thrall]], [[Dread Archer]], [[Dread Knight]], [[Bone Colossus]], [[Dark General]], [[Lich Commander]] | Immune to poison and Bleeding. |
| [[Undead Thrall]] | Always: [[Dread Thrall]], [[Dread Archer]] | An animated corpse bound to a necromancer. May rise again at 1 HP after a piercing or slashing kill (40% chance). +15 melee defense while a necromancer is alive. |
| [[Death Throes]] | Possible bonus: [[Bone Colossus]] | Explodes on death, dealing 10 damage to all adjacent units. |
| [[Drain Life]] | Possible bonus: [[Dread Knight]] | Heals 3 HP on each successful melee hit. |
| [[Regeneration]] | Possible bonus: [[Bone Colossus]], [[Lich Commander]] | Heals 5 HP at the start of each turn. |
| [[Shadowcloak]] | Possible bonus: [[War Necromancer]], [[Lich Commander]] | +3 ranged def always. +10 bonus at range 4+, +5 at range 2-3, +0 adjacent. Close the distance! |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Dark Soldier]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Possible bonus: [[Dread Archer]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Terrifying]] | Possible bonus: [[War Necromancer]], [[Dark General]], [[Lich Commander]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Dread Thrall]]*, [[Dark Soldier]]*, [[Bone Colossus]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Dread Archer]]*, [[War Necromancer]]*, [[Lich Commander]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warcaster]] | [[Dread Knight]]* | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]], [[Earthquake]] |
| [[Warlord (Variant)\|Warlord]] | [[Dark General]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

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
| [[Earthquake]] | Warcaster (Boss) | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |
| [[Eldritch Blast]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Fireball (Ability)\|Fireball]] | Warcaster (Champion+) | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | Warcaster (Champion+) | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Magic Missile]] | Warcaster (Elite+) | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Plague Bolt]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 12 | 2 turns | — | Hurls a glob of concentrated pestilence that deals minor damage and poisons the target. *5-10 (+ poison)* |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Stone Shards]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Telekinetic Crush]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 24 | 3 turns | — | Slam an enemy with a wall of psionic force. Deals 20-30 force damage (scaled by spell power) and roots them in place. *20-30 force (+ root, scales with Magic Power)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Deep Crystal Cave Encounter]], [[Deep Stalagmite Encounter]], [[Plains — Late Tier]], [[Ruins — Late Tier]].

*Generated from `enemies/dread_host.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
