---
id: passive_stone_flesh
type: enemy_passive
category: Enemy Passives
aliases:
  - passive_stone_flesh
tags:
  - enemy-passive/coded
  - type/enemy_passive
source: passives/enemy_passives.json
coded: true
up: "[[Enemy Passives]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Passives]]

An enemy passive: a fixed stat bonus (below) plus behaviour handled in game code.

> +3 armor always, -5 initiative. +5 bonus armor vs slash/pierce, +0 vs blunt. Blunt deals +25% damage. Shrugs off stuns and roots 50% of the time. Use maces!

## Effects

- +3 [[Stats#Armor|Armor]]
- -5 [[Stats#Initiative|Initiative]]

## Tuning parameters

Numbers the game code uses for this passive (fractions shown as %).

| Parameter | Value |
|---|---|
| Base Armor | 3 |
| Slash Pierce Bonus | 5 |
| Blunt Bonus Pct | 25% |

## Referenced by

- **Enemies with this passive:** [[Stone Giant]]

*Generated from `passives/enemy_passives.json`. Edits will be overwritten — put your own notes in Notes/.*
