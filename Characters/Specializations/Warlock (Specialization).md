---
id: spec_warlock
type: specialization
category: Specializations
aliases:
  - Warlock
  - spec_warlock
tags:
  - specialization/sorcery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: dark_kills
points_per_threshold: 1
spec_category: sorcery
up: "[[Specializations]]"
---

[[Home]] › [[Your Company]] › [[Specializations]]

A Sorcery specialization. Tracks *Dark Kills* — every 4 → 1 point.

> Forbidden power, willingly paid for. Your curses and drains bite deeper — the dark repays what you feed it.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Warlock I | Warlock II | Warlock III |
|---|---|---|---|
| [[Stats#Willpower\|Willpower]] | +4 | +7 | +10 |
| [[Stats#Max HP\|Max HP]] | +5 | +10 | +15 |
| Dark abilities: damage | +10% | +20% | +30% |
| Dark abilities: healing | — | +15% | +25% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Dark Kills |
| Threshold | every 4 |
| Points per threshold | 1 |

A unit may choose a specialization every 4 levels. *Sorcery category:* One per magic school. Spell potency only boosts spells of that school; body stats (willpower, fatigue, HP, resistances) always apply.

> [!note]- Developer notes
> *separator:* ── SORCERY (9) ── one per magic school. Spell potency is tag-filtered: it ONLY boosts spells of that school. Body stats (willpower/fatigue/hp/resist) are always-on.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
