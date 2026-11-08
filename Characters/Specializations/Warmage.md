---
id: spec_warmage
type: specialization
category: Specializations
aliases:
  - spec_warmage
tags:
  - specialization/battlemage
  - type/specialization
source: specializations/specializations.json
metrics:
  - abilities_used
  - spell_kills
points_per_threshold: 2
spec_category: battlemage
---

A Battlemage specialization. Tracks *Abilities Used* (every 6) **and** *Spell Kills* (every 5) — both must climb; 2 points per threshold.

> A tireless generalist of the arcane battlefield. Requires steady spellcasting and spell kills both.

## Levels

Each column is the full bonus at that level (not added to the previous one).

| Bonus | Warmage I | Warmage II | Warmage III |
|---|---|---|---|
| [[Stats#Willpower\|Willpower]] | +4 | +7 | +10 |
| [[Stats#Max Fatigue\|Max Fatigue]] | +10 | +15 | +20 |
| [[Stats#Fatigue Recovery\|Fatigue Recovery]] | +2 | +3 | +5 |
| Magic abilities: damage | +8% | +16% | +24% |

## How it's earned

|  | Value |
|---|---|
| Tracks | Abilities Used, every 6 |
| Tracks | Spell Kills, every 5 |
| Points per threshold | 2 |

A unit may choose a specialization every 4 levels. *Battlemage category:* Hybrids. Every tracked metric must climb to unlock. Weapon-specific bonuses only apply with that weapon, and spell-type potency only applies to that type of spell.

## Referenced by

- **Sponsored by guilds:** [[Arcane Conclave (Guild)|Arcane Conclave]]

> [!note]- Developer notes
> *separator:* ── BATTLEMAGE (10) ── hybrids. requires_metrics: ALL listed metrics must climb to unlock. weapon_tag bonuses only apply with that weapon; tag_filter potency only applies to that spell type.

*Generated from `specializations/specializations.json`. Edits will be overwritten — put your own notes in Notes/.*
