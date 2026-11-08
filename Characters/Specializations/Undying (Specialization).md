---
id: spec_death_cheater
type: specialization
category: Specializations
aliases:
  - Undying
  - spec_death_cheater
tags:
  - specialization/endurance
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 1
metric: times_survived_lethal
points_per_threshold: 5
spec_category: endurance
---

An Endurance specialization. Tracks *Near-Death Survivals* — every 1 → 5 points.

> Death keeps knocking. The door stays shut.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Undying I | Undying II | Undying III |
|---|---|---|---|
| [[Stats#Max HP\|Max HP]] | +10 | +18 | +28 |
| [[Stats#Willpower\|Willpower]] | +3 | +6 | +10 |
| [[Stats#Dodge\|Dodge]] | — | +3% | +5% |
| [[Stats#Melee Defense\|Melee Defense]] | — | — | +3 |

## How it's earned

|  | Value |
|---|---|
| Tracks | Near-Death Survivals |
| Threshold | every 1 |
| Points per threshold | 5 |

A unit may choose a specialization every 4 levels. *Endurance category:* Survival-focused specializations.

> [!note]- Developer notes
> *separator:* ── ENDURANCE (8) ── survival-focused specializations

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
