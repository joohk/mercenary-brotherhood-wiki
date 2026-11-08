---
id: bounty_purge_region
type: quest
category: Quests
subtype: bounties
aliases:
  - bounty_purge_region
  - "Bounty: Purge {faction_name} Near {settlement_name}"
tags:
  - quest/bounties
  - quest_type/bounty
  - type/quest
source: quests/bounties.json
bounty_subtype: multi_warband
company_level_max: 7
company_level_min: 3
difficulty_tier: 2
giver_type: settlement
gold_max: 560
gold_min: 350
quest_type: bounty
reputation_change: 10
xp_company: 60
xp_squad: 40
---

A bounty for company level 3-7, given by a settlement. In game the title reads `Bounty: Purge {faction_name} Near {settlement_name}`, with the blanks filled in when it is posted.

> The *leader title* of *settlement* demands the *faction* be driven from the surrounding area. Defeat their warbands near the settlement.

## Overview

|  | Value |
|---|---|
| Type | Bounty |
| Bounty kind | Multi Warband |
| Given by | A settlement |
| [[Glossary#Numbers used on this wiki\|Company level]] | 3-7 |
| Difficulty tier | 2 of 5 |
| Time limit | None |
| Enemy faction | Chosen when the quest is posted |
| Area | within 15 hexes of the settlement |

**Hint:** Defeat *faction* warbands near *settlement*.

## Objectives

| Objective | Type | Count | Target |
|---|---|---|---|
| Defeat *faction* warbands near *settlement* | Defeat Warbands | 3 | the chosen faction |

## Rewards

|  | Value |
|---|---|
| Gold | 350-560 |
| Company XP | 60 |
| Squad XP | 40 |
| Reputation | +10 |
| Settlement security | +15 |
| Faction relations | -5 with the chosen faction |

## Bounty board text

How this bounty reads on the bounty board:

- **Title:** Bounty: Drive Out *faction*
- **Description:** A camp of *faction* has settled nearby and is raiding the surrounding area. Drive their warbands out and collect the bounty.
- **Hint:** Defeat *faction* warbands in the surrounding area.

## Where it is offered

Posted dynamically as a bounty contract; the target faction is chosen at posting.

*Generated from `quests/bounties.json`. Edits will be overwritten — put your own notes in Notes/.*
