---
id: monster_lair
type: poi
category: Points of Interest
aliases:
  - monster_lair
tags:
  - poi/respawning
  - type/poi
source: pois/poi_templates.json
active_count: 7
poi_kind: respawning
respawn_days: 35
spacing_tier: minor
up: "[[Points of Interest]]"
---

[[Home]] › [[World]] › [[Points of Interest]]

A respawning point of interest (up to 7 active at once, respawning after 35 days).

![[_assets/MonsterLair.webp|160]]

> The den of a powerful creature. Only the bold or foolish venture here.

## Details

|  | Value |
|---|---|
| Active at once | 7 |
| Respawns after | 35 days |
| Spacing | Minor |
| Preferred terrain | Forest, Mountain, Swamp, Hills |
| Discovery radius | 3 hexes |
| Encounter tables | [[Boar Nesting Ground (Encounter Table)\|Boar Nesting Ground]] |

## Lair kinds

Each lair rolls a kind when it spawns (among kinds allowed at your company level, by weight). The kind decides the fight, whatever the terrain.

| Kind | Encounter table | [[Glossary#Numbers used on this wiki\|Company level]] | [[Glossary#Numbers used on this wiki\|Weight]] | Description |
|---|---|---|---|---|
| Boar Warren | [[Boar Nesting Ground (Encounter Table)\|Boar Nesting Ground]] | 1-6 | 30 | Root-choked hollows and mud wallows where a sounder of wild boars has denned up. The tuskers are fiercely territorial. |
| Brood Hollow | [[Brood Hollow]] | 2-6 | 25 | Torn egg-sacs litter a sunken hollow, and the ground seems to crawl. Spider broodlings hatched here have nothing to eat but each other, and whoever comes next. |
| Bear Den | [[Bear Den]] | 3-8 | 25 | Trees clawed bare mark the way to a deep, musky den. Whatever lives here has stopped being afraid of men. |
| Spider Nest | [[Giant Spider Nest (Encounter Table)\|Giant Spider Nest]] | 5+ | 30 | Sheets of grey web choke every gap and hollow. Something with too many legs is still home. |
| Troll Cave | [[Troll Cave (Encounter Table)\|Troll Cave]] | 6+ | 25 | Cracked bones and a stench of old meat mark the mouth of a cave troll's den. |
| Wyvern Roost | [[Wyvern Roost (Encounter Table)\|Wyvern Roost]] | 6+ | 20 | A high, foul-smelling eyrie of splintered bone. The wyvern that built it hunts anything that moves. |
| Dragon's Hoard | [[Dragon's Hoard]] | 9+ | 8 | Gold glints in the dark past the claw-scarred entrance. Whatever piled it there is still coiled around it. |

> [!note]- Developer notes
> A lair gets a KIND when it spawns -- a wyvern roost is a wyvern roost wherever it sits, so terrain is deliberately NOT consulted when picking the fight. The kind is stamped onto the POI (lair_kind/lair_table/name/description) and persists, so what the player is told they are walking into is exactly what they fight. min_company_level gates which kinds can spawn; weight is the roll among those. Every table here must be beast/monster-only -- never point a lair at the generic terrain tables (forest_mid etc.), which carry humanoid factions like barbarians (Wilding Elves) and inquisition.

*Generated from `pois/poi_templates.json`. Edits will be overwritten — put your own notes in Notes/.*
