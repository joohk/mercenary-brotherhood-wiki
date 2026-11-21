---
type: combat_sheet
aliases:
  - Demons abilities
  - Demons reference
tags:
  - combat-sheet
  - faction/demons
  - type/combat_sheet
source:
  - enemies/demons.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: Demons
faction_id: demons
level_min: 3
tier_max: 4
tier_min: 2
units: 6
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for the [[Demons]]: 6 unit types (tiers 2-4), from company level 3+. They fight as [[How Enemies Behave#Cunning|Cunning]] — intelligent and devious.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[Demons]].

![[_assets/Units/ArchDemon.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/Hellhound.webp\|40]] | [[Hellhound]] | 2 | 79 | 7 | 75 / 47 | 0 / 40 | 66 | 14-22 piercing | Slash 10 · Pierce 10 · Blunt 10 · Fire 50 | [[Fire Breath]] |
| ![[_assets/Units/Imp.webp\|40]] | [[Imp]] | 2 | 46 | 6 | 66 / 55 | 0 / 48 | 72 | 10-15 slashing | Fire 40 | — |
| ![[_assets/Units/CorruptedKnight.webp\|40]] | [[Corrupted Knight]] | 3 | 137 | 15 | 89 / 71 | 0 / 61 | 53 | 22-33 slashing | Slash 35 · Pierce 26 · Blunt 30 · Fire 20 · Shadow 20 | [[Cleave (Ability)\|Cleave]], [[Life Drain]] |
| ![[_assets/Units/LesserDemon.webp\|40]] | [[Lesser Demon]] | 3 | 123 | 12 | 85 / 63 | 0 / 55 | 55 | 25-39 slashing | Slash 20 · Pierce 20 · Blunt 20 · Fire 40 · Shadow 15 | [[Fire Breath]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/ArchDemon.webp\|40]] | [[Arch Demon]] | 4 | 234 | 19 | 108 / 80 | 90 / 72 | 50 | 41-62 slashing | Slash 50 · Pierce 50 · Blunt 50 · Fire 60 · Shadow 25 | [[Fire Breath]], [[Ground Slam]], [[Hellfire Rebuke]] |
| ![[_assets/Units/DemonBrute.webp\|40]] | [[Demon Brute]] | 4 | 203 | 17 | 102 / 74 | 0 / 60 | 38 | 36-55 blunt | Slash 35 · Pierce 35 · Blunt 35 · Fire 30 | [[Ground Slam]], [[Fire Breath]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Fire Breath]] | [[Hellhound]], [[Lesser Demon]], [[Arch Demon]], [[Demon Brute]] | Cone, 1 hex | 1 | 22 | 4 turns | — | Exhale draconic flame at an adjacent enemy. Burns the targeted hex and the three hexes immediately behind it. Hits allies caught in the blast. Ignores armor. *18-26 per target (4-hex fan, ignores armor, burning)* |
| [[Cleave (Ability)\|Cleave]] | [[Corrupted Knight]], [[Lesser Demon]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Life Drain]] | [[Corrupted Knight]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Ground Slam]] | [[Arch Demon]], [[Demon Brute]] | Area (radius 1), 1 hex | 1 | 25 | 3 turns | — | Slam the ground with devastating force, stunning all adjacent enemies for 1 turn and knocking them back 1 hex. Rolls melee to-hit against each enemy. |
| [[Hellfire Rebuke]] | [[Arch Demon]] | Area (radius 1), 1 hex | 1 | 24 | — | 1 | Erupt in infernal flame, dealing 12-20 damage to adjacent enemies hit and applying burning. *12-20 (+ burning, melee to-hit per target)* |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Battle-Hardened (Enemy Passive)\|Battle-Hardened]] | Always: [[Corrupted Knight]] | +4 melee defense, +4 ranged defense from years of combat. |
| [[Bloodless]] | Always: [[Corrupted Knight]] | No blood left to spill. Immune to Bleeding. |
| [[Dark Pact (Enemy Passive)\|Dark Pact]] | Always: [[Corrupted Knight]] | +8 melee attack, +5 damage max, -15 max HP. Sacrificed health for power. |
| [[Enrage]] | Always: [[Demon Brute]]<br>Possible bonus: [[Hellhound]], [[Lesser Demon]] | +30% damage when below 50% HP. |
| [[Evasion]] | Always: [[Imp]] | +6 effective defense from supernatural agility. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Corrupted Knight]], [[Lesser Demon]], [[Arch Demon]], [[Demon Brute]]<br>Possible bonus: [[Hellhound]] | Immune to morale checks and Shaken. |
| [[Feral Speed]] | Always: [[Hellhound]] | +8 initiative from animal instincts. |
| [[Fire Aura]] | Always: [[Hellhound]], [[Lesser Demon]], [[Arch Demon]]<br>Possible bonus: [[Imp]], [[Demon Brute]] | 25% chance to burn melee attackers. |
| [[Fleet-Footed]] | Always: [[Imp]] | +6 initiative, +3 ranged defense from quick footwork. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Always: [[Demon Brute]]<br>Possible bonus: [[Corrupted Knight]], [[Lesser Demon]], [[Arch Demon]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Magic Resistance]] | Always: [[Arch Demon]]<br>Possible bonus: [[Lesser Demon]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Massive Frame]] | Always: [[Demon Brute]] | +20 max HP, +3 armor, -6 initiative. Shrugs off stuns and roots 50% of the time. Enormous and slow. |
| [[Nimble (Enemy Passive)\|Nimble]] | Always: [[Imp]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Pack Tactics (Enemy Passive)\|Pack Tactics]] | Always: [[Hellhound]] | +10 hit chance when an ally is adjacent to the target. |
| [[Regeneration]] | Always: [[Lesser Demon]], [[Arch Demon]]<br>Possible bonus: [[Demon Brute]] | Heals 5 HP at the start of each turn. |
| [[Terrifying]] | Always: [[Arch Demon]]<br>Possible bonus: [[Corrupted Knight]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |
| [[Dark Blessing]] | Possible bonus: [[Arch Demon]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Death Throes]] | Possible bonus: [[Demon Brute]] | Explodes on death, dealing 10 damage to all adjacent units. |
| [[Drain Life]] | Possible bonus: [[Corrupted Knight]] | Heals 3 HP on each successful melee hit. |
| [[Predatory Instinct]] | Possible bonus: [[Hellhound]] | +5 melee attack, +4 initiative from hunter's reflexes. |
| [[Undying Will]] | Possible bonus: [[Arch Demon]] | The first time HP would reach 0, survive with 1 HP instead. Once per combat. |
| [[Venomous (Enemy Passive)\|Venomous]] | Possible bonus: [[Imp]] | 30% chance to poison the target on hit. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Hellhound]]*, [[Imp]]*, [[Lesser Demon]]*, [[Arch Demon]]*, [[Demon Brute]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Warcaster]] | [[Corrupted Knight]]* | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]], [[Earthquake]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Earthquake]] | Warcaster (Boss) | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |
| [[Eldritch Blast]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Exploit Opening]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Fireball (Ability)\|Fireball]] | Warcaster (Champion+) | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Ice Shard (Ability)\|Ice Shard]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | Warcaster (Champion+) | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Magic Missile]] | Warcaster (Elite+) | Enemy, 6 hexes | 1 | 20 | 1 turn | — | Launch a bolt of arcane energy at a distant target. Long range but moderate damage. *8-18 (reduced by armor)* |
| [[Plague Bolt]] | Warcaster (Champion+) | Enemy, 4 hexes | 1 | 12 | 2 turns | — | Hurls a glob of concentrated pestilence that deals minor damage and poisons the target. *5-10 (+ poison)* |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Soul Rend (Ability)\|Soul Rend]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Stone Shards]] | Warcaster (Elite+) | Enemy, 5 hexes | 1 | 18 | 1 turn | — | Hurl a volley of razor-sharp stone fragments at an enemy for 8-18 blunt damage and 1 Fracture. Fracture: -2 armor and -4% physical resistance a stack for the rest of the battle, up to 5 stacks. Damage scales with Magic Power. *8-18 blunt damage, 1 Fracture* |
| [[Telekinetic Crush]] | Warcaster (Boss) | Enemy, 4 hexes | 1 | 24 | 3 turns | — | Slam an enemy with a wall of psionic force. Deals 20-30 force damage (scaled by spell power) and roots them in place. *20-30 force (+ root, scales with Magic Power)* |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |

## Arch-villains

**[[The Void Herald]]** — *Xar'kethos*. From company level 10 · 600 HP · 22 armor · damage 30-42 · resists Slash 20 · Pierce 30 · Blunt 10

Escort: 1× [[Demon Brute]], 2× [[Lesser Demon]], 2× [[Corrupted Knight]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Fireball (Ability)\|Fireball]] | from the start | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Eldritch Blast]] | from the start | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Soul Rend (Ability)\|Soul Rend]] | from the start | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Rift Swap]] | from the start | Enemy, 14 hexes | 1 | 15 | 4 turns | — | Trade places with a shooter up to 14 tiles away, leaving them among your guards. |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | below 40% HP | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Earthquake]] | below 40% HP | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |

## Where you meet them

Leads groups in: [[Dungeon — Boss Encounter]], [[Ruins — Mid Tier]], [[Deep Crystal Cave Encounter]], [[Deep Dark Ruins Encounter]], [[Deep Tunnel Encounter]], [[Deep Cavern Encounter]], [[Ruins — Late Tier]].

*Generated from `enemies/demons.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
