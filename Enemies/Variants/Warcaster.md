---
id: warcaster
type: variant_archetype
category: Enemy Variants
aliases:
  - warcaster
tags:
  - type/variant_archetype
  - variant/auto
source: variants/variant_pools.json
abilities: 10
assignment: auto
---

A variant archetype auto-assigned to enemies that already have magic abilities or carry a staff or wand.

> Offensive spellcasters — auto-assigned to enemies that already have magic abilities or a staff/wand.

## Ability pools

| Pool | Abilities | Drawn by |
|---|---|---|
| Lesser | [[Magic Missile]], [[Eldritch Blast]], [[Stone Shards]] | Elite, Champion |
| Greater | [[Fireball (Ability)\|Fireball]], [[Lightning Bolt (Ability)\|Lightning Bolt]], [[Ice Shard (Ability)\|Ice Shard]], [[Plague Bolt]] | Champion, Boss |
| Signature | [[Soul Rend (Ability)\|Soul Rend]], [[Telekinetic Crush]] | Boss |
| Capstone | [[Earthquake]] | Boss |

## How variants work

Any enemy can spawn as a stronger variant that gains extra abilities from its archetype's pools: an **Elite** draws 1 from the lesser pool, a **Champion** 2 from the lesser and greater pools, and a **Boss** 3: from the greater and signature pools plus one capstone. Bosses also have every ability cooldown reduced by 1 turn. All abilities in one archetype are of the same broad type, so a melee unit never gains a spell; racial abilities are only granted to units of that race.

Which archetype an enemy uses: the one its own data names, if any; otherwise it is classified from its stance, abilities and weapon — ranged units become [[Skirmisher (Variant)|Skirmisher]], spellcasters [[Warcaster]], healers [[Zealot (Variant)|Zealot]], and everything else [[Brute]]. Warlord and Shadow are never auto-assigned.

*Generated from `variants/variant_pools.json`. Edits will be overwritten — put your own notes in Notes/.*
