---
id: spec_templar
type: specialization
category: Specializations
aliases:
  - Templar
  - spec_templar
tags:
  - specialization/sorcery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: holy_kills
points_per_threshold: 1
spec_category: sorcery
---

A Sorcery specialization. Tracks *Holy Kills* — every 4 → 1 point.

> Divine wrath given an edge. Your holy magic burns brighter — and does nothing for lesser powers.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Templar I | Templar II | Templar III |
|---|---|---|---|
| [[Stats#Willpower\|Willpower]] | +4 | +7 | +10 |
| [[Stats#Max Fatigue\|Max Fatigue]] | +8 | +12 | +16 |
| Holy abilities: damage | +10% | +20% | +30% |
| [[Stats#Magic Resist\|Magic Resist]] | — | +5 | +8 |
| Holy abilities: healing | — | +15% | +25% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Holy Kills |
| Threshold | every 4 |
| Points per threshold | 1 |

A unit may choose a specialization every 4 levels. *Sorcery category:* One per magic school. Spell potency only boosts spells of that school; body stats (willpower, fatigue, HP, resistances) always apply.

## Referenced by

- **Sponsored by guilds:** [[Holy Order]]

> [!note]- Developer notes
> *separator:* ── SORCERY (9) ── one per magic school. Spell potency is tag-filtered: it ONLY boosts spells of that school. Body stats (willpower/fatigue/hp/resist) are always-on.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
