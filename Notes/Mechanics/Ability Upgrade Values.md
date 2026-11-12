---
type: guide
tags:
  - guide/mechanics
source: game code + skills/*_skill_traits.json
---

What each skill-trait upgrade **actually** does in combat, next to what the game says it does. Many upgrade descriptions are vague ("deals increased damage"); the right-hand column gives the exact numbers the combat code uses. See [[Skill Traits and Upgrades]] for how ranks work.

> [!info] How to read this
> **A → B** means *before the upgrade → after it*. ×1.3 means +30%. Damage ranges are before spell-power or weapon scaling. Durations: 100 game-time units = 1 turn. Decoded from the compiled game code of the current Early Access build; a patch can change any of it.

## Doesn't match its description

| Skill | Skill trait | Rank | Game says | Code does |
|---|---|---|---|---|
| [[Dagger Mastery]] | [[Shadow Strike (Skill Trait)\|Shadow Strike]] | 2 | Range increases to 4 and damage bonus increases to +35%. | Damage ×1.2 → ×1.35. ⚠ Range stays 3: the promised range increase is not applied anywhere in the code |
| [[Dagger Mastery]] | [[Shadow Strike (Skill Trait)\|Shadow Strike]] | 3 | Range increases to 5, damage bonus to +50%, and guaranteed backstab critical. | Damage ×1.5. ⚠ Range stays 3: the promised range increase is not applied anywhere in the code |

## By skill tree

129 upgrade ranks across 36 skill trees.

### Arcane Mastery

Tree: [[Arcane Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Arcane Shield (Skill Trait)\|Arcane Shield]] | 2 | Arcane Shield absorbs ~40 damage instead of ~27. | Barrier 27 → 40 |
| [[Fireball (Skill Trait)\|Fireball]] | 2 | Fireball deals increased damage. | Damage ×1.3 (+30%) |
| [[Haste (Skill Trait)\|Haste]] | 2 | Haste grants +2 AP instead of +1. | +1 AP → +2 AP |
| [[Ice Shard (Skill Trait)\|Ice Shard]] | 2 | Root duration doubled. | Root duration doubled |
| [[Lightning Bolt (Skill Trait)\|Lightning Bolt]] | 2 | Lightning chains to 2 targets instead of 1. | Chains to at least 2 targets |

### Archery

Tree: [[Archery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Called Shot (Skill Trait)\|Called Shot]] | 2 | +40% damage, +20 to-hit. | To-hit +15 → +35; damage ×1.25 → ×1.4 |
| [[Flurry (Skill Trait)\|Flurry]] | 2 | Fires three arrows instead of two, with a reduced hit penalty. | Arrows 2 → 3; hit penalty −20 → −10 |
| [[Piercing Shot (Skill Trait)\|Piercing Shot]] | 2 | Damage rises to 95% per target and gains +5 to-hit on each shot. | Damage per target 80% → 95%; to-hit +0 → +5 |
| [[Pinning Shot (Skill Trait)\|Pinning Shot]] | 2 | Root lasts 3 turns. Also -10 initiative. | Root 3 turns, plus an extra debuff |
| [[Volley (Skill Trait, Archery)\|Volley]] | 2 | Volley's radius increases to 2 and hit penalty reduced by 10%. | Blast radius +1; smaller hit penalty |

### Armor Breaker

Tree: [[Armor Breaker]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Shatter (Skill Trait)\|Shatter]] | 2 | Armor reduction increased to 3 and 3 uses per battle. | Armor shred 2 → 3; uses per battle 2 → 3 |
| [[Skull Crack (Skill Trait, Armor Breaker)\|Skull Crack]] | 2 | Stun chance increased to 45%. | Stun chance 30% → 45%; damage ×1.1 (both skill trees get both parts) |

### Axe Fighting

Tree: [[Axe Fighting]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Decapitate (Skill Trait)\|Decapitate]] | 2 | Instant kill threshold rises to 30% HP and fatigue cost reduced. | Execute threshold 25% → 30% of max HP; fatigue cost −5 |
| [[Decapitate (Skill Trait)\|Decapitate]] | 3 | Instant kill threshold rises to 35% HP. Deals 180% weapon damage. Can be used twice per battle. | Execute threshold 35%; fatigue cost −5; uses per battle → 2 |
| [[Headlong Charge (Skill Trait)\|Headlong Charge]] | 2 | Damage rises to 165% and the charge gains +10 to-hit. | Damage ×1.4 → ×1.65; to-hit +5 → +15 |
| [[Headlong Charge (Skill Trait)\|Headlong Charge]] | 3 | Damage rises to 190% and successful hits also stun the target for one turn. | Damage ×1.9; to-hit +15 |
| [[Rending Chop (Skill Trait, Axe Fighting)\|Rending Chop]] | 2 | Bleeding lasts 4 ticks and deals 40% more damage per tick (7 instead of 5). | Bleeding 7 per tick for 4 ticks |
| [[Sundering Blow (Skill Trait)\|Sundering Blow]] | 2 | Armor reduction increases to 5 per hit. | Armor shred 3 → 5 |
| [[Sundering Blow (Skill Trait)\|Sundering Blow]] | 3 | Armor reduction increases to 7 per hit. Can be used 3 times per battle. | Armor shred 7; uses per battle → 3 |

### Battle Hardened

Tree: [[Battle Hardened (Skill)\|Battle Hardened]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Second Wind (Skill Trait)\|Second Wind]] | 2 | Second Wind heals 5 additional HP and can be used twice per battle. | Heals 5 more HP; uses per battle 1 → 2 |

### Berserker

Tree: [[Berserker (Skill)\|Berserker]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Frenzy (Skill Trait)\|Frenzy]] | 2 | Penalty reduced to -10 hit, 2 uses per battle. | Hit penalty −15 → −10; uses per battle 1 → 2 |
| [[Rending Chop (Skill Trait, Berserker)\|Rending Chop]] | 2 | Bleeding deals 7 damage per tick and lasts 4 ticks. | Bleeding 7 per tick for 4 ticks |

### Blood Magic

Tree: [[Blood Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Blood Bond (Skill Trait)\|Blood Bond]] | 2 | Healing increased to 30 HP. | Heal 25 → 30 (before magic-power scaling) |
| [[Sanguine Power]] | 2 | Sanguine Burst deals increased damage and has wider radius. | Damage 12–20 → 15–25; radius 2 → 3 |
| [[Sanguine Power]] | 3 | Sanguine Burst mastery — maximum damage and radius. | Damage 18–30; radius 3 |

### Charging

Tree: [[Charging]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Barreling Shove (Skill Trait)\|Barreling Shove]] | 2 | The shove deals 115% weapon damage instead of 90% and stuns the target. | Damage 90% → 115% of weapon damage; adds a stun on a target that survives |
| [[Death or Glory (Skill Trait)\|Death or Glory]] | 2 | Twice per battle, and the self-exposure is halved. | Self-exposure (−15 dodge, −10 Melee DEF) → (−8, −5); +1 use per battle |
| [[Lance Rush (Skill Trait)\|Lance Rush]] | 2 | The run may stretch to 5 hexes, reaching 190% weapon damage, and gains +5 to-hit. | Run 4 → 5 hexes; momentum to-hit +5 → +10; range +1 |
| [[Rout (Skill Trait)\|Rout]] | 2 | Drives the target 3 hexes instead of 2. | Push 2 → 3 hexes |
| [[Trample]] | 2 | Trampled enemies are left flat-footed and lose 1 AP next turn. | Trampled enemies lose 1 AP on their next turn |
| [[Warpath (Skill Trait)\|Warpath]] | 2 | The path may run 6 hexes instead of 4. | Run 4 → 6 hexes; range +2 |

### Crossbow Mastery

Tree: [[Crossbow Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Crippling Shot (Skill Trait, Crossbow Mastery)\|Crippling Shot]] | 2 | Movement penalty increases to -3 and defense penalty increases to -8. | Movement −2 → −3; defense −5 → −8; duration 3 → 4 turns |
| [[Penetrating Bolt (Skill Trait, Crossbow Mastery)\|Penetrating Bolt]] | 2 | Also deals +15% bonus damage and can be used twice per battle. | Damage ×1.0 → ×1.15; uses per battle → 2 |

### Dagger Mastery

Tree: [[Dagger Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Lacerate (Skill Trait)\|Lacerate]] | 2 | Bleeding increases to 7 damage per tick for 5 ticks and damage dealt increases to 75%. | Damage 60% → 75%, plus heavier bleeding |
| [[Shadow Strike (Skill Trait)\|Shadow Strike]] | 2 | Range increases to 4 and damage bonus increases to +35%. | Damage ×1.2 → ×1.35. ⚠ Range stays 3: the promised range increase is not applied anywhere in the code |
| [[Shadow Strike (Skill Trait)\|Shadow Strike]] | 3 | Range increases to 5, damage bonus to +50%, and guaranteed backstab critical. | Damage ×1.5. ⚠ Range stays 3: the promised range increase is not applied anywhere in the code |
| [[Slip Strike (Skill Trait)\|Slip Strike]] | 2 | Damage increases to 95% and gains +5 to-hit. | Damage 75% → 95%; to-hit +0 → +5 |
| [[Slip Strike (Skill Trait)\|Slip Strike]] | 3 | Damage rises to 115% and successful hits also apply Bleeding for 2 turns. | Damage 115%; to-hit +5 |
| [[Throat Slash (Skill Trait)\|Throat Slash]] | 2 | Finisher threshold increases to 50% HP and bonus damage increases to +75%. | Finisher below 40% → 50% HP; finisher bonus ×1.5 → ×1.75 |
| [[Throat Slash (Skill Trait)\|Throat Slash]] | 3 | Finisher threshold rises to 60% HP and bonus damage to +100%. Guaranteed critical on finisher. | Finisher below 60% HP; finisher bonus ×2.0 |

### Dark Magic

Tree: [[Dark Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Curse (Skill Trait)\|Curse]] | 2 | Curse also reduces Melee DEF by 5. | Adds −5 Melee Defense to the curse |
| [[Fatigue Drain (Skill Trait)\|Fatigue Drain]] | 2 | Drains 20 fatigue from target, restores 15 to self. | Drain 15 → 20 (fatigue restored to the caster stays 15) |
| [[Soul Rend (Skill Trait)\|Soul Rend]] | 2 | Soul Rend deals 20-30 damage and reduces willpower by 25. | Damage 15–25 → 20–30; willpower −15 → −25 |
| [[Soul Rend (Skill Trait)\|Soul Rend]] | 3 | Soul Rend deals 24-36 damage and reduces willpower by 30. | Damage 24–36; willpower −30 |
| [[Wither (Skill Trait)\|Wither]] | 2 | Wither deals 5 damage/tick instead of 4. | Damage per tick 4 → 5 |

### Executioner

Tree: [[Executioner (Skill)\|Executioner]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Coup de Grace (Skill Trait)\|Coup de Grace]] | 2 | Damage bonus increased and 3 uses per battle. | Damage ×1.5 → ×2.0; uses per battle 2 → 3 |

### Flanking

Tree: [[Flanking]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Blindside (Skill Trait)\|Blindside]] | 2 | Hits harder and always crits against a side-arc target below half HP. | Damage ×1.3 → ×1.6; extra effect against side-arc targets |
| [[Circle the Prey (Skill Trait)\|Circle the Prey]] | 2 | Costs no AP once per battle. | First use each battle costs no AP |
| [[Expose the Flank (Skill Trait)\|Expose the Flank]] | 2 | The opening lasts 3 rounds. | Lasts 2 → 3 rounds |
| [[Pivot Strike (Skill Trait)\|Pivot Strike]] | 2 | The forced turn also costs the target 1 AP. | The target loses 1 AP on its next turn |
| [[Two Fronts (Skill Trait)\|Two Fronts]] | 2 | Each strike that lands refunds 1 fatigue. | Each strike that lands refunds 1 fatigue |

### Formation Fighter

Tree: [[Formation Fighter]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Brace (Skill Trait, Formation Fighter)\|Brace]] | 2 | +40% damage on the counter, triggers on 2 enemies, and can be used twice per battle. | Counter damage ×1.25 → ×1.4; triggers 1 → 2; uses per battle → 2 |
| [[Hold the Line (Skill Trait)\|Hold the Line]] | 2 | +15 Melee Defense, 2 uses per battle. | Melee Defense bonus +10 → +15 (the ability has no per-battle use limit to begin with) |
| [[Long Thrust (Skill Trait)\|Long Thrust]] | 2 | +20 to-hit, deals 110% damage. | To-hit +10 → +20; damage 100% → 110% |

### Giant Slayer

Tree: [[Giant Slayer]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Thunderstrike (Skill Trait, Giant Slayer)\|Thunderstrike]] | 2 | Deals 130% damage instead of 110%, the stun lasts 2 turns, and adjacent enemies are staggered (-10 initiative for 2 turns). | Damage 110% → 130%; stun 1 → 2 turns; staggers adjacent enemies |

### Hammer Fighting

Tree: [[Hammer Fighting]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Armor Crush (Skill Trait)\|Armor Crush]] | 2 | Armor reduction increases to 6 per use. | Armor shred 4 → 6 |
| [[Earthshaker (Skill Trait)\|Earthshaker]] | 2 | Damage increases to 70% and also reduces movement by 2 for 2 turns. | Damage 50% → 70% |
| [[Earthshaker (Skill Trait)\|Earthshaker]] | 3 | Damage increases to 90%. Stuns for 2 turns and reduces movement by 3. | Damage 90%; movement penalty 2 → 3 |
| [[Thunderstrike (Skill Trait, Hammer Fighting)\|Thunderstrike]] | 2 | Deals 130% damage instead of 110%, the stun lasts 2 turns, and adjacent enemies are staggered (-10 initiative for 2 turns). | Damage 110% → 130%; stun 1 → 2 turns; staggers adjacent enemies |

### Holy Magic

Tree: [[Holy Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Cleanse (Skill Trait)\|Cleanse]] | 2 | Cleanse radius increases to 2 hexes. | Radius 2 |
| [[Cleanse (Skill Trait)\|Cleanse]] | 3 | Cleanse radius increases to 3 hexes. | Radius 3 |
| [[Martyr's Grace (Skill Trait)\|Martyr's Grace]] | 2 | Also heals the protected ally for 10 HP when the effect ends. | Heals the protected ally 10 HP when the effect ends |
| [[Mend (Skill Trait)\|Mend]] | 2 | Mend heals for increased amount. | Heal ×1.3 (base 24 → 31, before magic-power scaling) |
| [[Mend (Skill Trait)\|Mend]] | 3 | Mend mastery — increased healing and removes one DoT effect. | Heal ×1.6 (base 24 → 38, before magic-power scaling), plus the extra effect in its description |
| [[Sanctuary (Skill Trait)\|Sanctuary]] | 2 | Fatigue Restore now removes 30 fatigue instead of 20. | Fatigue removed 20 → 30 |
| [[Smite]] | 2 | Smite deals 25% more damage. | Damage ×1.25 |
| [[Sunburst (Skill Trait)\|Sunburst]] | 2 | Sunburst damage increased to 14-22. | Damage 10–16 → 14–22 |

### Mace Fighting

Tree: [[Mace Fighting]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Concussion (Skill Trait)\|Concussion]] | 2 | Penalties increase to -15 melee attack and -15 initiative. Duration extends to 4 turns. | Attack and initiative penalties −10 → −15; duration 3 → 4 turns |
| [[Concussion (Skill Trait)\|Concussion]] | 3 | Penalties increase to -20 melee attack, -20 initiative, and also -5 melee defense. Duration 5 turns. | Attack and initiative penalties −20; duration 5 turns |
| [[Crushing Blow (Skill Trait, Mace Fighting)\|Crushing Blow]] | 2 | Knockback distance doubles to 2 hexes. | Knockback 1 → 2 hexes |
| [[Shieldbreaker (Skill Trait)\|Shieldbreaker]] | 2 | Defense reduction increases to -15 and also reduces ranged defense by 15. | Defense penalty −10 → −15, plus a second debuff |
| [[Skull Crack (Skill Trait, Mace Fighting)\|Skull Crack]] | 2 | Stun chance increases to 45% and deals +10% bonus damage. | Stun chance 30% → 45%; damage ×1.1 (both skill trees get both parts) |

### Marksman

Tree: [[Marksman (Skill)\|Marksman]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Crippling Shot (Skill Trait, Marksman)\|Crippling Shot]] | 2 | -3 movement, -8 melee defense for 4 turns. | Movement −2 → −3; defense −5 → −8; duration 3 → 4 turns |
| [[Penetrating Bolt (Skill Trait, Marksman)\|Penetrating Bolt]] | 2 | 2 uses per battle, +15% damage. | Damage ×1.0 → ×1.15; uses per battle → 2 |

### Melee Mastery

Tree: [[Melee Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Battle Cry (Skill Trait, Melee Mastery)\|Battle Cry]] | 2 | Battle Cry's radius increases to 4 and willpower bonus to +20. | Radius 3 → 4; ally bonus +15 → +20 |
| [[Cleave (Skill Trait, Melee Mastery)\|Cleave]] | 2 | Cleave's hit penalty is reduced by 10%. | Hit penalty −20 → −10 |
| [[Disarming Strike (Skill Trait, Melee Mastery)\|Disarming Strike]] | 2 | Target deals 35% less damage for 3 turns. | Target damage −25% → −35%; duration 2 → 3 turns |

### Nature Magic

Tree: [[Nature Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Bloom of Life (Skill Trait)\|Bloom of Life]] | 2 | Bloom of Life heals 20 HP instead of 14. | Heal 14 → 20 |
| [[Entangling Roots (Skill Trait)\|Entangling Roots]] | 2 | Entangling Roots also deals 4-8 spell damage on cast. | Also deals 4–8 spell damage before rooting |
| [[Thorn Lance (Skill Trait)\|Thorn Lance]] | 2 | Thorn Lance deals 9-18 damage instead of 6-14. | Damage 6–14 → 9–18 |
| [[Thornskin (Skill Trait)\|Thornskin]] | 2 | Thornskin reflects 9 damage instead of 6. | Reflect 6 → 9 |
| [[Thornskin (Skill Trait)\|Thornskin]] | 3 | Thornskin reflects 12 damage instead of 9. | Reflect 12 |
| [[Verdant Wind (Skill Trait)\|Verdant Wind]] | 2 | Verdant Wind restores 9 fatigue/round instead of 6. | Fatigue restored per round 6 → 9 |
| [[Wildshape (Skill Trait)\|Wildshape]] | 2 | Wildshape's defense penalty is halved (-5 instead of -10). | Defense penalty −10 → −5 |

### Pincer

Tree: [[Pincer]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Exploit Opening (Skill Trait)\|Exploit Opening]] | 2 | Full damage, 2 uses per battle. | Damage 75% → 100%; uses per battle → 2 |

### Shadow Magic

Tree: [[Shadow Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Shadow Bolt Mastery]] | 2 | Shadow Bolt deals increased damage. | Damage 10–24 → 13–31 |
| [[Shadow Cloak Mastery]] | 2 | Shadow Cloak dodge bonus increased to +20. | Dodge +15 → +20 |
| [[Shadow Nova Mastery (Skill Trait)\|Shadow Nova Mastery]] | 2 | Shadow Nova deals increased damage and has larger radius. | Radius 2 → 3; damage 8–16 → 11–21 (before magic-power scaling) |
| [[Shadow Veil Mastery (Skill Trait)\|Shadow Veil Mastery]] | 2 | Shadow Veil penalty increased to -15 and lasts longer. | Penalty −10 → −15; duration 3 → 4.5 turns |
| [[Shadow Walk Mastery (Skill Trait)\|Shadow Walk Mastery]] | 2 | Shadow Walk range increased to 7 hexes. | Range at least 7 hexes |

### Shamanism

Tree: [[Shamanism]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Bloodscent (Skill Trait)\|Bloodscent]] | 2 | Bloodscent grants a stronger buff per stack (13% instead of 10%). | Bonus per stack 10% → 13% |

### Shield Wall

Tree: [[Shield Wall (Skill)\|Shield Wall]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Shield Bash (Skill Trait)\|Shield Bash]] | 2 | Shield Bash's stun now lasts an additional turn. | Stun 1 → 2 turns |

### Skirmisher

Tree: [[Skirmisher (Skill)\|Skirmisher]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Sprint (Skill Trait)\|Sprint]] | 2 | Sprint moves 4 hexes. | Move 3 → 4 hexes; uses per battle → 2 |

### Spear Fighting

Tree: [[Spear Fighting]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Brace (Skill Trait, Spear Fighting)\|Brace]] | 2 | Free attack damage bonus increases to +40%, impales the first two foes that charge, and can be used twice per battle. | Counter damage ×1.25 → ×1.4; triggers 1 → 2; uses per battle → 2 |

### Staff Mastery

Tree: [[Staff Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Barrier Strike (Skill Trait)\|Barrier Strike]] | 2 | Grants 12 absorption HP per hit instead of 8. | Absorption per hit 8 → 12 |
| [[Staff Slam (Skill Trait)\|Staff Slam]] | 2 | 85% damage. Affected enemies lose 5 initiative. | Damage 70% → 85%, plus an initiative debuff |

### Stone Magic

Tree: [[Stone Magic]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Boulder Mastery]] | 2 | Boulder Throw deals increased damage (24-40) and applies a stronger initiative penalty (-15). | Damage 20–35 → 24–40; initiative penalty −10 → −15 |
| [[Earthquake Mastery (Skill Trait)\|Earthquake Mastery]] | 2 | Earthquake damage increased to 14-24 and radius expanded to 3. | Damage 10–18 → 14–24; blast radius +1 |
| [[Stone Bastion (Skill Trait)\|Stone Bastion]] | 2 | Stone Bastion grants +15 armor, +12 melee defense, +8 willpower. | Armor +12 → +15; defense +10 → +12; willpower +5 → +8 |
| [[Tremor Mastery (Skill Trait)\|Tremor Mastery]] | 2 | Tremor stun chance increased to 80% and damage increased to 8-16. | Damage 6–12 → 8–16; stun chance 60% → 80% |

### Swordsmanship

Tree: [[Swordsmanship]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Blade Dance (Skill Trait)\|Blade Dance]] | 2 | Hit penalty reduced to -5%. Each slash deals +10% bonus damage. | Hit penalty −10 → −5; damage per slash ×1.0 → ×1.1 (2 slashes) |
| [[Blade Dance (Skill Trait)\|Blade Dance]] | 3 | No hit penalty. Each slash deals +20% bonus damage and can chain a third strike at -15%. | No hit penalty; damage per slash ×1.2; 3 slashes |
| [[Disarming Strike (Skill Trait, Swordsmanship)\|Disarming Strike]] | 2 | Damage penalty increases to 35% and duration extends to 3 turns. | Target damage −25% → −35%; duration 2 → 3 turns |
| [[Twin Strike (Skill Trait, Swordsmanship)\|Twin Strike]] | 2 | Follow-up strike scales to 85% damage. | Follow-up strike 70% → 85% |
| [[Twin Strike (Skill Trait, Swordsmanship)\|Twin Strike]] | 3 | Follow-up strike rises to 100% damage and the ability can be used three times per battle. | Follow-up strike 100%; uses per battle → 3 |

### Tactician

Tree: [[Tactician]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Command (Skill Trait)\|Command]] | 2 | 2 uses per battle. | Uses per battle 1 → 2 |

### Telekinesis

Tree: [[Telekinesis]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[TK Grasp Mastery]] | 2 | TK Grasp also reduces ranged attack by -5. | Adds a second debuff |
| [[TK Lift Mastery]] | 2 | TK Lift also applies -5 initiative debuff. | Adds an initiative debuff |
| [[TK Push Mastery]] | 2 | TK Push distance increased to 3 hexes. | Push 2 → 3 hexes |
| [[TK Shatter Mastery]] | 2 | TK Shatter deals increased damage and has larger radius. | Damage 10–18 → 13–23; blast radius +1 |
| [[TK Shield Mastery]] | 2 | TK Shield grants +10 additional barrier HP. | +10 barrier |
| [[TK Slam Mastery]] | 2 | TK Slam deals increased damage. | Damage 12–22 → 16–29 |
| [[TK Swap Mastery]] | 2 | TK Swap no longer requires a hit roll. | Swaps even if the hit roll fails |
| [[TK Wave Mastery]] | 2 | TK Wave radius increased and push distance doubled. | Radius 2 → 3; push 1 → 2 |

### Thrown Weapons

Tree: [[Thrown Weapons]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Aimed Throw (Skill Trait)\|Aimed Throw]] | 2 | Damage bonus increases to +45% and auto-hit range extends to 3. | Damage bonus ×1.3 → ×1.45; auto-hit range 2 → 3 |
| [[Fan of Blades (Skill Trait)\|Fan of Blades]] | 2 | Damage increases to 75% and hit penalty reduced to -5%. | Damage 60% → 75%; hit penalty −10 → −5 |
| [[Ricochet (Skill Trait)\|Ricochet]] | 2 | Bounces to 2 additional enemies and bounce damage increases to 75%. | Bounces 1 → 2; bounce damage 60% → 75% |
| [[Ricochet (Skill Trait)\|Ricochet]] | 3 | Bounces to 3 enemies, bounce damage increases to 85%, and each bounce applies Bleeding. | Bounces 3; bounce damage 85% |

### Tinkering

Tree: [[Tinkering]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Fire Bomb (Skill Trait)\|Fire Bomb]] | 2 | Blast radius increased to 2. | Blast radius +1 |
| [[Gyro-Saw Disc (Skill Trait)\|Gyro-Saw Disc]] | 2 | Increased damage and heavier bleeding. | Damage 14–28, plus heavier bleeding |
| [[Steam-Powered Punch (Skill Trait)\|Steam-Powered Punch]] | 2 | Knockback increased to 3 tiles. | Knockback 2 → 3 |
| [[Tesla Coil (Skill Trait)\|Tesla Coil]] | 2 | Chains to 2 targets instead of 1. | Chains 1 → 2 |

### Two-Handed Mastery

Tree: [[Two-Handed Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Cleave (Skill Trait, Two Handed Mastery)\|Cleave]] | 2 | Cleave accuracy penalty halved (-10 instead of -20). | Hit penalty −20 → −10 |
| [[Devastating Charge (Skill Trait)\|Devastating Charge]] | 2 | Primary slam rises to 170% damage, sweep to 85%, and catches up to 3 nearby foes. | Primary hit ×1.4 → ×1.7; splash ×0.7 → ×0.85; splash targets 2 → 3 |
| [[Devastating Charge (Skill Trait)\|Devastating Charge]] | 3 | A truly devastating rush: primary slam to 200% damage, sweep to 100%, catching up to 4 nearby foes. | Primary hit ×1.4 → ×1.7; splash ×0.7 → ×0.85; splash targets 2 → 3; Primary hit ×2.0; splash ×1.0; splash targets 4 |
| [[Sweeping Blow (Skill Trait)\|Sweeping Blow]] | 2 | Primary strike rises to 120% damage and the follow-through to 100%. | Primary hit 110% → 120%; follow-through 80% → 100% |
| [[Whirlwind (Skill Trait)\|Whirlwind]] | 2 | The whirlwind widens to strike all enemies within 2 hexes. | Radius 1 → 2 |
| [[Whirlwind (Skill Trait)\|Whirlwind]] | 3 | The spin lands with crushing force, dealing +25% damage on top of its 2-hex reach. | Radius 1 → 2 |

### Wand Mastery

Tree: [[Wand Mastery]]

| Skill trait | Rank | Game says | Code does |
|---|---|---|---|
| [[Mana Surge (Skill Trait)\|Mana Surge]] | 2 | 150% damage. Also restores 5 willpower to self. | Also restores 5 willpower to the caster |

## Not decoded yet

These upgrades rely on code outside the ability handlers (mostly passive traits). Their in-game descriptions are on the trait pages.

- Archery — Headshot, rank 2
- Archery — Hobbling Shots, rank 2
- Archery — Steady Aim, rank 2
- Armor Breaker — Concussive Strike, rank 2
- Assassination — Backstab, rank 2
- Assassination — Deathblow, rank 2
- Assassination — Exploit Weakness, rank 2
- Assassination — Lethal Ambush, rank 2
- Assassination — Throat Cutter, rank 2
- Axe Fighting — Berserker, rank 2
- Axe Fighting — Berserker, rank 3
- Axe Fighting — Rend, rank 2
- Axe Fighting — Skull Splitter, rank 2
- Battle Hardened — Bloodied Fury, rank 2
- Battle Hardened — Grit, rank 2
- Battle Hardened — Undying, rank 2
- Battle Hardened — War Veteran, rank 2
- Berserker — Blood Fury, rank 2
- Berserker — Pain Tolerance, rank 2
- Berserker — See Red, rank 2
- Blood Magic — Red Mist, rank 2
- Blood Magic — Sacrifice Mastery, rank 2
- Blood Magic — Sacrifice Mastery, rank 3
- Bloodied Veteran — Old Wounds, rank 2
- Charging — Breakthrough, rank 2
- Charging — Committed, rank 2
- Counter Fighter — Punish, rank 2
- Crossbow Mastery — Enchanted Bolt, rank 2
- Crossbow Mastery — Enchanted Bolt, rank 3
- Crossbow Mastery — Pinning Bolts, rank 2
- Crossbow Mastery — Pinning Bolts, rank 3
- Crossbow Mastery — Point Blank, rank 2
- Dagger Mastery — Death from Shadow, rank 2
- Dagger Mastery — Death from Shadow, rank 3
- Dagger Mastery — Serrated, rank 2
- Dagger Mastery — Vital Strike, rank 2
- Dark Magic — Eldritch Mastery, rank 2
- Dark Magic — Eldritch Mastery, rank 3
- Dark Magic — Greater Life Drain, rank 2
- Dodge Master — Ghost Step, rank 2
- Dual Wield Mastery — Dance of Blades, rank 2
- Executioner — Killing Momentum, rank 2
- Executioner — Merciless, rank 2
- Executioner — Reaper, rank 2
- Flanking — Cut the Strings, rank 2
- Flanking — Encircled, rank 2
- Flanking — No Safe Side, rank 2
- Flanking — Off Angle, rank 2
- Flanking — Vulture, rank 2
- Formation Fighter — Anchor, rank 2
- Formation Fighter — Phalanx, rank 2
- Hammer Fighting — Avalanche, rank 2
- Hammer Fighting — Avalanche, rank 3
- Hammer Fighting — Stagger, rank 2
- Heavy Armor Proficiency — Bulwark, rank 2
- Heavy Armor Proficiency — Juggernaut, rank 2
- Heavy Armor Proficiency — Juggernaut, rank 3
- Heavy Armor Proficiency — Last Bastion, rank 2
- Heavy Armor Proficiency — Stubborn, rank 2
- Heavy Armor Proficiency — Unyielding, rank 2
- Holy Magic — Divine Shield, rank 2
- Holy Magic — Divine Shield, rank 3
- Last Stand — Last Breath, rank 2
- Light Armor Proficiency — Evasive Roll, rank 2
- Light Armor Proficiency — Fleet Foot, rank 2
- Light Armor Proficiency — Shadow Runner, rank 2
- Light Armor Proficiency — Skirmisher, rank 2
- Light Armor Proficiency — Skirmisher, rank 3
- Light Armor Proficiency — Wind Dancer, rank 2
- Mace Fighting — Concussive, rank 2
- Mace Fighting — Daze, rank 2
- Mace Fighting — Obliterate, rank 2
- Mace Fighting — Obliterate, rank 3
- Melee Mastery — Crushing Blow, rank 2
- Melee Mastery — Executioner, rank 2
- Melee Mastery — Riposte, rank 2
- Nature Magic — Evergreen, rank 2
- Nature Magic — Evergreen, rank 3
- Performance — Resonant Voice, rank 2
- Performance — Shattering Crescendo, rank 2
- Pincer — Opportunist, rank 2
- Pincer — Wolf Pack, rank 2
- Poisoner — Festering Wounds, rank 2
- Poisoner — Numbing Agent, rank 2
- Poisoner — Plague Bearer, rank 2
- Poisoner — Venomous, rank 2
- Shamanism — Greater Leech, rank 2
- Shamanism — War-Caller, rank 2
- Shield Wall — Bulwark, rank 2
- Shield Wall — Counterstrike, rank 2
- Shield Wall — Fortress, rank 2
- Shield Wall — Shield Cover, rank 2
- Skirmisher — Ghost Step, rank 2
- Skirmisher — Opportunist Strike, rank 2
- Spear Fighting — Bulwark Line, rank 2
- Spear Fighting — Bulwark Line, rank 3
- Spear Fighting — Impaling Reach, rank 2
- Spear Fighting — Phalanx, rank 2
- Spear Fighting — Phalanx, rank 3
- Spear Fighting — Set Pike, rank 2
- Steadfast — Defiant, rank 2
- Steadfast — Inspiring Presence, rank 2
- Suppressor — Harassing Fire, rank 2
- Swordsmanship — Counter Stance, rank 2
- Swordsmanship — Counter Stance, rank 3
- Swordsmanship — Master Duelist, rank 2
- Swordsmanship — Master Duelist, rank 3
- Swordsmanship — Parry, rank 2
- Thrown Weapons — Crippling Throw, rank 2
- Thrown Weapons — Scatter Shot, rank 2
- Thrown Weapons — Scatter Shot, rank 3
- Tinkering — Overcharge, rank 2
- Tinkering — Spring Jump, rank 2
- Wand Mastery — Arcane Barrage, rank 2

*Generated by `wiki-builder/mechanics/make_upgrade_page.py` from the game data and `code_effects.json`. Re-run it after a rebuild.*
