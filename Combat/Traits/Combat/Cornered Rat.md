---
id: trait_cornered_rat
type: trait
category: Traits
subtype: combat
aliases:
  - trait_cornered_rat
tags:
  - rarity/uncommon
  - trait/combat
  - type/trait
source: traits/combat_traits.json
attack_affinity:
  - melee
rarity: uncommon
---

An uncommon combat trait (conditional).

> When alone or below half health: +12 melee/ranged defense and +10% damage. A cornered rat bites hardest.

## Effects

- +12 Cornered Defense
- +10% Cornered Damage

## Referenced by

- **In racial trait pool of:** [[Ratkin]]

> [!note]- Developer notes
> Race-exclusive (Ratkin). Gated in terrain_traits.py: triggers when no adjacent allies OR below 50% HP.

*Generated from `traits/combat_traits.json`. Edits will be overwritten — put your own notes in Notes/.*
