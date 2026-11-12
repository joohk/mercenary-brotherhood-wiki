---
id: passive_dark_iron_armor
type: enemy_passive
category: Enemy Passives
aliases:
  - passive_dark_iron_armor
tags:
  - enemy-passive/coded
  - type/enemy_passive
source: passives/enemy_passives.json
coded: true
up: "[[Enemy Passives]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Passives]]

An enemy passive: a fixed stat bonus (below) plus behaviour handled in game code.

> +3 armor, +5 melee defense. Fire and magic attacks ignore 2 armor and corrode -1 armor per hit. Corrodes: -1 armor every 3 turns.

## Effects

- +3 [[Stats#Armor|Armor]]
- +5 [[Stats#Melee Defense|Melee Defense]]

## Tuning parameters

Numbers the game code uses for this passive (fractions shown as %).

| Parameter | Value |
|---|---|
| Base Armor | 3 |
| Fire Armor Bypass | 2 |
| Corrode Interval | 3 |
| Fire Corrode Per Hit | 1 |

## Referenced by

- **Enemies with this passive:** [[Copper Golem]], [[Duergar Dark Smith]], [[Duergar Ironguard]], [[Duergar Lord]], [[Duergar Stonekeeper]], [[Duergar Warpriest]], [[Iron Golem]], [[Mithril Golem]]
- **Possible bonus passive of:** [[Duergar Crossbowman]], [[Duergar Taskmaster]]

*Generated from `passives/enemy_passives.json`. Edits will be overwritten — put your own notes in Notes/.*
