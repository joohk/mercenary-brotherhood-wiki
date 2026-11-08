---
id: trait_blood_grudge
type: trait
category: Traits
subtype: combat
aliases:
  - trait_blood_grudge
tags:
  - rarity/uncommon
  - trait/combat
  - type/trait
source: traits/combat_traits.json
attack_affinity:
  - melee
  - ranged
rarity: uncommon
---

An uncommon combat trait (conditional).

> A blood grudge burns against *faction*: +15% damage when striking them, but reckless fury leaves them exposed — -5 melee and ranged defense against them.

## Effects

- +15% Grudge Damage
- +5 Grudge Defense Penalty

> [!note]- Developer notes
> Granted at runtime (never rolled): a blood grudge against one faction. Set unit.grudge_faction + stamp via grudge_system.grant_grudge. Gated in terrain_traits.py — the bonus/penalty apply ONLY when the opponent is that faction. One per unit at a time.

*Generated from `traits/combat_traits.json`. Edits will be overwritten — put your own notes in Notes/.*
