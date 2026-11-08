---
id: spec_spellsword
type: specialization
category: Specializations
aliases:
  - spec_spellsword
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - melee_finishing_blows
  - spell_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Melee Kills* (every 5) **and** *Spell Kills* (every 5) — both must climb; 2 points per threshold.

> Steel in one hand, spell in the other — and neither idle. You must both cut and cast to earn this, and to use it.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Spellsword I | Spellsword II | Spellsword III |
|---|---|---|---|
| [[Stats#Melee Attack\|Melee Attack]] | +3 | +5 | +8 |
| [[Stats#Initiative\|Initiative]] | +2 | +3 | +5 |
| Magic abilities: damage | +8% | +16% | +24% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Melee Kills, every 5 |
| Tracks | Spell Kills, every 5 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Arcane Conclave (Guild)|Arcane Conclave]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
