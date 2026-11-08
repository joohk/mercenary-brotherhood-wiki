---
id: spec_witch_hunter
type: specialization
category: Specializations
aliases:
  - Witch Hunter
  - spec_witch_hunter
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - crossbow_kills
  - caster_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Crossbow Kills* (every 4) **and** *Caster Kills* (every 3) — both must climb; 2 points per threshold.

> A bolt for every spellcaster. Requires crossbow kills and slaying enemy casters; the bolt bonuses need a crossbow.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Witch Hunter I | Witch Hunter II | Witch Hunter III |
|---|---|---|---|
| [[Stats#Ranged Attack\|Ranged Attack]] (with crossbows) | +4 | +6 | +10 |
| [[Stats#Magic Resist\|Magic Resist]] | +6 | +10 | +16 |
| [[Stats#Crit Chance\|Crit Chance]] (with crossbows) | — | +2% | +4% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Crossbow Kills, every 4 |
| Tracks | Caster Kills, every 3 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Holy Order]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
