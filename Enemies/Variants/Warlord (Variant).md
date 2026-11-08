---
id: warlord
type: variant_archetype
category: Enemy Variants
aliases:
  - Warlord
  - warlord
tags:
  - type/variant_archetype
  - variant/explicit
source: variants/variant_pools.json
abilities: 10
assignment: explicit
---

A variant archetype given only to enemies that name it in their data.

> Melee commanders — buffs allies + fights. No magic. call_reinforcements is in BOTH greater (so Champions can roll it) and capstone (Bosses); the grant dedups across draws so a Boss never gets it twice.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Battle Cry (Ability)\|Battle Cry]], [[Shield Bash (Ability)\|Shield Bash]] | Elite, Champion |
| Greater | [[Rally (Ability)\|Rally]], [[Command (Ability)\|Command]], [[War Horn]], [[Hold the Line (Ability)\|Hold the Line]], [[Call Reinforcements]] | Champion, Boss |
| Signature | [[Cleave (Ability)\|Cleave]] | Boss |
| Capstone | [[Coup de Grace (Ability)\|Coup de Grace]], [[Call Reinforcements]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

## Enemies with this archetype

17 enemies set it explicitly (listed under *Referenced by*).

## Referenced by

- **Enemies with this archetype:** [[Bandit Captain]], [[Dark General]], [[Deserter Captain]], [[Deserter Sergeant]], [[Duergar Lord]], [[Duergar Taskmaster]], [[Gnoll Alpha]], [[Jotun Warlord]], [[Mercenary Captain]], [[Orc Veteran Sergeant]], [[Orc Warchief]], [[Rabble Ringleader]], [[Ratkin Ashigaru-Kashira]], [[Ratkin Chieftain]], [[Slann Warlord]], [[Thrall Taskmaster]], [[Wilding Warchief]]

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
