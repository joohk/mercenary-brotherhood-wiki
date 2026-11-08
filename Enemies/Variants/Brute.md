---
id: brute
type: variant_archetype
category: Enemy Variants
aliases:
  - brute
tags:
  - type/variant_archetype
  - variant/auto
source: variants/variant_pools.json
abilities: 10
assignment: auto
---

A variant archetype the default for every melee enemy that matches nothing else.

> Weapon-agnostic melee bruisers — the default for any aggressive/defensive melee enemy. No magic, no ranged.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Exploit Opening (Ability, ability_exploit_opening)\|Exploit Opening]], [[Shield Bash (Ability)\|Shield Bash]], [[Sneak Attack (Ability)\|Sneak Attack]] | Elite, Champion |
| Greater | [[Cleave (Ability)\|Cleave]], [[Frenzy (Ability)\|Frenzy]], [[Shatter (Ability)\|Shatter]], [[Bull Rush (Ability)\|Bull Rush]] | Champion, Boss |
| Signature | [[Coup de Grace (Ability)\|Coup de Grace]], [[Killing Blow (Ability)\|Killing Blow]] | Boss |
| Capstone | [[Thunderclap (Ability)\|Thunderclap]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
