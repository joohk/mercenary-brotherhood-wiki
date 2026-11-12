---
id: shadow
type: variant_archetype
category: Enemy Variants
aliases:
  - shadow
tags:
  - type/variant_archetype
  - variant/explicit
source: variants/variant_pools.json
abilities: 7
assignment: explicit
up: "[[Enemy Variants]]"
---

[[Home]] › [[Bestiary]] › [[Enemy Variants]]

A variant archetype given only to enemies that name it in their data.

> [!warning] Unused
> No enemy in the shipped data sets this archetype, so it never appears in play unless a mod assigns it.

> Assassins / rogues — dagger strikes, mobility, a little shadow magic.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Shadow Strike (Ability)\|Shadow Strike]], [[Slip Strike (Ability)\|Slip Strike]] | Elite, Champion |
| Greater | [[Lacerate (Ability)\|Lacerate]], [[Throat Slash (Ability)\|Throat Slash]], [[Shadow Walk]] | Champion, Boss |
| Signature | [[Decapitate (Ability)\|Decapitate]] | Boss |
| Capstone | [[Shadow Nova]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
