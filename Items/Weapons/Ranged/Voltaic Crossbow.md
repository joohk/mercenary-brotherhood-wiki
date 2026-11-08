---
id: voltaic_crossbow
type: item
category: Items
subtype: weapons_ranged
aliases:
  - voltaic_crossbow
tags:
  - item/ranged-weapon
  - slot/ranged
  - tier/5
  - type/item
source: items/weapons_ranged.json
damage_max: 32
damage_min: 22
damage_type: piercing
family: mechanical crossbow
hands: two-handed
price: 2160
range: 6
rarity: normal
slot: ranged
spawn_weight: 3
tier: 5
---

A tier-5 two-handed piercing mechanical crossbow dealing 22-32 damage at range 6, worth 2160 gold.

![[_assets/Icons/tier_5/crossbow.webp|96]]

## Stats

| Stat | Value |
|---|---|
| Tier | 5 |
| Damage type | Piercing |
| Hands | Two-handed |
| Ranged Damage | 22-32 |
| [[Stats#Armor Pen\|Armor Pen]] | +8 |
| [[Stats#Initiative\|Initiative]] | -5 |
| Range | 6 hexes |
| Price | 2160 |
| Rarity | Normal |
| [[Glossary#Numbers used on this wiki\|Spawn weight]] | 3 |

## Effects

- On hit: lowers the target's Initiative (20%)

## Gnome gear

Mechanical weapon: units that are not gnomes and lack the [[Tinkering]] skill take -10 to hit with it. Carrying a gadget is what lets a unit build up hidden Tinkering proficiency.

## Same line

Items of this line, by tier: [[Springlock Crossbow]] (T1) → [[Repeating Crossbow]] (T2) → [[Pressure-Bolt Crossbow]] (T3) → [[Steamwinder Crossbow]] (T4) → **Voltaic Crossbow** (T5) → [[Cogwork Arbalest]] (T6)

## Related

- **Tags:** Crossbow, Ranged, Two-handed, Mechanical, Gadget, Gnome Crafted

> [!note]- Developer notes
> Gnome Mechanical Crossbows — slightly lower damage than standard crossbows, but special passives at higher tiers. -10 hit penalty for non-gnomes without skill_tinkering (keyed on the 'mechanical' tag). The 'gadget' tag is load-bearing: it is skill_tinkering's discovery_tags gate, so carrying one is what lets a unit accrue hidden Tinkering proficiency from gadget use.

*Generated from `items/weapons_ranged.json`. Edits will be overwritten — put your own notes in Notes/.*
