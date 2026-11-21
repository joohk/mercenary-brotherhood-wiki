---
type: combat_sheet
aliases:
  - Vampires abilities
  - Vampires reference
tags:
  - combat-sheet
  - faction/vampires
  - type/combat_sheet
source:
  - enemies/vampires.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Vampires
faction_id: vampires
level_min: 4
tier_max: 4
tier_min: 2
units: 8
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Vampires]]: 8 unit types (tiers 2-4), from company level 4+. They fight as [[How Enemies Behave#Cunning|Cunning]] — intelligent and devious.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Vampires]].

![[_assets/Units/VampireElder.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/ThrallCrossbowman.webp\|40]] | [[Thrall Crossbowman]] | 2 | 59 | 6 | 46 / 36 | 64 / 40 | 40 | 8-14 piercing, ranged | Slash 1 · Blunt 1 | [[Flurry (Ability)\|Flurry]] |
| ![[_assets/Units/ThrallGuard.webp\|40]] | [[Thrall Guard]] | 2 | 86 | 9 | 66 / 51 | 0 / 42 | 53 | 15-25 slashing | Slash 6 · Pierce 5 · Blunt 7 | [[Shield Bash (Ability)\|Shield Bash]] |
| ![[_assets/Units/ThrallMilitia.webp\|40]] | [[Thrall Militia]] | 2 | 73 | 6 | 57 / 42 | 0 / 37 | 50 | 8-16 slashing | Slash 1 · Blunt 1 | — |
| ![[_assets/Units/VampireFledgling.webp\|40]] | [[Vampire Fledgling]] | 3 | 115 | 9 | 80 / 60 | 0 / 55 | 63 | 16-25 piercing | Slash 8 · Pierce 6 · Blunt 9 · **Fire -20** · Shadow 20 | [[Life Drain]] |
| ![[_assets/Units/VampireKnight.webp\|40]] | [[Vampire Knight]] | 3 | 152 | 14 | 92 / 71 | 0 / 61 | 59 | 22-33 slashing | Slash 22 · Pierce 14 · Blunt 9 · **Fire -15** · Shadow 25 | [[Life Drain]], [[Shadow Step (Ability)\|Shadow Step]] |
| ![[_assets/Units/VampireNightblade.webp\|40]] | [[Vampire Nightblade]] | 3 | 108 | 8 | 87 / 67 | 0 / 67 | 66 | 20-32 slashing | Slash 8 · Pierce 6 · Blunt 9 · **Fire -15** · Shadow 25 | [[Shadow Step (Ability)\|Shadow Step]], [[Exploit Opening]] |
| ![[_assets/Units/VampireElder.webp\|40]] | [[Vampire Elder]] | 4 | 265 | 19 | 114 / 89 | 0 / 78 | 70 | 28-46 slashing | Slash 25 · Pierce 9 · Blunt 12 · **Fire -15** · Shadow 40 | [[Life Drain]], [[Shadow Step (Ability)\|Shadow Step]], [[Red Feast (Ability)\|Red Feast]], [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/VampireLord.webp\|40]] | [[Vampire Lord]] | 4 | 203 | 14 | 104 / 80 | 0 / 72 | 62 | 24-38 slashing | Slash 9 · Pierce 8 · Blunt 10 · **Fire -15** · Poison 30 · Shadow 35 | [[Life Drain]], [[Shadow Step (Ability)\|Shadow Step]], [[Red Feast (Ability)\|Red Feast]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Flurry (Ability)\|Flurry]] | [[Thrall Crossbowman]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Shield Bash (Ability)\|Shield Bash]] | [[Thrall Guard]] | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Exploit Opening]] | [[Vampire Nightblade]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Life Drain]] | [[Vampire Fledgling]], [[Vampire Knight]], [[Vampire Elder]], [[Vampire Lord]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Shadow Step (Ability)\|Shadow Step]] | [[Vampire Knight]], [[Vampire Nightblade]], [[Vampire Elder]], [[Vampire Lord]] | Empty hex, 3 hexes (no line of sight) | 0 | 16 | 2 turns | 2 | Vanish into shadow and reappear up to 3 hexes away. Cannot be used if rooted. Free action. |
| [[Rally (Ability)\|Rally]] | [[Vampire Elder]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Red Feast (Ability)\|Red Feast]] | [[Vampire Elder]], [[Vampire Lord]] | Adjacent enemy | 1 | 24 | — | 1 | Drain the life force of an adjacent enemy, dealing 15-25 armor-ignoring damage and healing for 100% of damage dealt. *15-25 (ignores armor, heals 100%, melee to-hit)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Ambush]] | Always: [[Vampire Nightblade]] | +15 melee attack on first attack of combat. |
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Vampire Knight]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Blood Drinking]] | Always: [[Vampire Fledgling]], [[Vampire Knight]], [[Vampire Nightblade]], [[Vampire Elder]], [[Vampire Lord]] | Heals for 25% of melee damage dealt. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Always: [[Thrall Guard]] | +5 melee defense, +5 willpower from professional training. |
| [[Evasion]] | Always: [[Vampire Nightblade]]<br>Possible bonus: [[Vampire Fledgling]] | +6 effective defense from supernatural agility. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Thrall Crossbowman]], [[Thrall Guard]], [[Thrall Militia]], [[Vampire Elder]], [[Vampire Lord]]<br>Possible bonus: [[Vampire Knight]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Vampire Fledgling]]<br>Possible bonus: [[Vampire Nightblade]] | +8 initiative from animal instincts. |
| [[Regeneration]] | Always: [[Vampire Elder]]<br>Possible bonus: [[Vampire Lord]] | Heals 5 HP at the start of each turn. |
| [[Terrifying]] | Always: [[Vampire Elder]], [[Vampire Lord]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |
| [[Dark Blessing]] | Possible bonus: [[Vampire Lord]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Desperate]] | Possible bonus: [[Thrall Militia]] | +5 melee attack, -5 melee defense, -10 willpower. Nothing left to lose. |
| [[Enrage]] | Possible bonus: [[Vampire Fledgling]] | +30% damage when below 50% HP. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Vampire Knight]], [[Vampire Elder]], [[Vampire Lord]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Magic Resistance]] | Possible bonus: [[Vampire Elder]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Nimble (Enemy Passive)\|Nimble]] | Possible bonus: [[Vampire Nightblade]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Predatory Instinct]] | Possible bonus: [[Vampire Fledgling]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Shadowy]] | Possible bonus: [[Vampire Nightblade]] | 20% miss chance for ranged attacks from beyond 5 hexes. |
| [[Shield Wall (Enemy Passive)\|Shield Wall]] | Possible bonus: [[Thrall Guard]], [[Vampire Knight]] | +3 melee def always. +8 from front, +3 from flank, +0 from rear. Flank the shield! |
| [[Steady Aim (Enemy Passive)\|Steady Aim]] | Possible bonus: [[Thrall Crossbowman]] | +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement! |
| [[Undying Will]] | Possible bonus: [[Vampire Elder]] | The first time HP would reach 0, survive with 1 HP instead. Once per combat. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Thrall Guard]]*, [[Thrall Militia]]*, [[Vampire Nightblade]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Thrall Crossbowman]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warcaster]] | [[Vampire Fledgling]]*, [[Vampire Knight]]*, [[Vampire Elder]]*, [[Vampire Lord]]* | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]], [[Earthquake]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Cleave (Ability)\|Cleave]] | Brute (Champion+) | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Earthquake]] | Warcaster (Boss) | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |
| [[Eldritch Blast]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Fireball (Ability)\|Fireball]] | Warcaster (Champion+) | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Ice Shard (Ability)\|Ice Shard]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | Warcaster (Champion+) | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Magic Missile]] | Warcaster (Elite+) | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Plague Bolt]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 12 | 2 turns | — | Hurls a glob of concentrated pestilence that deals minor damage and poisons the target. *5-10 (+ poison)* |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Soul Rend (Ability)\|Soul Rend]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Stone Shards]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Telekinetic Crush]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 24 | 3 turns | — | Slam an enemy with a wall of psionic force. Deals 20-30 force damage (scaled by spell power) and roots them in place. *20-30 force (+ root, scales with Magic Power)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[Volley (Ability)\|Volley]] | Skirmisher (Champion+) | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |

## Arch-villains

**[[Bloodlord Kael]]** — *The Undying*. From company level 9 · 500 HP · 20 armor · damage 28-40 · resists Slash 25 · **Pierce -15** · Blunt 15

Escort: 1× [[Vampire Lord]], 2× [[Vampire Knight]], 2× [[Vampire Nightblade]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Life Drain]] | from the start | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Blood Call]] | from the start | Enemy, 12 hexes | 1 | 12 | 3 turns | — | Seize a shooter by the blood from up to 12 tiles away, drag them to your side and drink from them. *14-22, heals the caster for the damage dealt* |
| [[Shadow Nova]] | below 50% HP | Self, radius 2 around | 1 | 20 | 3 turns | 2 | Release an eruption of dark energy around the caster, damaging all nearby enemies. *8-16 shadow (AoE r2)* |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Ruins — Mid Tier]], [[Forest — Late Tier]], [[Ruins — Late Tier]].

*Generated from `enemies/vampires.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
