---
id: spec_spiritbinder
type: specialization
category: Specializations
aliases:
  - spec_spiritbinder
tags:
  - specialization/sorcery
  - type/specialization
source: specializations/specializations.json
base_threshold_interval: 3
metric: shamanism_kills
points_per_threshold: 2
spec_category: sorcery
---

A Sorcery specialization. Tracks *Shamanism Kills* — every 3 → 2 points.

> The blood-tradition's voice. Shamanic magic heals through fury and strikes with the ancestors' weight — no temple art will serve.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Spiritbinder I | Spiritbinder II | Spiritbinder III |
|---|---|---|---|
| [[Stats#Willpower\|Willpower]] | +4 | +7 | +10 |
| [[Stats#Max HP\|Max HP]] | +5 | +10 | +15 |
| Shamanism abilities: damage | +8% | +16% | +24% |
| Shamanism abilities: healing | +15% | +30% | +45% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Shamanism Kills |
| Threshold | every 3 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Sorcery category:* One per magic school. Spell potency only boosts spells of that school; body stats (willpower, fatigue, HP, resistances) always apply.

## Referenced by

- **Sponsored by guilds:** [[Wildwardens]]

> [!note]- Developer notes
> *separator:* ── SORCERY (9) ── one per magic school. Spell potency is tag-filtered: it ONLY boosts spells of that school. Body stats (willpower/fatigue/hp/resist) are always-on.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
