---
type: combat_sheet
aliases:
  - The Umbral Court abilities
  - The Umbral Court reference
tags:
  - combat-sheet
  - faction/umbral_court
  - type/combat_sheet
source:
  - enemies/umbral_court.json
  - abilities/combat_abilities.json
  - passives/enemy_passives.json
  - variants/variant_pools.json
faction: The Umbral Court
faction_id: umbral_court
level_min: 4
tier_max: 5
tier_min: 1
units: 10
up: "[[Combat Sheets]]"
---

[[Home]] › [[Bestiary]] › [[Combat Sheets]]

Fight reference for [[The Umbral Court]]: 10 unit types (tiers 1-5), from company level 4+. They fight as [[How Enemies Behave#Cunning|Cunning]] — intelligent and devious.

> [!info]- How to read this sheet
> Click a unit for its full page. **Units** lists each enemy's stats, the damage type it deals and what it resists (weaknesses in **bold**). **Abilities** and **Passives** list each one once with who has it. Elite, Champion and Boss variants draw extra abilities, listed under **Variant upgrades**. Back to [[Combat Sheets]] · faction page: [[The Umbral Court]].

![[_assets/Units/UmbralMatriarch.webp|120]]

## Units

|  | Unit | Tier | HP | Armor | MAtk / MDef | RAtk / RDef | Init | Damage | Resist % (weak in bold) | Abilities |
|---|---|---|---|---|---|---|---|---|---|---|
| ![[_assets/Units/ThrallArcher.webp\|40]] | [[Thrall Archer]] | 1 | 38 | 0 | 25 / 20 | 44 / 24 | 50 | 8-13 piercing, ranged | Slash 1 · Blunt 1 | — |
| ![[_assets/Units/ThrallSlave.webp\|40]] | [[Thrall Slave]] | 1 | 48 | 1 | 40 / 28 | 0 / 24 | 49 | 10-17 slashing | Slash 1 · Blunt 1 | — |
| ![[_assets/Units/CourtSpider.webp\|40]] | [[Court Spider]] | 2 | 73 | 6 | 72 / 55 | 0 / 45 | 68 | 11-18 piercing | Slash 10 | [[Web Shot]] |
| ![[_assets/Units/ThrallTaskmaster.webp\|40]] | [[Thrall Taskmaster]] | 2 | 90 | 7 | 70 / 53 | 0 / 46 | 54 | 15-25 slashing | Slash 6 · Pierce 5 · Blunt 7 | [[Rally (Ability)\|Rally]] |
| ![[_assets/Units/GiantSpider.webp\|40]] | [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]] | 3 | 172 | 14 | 85 / 63 | 0 / 46 | 60 | 21-32 piercing | Slash 25 · Pierce 10 | [[Web Shot]], [[Cleave (Ability)\|Cleave]] |
| ![[_assets/Units/UmbralArcher.webp\|40]] | [[Umbral Archer]] | 3 | 90 | 8 | 66 / 55 | 97 / 64 | 70 | 12-21 piercing, ranged | Slash 8 · Pierce 6 · Blunt 9 | [[Flurry (Ability)\|Flurry]], [[Volley (Ability)\|Volley]] |
| ![[_assets/Units/UmbralSwordsman.webp\|40]] | [[Umbral Swordsman]] | 3 | 115 | 12 | 97 / 80 | 0 / 69 | 75 | 23-34 slashing | Slash 10 · Pierce 8 · Blunt 15 | [[Exploit Opening]] |
| ![[_assets/Units/UmbralBlademaster.webp\|40]] | [[Umbral Blademaster]] | 4 | 149 | 14 | 114 / 96 | 0 / 82 | 91 | 38-61 slashing | Slash 12 · Pierce 11 · Blunt 18 | [[Shadow Step (Ability)\|Shadow Step]], [[Exploit Opening]] |
| ![[_assets/Units/UmbralShadowcaster.webp\|40]] | [[Umbral Shadowcaster]] | 4 | 113 | 8 | 64 / 56 | 108 / 72 | 66 | 32-52 blunt | Slash 4 · Pierce 2 · Blunt 4 | [[Life Drain]], [[Mend (Ability)\|Mend]] |
| ![[_assets/Units/UmbralMatriarch.webp\|40]] | [[Umbral Matriarch]] | 5 | 179 | 18 | 111 / 92 | 119 / 88 | 91 | 46-75 slashing | Slash 14 · Pierce 13 · Blunt 21 | [[Shadow Step (Ability)\|Shadow Step]], [[Rally (Ability)\|Rally]], [[Life Drain]] |

*Damage = base damage plus the main weapon, with the damage type it deals. Resistances are percentages: positive values reduce that damage type, negative values are a weakness (more damage taken). Totals add the unit's natural resistance and its worn armor, helmet and shield; the game caps resistance at 90%. Stance and full stats are on each unit's page.*

## Abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Rally (Ability)\|Rally]] | [[Thrall Taskmaster]], [[Umbral Matriarch]] | Self, radius 2 around | 1 | 8 | — | 1 | A battle cry that restores willpower to nearby allies. 1 use per battle. |
| [[Web Shot]] | [[Court Spider]], [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]] | Enemy, 3 hexes | 1 | 10 | 2 turns | 2 | Fire a strand of sticky web at a ranged target, rooting them in place for their next turn. 2 uses per battle. |
| [[Cleave (Ability)\|Cleave]] | [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]] | Area (radius 1), 1 hex | 1 | 18 | 2 turns | — | A wide sweeping strike that hits all adjacent enemies for full damage at -20 to-hit. |
| [[Exploit Opening]] | [[Umbral Swordsman]], [[Umbral Blademaster]] | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Flurry (Ability)\|Flurry]] | [[Umbral Archer]] | Enemy, weapon range | 1 | 15 | 3 turns | — | Loose two arrows in a single action at -20% hit chance each. |
| [[Volley (Ability)\|Volley]] | [[Umbral Archer]] | Area (radius 1), 6 hexes | 1 | 15 | 3 turns | — | Fire a spread of arrows at a target hex, hitting all enemies within radius 1 at -20 to-hit for 80% damage. |
| [[Life Drain]] | [[Umbral Shadowcaster]], [[Umbral Matriarch]] | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Rip life force from an enemy, healing yourself for a portion of the damage dealt. *10-20 (heals caster 50%)* |
| [[Mend (Ability)\|Mend]] | [[Umbral Shadowcaster]] | Ally, 4 hexes (no line of sight) | 1 | 18 | 3 turns | — | Channel healing energy to restore an ally's wounds. *(only on an injured target)* *Heals 24 HP* |
| [[Shadow Step (Ability)\|Shadow Step]] | [[Umbral Blademaster]], [[Umbral Matriarch]] | Empty hex, 3 hexes (no line of sight) | 0 | 16 | 2 turns | 2 | Vanish into shadow and reappear up to 3 hexes away. Cannot be used if rooted. Free action. |

*Cooldown is turns between uses; "—" means none. Uses / battle "—" means unlimited.*

## Passives

| Passive | Who has it | Effect |
|---|---|---|
| [[Ambush]] | Always: [[Umbral Blademaster]]<br>Possible bonus: [[Umbral Swordsman]] | +15 melee attack on first attack of combat. |
| [[Chitinous Plates]] | Always: [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]]<br>Possible bonus: [[Court Spider]] | +5 armor, -3 initiative from insectoid exoskeleton. |
| [[Dark Blessing]] | Always: [[Umbral Shadowcaster]], [[Umbral Matriarch]] | +5 armor, +10 willpower from unholy patron's protection. |
| [[Evasion]] | Always: [[Umbral Swordsman]], [[Umbral Blademaster]]<br>Possible bonus: [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]], [[Umbral Shadowcaster]], [[Umbral Matriarch]] | +6 effective defense from supernatural agility. |
| [[Fearless (Enemy Passive)\|Fearless]] | Always: [[Umbral Matriarch]]<br>Possible bonus: [[Umbral Blademaster]], [[Umbral Shadowcaster]] | Immune to morale checks and Shaken. |
| [[Intimidating Presence]] | Always: [[Thrall Taskmaster]] | Adjacent enemies suffer -5 willpower on morale checks. |
| [[Keen Senses]] | Always: [[Umbral Archer]] | +3 ranged attack, +1 vision always. +6 bonus vs targets in the open (no adjacent cover terrain). |
| [[Magic Resistance]] | Always: [[Umbral Shadowcaster]]<br>Possible bonus: [[Umbral Matriarch]] | 15-50% chance to resist status effects, higher with more willpower. Reduces incoming spell damage. |
| [[Nimble (Enemy Passive)\|Nimble]] | Always: [[Court Spider]]<br>Possible bonus: [[Umbral Archer]], [[Umbral Swordsman]], [[Umbral Blademaster]] | +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down. |
| [[Precise Strikes (Enemy Passive)\|Precise Strikes]] | Always: [[Umbral Blademaster]]<br>Possible bonus: [[Umbral Swordsman]] | +3 melee attack always. +6 bonus from front arc, +0 from flank/rear. Flank to avoid! |
| [[Shadowcloak]] | Always: [[Umbral Archer]], [[Umbral Swordsman]], [[Umbral Blademaster]], [[Umbral Shadowcaster]], [[Umbral Matriarch]] | +3 ranged def always. +10 bonus at range 4+, +5 at range 2-3, +0 adjacent. Close the distance! |
| [[Slave-Driven]] | Always: [[Thrall Archer]], [[Thrall Slave]] | -10 willpower, +5 melee attack. The taskmaster's whip hurts more than the enemy. |
| [[Terrifying]] | Always: [[Umbral Matriarch]]<br>Possible bonus: [[Umbral Shadowcaster]] | Enemies must pass a morale check (with -15 willpower penalty) when first engaging in melee. |
| [[Venomous (Enemy Passive)\|Venomous]] | Always: [[Court Spider]], [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]] | 30% chance to poison the target on hit. |
| [[Web Spinner]] | Always: [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]]<br>Possible bonus: [[Court Spider]] | 20% chance to root target for 1 turn on hit. |
| [[Disciplined (Enemy Passive)\|Disciplined]] | Possible bonus: [[Thrall Taskmaster]] | +5 melee defense, +5 willpower from professional training. |
| [[Enrage]] | Possible bonus: [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]] | +30% damage when below 50% HP. |
| [[Frenzy (Enemy Passive)\|Frenzy]] | Possible bonus: [[Umbral Blademaster]] | +2 melee attack per successful hit in this combat, stacking. |
| [[Heavy Blows (Enemy Passive)\|Heavy Blows]] | Possible bonus: [[Thrall Taskmaster]] | +2 damage always. +4 bonus damage vs targets above 50% HP. Punishes healthy targets. |
| [[Iron Discipline (Enemy Passive)\|Iron Discipline]] | Possible bonus: [[Umbral Matriarch]] | +15 willpower. Adjacent allies gain +5 willpower on morale checks. On death, allies within 3 hexes suffer -10 willpower for 2 turns. |
| [[Shadowy]] | Possible bonus: [[Umbral Archer]] | 20% miss chance for ranged attacks from beyond 5 hexes. |

*Possible bonus passives are rolled onto some spawns (e.g. stronger variants).*

## Variant upgrades

Stronger versions of these units appear as the campaign goes on. Each draws random extra abilities from its archetype's pools: **Elite** 1 from Lesser; **Champion** 2 from Lesser + Greater; **Boss** 3: 2 from Greater + Signature plus the Capstone, and bosses get -1 cooldown on all abilities. Racial abilities are only granted to units of that race.

| Archetype | Units | Lesser (Elite+) | Greater (Champion+) | Signature / Capstone (Boss) |
|---|---|---|---|---|
| [[Brute]] | [[Thrall Slave]]*, [[Court Spider]]*, [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]]*, [[Umbral Swordsman]]*, [[Umbral Blademaster]]* | [[Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]], [[Thunderclap (Ability)\|Thunderclap]] |
| [[Skirmisher (Variant)\|Skirmisher]] | [[Thrall Archer]]*, [[Umbral Archer]]*, [[Umbral Shadowcaster]]*, [[Umbral Matriarch]]* | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | [[Called Shot (Ability)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]], [[Fan of Blades (Ability)\|Fan of Blades]] |
| [[Warlord (Variant)\|Warlord]] | [[Thrall Taskmaster]] | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | [[Cleave (Ability)\|Cleave]], [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] |

*\* archetype not set in the data; the game picks it automatically from behaviour, abilities and weapons, and the wiki shows the likely result. The data calls the top tier "boss"; since the Nov 12 patch these are the **Corrupted** mini-bosses (its Boss Fortitude passive is now named Corrupted Fortitude).*

### Variant abilities

| Ability | Used by | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Aimed Throw (Ability)\|Aimed Throw]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 14 | 3 turns | — | A precisely aimed throw at +30% damage. Guaranteed to hit at range 2 or less. *(needs a throwing weapon)* |
| [[Battle Cry (Ability)\|Battle Cry]] | Warlord (Elite+) | Self, radius 3 around | 1 | 8 | — | 1 | A roaring war shout that bolsters nearby allies and rattles nearby foes. |
| [[Bull Rush (Ability)\|Bull Rush]] | Brute (Champion+) | Enemy, 3 hexes | 2 | 20 | 3 turns | — | Charge up to 2 hexes toward an enemy, slamming into them and pushing them back 2 hexes. 80% weapon damage. |
| [[Call Reinforcements]] | Warlord (Champion+), Warlord (Boss) | Self | 2 | 15 | 4 turns | 2 | Bellow for backup, dragging fresh fighters onto the field beside you. Summons 2-3 lesser allies near the caster. Enemy boss ability only. 2 uses per battle (1 for a Champion, 3 for a Corrupted foe). |
| [[Called Shot (Ability)\|Called Shot]] | Skirmisher (Boss) | Enemy, weapon range | 1 | 22 | 3 turns | — | Take careful aim for a devastating shot. +25% damage and +15 to-hit, but costs extra fatigue. |
| [[Command (Ability)\|Command]] | Warlord (Champion+) | Adjacent ally | 1 | 8 | — | 1 | Grant an adjacent ally +1 AP on their next turn. A leader's voice cuts through the chaos. |
| [[Coup de Grace (Ability)\|Coup de Grace]] | Brute (Boss), Warlord (Boss) | Adjacent enemy | 1 | 18 | — | 2 | A devastating finishing blow against a wounded enemy (under 25% HP). Deals 50% bonus damage. |
| [[Crippling Shot (Ability)\|Crippling Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | Aim for the joints. Reduces target movement by 2 and melee defense by 5 for 3 turns. Requires a crossbow. |
| [[Fan of Blades (Ability)\|Fan of Blades]] | Skirmisher (Boss) | Area (radius 1), 4 hexes | 1 | 16 | 2 turns | — | Hurl a spread of weapons at a target hex, hitting all enemies in radius 1 at 60% damage and -10 to-hit. *(needs a throwing weapon)* |
| [[Frenzy (Ability)\|Frenzy]] | Brute (Champion+) | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Hold the Line (Ability)\|Hold the Line]] | Warlord (Champion+) | Self, radius 1 around | 1 | 10 | — | — | Sustained: Allies adjacent to you when you cast gain +10 Melee Defense while you maintain concentration, even if they move away. Drains 4 fatigue/turn. |
| [[Killing Blow (Ability)\|Killing Blow]] | Brute (Boss) | Adjacent enemy | 1 | 5 | 4 turns | — | An execution strike at 150% weapon damage, usable on a target below 35% HP, or below 50% from behind. Refunds 1 AP if the blow kills. 4-turn cooldown. |
| [[Piercing Shot (Ability)\|Piercing Shot]] | Skirmisher (Elite+) | Enemy, 6 hexes | 1 | 16 | 3 turns | — | Loose a heavy arrow that punches through the target and into a second enemy in a straight line behind them. Each enemy is rolled separately at 80% damage. *(needs a bow)* |
| [[Pinning Shot (Ability)\|Pinning Shot]] | Skirmisher (Champion+) | Enemy, weapon range | 1 | 15 | 3 turns | — | A shot through the leg. Deals normal damage, Roots the target for 2 turns and lays 1 extra Suppression. |
| [[Shatter (Ability)\|Shatter]] | Brute (Champion+) | Adjacent enemy | 1 | 14 | — | 2 | A devastating blow that splinters the target's armor, reducing it by 2 for the rest of combat. |
| [[Shield Bash (Ability)\|Shield Bash]] | Brute (Elite+), Warlord (Elite+) | Adjacent enemy | 1 | 18 | — | 1 | Strike with your shield for 50% damage to stun an adjacent enemy and knock it back 1 hex, buying your allies a free turn. |
| [[Sneak Attack (Ability)\|Sneak Attack]] | Brute (Elite+) | Adjacent enemy | 1 | 8 | 3 turns | — | A strike at +20% to hit: 150% weapon damage and ignores 5 armor from behind, 100% weapon damage from anywhere else. 3-turn cooldown. |
| [[Sprint (Ability)\|Sprint]] | Skirmisher (Elite+) | Self | 0 | 5 | — | 1 | Burst of speed as a free action — move 3 additional hexes this turn. Once per battle. |
| [[Thunderclap (Ability)\|Thunderclap]] | Brute (Boss) | Self, radius 1 around | 1 | 14 | 3 turns | — | Slam the ground with tremendous force, pushing all adjacent enemies 1 hex away. No damage, but breaks formations. |
| [[War Horn]] | Warlord (Champion+) | Self, radius 3 around | 1 | 12 | — | 1 | Sound a mighty war horn. All allies within 3 hexes gain +5 initiative and +3 melee attack for 2 turns. Enemies within 3 hexes lose 5 willpower. |

## Arch-villains

**[[The Shadow Weaver]]** — *Vaelith of the Deep Dark*. From company level 10 · 360 HP · 15 armor · damage 26-36 · resists Slash 10 · Pierce 15

Escort: 1× [[Umbral Blademaster]], 2× [[Giant Spider (Enemy, Umbral Court)|Giant Spider (The Umbral Court)]], 2× [[Umbral Archer]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Opportunist Strike (Ability)\|Opportunist Strike]] | from the start | Adjacent enemy | 1 | 15 | — | 2 | Strike a vulnerable enemy within melee reach from the side or behind. Flank: +15 hit, +25% damage. Backstab: +25 hit, +50% damage. Cannot target a foe facing you. |
| [[Exploit Opening]] | from the start | Adjacent enemy | 1 | 18 | — | 1 | A guaranteed hit against a flanked enemy at 75% damage. Requires an ally adjacent to the target. |
| [[Shadow Nova]] | from the start | Self, radius 2 around | 1 | 20 | 3 turns | 2 | Release an eruption of dark energy around the caster, damaging all nearby enemies. *8-16 shadow (AoE r2)* |
| [[Shadow Stalk]] | from the start | Enemy, 14 hexes (no line of sight) | 2 | 15 | 3 turns | — | Step through the dark to the side of a shooter up to 14 tiles away, through any wall, and strike. |
| [[Frenzy (Ability)\|Frenzy]] | below 45% HP | Adjacent enemy | 1 | 18 | — | 1 | Attack twice in rapid succession at -15 hit chance each. Exhausting but deadly. |
| [[Soul Rend (Ability)\|Soul Rend]] | below 45% HP | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |

**[[The Witch Queen]]** — *Seraphel of the Veil*. From company level 10 · 400 HP · 16 armor · damage 24-34 · resists Slash 10 · Pierce 25 · **Blunt -10**

Escort: 1× [[Umbral Shadowcaster]], 2× [[Umbral Swordsman]], 2× [[Umbral Archer]]

| Ability | When | Target / range | AP | Fatigue | Cooldown | Uses / battle | What it does |
|---|---|---|---|---|---|---|---|
| [[Fireball (Ability)\|Fireball]] | from the start | Enemy + radius 1, 4 hexes | 1 | 35 | 3 turns | — | Hurl a ball of fire that explodes on impact, dealing damage and setting all nearby enemies ablaze. *15-30 (+ burning)* |
| [[Lightning Bolt (Ability)\|Lightning Bolt]] | from the start | Enemy, 5 hexes | 1 | 28 | 3 turns | — | Strike an enemy with a bolt of lightning that chains to a nearby foe for half damage. *10-30 (chains 50% to adjacent)* |
| [[Ice Shard (Ability)\|Ice Shard]] | from the start | Enemy, 4 hexes | 1 | 25 | 2 turns | — | Launch a shard of ice that damages and roots the target in place. *10-25 (+ root)* |
| [[Soul Rend (Ability)\|Soul Rend]] | from the start | Enemy, 4 hexes | 1 | 30 | 3 turns | — | Tear at an enemy's very essence, dealing armor-ignoring damage and crushing their willpower. Damage scales as the target nears 25% HP: +50% at half HP, +100% at quarter HP or below. *15-25 (ignores armor, -15 willpower, scales up to 2x at 25% target HP)* |
| [[Veil of Mirrors]] | from the start | Self | 1 | 10 | 6 turns | — | For 5 turns, the next 2 ranged hits on you, spells included, go back at whoever fired them. |
| [[Eldritch Blast]] | below 45% HP | Enemy, 5 hexes | 1 | 25 | 1 turn | — | A beam of pure eldritch energy that ignores armor. Can be used every turn. *10-25 (ignores armor)* |
| [[Earthquake]] | below 45% HP | Enemy + radius 2, 5 hexes | 1 | 35 | 3 turns | — | Split the earth beneath a distant area. Every enemy within 2 of the target takes 13-21 blunt damage and 1 Fracture, and is rooted for 1 turn. *13-21 blunt damage in radius 2, 1 Fracture each, root 1 turn* |

## Where you meet them

Leads groups in: [[Mid-depth Tunnel Encounter]], [[Mid-depth Cavern Encounter]], [[Mid-depth Mushroom Forest Encounter]], [[Mid-depth Stalagmite Encounter]], [[Mid-depth Fungal Bog Encounter]], [[Deep Dark Ruins Encounter]], [[Deep Tunnel Encounter]], [[Deep Cavern Encounter]], [[Deep Stalagmite Encounter]], [[Forest — Late Tier]], [[Forest — Umbral Court Raid]], [[Ruins — Late Tier]].

*Generated from `enemies/umbral_court.json`, `abilities/combat_abilities.json`, `passives/enemy_passives.json`, `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
