---
id: skirmisher
type: variant_archetype
category: Enemy Variants
aliases:
  - Skirmisher
  - skirmisher
tags:
  - type/variant_archetype
  - variant/auto
source: variants/variant_pools.json
abilities: 9
assignment: auto
---

A variant archetype auto-assigned to ranged enemies.

> Ranged harassers — auto-assigned to ranged-behaviour / bow-crossbow-thrown enemies. No magic.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Flurry (Ability)\|Flurry]], [[Sprint (Ability, ability_sprint)\|Sprint]], [[Piercing Shot (Ability)\|Piercing Shot]] | Elite, Champion |
| Greater | [[Volley (Ability)\|Volley]], [[Pinning Shot (Ability, ability_pinning_shot)\|Pinning Shot]], [[Crippling Shot (Ability)\|Crippling Shot]] | Champion, Boss |
| Signature | [[Called Shot (Ability, ability_called_shot)\|Called Shot]], [[Aimed Throw (Ability)\|Aimed Throw]] | Boss |
| Capstone | [[Fan of Blades (Ability)\|Fan of Blades]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
