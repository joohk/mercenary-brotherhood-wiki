---
id: passive_nimble
type: enemy_passive
category: Enemy Passives
aliases:
  - Nimble
  - passive_nimble
tags:
  - enemy-passive/coded
  - type/enemy_passive
source: passives/enemy_passives.json
coded: true
---

An enemy passive: a fixed stat bonus (below) plus behaviour handled in game code.

> +4 melee def, +3 ranged def always. +6/+5 bonus while above 75% HP. Wounds slow it down.

## Effects

- +4 [[Stats#Melee Defense|Melee Defense]]
- +3 [[Stats#Ranged Defense|Ranged Defense]]

## Tuning parameters

Numbers the game code uses for this passive (fractions shown as %).

| Parameter | Value |
|---|---|
| Base Mdef | 4 |
| Base Rdef | 3 |
| Bonus Mdef | 6 |
| Bonus Rdef | 5 |
| Hp Threshold | 75% |

## Referenced by

- **Arch-villains with this passive:** [[The Shadow Weaver]], [[Warlord Ash]]
- **Enemies with this passive:** [[Court Spider]], [[Cult Assassin]], [[Goblin Shaman (Enemy)|Goblin Shaman]], [[Goblin Skirmisher]], [[Halfling Cutpurse]], [[Imp]]
- **Possible bonus passive of:** [[Bog Lurker]], [[Cutpurse]], [[Deserter Archer]], [[Elf Bandit Archer]], [[Elf Veteran Archer]], [[Giant Spider (Enemy, Beasts)|Giant Spider]], [[Gnoll Stalker]], [[Goblin Poisoner]], [[Goblin Sapper-Veteran]], [[Goblin Wolfrider]], [[Halfling Scout-Veteran]], [[Kesharan Horse Archer]], [[Mercenary Crossbowman]], [[Ratkin Alchemist]], [[Ratkin Bowman]], [[Ratkin Plague Shaman]], [[Ratkin Scrapper]], [[Ratkin Shinobi]], [[Ratkin Tunneler]], [[Ratkin Yabusame]], [[Skink Javelineer]], [[Spider Broodling]], [[Umbral Archer]], [[Umbral Blademaster]], [[Umbral Swordsman]], [[Vampire Nightblade]], [[Wilding Huntsman]], [[Witch Finder]]

*Generated from `passives/enemy_passives.json`. Edits will be overwritten — put your own notes in Notes/.*
