---
id: spec_archmage
type: specialization
category: Specializations
aliases:
  - Archmage
  - spec_archmage
tags:
  - specialization/sorcery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 5
metric: arcane_kills
points_per_threshold: 2
spec_category: sorcery
up: "[[Specializations]]"
---

[[Home]] › [[Your Company]] › [[Specializations]]

A Sorcery specialization. Tracks *Arcane Kills* — every 5 → 2 points.

> Master of the raw arcane. Your spells strike harder and wider — but only the arcane answers your call.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Archmage I | Archmage II | Archmage III |
|---|---|---|---|
| [[Stats#Willpower\|Willpower]] | +4 | +7 | +10 |
| [[Stats#Max Fatigue\|Max Fatigue]] | +10 | +15 | +20 |
| Arcane abilities: damage | +10% | +20% | +30% |
| Arcane abilities: crit chance | +3% | +4% | +5% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Arcane Kills |
| Threshold | every 5 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Sorcery category:* One per magic school. Spell potency only boosts spells of that school; body stats (willpower, fatigue, HP, resistances) always apply.

## Referenced by

- **Sponsored by guilds:** [[Arcane Conclave (Guild)|Arcane Conclave]]

> [!note]- Developer notes
> *separator:* ── SORCERY (9) ── one per magic school. Spell potency is tag-filtered: it ONLY boosts spells of that school. Body stats (willpower/fatigue/hp/resist) are always-on.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
