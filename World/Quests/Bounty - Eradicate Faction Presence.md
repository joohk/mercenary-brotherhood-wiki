---
id: bounty_eradicate_presence
type: quest
category: Quests
subtype: bounties
aliases:
  - bounty_eradicate_presence
  - "Bounty: Eradicate {faction_name} Presence"
tags:
  - quest/bounties
  - quest_type/bounty
  - type/quest
source: quests/bounties.json
bounty_subtype: multi_warband
company_level_min: 6
difficulty_tier: 3
giver_type: settlement
gold_max: 980
gold_min: 630
quest_type: bounty
reputation_change: 14
xp_company: 100
xp_squad: 70
---

A bounty for company level 6+, given by a settlement. In game the title reads `Bounty: Eradicate {faction_name} Presence`, with the blanks filled in when it is posted.

> The *faction* have amassed a dangerous concentration of forces near *settlement*. Crush their warbands before they overwhelm the region.

## Overview

|  | Value |
|---|---|
| Type | Bounty |
| Bounty kind | Multi Warband |
| Given by | A settlement |
| [[Glossary#Numbers used on this wiki\|Company level]] | 6+ |
| Difficulty tier | 3 of 5 |
| Time limit | None |
| Enemy faction | Chosen when the quest is posted |
| Area | within 18 hexes of the settlement |

**Hint:** Destroy *faction* warbands near *settlement*.

## Objectives

| Objective | Type | Count | Target |
|---|---|---|---|
| Defeat *faction* warbands near *settlement* | Defeat Warbands | 4 | the chosen faction |

## Rewards

|  | Value |
|---|---|
| Gold | 630-980 |
| Company XP | 100 |
| Squad XP | 70 |
| Reputation | +14 |
| Settlement security | +20 |
| Faction relations | -8 with the chosen faction |

## Bounty board text

How this bounty reads on the bounty board:

- **Description:** A dangerous concentration of *faction* forces has gathered nearby. Crush their warbands before they overwhelm the region.
- **Hint:** Destroy *faction* warbands in the surrounding area.

## Where it is offered

Posted dynamically as a bounty contract; the target faction is chosen at posting.

*Generated from `quests/bounties.json`. Edits will be overwritten — put your own notes in Notes/.*
