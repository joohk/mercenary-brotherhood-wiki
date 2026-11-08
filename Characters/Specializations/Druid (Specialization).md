---
id: spec_druid
type: specialization
category: Specializations
aliases:
  - Druid
  - spec_druid
tags:
  - specialization/sorcery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: nature_kills
points_per_threshold: 1
spec_category: sorcery
---

A Sorcery specialization. Tracks *Nature Magic Kills* — every 4 → 1 point.

> The living green, bent to war and mercy alike. Nature magic mends and lashes through you — root and thorn answer no other.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Druid I | Druid II | Druid III |
|---|---|---|---|
| [[Stats#Max HP\|Max HP]] | +6 | +12 | +20 |
| [[Stats#Poison Resist\|Poison Resist]] | +8% | +12% | +20% |
| Nature abilities: damage | +8% | +16% | +24% |
| Nature abilities: healing | +15% | +30% | +45% |
| [[Stats#Willpower\|Willpower]] | — | +5 | +8 |

## How it's earned

|  | Value |
|---|---|
| Tracks | Nature Magic Kills |
| Threshold | every 4 |
| Points per threshold | 1 |

A unit may choose a specialization every 4 levels. *Sorcery category:* One per magic school. Spell potency only boosts spells of that school; body stats (willpower, fatigue, HP, resistances) always apply.

## Referenced by

- **Sponsored by guilds:** [[Wildwardens]]

> [!note]- Developer notes
> *separator:* ── SORCERY (9) ── one per magic school. Spell potency is tag-filtered: it ONLY boosts spells of that school. Body stats (willpower/fatigue/hp/resist) are always-on.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
