---
id: quest_trade_revenge
type: quest
category: Quests
subtype: trade
aliases:
  - quest_trade_revenge
tags:
  - quest/trade
  - quest_type/escort
  - type/quest
source: quests/trade_quests.json
company_level_min: 2
difficulty_tier: 2
giver_type: settlement
gold_max: 420
gold_min: 250
quest_source: trade
quest_type: escort
reputation_change: 6
time_limit_days: 60
xp_company: 35
xp_squad: 20
---

A trade quest (escort) for company level 2+, given by a settlement.

> A merchant from *settlement* was robbed by *faction* near *destination*. Travel there, recover the goods, and return them here.

## Overview

|  | Value |
|---|---|
| Type | Escort |
| Given by | A settlement |
| [[Glossary#Numbers used on this wiki\|Company level]] | 2+ |
| Difficulty tier | 2 of 5 |
| Time limit | 60 days |
| Enemy faction | Chosen when the quest is posted |
| Destination | Chosen when the quest is posted |

**Hint:** Travel to *destination*, fight the *faction*, then return to *settlement*.

## Objectives

| Objective | Type | Count | Target |
|---|---|---|---|
| Travel to *destination* | Reach Location | 1 | the destination settlement |
| Defeat *faction* (*target count*) | Kill Enemies | 4 | the chosen faction |
| Return to *settlement* | Reach Location | 1 | the quest-giving settlement |

## Rewards

|  | Value |
|---|---|
| Gold | 250-420 |
| Company XP | 35 |
| Squad XP | 20 |
| Reputation | +6 |
| Faction relations | -3 with the chosen faction |

## Battle

The enemy warband is placed near the destination.

## Where it is offered

Posted by settlements from the trade system (market surpluses, shortages and escorts).

*Generated from `quests/trade_quests.json`. Edits will be overwritten — put your own notes in Notes/.*
