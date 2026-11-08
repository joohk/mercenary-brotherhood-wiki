---
id: spec_arcane_archer
type: specialization
category: Specializations
aliases:
  - spec_arcane_archer
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - ranged_kills
  - arcane_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Ranged Kills* (every 5) **and** *Arcane Kills* (every 5) — both must climb; 2 points per threshold.

> Every arrow sings with borrowed power. Requires bow-work and arcane skill both; the draw bonus needs a bow in hand.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Arcane Archer I | Arcane Archer II | Arcane Archer III |
|---|---|---|---|
| [[Stats#Ranged Attack\|Ranged Attack]] (with bows) | +4 | +6 | +10 |
| [[Stats#Initiative\|Initiative]] | +2 | +3 | +5 |
| Arcane abilities: damage | +10% | +18% | +28% |
| Ranged Range (with bows) | — | +1 | +1 |

## How it's earned

|  | Value |
|---|---|
| Tracks | Ranged Kills, every 5 |
| Tracks | Arcane Kills, every 5 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
