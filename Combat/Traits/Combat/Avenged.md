---
id: trait_avenged
type: trait
category: Traits
subtype: combat
aliases:
  - trait_avenged
tags:
  - rarity/uncommon
  - trait/combat
  - type/trait
source: traits/combat_traits.json
attack_affinity:
  - melee
  - ranged
rarity: uncommon
up: "[[Traits]]"
---

[[Home]] › [[Your Company]] › [[Traits]]

An uncommon combat trait (conditional).

> A blood grudge fulfilled. A quiet, lasting edge endures: +7% damage against *faction*.

## Effects

- +7% Avenged Damage

> [!note]- Developer notes
> A blood grudge fulfilled (grudge_system.resolve_grudge). Smaller PERMANENT edge, no reckless penalty. Gated in terrain_traits.py vs unit.avenged_factions. Grants the trait once; the faction list can grow.

*Generated from `traits/combat_traits.json`. Edits will be overwritten — put your own notes in Notes/.*
