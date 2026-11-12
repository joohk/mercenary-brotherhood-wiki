---
type: guide
tags:
  - guide/mechanics
source: game code (systems/skill_system.py, modes/tactical/ability_resolver.py, combat_manager.py)
---

How skill traits, their ranks and their upgrades work, and why an ability's tooltip never changes when you upgrade it.

> [!info] Source
> Decoded from the compiled game code of the current Early Access build; a patch can change it.

## Ranks replace, they don't stack

A skill trait's **rank 1** applies its base effects, for example granting the [[Fireball (Ability)|Fireball]] spell. Each upgrade rank **replaces** the previous rank's effects with its own:

- Going from rank 1 to rank 2 removes rank 1's effects and applies rank 2's.
- Any ability the trait granted at rank 1 is carried over, so you never lose the spell itself.
- Rank 3 replaces rank 2 in the same way. In the current data, every rank 3 either keeps rank 2's upgrade or swaps it for a stronger "mastery" version that the code checks first, so nothing is lost.

## Upgrades are hidden tags

Most ability upgrades don't change any number you can see. They give the unit a hidden **upgrade tag** such as `fireball_improved`, and the ability's code checks for that tag when it runs. For example, Fireball with `fireball_improved` deals ×1.3 damage.

There are two consequences:

- **Tooltips never show upgrades.** The combat tooltip is built only from the ability's base data: description, AP, fatigue, range, cooldown and uses. That's true for every ability, so an unchanged tooltip is not a sign that an upgrade failed.
- **Descriptions can be vague.** Many say only "deals increased damage". [[Ability Upgrade Values]] lists the exact numbers for every decoded upgrade, next to what the game says.

## Extra uses, range and cost

A few upgrades change an ability's numbers directly instead:

| Change | Abilities |
|---|---|
| Extra uses per battle | Second Wind, Sprint, Command, Frenzy, Penetrating Bolt, Exploit Opening, Brace → 2 · Coup de Grace, Shatter, Sundering Blow (rank 3), Twin Strike (rank 3) → 3 · Decapitate (rank 3) → 2 · Death or Glory +1 |
| Longer range | Lance Rush +1 · Warpath +2 |
| Bigger blast radius (+1) | Fire Bomb · Volley · Earthquake · TK Shatter |
| Lower fatigue cost | Decapitate −5 |

One upgrade's promise isn't kept: **Shadow Strike** says its range rises to 4 (rank 2) and 5 (rank 3), but no code extends it, so it stays 3. Its damage bonuses do work.

## Related

- [[Ability Upgrade Values]] · [[Skills]] · [[Skill Traits]] · [[Abilities]]
