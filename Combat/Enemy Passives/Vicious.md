---
id: passive_vicious
type: enemy_passive
category: Enemy Passives
aliases:
  - passive_vicious
tags:
  - enemy-passive/coded
  - type/enemy_passive
source: passives/enemy_passives.json
coded: true
---

An enemy passive: a fixed stat bonus (below) plus behaviour handled in game code. No enemy, villain or item in the data lists it; the game may apply it to enemy variants.

> +1 damage always. +5 bonus damage vs bleeding, poisoned, or burning targets. Cure status fast!

## Effects

- +1 [[Stats#Damage Min|Damage]]

## Tuning parameters

Numbers the game code uses for this passive (fractions shown as %).

| Parameter | Value |
|---|---|
| Base Dmg | 1 |
| Status Bonus | 5 |

*Generated from `passives/enemy_passives.json`. Edits will be overwritten — put your own notes in Notes/.*
