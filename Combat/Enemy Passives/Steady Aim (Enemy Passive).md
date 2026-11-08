---
id: passive_steady_aim
type: enemy_passive
category: Enemy Passives
aliases:
  - Steady Aim
  - passive_steady_aim
tags:
  - enemy-passive/coded
  - type/enemy_passive
source: passives/enemy_passives.json
coded: true
---

An enemy passive: a fixed stat bonus (below) plus behaviour handled in game code.

> +3 ranged attack always. +9 bonus if this unit did not move this turn. Rush it to force movement!

## Effects

- +3 [[Stats#Ranged Attack|Ranged Attack]]

## Tuning parameters

Numbers the game code uses for this passive (fractions shown as %).

| Parameter | Value |
|---|---|
| Base Ratk | 3 |
| Stationary Bonus | 9 |

## Referenced by

- **Enemies with this passive:** [[Duergar Crossbowman]], [[Elf Bandit Archer]], [[Elf Veteran Archer]], [[Mercenary Crossbowman]], [[Ratkin Tanegashima Gunner]], [[Ratkin Yabusame]]
- **Possible bonus passive of:** [[Dread Archer]], [[Goblin Sapper-Veteran]], [[Mountain Cub]], [[Skeleton Archer]], [[Thrall Crossbowman]]

*Generated from `passives/enemy_passives.json`. Edits will be overwritten — put your own notes in Notes/.*
