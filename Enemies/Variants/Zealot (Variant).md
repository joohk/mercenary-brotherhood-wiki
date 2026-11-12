---
id: zealot
type: variant_archetype
category: Enemy Variants
aliases:
  - Zealot
  - zealot
tags:
  - type/variant_archetype
  - variant/auto
source: variants/variant_pools.json
abilities: 7
assignment: auto
up: "[[Enemy Variants]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Variants]]

A variant archetype auto-assigned to enemies that already have a healing ability.

> Holy/support casters — auto-assigned to enemies that already have a heal ability. Heals + smites.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Minor Heal]], [[Smite Undead]] | Elite, Champion |
| Greater | [[Mend (Ability)\|Mend]], [[Sunburst (Ability)\|Sunburst]], [[Arcane Shield (Ability)\|Arcane Shield]] | Champion, Boss |
| Signature | [[Martyr's Grace (Ability)\|Martyr's Grace]] | Boss |
| Capstone | [[Bloom of Life (Ability)\|Bloom of Life]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
