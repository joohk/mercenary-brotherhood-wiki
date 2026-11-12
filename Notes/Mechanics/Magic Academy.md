---
type: guide
tags:
  - guide/mechanics
source: game code (systems/arcane_training_manager.py) + settlements data
---

The **Arcane Training** service teaches spells for gold. Only two settlements offer it: [[Lyceum of Ashenmoor]] and [[Academy of the Veiled Star]].

> [!info] Source
> Decoded from the compiled game code of the current Early Access build; a patch can change it.

## How it works

| | |
|---|---|
| Spells on offer | 4, picked at random from every ability tagged *magic* (83 in the current data) |
| Restock | Every 14 days |
| Price | 300 gold, +100 for an area spell, +50 for a healing or holy spell |
| Who can learn | Any mercenary who can cast spells, whether from their background or from earlier training |
| Can't learn | A spell the mercenary already has from any source, or one of their race's own abilities |

A taught spell is permanent.

## Known bug: Awakening spells for sale

The academy's pool is every *magic*-tagged ability, and nothing excludes the **Awakening** abilities, which you would normally get only from Awakening traits. 14 of the 83 are Awakening spells:

Mass Haste · Meteor Strike · Arcane Nova · Levitate · Absorb Material · Blur · Gravitational Crush · Phase Shift · Nature Walk · Rift Walk · Life Clone · Invisibility · Ghost Walk · Cataclysm

With 4 picks per restock, about **half of all restocks offer at least one of them**. If you bought one by accident, [[Save Files]] explains how to remove it.

## Related

- [[Skill Traits and Upgrades]] · [[Settlements]] · [[Abilities]]
