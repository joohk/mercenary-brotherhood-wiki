---
id: prime_race_clan
type: founding
category: Foundings
aliases:
  - prime_race_clan
tags:
  - founding/prime_race
  - type/founding
source: foundings/foundings.json
founding_type: prime_race
up: "[[Foundings]]"
---

[[Home]] › [[Your Company]] › [[Foundings]]

A founding (your company's origin, chosen at new-game setup) of type *Prime Race*.

> A clan built around a single Prime race. Recruitment and economy are weighted, not locked: your Prime race is everywhere and cheap, kindred races appear sometimes at a small premium, and outsiders are rare and costly to hire and keep.

## The catch

You can hire an off-race specialist to cover your Prime race's structural gap, but it is expensive to buy AND to keep — doing it often wrecks your economy. You are pushed to win with your Prime race's strengths and live with its weaknesses.

## Rules

| Lever | Value |
|---|---|
| Races that can be Prime | [[Human]], [[Dwarf]], [[Elf]], [[Halfling]], [[Goblin]], [[Orc]] |

## Race affinities

Each Prime race has a set of *friendly* (kindred) races; every other race is *other*.

| Prime race | Friendly races |
|---|---|
| [[Human]] | [[Dwarf]], [[Elf]], [[Halfling]], [[Gnome]] |
| [[Dwarf]] | [[Human]], [[Gnome]], [[Stoneman]], [[Halfling]] |
| [[Elf]] | [[Wild Elf]], [[Sylphborne]], [[Spriggan]], [[Halfling]] |
| [[Halfling]] | [[Human]], [[Gnome]], [[Elf]], [[Dwarf]] |
| [[Goblin]] | [[Orc]], [[Half-Troll]], [[Gnoll]], [[Ratkin]] |
| [[Orc]] | [[Goblin]], [[Half-Ogre]], [[Half-Troll]], [[Minotaur]] |

## Race tiers

| Tier | Recruit weight | Non-native inject weight | Hire cost | Upkeep |
|---|---|---|---|---|
| Prime | ×8 | ×1 | ×0.7 | ×0.8 |
| Friendly | ×3 | ×0.4 | ×1.15 | ×1.15 |
| Other | ×0.1 | — | ×2 | ×1.75 |

Recruit weight scales how often a race appears in recruit pools and drafts; the inject weight lets a Prime or friendly race appear in settlements it isn't native to.

> [!note]- Developer notes
> *affinities:* Prime race -> its set of Friendly (kindred) races. Any race not Prime and not Friendly is 'Other'.
>
> *prime_eligible:* Curated core/iconic races eligible to be a clan's Prime. Independent of recruitment_threshold rarity (e.g. orc is classed uncommon but is Prime-eligible here).
>
> *tiers:* All multipliers are tunable. recruit_weight_mult scales the chance a race appears in recruit pools / drafts. recruit_inject_weight is the base weight given to a Prime/Friendly race that is NOT native to a settlement so it can still show up. hire_cost_mult and upkeep_mult scale gold to hire and salary per payday.

*Generated from `foundings/foundings.json`. Edits will be overwritten — put your own notes in Notes/.*
