---
type: guide
tags:
  - guide/mechanics
source: game code (systems/encounter_builder.py and related)
---

How the game decides how strong a fight is. In short: **squad size and your mercenaries' levels set the size of every fight; company level decides which enemies can appear and how good they are; the day count plays no part.**

> [!info] Source
> Decoded from the compiled game code of the current Early Access build. The numbers are the game's own constants; a patch can change them.

## The threat budget

Every fight gets a **threat budget**. The game buys enemies with it until the budget is spent or the enemy cap is reached.

```
effective level  = company level + progress toward the next company level (0.0–1.0)
points per merc  = 2.0 at company level 1, 2.5 at 3, 3.5 at 8, 5.0 at 15 (straight lines in between)

budget = max(2, squad size × 0.8 × points per merc)
         × the encounter table's pool scale
         × (1 + 0.01 × total levels of every living mercenary you own)
         × Enemy Numbers setting × Threat Ladder multiplier

enemy cap = max(4, round(squad size × 1.5))
```

Each enemy costs its **threat cost** (shown on its page, e.g. [[Skink Screen]] costs 2). Enemies without one cost 2 / 3 / 5 / 8 / 12 for tiers 1–5. Enemies an [[Encounter Tables|encounter table]] marks as required always spawn and are paid for first.

## Party size

Party size counts twice: more mercenaries mean a bigger budget **and** a higher cap (1.5 enemies per mercenary, never fewer than 4). "Squad size" is the squad that is actually fighting.

| Squad (company level 4, mercs averaging level 5.5) | Budget | Enemy cap |
|---|---|---|
| 6 | ≈ 17 | 9 |
| 8 | ≈ 25 | 12 |
| 10 | ≈ 34 | 15 |

## Mercenary levels

**Every level of every living mercenary adds 1% to the budget, whether they fight or sit on the bench.** The game sums your whole company, not just the deployed squad.

- A mid-game squad of 8 at level 5.5 fights a budget of about 25. Add a bench of 8 more at the same level and every fight grows to about 32.5.
- In the endgame, 10 mercenaries averaging level 13.5 multiply the budget by 2.35.

## Company level

Company level does not just add points. It changes *which* enemies you meet and *how good* they are.

- **Which table you roll on.** Each terrain switches tables at set company levels (plains: early → mid at 5 → late at 8). Once you are past halfway to your next company level, groups meant for that level start to mix in.
- **Points per mercenary**, from the formula above.
- **Elite, Champion and Boss chances** per enemy (see [[Enemy Variants]]):

| Company level | Elite | Champion | Boss |
|---|---|---|---|
| 1–2 | 0% | 0% | 0% |
| 3–5 | 6% | 0% | 0% |
| 6–10 | 15% | 10% | 0% |
| 11–15 | 20% | 10% | 2% |
| 16+ | 30% | 15% | 5% |

Each fight also has a 5% chance to upgrade one enemy a rank above what your level normally allows.

- **Enemy stats.** From company level 5, enemy damage rises 6% per level, capped at +50% (reached around level 13). Enemy [[Stats#Initiative|Initiative]] gains +3 per level above 5, up to 80.

## Time

**Time does not scale fights.** The day count appears nowhere in the budget, enemy stats or variant rolls. Taking it slow does not make fights harder; levelling does. The developer's balance tests assume roughly company level 1 by day 15, 4 by day 75, 7 by day 180 and 10 by day 300, but that is only the expected pace.

The one clock-driven system is **invasions**. Each enemy faction with a stronghold near you fills an aggression meter by `0.6 + 0.085 × company level` per day, plus more on higher Threat Ladder tiers. At 100 it sends 3–5 warbands at a settlement: roughly every 146 days at company level 1, 98 at level 5 and 69 at level 10.

## Other multipliers

| Factor | Effect |
|---|---|
| **Enemy Numbers** (new-game setting) | Budget ×0.7 fewer · ×1.0 standard · ×1.3 more · ×1.6 horde (horde also raises the cap by a third) |
| **Veteran Threat** (new-game setting) | Picks tables as if you were −1 / 0 / +2 / +3 company levels; the two hardest settings add a 6% or 12% minimum Elite chance |
| **Threat Ladder** (0–10, chosen per run) | +6% budget per tier, up to ×1.6 |
| **Where you are on the map** (random encounters) | Company level used: −2 in the core, −1 inner, 0 middle, +1 outer edge. Elite rates ×0.3 / ×0.7 / ×1.0 / ×1.8. From company level 3 the edge always includes at least one Elite. |

## Map warbands are frozen

Visible [[Enemy Warbands|warbands]] build their roster **when they spawn**, from your first squad's size and your company level at that moment, and never change afterwards. A band that has wandered since you were weaker stays weaker.

## Related

- [[Encounter Tables]] · [[Enemy Variants]] · [[Enemy Warbands]] · [[Factions]]
