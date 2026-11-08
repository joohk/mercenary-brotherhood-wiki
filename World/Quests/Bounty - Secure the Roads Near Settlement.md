---
id: bounty_clear_territory
type: quest
category: Quests
subtype: bounties
aliases:
  - bounty_clear_territory
  - "Bounty: Secure the Roads Near {settlement_name}"
tags:
  - quest/bounties
  - quest_type/bounty
  - type/quest
source: quests/bounties.json
bounty_subtype: multi_warband
company_level_max: 8
company_level_min: 3
difficulty_tier: 2
giver_type: settlement
gold_max: 500
gold_min: 310
quest_type: bounty
reputation_change: 8
xp_company: 50
xp_squad: 35
---

A bounty for company level 3-8, given by a settlement. In game the title reads `Bounty: Secure the Roads Near {settlement_name}`, with the blanks filled in when it is posted.

> Travelers report *faction* warbands blocking the roads near *settlement*. Clear them out.

## Overview

|  | Value |
|---|---|
| Type | Bounty |
| Bounty kind | Multi Warband |
| Given by | A settlement |
| [[Glossary#Numbers used on this wiki\|Company level]] | 3-8 |
| Difficulty tier | 2 of 5 |
| Time limit | None |
| Enemy faction | Chosen when the quest is posted |
| Area | within 12 hexes of the settlement |

**Hint:** Hunt *faction* warbands close to *settlement*.

## Objectives

| Objective | Type | Count | Target |
|---|---|---|---|
| Defeat *faction* warbands near *settlement* | Defeat Warbands | 2 | the chosen faction |

## Rewards

|  | Value |
|---|---|
| Gold | 310-500 |
| Company XP | 50 |
| Squad XP | 35 |
| Reputation | +8 |
| Settlement security | +12 |

## Bounty board text

How this bounty reads on the bounty board:

- **Title:** Bounty: Secure the Nearby Roads
- **Description:** Travelers report *faction* warbands blocking the nearby roads. Clear them out.
- **Hint:** Hunt *faction* warbands in the surrounding area.

## Where it is offered

Posted dynamically as a bounty contract; the target faction is chosen at posting.

*Generated from `quests/bounties.json`. Edits will be overwritten — put your own notes in Notes/.*
