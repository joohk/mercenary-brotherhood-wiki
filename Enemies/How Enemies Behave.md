---
type: ai_profile_page
tags:
  - type/ai_profile_page
source: ai/ai_profiles.json
up: "[[Bestiary]]"
---

[[Home]] › [[Bestiary]]

Every enemy faction fights with one of 7 AI profiles. The profile decides how well units coordinate, whom they target and when they break.

## Profiles and stances

An enemy's **AI profile** comes from its faction (see the table below). Separately, each unit has a **stance** — the `ai_behavior` field (older files call it `ai_profile`), with the values aggressive, defensive and ranged. The stance is a per-unit fighting style, **not** one of the profiles on this page:

- **Aggressive** (125 units): closes in and fights in melee.
- **Defensive** (13 units): holds its ground and protects its allies.
- **Ranged** (50 units): keeps its distance and attacks from range.

Reading the profiles: percentages are tendencies (0% never, 100% always), shown in words as high (70%+), medium (40-60%) and low. The *weights* are relative target-scoring values; how the AI combines them is not stated in the data.

If a faction is not listed, the default profile is [[How Enemies Behave#Undisciplined|Undisciplined]].

## Disciplined

*Holds formation, coordinated.*

**High:** coordination, focus fire, guarding its ranged units, hunting healers and casters · **Low:** flanking

Targets the weakest target. Holds the line; flees when alone. Retreats when wounded (30%).

| Setting | Value |
|---|---|
| Coordination | 90% |
| Focus fire | 80% |
| Flanking | 30% |
| Protects its ranged units | 70% |
| Goes after healers and casters | 70% |
| Retreats when wounded | 30% |
| Targets | the weakest target |
| Holds the line | Yes |
| Flees when alone | Yes |
| Hit-chance weight | 25 |
| Kill-securing weight | 100 |
| Morale-pressure weight | 15 |
| Surround weight | 8 |

**Factions:** [[Duergar]], [[Kesharan Dominion]], [[Ratkin Empire]], [[Saurian Legions]], [[The Inquisition]]

## Professional

*Skilled and pragmatic.*

**High:** coordination · **Medium:** focus fire, flanking, guarding its ranged units, hunting healers and casters

Targets the most dangerous target. Flees when alone. Retreats when wounded (25%).

| Setting | Value |
|---|---|
| Coordination | 70% |
| Focus fire | 60% |
| Flanking | 40% |
| Protects its ranged units | 50% |
| Goes after healers and casters | 50% |
| Retreats when wounded | 25% |
| Targets | the most dangerous target |
| Holds the line | No |
| Flees when alone | Yes |
| Hit-chance weight | 20 |
| Kill-securing weight | 90 |
| Morale-pressure weight | 10 |
| Surround weight | 6 |

**Factions:** [[Deserters]], [[Rival Mercenaries]], [[Veteran Company]]

## Undisciplined

*Unpredictable, low coordination.*

**Medium:** flanking · **Low:** coordination, focus fire, guarding its ranged units · **None:** hunting healers and casters

Targets random targets. Flees when alone; scatters when its leader dies. Never retreats when wounded.

| Setting | Value |
|---|---|
| Coordination | 30% |
| Focus fire | 30% |
| Flanking | 40% |
| Protects its ranged units | 10% |
| Goes after healers and casters | 0% |
| Retreats when wounded | 0% |
| Targets | random targets |
| Holds the line | No |
| Flees when alone | Yes |
| Scatters when its leader dies | Yes |

**Factions:** [[Bandits]], [[Desperate Rabble]], [[Feral Gnolls]], [[Greenskin Warband]], [[Wilding Elves]]

This is the default profile for any faction not in the map.

## Swarm

*Flanks and surrounds.*

**High:** flanking · **Medium:** coordination, focus fire · **None:** guarding its ranged units, hunting healers and casters

Targets the nearest target. Flees when alone; tries to surround. Never retreats when wounded.

| Setting | Value |
|---|---|
| Coordination | 50% |
| Focus fire | 40% |
| Flanking | 70% |
| Protects its ranged units | 0% |
| Goes after healers and casters | 0% |
| Retreats when wounded | 0% |
| Targets | the nearest target |
| Holds the line | No |
| Flees when alone | Yes |
| Tries to surround | Yes |
| Surround weight | 10 |

**Factions:** [[Beasts]], [[Ratkin Swarm]], [[Wolf Pack (Faction)|Wolf Pack]]

## Relentless

*Fearless, charges without thought.*

**Low:** coordination, focus fire · **None:** flanking, guarding its ranged units, hunting healers and casters

Targets the nearest target. Fearless. Never retreats when wounded.

| Setting | Value |
|---|---|
| Coordination | 5% |
| Focus fire | 10% |
| Flanking | 0% |
| Protects its ranged units | 0% |
| Goes after healers and casters | 0% |
| Retreats when wounded | 0% |
| Targets | the nearest target |
| Holds the line | No |
| Fearless | Yes |

**Factions:** [[The Dread Host]], [[The Restless Dead]]

## Cunning

*Intelligent and devious.*

**High:** coordination, focus fire, hunting healers and casters · **Medium:** flanking, guarding its ranged units

Targets the most dangerous target. Flees when alone; ranged units keep their distance. Retreats when wounded (35%).

| Setting | Value |
|---|---|
| Coordination | 85% |
| Focus fire | 70% |
| Flanking | 60% |
| Protects its ranged units | 60% |
| Goes after healers and casters | 80% |
| Retreats when wounded | 35% |
| Targets | the most dangerous target |
| Holds the line | No |
| Flees when alone | Yes |
| Ranged units keep their distance | Yes |
| Hit-chance weight | 30 |
| Kill-securing weight | 120 |
| Morale-pressure weight | 20 |
| Surround weight | 10 |

**Factions:** [[Cult of the Hollow Eye]], [[Demons]], [[Swamp Dwellers]], [[The Jotunblight]], [[The Umbral Court]], [[Vampires]]

## Elite

*Dangerous and coordinated.*

**High:** coordination, focus fire, guarding its ranged units, hunting healers and casters · **Medium:** flanking

Targets the most dangerous target. Never retreats when wounded.

| Setting | Value |
|---|---|
| Coordination | 95% |
| Focus fire | 90% |
| Flanking | 50% |
| Protects its ranged units | 80% |
| Goes after healers and casters | 90% |
| Retreats when wounded | 0% |
| Targets | the most dangerous target |
| Holds the line | No |
| Hit-chance weight | 35 |
| Kill-securing weight | 140 |
| Morale-pressure weight | 25 |
| Surround weight | 12 |

**Factions:** none. Which units use it is not stated in the data; the name suggests the [[Arch-Villains]].

## Faction profiles

| Faction | Profile | Faction tweak |
|---|---|---|
| [[Bandits]] | [[How Enemies Behave#Undisciplined\|Undisciplined]] | — |
| [[Beasts]] | [[How Enemies Behave#Swarm\|Swarm]] | Goes after healers and casters 20% |
| [[Cult of the Hollow Eye]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[Demons]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[Deserters]] | [[How Enemies Behave#Professional\|Professional]] | — |
| [[Desperate Rabble]] | [[How Enemies Behave#Undisciplined\|Undisciplined]] | — |
| [[Duergar]] | [[How Enemies Behave#Disciplined\|Disciplined]] | — |
| [[Feral Gnolls]] | [[How Enemies Behave#Undisciplined\|Undisciplined]] | — |
| [[Greenskin Warband]] | [[How Enemies Behave#Undisciplined\|Undisciplined]] | Coordination 40%, Focus fire 40% |
| [[Kesharan Dominion]] | [[How Enemies Behave#Disciplined\|Disciplined]] | — |
| [[Ratkin Empire]] | [[How Enemies Behave#Disciplined\|Disciplined]] | — |
| [[Ratkin Swarm]] | [[How Enemies Behave#Swarm\|Swarm]] | Goes after healers and casters 30% |
| [[Rival Mercenaries]] | [[How Enemies Behave#Professional\|Professional]] | — |
| [[Saurian Legions]] | [[How Enemies Behave#Disciplined\|Disciplined]] | — |
| [[Swamp Dwellers]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[The Dread Host]] | [[How Enemies Behave#Relentless\|Relentless]] | — |
| [[The Inquisition]] | [[How Enemies Behave#Disciplined\|Disciplined]] | — |
| [[The Jotunblight]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[The Restless Dead]] | [[How Enemies Behave#Relentless\|Relentless]] | Goes after healers and casters 0% |
| [[The Umbral Court]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[Vampires]] | [[How Enemies Behave#Cunning\|Cunning]] | — |
| [[Veteran Company]] | [[How Enemies Behave#Professional\|Professional]] | — |
| [[Wilding Elves]] | [[How Enemies Behave#Undisciplined\|Undisciplined]] | — |
| [[Wolf Pack (Faction)\|Wolf Pack]] | [[How Enemies Behave#Swarm\|Swarm]] | — |

## Faction overrides

These factions adjust their profile:

- [[Beasts]]: goes after healers and casters 20% (profile: 0%)
- [[Greenskin Warband]]: coordination 40% (profile: 30%); focus fire 40% (profile: 30%)
- [[Ratkin Swarm]]: goes after healers and casters 30% (profile: 0%)
- [[The Restless Dead]]: goes after healers and casters 0% (profile: 0%)

## Unit-type tweaks

Units whose id contains one of these words get extra adjustments on top of their faction profile. The game's matching rule is not in the data: the last column is a best guess (the word appears as a whole part of the unit's id).

*At least / at most* clamp how strongly the unit goes after healers and casters.

| Id word | Adjustment | Likely applies to |
|---|---|---|
| `abomination` | Goes after healers and casters (at most) 10% | [[Cult Abomination]] |
| `bandit_captain` | Goes after healers and casters (at least) 50% | [[Bandit Captain]] |
| `bog_lurker` | Goes after healers and casters (at most) 10% | [[Bog Lurker]] |
| `dark_general` | Goes after healers and casters (at least) 60% | [[Dark General]] |
| `frost_wolf` | Goes after healers and casters (at most) 10% | [[Frost Wolf]] |
| `goblin` | Goes after healers and casters 40%; Targets the weakest target | [[Goblin Poisoner]], [[Goblin Shaman (Enemy)\|Goblin Shaman]], [[Goblin Skirmisher]], [[Goblin Wolfrider]] |
| `hedge_witch` | Goes after healers and casters (at least) 50% | [[Goblin Bandit Shaman]] |
| `hound` | Goes after healers and casters (at most) 10% | [[Void Hound]] |
| `lich` | Goes after healers and casters (at least) 80% | [[Lich Commander]] |
| `marsh_crawler` | Goes after healers and casters (at most) 10% | [[Marsh Crawler]] |
| `mountain_cub` | Goes after healers and casters (at most) 10% | [[Mountain Cub]] |
| `necromancer` | Goes after healers and casters (at least) 70% | [[Necromancer]], [[War Necromancer]] |
| `ogre` | Targets the most dangerous target | [[Ogre]], [[Ogre Crusher]] |
| `orc` | Targets the most dangerous target | [[Orc Brute]], [[Orc Grunt]], [[Orc Shaman]], [[Orc Warchief]] |
| `shaman` | Goes after healers and casters (at least) 60% | [[Goblin Shaman (Enemy)\|Goblin Shaman]], [[Jotun Shaman]], [[Orc Shaman]], [[Ratkin Plague Shaman]], [[Thornwoad Shaman]] |
| `spider` | Goes after healers and casters (at most) 10% | [[Court Spider]], [[Giant Spider (Enemy, Beasts)\|Giant Spider (Beasts)]], [[Giant Spider (Enemy, Umbral Court)\|Giant Spider (The Umbral Court)]], [[Spider Broodling]] |
| `swamp_horror` | Goes after healers and casters (at most) 10% | [[Swamp Horror]] |
| `taskmaster` | Goes after healers and casters (at most) 100% | [[Duergar Taskmaster]], [[Thrall Taskmaster]] |
| `thrall` | Goes after healers and casters (at most) 20% | [[Dread Thrall]], [[Thrall Archer]], [[Thrall Crossbowman]], [[Thrall Guard]], [[Thrall Militia]], [[Thrall Slave]], [[Thrall Taskmaster]] |
| `troll` | Targets the most dangerous target | [[Bog Troll]], [[Cave Troll]] |
| `wolfrider` | Goes after healers and casters 40%; Targets the weakest target | [[Goblin Wolfrider]] |
| `wretch` | Goes after healers and casters (at most) 20% | [[Cult Wretch]] |

*Generated from `ai/ai_profiles.json`. Edits will be overwritten — put your own notes in Notes/.*
