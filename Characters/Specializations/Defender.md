---
id: spec_the_pinch
type: specialization
category: Specializations
aliases:
  - spec_the_pinch
tags:
  - specialization/tactics
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 4
metric: turns_survived_surrounded
points_per_threshold: 2
spec_category: tactics
---

A Tactics specialization. Tracks *Turns Surrounded* — every 4 → 2 points.

> Cornered is a state of mind. Theirs, not yours.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Defender I | Defender II | Defender III |
|---|---|---|---|
| [[Stats#Melee Attack\|Melee Attack]] per adjacent enemy beyond the first | +1 | +2 | +3 |
| [[Stats#Melee Defense\|Melee Defense]] per adjacent enemy beyond the first | +2 | +3 | +4 |
| [[Stats#Max HP\|Max HP]] | — | +5 | +10 |
| [[Stats#Dodge\|Dodge]] | — | +3% | +5% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Turns Surrounded |
| Threshold | every 4 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Tactics category:* Positioning and skill-focused specializations.

## Referenced by

- **Sponsored by guilds:** [[Blade Circle]]

> [!note]- Developer notes
> *separator:* ── TACTICS (8) ── positioning and skill-focused specializations

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
