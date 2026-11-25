---
type: page
aliases:
  - Race Locations
  - Where to recruit
  - Recruit pools
tags:
  - type/page
source:
  - "settlements/*.json"
  - "races/*.json"
  - foundings/foundings.json
  - guilds/guilds.json
  - traits/company_traits.json
  - pois/poi_templates.json
  - "backgrounds/*.json"
up: "[[Your Company]]"
---

[[Home]] › [[Your Company]]

Where each race can be recruited, with every weight, gate and modifier in the game data that decides who shows up in a settlement's recruit pool, a guild hall or your starting draft.

## How recruit pools are built

- **Settlement recruit pools** draw each candidate's race from the settlement's `racial_composition`. These are the shares shown under *Population* on every settlement page. The tables below give the raw weight and the "Share", which is the weight divided by that settlement's total.
- **Race gate (`recruitment_threshold`).** Every race has one: 0, 5, 10, 12 or 15 (see the finder). The data's note on foundings says a race "is only added to town recruit pools once it clears the company-level gate", and that races below 5 are common. So a threshold-15 race can live in a town without showing up in its recruit pool early on.
- **`racial_availability`** is a per-settlement override field. It is empty for every settlement in the current data.
- **Retired races:** a race with `recruitable: false` still lives in settlements but never appears in a hire pool.
- **Background:** after the race is picked, the recruit's background is rolled from that race's `available_backgrounds`, weighted by each background's `recruitment_weight` (see [[Where Backgrounds Come From]]). Backgrounds marked `temple_only` are offered only at temples.
- **Name:** recruits are named from their home realm's pool first, and from the race's own pool only if the realm has none (see [[Recruit Names]]). So a name tells you the realm, not the race.
- **Crossroads Tavern** (a map point of interest; 10 on the map) keeps a pool of 3 recruits that refreshes every 21 days. The data gives it no race rule.

## Company traits that change recruiting

| Company trait | Modifier | Value | In-game text |
|---|---|---|---|
| [[Affordable Contracts]] | Hire Cost Multiplier | 0.75 | Fair terms and a strong reputation make hiring cheaper. Recruitment costs reduced by 25%. |
| [[Cultural Bridge]] | Recruitment Threshold Reduction | 5 | The company's diversity is its strength. Racial relation thresholds for recruitment reduced by 5. |
| [[Famous Banner]] | Recruit Arrive Multiplier | 1.5 | Warriors seek out this company's banner. Recruitment pools refill 50% faster. |
| [[Loyal Ranks]] | Recruit Leave Multiplier | 0.4 | Recruits stick around, waiting for their chance. Recruit pool attrition reduced by 60%. |
| [[Talent Scouts]] | Exotic Race Multiplier | 2 | The company's scouts travel far to find exceptional recruits. Uncommon and rare races appear twice as often. |

## Prime Race Clan founding

Under the [[Prime Race Clan]] founding, every race is Prime, Friendly or Other. Its pool weight is multiplied, and a Prime or Friendly race that isn't native to a settlement is added with a base weight so it can still appear.

| Tier | Pool weight | Base weight where not native | Hire cost | Upkeep |
|---|---|---|---|---|
| Prime | ×8 | 1 | ×0.7 | ×0.8 |
| Friendly | ×3 | 0.4 | ×1.15 | ×1.15 |
| Other | ×0.1 | — | ×2 | ×1.75 |

| Prime race | Friendly races |
|---|---|
| [[Dwarf]] | [[Human]], [[Gnome]], [[Stoneman]], [[Halfling]] |
| [[Elf]] | [[Wild Elf]], [[Sylphborne]], [[Spriggan]], [[Halfling]] |
| [[Goblin]] | [[Orc]], [[Half-Troll]], [[Gnoll]], [[Ratkin]] |
| [[Halfling]] | [[Human]], [[Gnome]], [[Elf]], [[Dwarf]] |
| [[Human]] | [[Dwarf]], [[Elf]], [[Halfling]], [[Gnome]] |
| [[Orc]] | [[Goblin]], [[Half-Ogre]], [[Half-Troll]], [[Minotaur]] |

## Outcasts founding

The [[Outcasts]] starting draft draws only from [[Dark Elf]], [[Half-Ogre]], [[Tiefling]], [[Wolfkin]], [[Orc]], up to 4 picks. Recruiting after the start is normal.

## Race finder

Thr is the race's `recruitment_threshold`. "Main in" counts the settlements where this race is the largest group.

| Race | Thr | Hireable | Settlements | Main in | Highest shares |
|---|---|---|---|---|---|
| [[Where Races Live#Arachne\|Arachne]] | 15 | No | 0 | 0 | — |
| [[Where Races Live#Dark Elf\|Dark Elf]] | 5 | Yes | 37 | 20 | [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Moonless]] 75% |
| [[Where Races Live#Deepkin\|Deepkin]] | 15 | Yes | 44 | 17 | [[Crystalspring]] 75%, [[Deephollow Proper]] 75%, [[Deepkeep]] 75% |
| [[Where Races Live#Dragolin\|Dragolin]] | 15 | Yes | 5 | 2 | [[Dragon's Perch]] 40%, [[Dragonscar]] 30%, [[Ember's Edge]] 10% |
| [[Where Races Live#Dwarf\|Dwarf]] | 0 | Yes | 128 | 32 | [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75% |
| [[Where Races Live#Elf\|Elf]] | 0 | Yes | 58 | 19 | [[Evenshade]] 75%, [[Moonleaf Ward]] 75%, [[Silverbough]] 75% |
| [[Where Races Live#Frostborn\|Frostborn]] | 15 | Yes | 8 | 2 | [[Glacierfall]] 45%, [[Rimespire]] 40%, [[Emberfall]] 20% |
| [[Where Races Live#Gnoll\|Gnoll]] | 12 | Yes | 0 | 0 | — |
| [[Where Races Live#Gnome\|Gnome]] | 0 | Yes | 102 | 13 | [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75% |
| [[Where Races Live#Goblin\|Goblin]] | 0 | Yes | 178 | 22 | [[Boglight]] 75%, [[Fangmarket]] 75%, [[Grubstake Fort]] 75% |
| [[Where Races Live#Half-Ogre\|Half-Ogre]] | 5 | Yes | 26 | 0 | [[Grimtusk Hold]] 20%, [[Bloodrock]] 15%, [[Bonehill]] 15% |
| [[Where Races Live#Half-Troll\|Half-Troll]] | 15 | Yes | 10 | 0 | [[Slag Furnace]] 20%, [[Grimtusk Hold]] 15%, [[Wolfspire]] 15% |
| [[Where Races Live#Halfling\|Halfling]] | 0 | Yes | 136 | 16 | [[Appleburrow]] 75%, [[Buttercup Hollow]] 75%, [[Honeystead]] 75% |
| [[Where Races Live#Human\|Human]] | 0 | Yes | 213 | 66 | [[Elmsworth]] 75%, [[Hollowfield]] 75%, [[Rivermere]] 75% |
| [[Where Races Live#Lizardfolk\|Lizardfolk]] | 0 | Yes | 11 | 5 | [[Boghollow]] 45%, [[Fenwatch]] 40%, [[Scalemire]] 40% |
| [[Where Races Live#Minotaur\|Minotaur]] | 15 | Yes | 9 | 2 | [[Horn's End]] 40%, [[Labyrinth's Gate]] 40%, [[Emberheart Forge]] 15% |
| [[Where Races Live#Orc\|Orc]] | 0 | Yes | 101 | 20 | [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Gorewhistle]] 75% |
| [[Where Races Live#Ratkin\|Ratkin]] | 12 | Yes | 4 | 0 | [[Gloomweb Market]] 20%, [[The Blind Bazaar]] 15%, [[The Crawling Dark]] 10% |
| [[Where Races Live#Spriggan\|Spriggan]] | 15 | Yes | 15 | 1 | [[Sporewick]] 40%, [[Starfall Glade]] 20%, [[Ironroot]] 20% |
| [[Where Races Live#Stoneman\|Stoneman]] | 15 | Yes | 18 | 0 | [[Abyssal Throne]] 25%, [[Emberheart Forge]] 25%, [[Iron Tomb Garrison]] 25% |
| [[Where Races Live#Sylphborne\|Sylphborne]] | 15 | Yes | 4 | 1 | [[Zephyr's Rest]] 45%, [[Moonhollow]] 15%, [[Windhaven]] 15% |
| [[Where Races Live#Tiefling\|Tiefling]] | 5 | Yes | 43 | 15 | [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75% |
| [[Where Races Live#Vampling\|Vampling]] | 15 | Yes | 21 | 1 | [[Nightbloom]] 35%, [[Nightveil]] 20%, [[Mistwall]] 15% |
| [[Where Races Live#Wild Elf\|Wild Elf]] | 10 | Yes | 0 | 0 | — |
| [[Where Races Live#Wolfkin\|Wolfkin]] | 5 | Yes | 28 | 15 | [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75% |
| [[Where Races Live#Wraithkin\|Wraithkin]] | 15 | Yes | 23 | 1 | [[Mistwall]] 35%, [[Umbral Gate]] 20%, [[Voidreach]] 20% |

## Arachne

[[Arachne]] · threshold 15 · **not hireable** (retired)

*This race is not in any settlement's population, so it never appears in settlement recruit pools. It can still come from a founding or guild, if the rules above allow it.*

**Guild backgrounds open to this race:** [[Reaver Hall]] (1 of 13), [[Blade Circle]] (1 of 10), [[Hunters' Lodge]] (3 of 11), [[Shadow Guild]] (7 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (1 of 12), [[Wildwardens]] (3 of 16), [[Cogwrights' Guild]] (3 of 10), [[Sawbones Hall]] (4 of 7)

## Dark Elf

[[Dark Elf]] · threshold 5

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Ashwoven]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Blackthread]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Moonless]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Shadowkin]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Silentstep]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Spider Court]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Spider Gate]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Spinelight]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Thornloom]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Umbral Redoubt]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Veilstone]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Weaver Hall]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Silkweb Grotto]] | Village | Surface | 0.45 | 45% | 1 of 4 |
| [[Umbral Gate]] | Fort | Surface | 0.45 | 45% | 1 of 5 |
| [[Spidersong Cavern]] | Village | Underground (mid) | 0.4 | 40% | 1 of 4 |
| [[Nightveil]] | Town | Surface | 0.4 | 40% | 1 of 5 |
| [[Gloomweb Market]] | Town | Underground (mid) | 0.3 | 30% | 1 of 5 |
| [[Shadowmere]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Duskhollow]] | Town | Underground (mid) | 0.25 | 25% | 1 of 5 |
| [[Nightbloom]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.2 | 20% | 2 of 6 |
| [[The Crawling Dark]] | Village | Underground (deep) | 0.2 | 20% | 2 of 5 |
| [[The Undermoot]] | Town | Underground (mid) | 0.2 | 20% | 1 of 6 |
| [[Cindervale]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Crowsreach]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Ember's Edge]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Mistwall]] | Village | Surface | 0.15 | 15% | 2 of 7 |
| [[Ravensholme]] | Town | Surface | 0.15 | 15% | 2 of 7 |
| [[Sablewood]] | Town | Surface | 0.15 | 15% | 2 of 7 |
| [[Voidreach]] | Town | Underground (deep) | 0.15 | 15% | 3 of 6 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.1 | 10% | 4 of 7 |
| [[Abyssal Throne]] | Fort | Underground (deep) | 0.1 | 10% | 5 of 5 |
| [[Blackmarket]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Drifter's Hollow]] | Village | Surface | 0.1 | 10% | 5 of 7 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.1 | 10% | 5 of 8 |
| [[Vagrant's Rest]] | Village | Surface | 0.1 | 10% | 5 of 7 |
| [[Blackthorn]] | Village | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Reaver Hall]] (1 of 13), [[Blade Circle]] (4 of 10), [[Hunters' Lodge]] (1 of 11), [[Shadow Guild]] (8 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (7 of 12), [[Holy Order]] (1 of 12), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (1 of 7)

## Deepkin

[[Deepkin]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Crystalspring]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Deephollow Proper]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Deepkeep]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Echohollow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Lowveil]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Moonshade Caverns]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Shaftwarden]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Stonefoot]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Underwell]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Vault of Silentstone]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Vault Warden]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Saltgrotto]] | Village | Surface | 0.5 | 50% | 1 of 4 |
| [[Tidewash]] | Village | Surface | 0.45 | 45% | 1 of 6 |
| [[The Crawling Dark]] | Village | Underground (deep) | 0.4 | 40% | 1 of 5 |
| [[Abyssal Throne]] | Fort | Underground (deep) | 0.3 | 30% | 1 of 5 |
| [[Voidreach]] | Town | Underground (deep) | 0.3 | 30% | 1 of 6 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.25 | 25% | 1 of 6 |
| [[Silkweb Grotto]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Spidersong Cavern]] | Village | Underground (mid) | 0.2 | 20% | 2 of 4 |
| [[Stillwater]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Ashwoven]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Blackthread]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Duskhollow]] | Town | Underground (mid) | 0.15 | 15% | 4 of 5 |
| [[Gloomweb Market]] | Town | Underground (mid) | 0.15 | 15% | 4 of 5 |
| [[Moonless]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Shadowkin]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Silentstep]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Spider Court]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Spider Gate]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Spinelight]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Thornloom]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Umbral Gate]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Umbral Redoubt]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Veilstone]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Weaver Hall]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[The Undermoot]] | Town | Underground (mid) | 0.15 | 15% | 4 of 6 |
| [[Bogside]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Deepforge]] | Town | Surface | 0.1 | 10% | 4 of 4 |
| [[Emberheart Forge]] | Fort | Underground (deep) | 0.1 | 10% | 5 of 5 |
| [[Greenmaw]] | Village | Surface | 0.1 | 10% | 3 of 6 |
| [[Mudburrow]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Scalemire]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Yarmouth]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Boghollow]] | Village | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Reaver Hall]] (1 of 13), [[Shadow Guild]] (1 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (6 of 12), [[Holy Order]] (3 of 12), [[Wildwardens]] (2 of 16), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (3 of 7)

## Dragolin

[[Dragolin]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Dragon's Perch]] | Village | Surface | 0.4 | 40% | 1 of 7 |
| [[Dragonscar]] | Town | Surface | 0.3 | 30% | 1 of 7 |
| [[Ember's Edge]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Sunstone]] | Town | Surface | 0.1 | 10% | 5 of 7 |
| [[Emberpeak]] | Town | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (9 of 18), [[Reaver Hall]] (2 of 13), [[Blade Circle]] (2 of 10), [[Arcane Conclave (Guild)|Arcane Conclave]] (4 of 12), [[Holy Order]] (3 of 12), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (1 of 10)

## Dwarf

[[Dwarf]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Deephearth Forge]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Graniteford]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Hammerbrook]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Ironhall]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Stonewallow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Stonehearth]] | Town | Surface | 0.6 | 60% | 1 of 4 |
| [[Deepforge]] | Town | Surface | 0.55 | 55% | 1 of 4 |
| [[Deephollow]] | Town | Surface | 0.55 | 55% | 1 of 4 |
| [[Irondelve]] | Town | Surface | 0.55 | 55% | 1 of 4 |
| [[Anvilheim]] | Town | Surface | 0.5 | 50% | 1 of 5 |
| [[Copperhollow]] | Village | Surface | 0.5 | 50% | 1 of 4 |
| [[Hammerfell]] | Fort | Surface | 0.5 | 50% | 1 of 4 |
| [[Deepforge Hold]] | Fort | Underground (shallow) | 0.45 | 45% | 1 of 5 |
| [[Emberpeak]] | Town | Surface | 0.45 | 45% | 1 of 6 |
| [[Granitehold]] | Fort | Surface | 0.45 | 45% | 1 of 4 |
| [[Greystone]] | Village | Surface | 0.45 | 45% | 1 of 4 |
| [[Molehill Outpost]] | Village | Underground (shallow) | 0.4 | 40% | 1 of 4 |
| [[Goldseam]] | Village | Surface | 0.4 | 40% | 1 of 5 |
| [[Granite Watch]] | Fort | Underground (shallow) | 0.4 | 40% | 1 of 5 |
| [[Crystalheim]] | Town | Surface | 0.4 | 40% | 1 of 5 |
| [[Silverton]] | Town | Surface | 0.35 | 35% | 1 of 5 |
| [[Emberfall]] | Town | Surface | 0.35 | 35% | 1 of 4 |
| [[Emberheart Forge]] | Fort | Underground (deep) | 0.35 | 35% | 1 of 5 |
| [[Slag Furnace]] | Town | Underground (mid) | 0.35 | 35% | 1 of 5 |
| [[The Sunken Stair]] | Town | Underground (shallow) | 0.35 | 35% | 1 of 5 |
| [[Redhill]] | Town | Surface | 0.3 | 30% | 2 of 5 |
| [[Coalpit]] | Village | Surface | 0.3 | 30% | 1 of 5 |
| [[Crystalvein Refuge]] | Village | Underground (shallow) | 0.3 | 30% | 1 of 4 |
| [[Highwall]] | Fort | Surface | 0.3 | 30% | 1 of 6 |
| [[Iron Tomb Garrison]] | Fort | Underground (mid) | 0.3 | 30% | 1 of 5 |
| [[Copper Falls]] | Village | Surface | 0.25 | 25% | 1 of 6 |
| [[Duskhollow]] | Town | Underground (mid) | 0.25 | 25% | 2 of 5 |
| [[Fort Greymere]] | Fort | Surface | 0.25 | 25% | 2 of 5 |
| [[Fort Ironclad]] | Fort | Surface | 0.25 | 25% | 2 of 5 |
| [[Northvale]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Rootcellar Market]] | Village | Underground (shallow) | 0.25 | 25% | 2 of 4 |
| [[Stonefist]] | Fort | Surface | 0.25 | 25% | 2 of 5 |
| [[Thornwall]] | Fort | Surface | 0.25 | 25% | 1 of 5 |
| [[Abyssal Throne]] | Fort | Underground (deep) | 0.2 | 20% | 3 of 5 |
| [[Barrowdale]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Battleford]] | Fort | Surface | 0.2 | 20% | 3 of 6 |
| [[Border Watch]] | Fort | Surface | 0.2 | 20% | 1 of 7 |
| [[Brasswick]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Coppergate]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Cragmoor]] | Village | Surface | 0.2 | 20% | 2 of 7 |
| [[Flintmarch]] | Fort | Surface | 0.2 | 20% | 2 of 6 |
| [[Greyport]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Hollow Root]] | Village | Underground (shallow) | 0.2 | 20% | 2 of 5 |
| [[Ironhaven]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Kingsmead]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Pinecrest]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Rampart Keep]] | Fort | Surface | 0.2 | 20% | 3 of 5 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.2 | 20% | 2 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Spidersong Cavern]] | Village | Underground (mid) | 0.2 | 20% | 3 of 4 |
| [[Sprocketville]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Stormgate]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[The Broken Shield]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Whitegate]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Elmhurst]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Hawkridge]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Rimespire]] | Fort | Surface | 0.2 | 20% | 2 of 5 |
| [[The Undermoot]] | Town | Underground (mid) | 0.2 | 20% | 2 of 6 |
| [[Briarford]] | Town | Surface | 0.15 | 15% | 2 of 5 |
| [[Cogsworth]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Crossroads Landing]] | Town | Surface | 0.15 | 15% | 2 of 7 |
| [[Crystalspring]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Deephollow Proper]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Deepkeep]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Dragonscar]] | Town | Surface | 0.15 | 15% | 2 of 7 |
| [[Dunmoor]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Dusthaven Depot]] | Trading Post | Surface | 0.15 | 15% | 4 of 5 |
| [[Echohollow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Gallowfield]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Glacierfall]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Gloomweb Market]] | Town | Underground (mid) | 0.15 | 15% | 5 of 5 |
| [[Halfway House]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Ironroot]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.15 | 15% | 2 of 8 |
| [[Labyrinth's Gate]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Last Chance]] | Village | Surface | 0.15 | 15% | 4 of 5 |
| [[Lowveil]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.15 | 15% | 2 of 8 |
| [[Moonshade Caverns]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Old Garrison]] | Fort | Surface | 0.15 | 15% | 3 of 6 |
| [[Pilgrim's Rest]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Ravensholme]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Shaftwarden]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Slag Market]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Stonecross]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Stonefoot]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Sunstone]] | Town | Surface | 0.15 | 15% | 2 of 7 |
| [[Temple of the Dawn]] | Temple | Surface | 0.15 | 15% | 3 of 6 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.15 | 15% | 3 of 6 |
| [[Thornhaven]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Three Rivers]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Trader's Bluff]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Tradewind]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Underwell]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Vault of Silentstone]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Vault Warden]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Wayward Inn]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Yarmouth]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[The Crawling Dark]] | Village | Underground (deep) | 0.15 | 15% | 3 of 5 |
| [[Brassburrow Fort]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Buttonwood]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Cogwhisper]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Crossroads Market]] | Trading Post | Surface | 0.1 | 10% | 5 of 5 |
| [[Dragon's Perch]] | Village | Surface | 0.1 | 10% | 3 of 7 |
| [[Dusthaven]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Emerald Reach]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Filigree Glen]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Kettlebridge]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Lensmoor]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Muleford]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Pinmoor]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Ratchet Grove]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.1 | 10% | 5 of 6 |
| [[Spindlewick]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Tickbrass]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Voidreach]] | Town | Underground (deep) | 0.1 | 10% | 5 of 6 |
| [[Ashenmoor]] | Village | Surface | 0.05 | 5% | 7 of 7 |
| [[Haymarket]] | Town | Surface | 0.05 | 5% | 5 of 5 |
| [[Heathwick]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Horn's End]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Oxbow]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Pennytop]] | Town | Surface | 0.05 | 5% | 5 of 5 |
| [[Tinkerton]] | Village | Surface | 0.05 | 5% | 5 of 5 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (11 of 18), [[Reaver Hall]] (2 of 13), [[Hunters' Lodge]] (1 of 11), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (5 of 12), [[Wildwardens]] (2 of 16), [[Cogwrights' Guild]] (5 of 10), [[Sawbones Hall]] (1 of 7)

**Temple-only backgrounds:** [[Crusader (Background)|Crusader]], [[Penitent]], [[Temple Guard]]

## Elf

[[Elf]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Evenshade]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Moonleaf Ward]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Silverbough]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Starlight Grove]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Thornwillow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Wyrdleaf]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Whisperwood]] | Village | Surface | 0.6 | 60% | 1 of 5 |
| [[Verdantshade]] | Village | Surface | 0.55 | 55% | 1 of 5 |
| [[Starfall Glade]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Moonhollow]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Silverglade]] | Village | Surface | 0.5 | 50% | 1 of 4 |
| [[Thistleveil]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Dawngrove]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Cedarlight]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Emerald Reach]] | Town | Surface | 0.35 | 35% | 1 of 6 |
| [[Ashgate]] | Village | Surface | 0.3 | 30% | 1 of 4 |
| [[Willowmere]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Ironroot]] | Village | Surface | 0.25 | 25% | 1 of 6 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.2 | 20% | 2 of 7 |
| [[Blackthorn]] | Village | Surface | 0.2 | 20% | 1 of 7 |
| [[Lanternwick]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Oakenford]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Temple of the Dawn]] | Temple | Surface | 0.2 | 20% | 2 of 6 |
| [[Thornhaven]] | Town | Surface | 0.2 | 20% | 2 of 7 |
| [[Copper Falls]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Fangwood]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Howling Pines]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.15 | 15% | 3 of 8 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.15 | 15% | 3 of 8 |
| [[Moonridge]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Pilgrim's Rest]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Pinecrest]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.15 | 15% | 3 of 6 |
| [[Sablewood]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.15 | 15% | 3 of 6 |
| [[Sporewick]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Stillwater]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Stonecross]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Zephyr's Rest]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Border Watch]] | Fort | Surface | 0.1 | 10% | 5 of 7 |
| [[Coppergate]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Crossroads Landing]] | Town | Surface | 0.1 | 10% | 6 of 7 |
| [[Elmsworth]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Hollowfield]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Honeydale]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Kingsmead]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Rivermere]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Stillbrook]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Sunstone]] | Town | Surface | 0.1 | 10% | 6 of 7 |
| [[Three Rivers]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Trader's Bluff]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Tradewind]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Whitegate]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Windhaven]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Wulfmere]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Hawkridge]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Ironhaven]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Mistwall]] | Village | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Blade Circle]] (3 of 10), [[Hunters' Lodge]] (9 of 11), [[Shadow Guild]] (1 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (5 of 12), [[Holy Order]] (5 of 12), [[Wildwardens]] (8 of 16), [[Sawbones Hall]] (3 of 7)

**Temple-only backgrounds:** [[Acolyte Militant]], [[Temple Guard]]

## Frostborn

[[Frostborn]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Glacierfall]] | Village | Surface | 0.45 | 45% | 1 of 6 |
| [[Rimespire]] | Fort | Surface | 0.4 | 40% | 1 of 5 |
| [[Emberfall]] | Town | Surface | 0.2 | 20% | 3 of 4 |
| [[Cragmoor]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Flintmarch]] | Fort | Surface | 0.15 | 15% | 4 of 6 |
| [[Northvale]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Crystalheim]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Ashenmoor]] | Village | Surface | 0.1 | 10% | 5 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (7 of 18), [[Reaver Hall]] (5 of 13), [[Hunters' Lodge]] (2 of 11), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (2 of 12), [[Wildwardens]] (3 of 16), [[Cogwrights' Guild]] (3 of 10)

## Gnoll

[[Gnoll]] · threshold 12

*This race is not in any settlement's population, so it never appears in settlement recruit pools. It can still come from a founding or guild, if the rules above allow it.*

**Guild backgrounds open to this race:** [[Reaver Hall]] (6 of 13), [[Hunters' Lodge]] (5 of 11), [[Shadow Guild]] (2 of 17), [[Wildwardens]] (7 of 16), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (1 of 7)

## Gnome

[[Gnome]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Brassburrow Fort]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Buttonwood]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Cogwhisper]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Filigree Glen]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Kettlebridge]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Lensmoor]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Pinmoor]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Ratchet Grove]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Spindlewick]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Tickbrass]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Sprocketville]] | Town | Surface | 0.5 | 50% | 1 of 5 |
| [[Cogsworth]] | Town | Surface | 0.45 | 45% | 1 of 5 |
| [[Brasswick]] | Town | Surface | 0.4 | 40% | 1 of 5 |
| [[Crystalvein Refuge]] | Village | Underground (shallow) | 0.3 | 30% | 2 of 4 |
| [[Tinkerton]] | Village | Surface | 0.3 | 30% | 2 of 5 |
| [[Tumblethorn]] | Village | Surface | 0.25 | 25% | 2 of 4 |
| [[Brambleshire]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Burrowton]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Cloverfield]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Copperhollow]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Deepforge]] | Town | Surface | 0.2 | 20% | 2 of 4 |
| [[Deephollow]] | Town | Surface | 0.2 | 20% | 2 of 4 |
| [[Honeydale]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Lanternwick]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Pennytop]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Rootcellar Market]] | Village | Underground (shallow) | 0.2 | 20% | 4 of 4 |
| [[Crystalheim]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.15 | 15% | 3 of 7 |
| [[Silverton]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Anvilheim]] | Town | Surface | 0.15 | 15% | 2 of 5 |
| [[Copper Falls]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Coppergate]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Crossroads Market]] | Trading Post | Surface | 0.15 | 15% | 3 of 5 |
| [[Deepforge Hold]] | Fort | Underground (shallow) | 0.15 | 15% | 3 of 5 |
| [[Emberpeak]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Granitehold]] | Fort | Surface | 0.15 | 15% | 4 of 4 |
| [[Greystone]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Halfway House]] | Village | Surface | 0.15 | 15% | 4 of 5 |
| [[Hammerfell]] | Fort | Surface | 0.15 | 15% | 3 of 4 |
| [[Haymarket]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Heathwick]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Hollow Root]] | Village | Underground (shallow) | 0.15 | 15% | 4 of 5 |
| [[Irondelve]] | Town | Surface | 0.15 | 15% | 2 of 4 |
| [[Kettlebrook]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Millwick]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Mudburrow]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Puddlegate]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Saltgrotto]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Scrapheap]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Stonehearth]] | Town | Surface | 0.15 | 15% | 2 of 4 |
| [[Sunstone]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Trader's Bluff]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Windhaven]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Molehill Outpost]] | Village | Underground (shallow) | 0.1 | 10% | 4 of 4 |
| [[Starfall Glade]] | Village | Surface | 0.1 | 10% | 3 of 5 |
| [[Aldwick]] | Village | Surface | 0.1 | 10% | 3 of 4 |
| [[Appleburrow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Blackthorn]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Buttercup Hollow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Cedarlight]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Coalpit]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Dawngrove]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Deephearth Forge]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Duskfield]] | Village | Surface | 0.1 | 10% | 3 of 4 |
| [[Emerald Reach]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Goldseam]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Graniteford]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Greenbank]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Greenmaw]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Hammerbrook]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Honeystead]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Ironhall]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Laketon]] | Village | Surface | 0.1 | 10% | 3 of 4 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.1 | 10% | 6 of 8 |
| [[Marshfield]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Moonhollow]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Muleford]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Pilgrim's Rest]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Rattletrap]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.1 | 10% | 6 of 6 |
| [[Slag Market]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Sporewick]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Stillwater]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Stonecross]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Stonewallow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Temple of the Dawn]] | Temple | Surface | 0.1 | 10% | 5 of 6 |
| [[The Sunken Stair]] | Town | Underground (shallow) | 0.1 | 10% | 4 of 5 |
| [[Thistledown]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Three Rivers]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Wayward Inn]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Whitegate]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Willowdene]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Willowmere]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Zephyr's Rest]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Crossroads Landing]] | Town | Surface | 0.05 | 5% | 7 of 7 |
| [[Greyport]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.05 | 5% | 6 of 8 |
| [[Rottenbow]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Thornhaven]] | Town | Surface | 0.05 | 5% | 7 of 7 |
| [[Tidewash]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Tradewind]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Wulfmere]] | Village | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Hunters' Lodge]] (4 of 11), [[Shadow Guild]] (4 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (5 of 12), [[Holy Order]] (3 of 12), [[Wildwardens]] (4 of 16), [[Cogwrights' Guild]] (3 of 10), [[Sawbones Hall]] (5 of 7)

**Temple-only backgrounds:** [[Acolyte Militant]]

## Goblin

[[Goblin]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Boglight]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Fangmarket]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Grubstake Fort]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Knifebottom]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Mucksprawl]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Ratrun]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Scrappers Drift]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Skewerden]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Gutstitch]] | Village | Surface | 0.55 | 55% | 1 of 5 |
| [[Greenmaw]] | Village | Surface | 0.5 | 50% | 1 of 6 |
| [[Mudburrow]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Scrapheap]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Rattletrap]] | Town | Surface | 0.45 | 45% | 1 of 6 |
| [[Spiketown]] | Fort | Surface | 0.45 | 45% | 1 of 5 |
| [[Slag Market]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Tinkerton]] | Village | Surface | 0.4 | 40% | 1 of 5 |
| [[Hollow Root]] | Village | Underground (shallow) | 0.35 | 35% | 1 of 5 |
| [[Molehill Outpost]] | Village | Underground (shallow) | 0.3 | 30% | 2 of 4 |
| [[Dunmoor]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Fenwatch]] | Village | Surface | 0.3 | 30% | 2 of 4 |
| [[Rootcellar Market]] | Village | Underground (shallow) | 0.3 | 30% | 1 of 4 |
| [[Rottenbow]] | Village | Surface | 0.3 | 30% | 1 of 6 |
| [[Blackmarket]] | Town | Surface | 0.25 | 25% | 1 of 6 |
| [[Crystalvein Refuge]] | Village | Underground (shallow) | 0.25 | 25% | 3 of 4 |
| [[Reed's End]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Skulltop]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Ashgate]] | Village | Surface | 0.2 | 20% | 4 of 4 |
| [[Boghollow]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Bogside]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Bonehill]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Coalpit]] | Village | Surface | 0.2 | 20% | 3 of 5 |
| [[Deepforge Hold]] | Fort | Underground (shallow) | 0.2 | 20% | 2 of 5 |
| [[Drifter's Hollow]] | Village | Surface | 0.2 | 20% | 1 of 7 |
| [[Duskhollow]] | Town | Underground (mid) | 0.2 | 20% | 3 of 5 |
| [[Dustfall]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Dusthaven]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Dusthaven Depot]] | Trading Post | Surface | 0.2 | 20% | 2 of 5 |
| [[Gloomweb Market]] | Town | Underground (mid) | 0.2 | 20% | 2 of 5 |
| [[Grimtusk Hold]] | Fort | Surface | 0.2 | 20% | 2 of 4 |
| [[Last Chance]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Marshfield]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Oxbow]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Shadowmere]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Silkweb Grotto]] | Village | Surface | 0.2 | 20% | 3 of 4 |
| [[Spidersong Cavern]] | Village | Underground (mid) | 0.2 | 20% | 4 of 4 |
| [[The Sunken Stair]] | Town | Underground (shallow) | 0.2 | 20% | 3 of 5 |
| [[Tradewind]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Vagrant's Rest]] | Village | Surface | 0.2 | 20% | 2 of 7 |
| [[Warg's Rest]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[The Undermoot]] | Town | Underground (mid) | 0.2 | 20% | 3 of 6 |
| [[Ashenmoor]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Barrowdale]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Blackthorn]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Bloodfield]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Bloodrock]] | Fort | Surface | 0.15 | 15% | 2 of 5 |
| [[Border Watch]] | Fort | Surface | 0.15 | 15% | 4 of 7 |
| [[Briarford]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Broken Palisade]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Cindervale]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Copperhollow]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Crossroads Landing]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Crossroads Market]] | Trading Post | Surface | 0.15 | 15% | 4 of 5 |
| [[Crushbone]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Deepforge]] | Town | Surface | 0.15 | 15% | 3 of 4 |
| [[Dreadmaw]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Goldseam]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Gorewhistle]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Greenbank]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Greyport]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Greystone]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Halfway House]] | Village | Surface | 0.15 | 15% | 5 of 5 |
| [[Highwall]] | Fort | Surface | 0.15 | 15% | 3 of 6 |
| [[Irondelve]] | Town | Surface | 0.15 | 15% | 3 of 4 |
| [[Ironfang Hold]] | Fort | Surface | 0.15 | 15% | 2 of 5 |
| [[Ironhaven]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Irontooth]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Muleford]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Old Garrison]] | Fort | Surface | 0.15 | 15% | 4 of 6 |
| [[Puddlegate]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Rendpost]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.15 | 15% | 4 of 6 |
| [[Sablewood]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Saltgrotto]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Scalemire]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Screamhold]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Silverglade]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Skullcairn]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Sporewick]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Stoneskull]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.15 | 15% | 4 of 6 |
| [[The Broken Shield]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Three Rivers]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Tusk Hollow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[War Drum]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Wayward Inn]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Wolfspire]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Yarmouth]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Hawkridge]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Nightveil]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[The Crawling Dark]] | Village | Underground (deep) | 0.15 | 15% | 4 of 5 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.1 | 10% | 5 of 7 |
| [[Redhill]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Silverton]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Anvilheim]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Battleford]] | Fort | Surface | 0.1 | 10% | 4 of 6 |
| [[Brambleshire]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Brasswick]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Burrowton]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Catterton]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Cloverfield]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Copper Falls]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Coppergate]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Cragmoor]] | Village | Surface | 0.1 | 10% | 5 of 7 |
| [[Crowsreach]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Dawngrove]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Deephollow]] | Town | Surface | 0.1 | 10% | 4 of 4 |
| [[Dragon's Perch]] | Village | Surface | 0.1 | 10% | 4 of 7 |
| [[Dragonscar]] | Town | Surface | 0.1 | 10% | 5 of 7 |
| [[Duskfield]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Ember's Edge]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Emberpeak]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Fangwood]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Flintmarch]] | Fort | Surface | 0.1 | 10% | 5 of 6 |
| [[Fort Greymere]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Gallowfield]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Granite Watch]] | Fort | Underground (shallow) | 0.1 | 10% | 4 of 5 |
| [[Haymarket]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Heathwick]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Horn's End]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Howling Pines]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Iron Tomb Garrison]] | Fort | Underground (mid) | 0.1 | 10% | 5 of 5 |
| [[Ironroot]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Kettlebrook]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Labyrinth's Gate]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Laketon]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.1 | 10% | 7 of 8 |
| [[Millwick]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Mistwall]] | Village | Surface | 0.1 | 10% | 4 of 7 |
| [[Nightbloom]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Pennytop]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[Pilgrim's Rest]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Pinecrest]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Rampart Keep]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Ravensholme]] | Town | Surface | 0.1 | 10% | 5 of 7 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.1 | 10% | 5 of 6 |
| [[Slag Furnace]] | Town | Underground (mid) | 0.1 | 10% | 5 of 5 |
| [[Stonefist]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Stonehearth]] | Town | Surface | 0.1 | 10% | 4 of 4 |
| [[Stormgate]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Sunstone]] | Town | Surface | 0.1 | 10% | 7 of 7 |
| [[Thornhaven]] | Town | Surface | 0.1 | 10% | 5 of 7 |
| [[Thornwall]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Tidewash]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Trader's Bluff]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Tumblethorn]] | Village | Surface | 0.1 | 10% | 3 of 4 |
| [[Umbral Gate]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Whitegate]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Windhaven]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Wulfmere]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Crystalheim]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Elmhurst]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Aldwick]] | Village | Surface | 0.05 | 5% | 4 of 4 |
| [[Cedarlight]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Cogsworth]] | Town | Surface | 0.05 | 5% | 5 of 5 |
| [[Emerald Reach]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Fort Ironclad]] | Fort | Surface | 0.05 | 5% | 5 of 5 |
| [[Glacierfall]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Honeydale]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Kingsreach]] | Capital | Surface | 0.05 | 5% | 7 of 8 |
| [[Moonridge]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Northvale]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Sprocketville]] | Town | Surface | 0.05 | 5% | 5 of 5 |
| [[Stonecross]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Temple of the Dawn]] | Temple | Surface | 0.05 | 5% | 6 of 6 |
| [[Verdantshade]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Whisperwood]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Zephyr's Rest]] | Village | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Reaver Hall]] (2 of 13), [[Blade Circle]] (3 of 10), [[Hunters' Lodge]] (2 of 11), [[Shadow Guild]] (10 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (3 of 12), [[Holy Order]] (1 of 12), [[Wildwardens]] (2 of 16), [[Cogwrights' Guild]] (3 of 10), [[Sawbones Hall]] (2 of 7)

## Half-Ogre

[[Half-Ogre]] · threshold 5

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Grimtusk Hold]] | Fort | Surface | 0.2 | 20% | 3 of 4 |
| [[Bloodrock]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Bonehill]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Crushbone]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Dreadmaw]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Dusthaven]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Emberheart Forge]] | Fort | Underground (deep) | 0.15 | 15% | 3 of 5 |
| [[Horn's End]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Iron Tomb Garrison]] | Fort | Underground (mid) | 0.15 | 15% | 4 of 5 |
| [[Ironfang Hold]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Skulltop]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Stonefist]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Stormgate]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Redhill]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Battleford]] | Fort | Surface | 0.1 | 10% | 5 of 6 |
| [[Flintmarch]] | Fort | Surface | 0.1 | 10% | 6 of 6 |
| [[Fort Greymere]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Fort Ironclad]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Granite Watch]] | Fort | Underground (shallow) | 0.1 | 10% | 5 of 5 |
| [[Highwall]] | Fort | Surface | 0.1 | 10% | 5 of 6 |
| [[Labyrinth's Gate]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Old Garrison]] | Fort | Surface | 0.1 | 10% | 5 of 6 |
| [[Spiketown]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[The Broken Shield]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Warg's Rest]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Border Watch]] | Fort | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (7 of 18), [[Reaver Hall]] (9 of 13), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (3 of 10)

## Half-Troll

[[Half-Troll]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Slag Furnace]] | Town | Underground (mid) | 0.2 | 20% | 2 of 5 |
| [[Grimtusk Hold]] | Fort | Surface | 0.15 | 15% | 4 of 4 |
| [[Wolfspire]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Bloodrock]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Bonehill]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Crushbone]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Dreadmaw]] | Town | Surface | 0.1 | 10% | 4 of 6 |
| [[Skulltop]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Gutstitch]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Warg's Rest]] | Village | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (6 of 18), [[Reaver Hall]] (11 of 13), [[Blade Circle]] (1 of 10), [[Holy Order]] (1 of 12), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (2 of 10)

**Temple-only backgrounds:** [[Penitent]]

## Halfling

[[Halfling]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Appleburrow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Buttercup Hollow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Honeystead]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Thistledown]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Willowdene]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Brambleshire]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Burrowton]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Cloverfield]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Kettlebrook]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Tumblethorn]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Honeydale]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Puddlegate]] | Village | Surface | 0.5 | 50% | 1 of 4 |
| [[Heathwick]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Pennytop]] | Town | Surface | 0.45 | 45% | 1 of 5 |
| [[Millwick]] | Village | Surface | 0.4 | 40% | 1 of 4 |
| [[Ashgate]] | Village | Surface | 0.25 | 25% | 2 of 4 |
| [[Crossroads Market]] | Trading Post | Surface | 0.25 | 25% | 2 of 5 |
| [[Greenbank]] | Village | Surface | 0.25 | 25% | 2 of 4 |
| [[Halfway House]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Laketon]] | Village | Surface | 0.25 | 25% | 2 of 4 |
| [[Muleford]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Rootcellar Market]] | Village | Underground (shallow) | 0.25 | 25% | 3 of 4 |
| [[Wayward Inn]] | Village | Surface | 0.25 | 25% | 1 of 6 |
| [[Aldwick]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Catterton]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Cogsworth]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Coppergate]] | Town | Surface | 0.2 | 20% | 3 of 6 |
| [[Duskfield]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Haymarket]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Hollow Root]] | Village | Underground (shallow) | 0.2 | 20% | 3 of 5 |
| [[Oakenford]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.2 | 20% | 2 of 6 |
| [[Silverglade]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Three Rivers]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Trader's Bluff]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Tradewind]] | Town | Surface | 0.2 | 20% | 3 of 6 |
| [[Willowmere]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Windhaven]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Blackthorn]] | Village | Surface | 0.15 | 15% | 4 of 7 |
| [[Bogside]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Brassburrow Fort]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Briarford]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Buttonwood]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Cedarlight]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Cogwhisper]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Copper Falls]] | Village | Surface | 0.15 | 15% | 5 of 6 |
| [[Crossroads Landing]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Crystalvein Refuge]] | Village | Underground (shallow) | 0.15 | 15% | 4 of 4 |
| [[Dawngrove]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Drifter's Hollow]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Dustfall]] | Village | Surface | 0.15 | 15% | 4 of 5 |
| [[Dusthaven Depot]] | Trading Post | Surface | 0.15 | 15% | 5 of 5 |
| [[Elmsworth]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Emerald Reach]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Evenshade]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Fenwatch]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Filigree Glen]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Greenmaw]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Gutstitch]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Hollowfield]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Ironroot]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Kettlebridge]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Kingsmead]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Lanternwick]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Last Chance]] | Village | Surface | 0.15 | 15% | 5 of 5 |
| [[Lensmoor]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Moonhollow]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Moonleaf Ward]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Mudburrow]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Oxbow]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Pilgrim's Rest]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Pinmoor]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Ratchet Grove]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Rattletrap]] | Town | Surface | 0.15 | 15% | 2 of 6 |
| [[Ravensholme]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Reed's End]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Rivermere]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Rottenbow]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.15 | 15% | 4 of 6 |
| [[Scrapheap]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Silverbough]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Spiketown]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Spindlewick]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Starlight Grove]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Stillbrook]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Stillwater]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Stonecross]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Sunstone]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Temple of the Dawn]] | Temple | Surface | 0.15 | 15% | 4 of 6 |
| [[Thistleveil]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Thornhaven]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Thornwall]] | Fort | Surface | 0.15 | 15% | 4 of 5 |
| [[Thornwillow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Tickbrass]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Tinkerton]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Vagrant's Rest]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Verdantshade]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Whitegate]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Wulfmere]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Wyrdleaf]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Yarmouth]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Elmhurst]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Hawkridge]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.1 | 10% | 6 of 7 |
| [[Silverton]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Starfall Glade]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Anvilheim]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Blackmarket]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Boghollow]] | Village | Surface | 0.1 | 10% | 3 of 6 |
| [[Border Watch]] | Fort | Surface | 0.1 | 10% | 6 of 7 |
| [[Brasswick]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Fangwood]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Gallowfield]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Goldseam]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Greyport]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Howling Pines]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Ironhaven]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.1 | 10% | 4 of 8 |
| [[Marshfield]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Moonridge]] | Village | Surface | 0.1 | 10% | 3 of 6 |
| [[Northvale]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Old Garrison]] | Fort | Surface | 0.1 | 10% | 6 of 6 |
| [[Pinecrest]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Rampart Keep]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Sablewood]] | Town | Surface | 0.1 | 10% | 6 of 7 |
| [[Scalemire]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Sporewick]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Sprocketville]] | Town | Surface | 0.1 | 10% | 4 of 5 |
| [[The Broken Shield]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[The Sunken Stair]] | Town | Underground (shallow) | 0.1 | 10% | 5 of 5 |
| [[Tidewash]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Whisperwood]] | Village | Surface | 0.1 | 10% | 3 of 5 |
| [[Zephyr's Rest]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Battleford]] | Fort | Surface | 0.05 | 5% | 6 of 6 |
| [[Highwall]] | Fort | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Blade Circle]] (3 of 10), [[Hunters' Lodge]] (5 of 11), [[Shadow Guild]] (9 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (6 of 12), [[Wildwardens]] (5 of 16), [[Sawbones Hall]] (3 of 7)

**Temple-only backgrounds:** [[Acolyte Militant]], [[Temple Guard]]

## Human

[[Human]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Elmsworth]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Hollowfield]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Rivermere]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Stillbrook]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Aldwick]] | Village | Surface | 0.65 | 65% | 1 of 4 |
| [[Duskfield]] | Village | Surface | 0.6 | 60% | 1 of 4 |
| [[Catterton]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Laketon]] | Village | Surface | 0.55 | 55% | 1 of 4 |
| [[Greenbank]] | Village | Surface | 0.5 | 50% | 1 of 4 |
| [[Haymarket]] | Town | Surface | 0.5 | 50% | 1 of 5 |
| [[Oxbow]] | Village | Surface | 0.5 | 50% | 1 of 5 |
| [[Briarford]] | Town | Surface | 0.45 | 45% | 1 of 5 |
| [[Kingsmead]] | Town | Surface | 0.45 | 45% | 1 of 5 |
| [[Northvale]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Pinecrest]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Fort Ironclad]] | Fort | Surface | 0.4 | 40% | 1 of 5 |
| [[Marshfield]] | Village | Surface | 0.4 | 40% | 1 of 5 |
| [[Muleford]] | Village | Surface | 0.4 | 40% | 1 of 5 |
| [[Stonecross]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Elmhurst]] | Town | Surface | 0.4 | 40% | 1 of 5 |
| [[Hawkridge]] | Town | Surface | 0.4 | 40% | 1 of 5 |
| [[Redhill]] | Town | Surface | 0.35 | 35% | 1 of 5 |
| [[Crossroads Market]] | Trading Post | Surface | 0.35 | 35% | 1 of 5 |
| [[Dusthaven]] | Town | Surface | 0.35 | 35% | 1 of 5 |
| [[Gallowfield]] | Village | Surface | 0.35 | 35% | 1 of 6 |
| [[Greyport]] | Town | Surface | 0.35 | 35% | 1 of 6 |
| [[Ironhaven]] | Town | Surface | 0.35 | 35% | 1 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.35 | 35% | 1 of 8 |
| [[Millwick]] | Village | Surface | 0.35 | 35% | 2 of 4 |
| [[Oakenford]] | Town | Surface | 0.35 | 35% | 1 of 5 |
| [[Pilgrim's Rest]] | Village | Surface | 0.35 | 35% | 1 of 6 |
| [[Rampart Keep]] | Fort | Surface | 0.35 | 35% | 1 of 5 |
| [[Temple of the Dawn]] | Temple | Surface | 0.35 | 35% | 1 of 6 |
| [[Whitegate]] | Town | Surface | 0.35 | 35% | 1 of 6 |
| [[Yarmouth]] | Town | Surface | 0.35 | 35% | 1 of 6 |
| [[Silverton]] | Town | Surface | 0.3 | 30% | 2 of 5 |
| [[Barrowdale]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Battleford]] | Fort | Surface | 0.3 | 30% | 1 of 6 |
| [[Crowsreach]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Dustfall]] | Village | Surface | 0.3 | 30% | 1 of 5 |
| [[Dusthaven Depot]] | Trading Post | Surface | 0.3 | 30% | 1 of 5 |
| [[Halfway House]] | Village | Surface | 0.3 | 30% | 1 of 5 |
| [[Lanternwick]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Last Chance]] | Village | Surface | 0.3 | 30% | 1 of 5 |
| [[Old Garrison]] | Fort | Surface | 0.3 | 30% | 1 of 6 |
| [[Ravensholme]] | Town | Surface | 0.3 | 30% | 1 of 7 |
| [[Riverfork Exchange]] | Trading Post | Surface | 0.3 | 30% | 1 of 6 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.3 | 30% | 1 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.3 | 30% | 1 of 6 |
| [[Stormgate]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Three Rivers]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Trader's Bluff]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Tradewind]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Willowmere]] | Town | Surface | 0.3 | 30% | 2 of 5 |
| [[Windhaven]] | Town | Surface | 0.3 | 30% | 1 of 6 |
| [[Wulfmere]] | Village | Surface | 0.3 | 30% | 1 of 6 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.25 | 25% | 1 of 7 |
| [[Ashenmoor]] | Village | Surface | 0.25 | 25% | 1 of 7 |
| [[Ashgate]] | Village | Surface | 0.25 | 25% | 3 of 4 |
| [[Coalpit]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Coppergate]] | Town | Surface | 0.25 | 25% | 1 of 6 |
| [[Cragmoor]] | Village | Surface | 0.25 | 25% | 1 of 7 |
| [[Crossroads Landing]] | Town | Surface | 0.25 | 25% | 1 of 7 |
| [[Dunmoor]] | Town | Surface | 0.25 | 25% | 2 of 5 |
| [[Emberfall]] | Town | Surface | 0.25 | 25% | 2 of 4 |
| [[Emerald Reach]] | Town | Surface | 0.25 | 25% | 2 of 6 |
| [[Flintmarch]] | Fort | Surface | 0.25 | 25% | 1 of 6 |
| [[Fort Greymere]] | Fort | Surface | 0.25 | 25% | 3 of 5 |
| [[Goldseam]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Greystone]] | Village | Surface | 0.25 | 25% | 2 of 4 |
| [[Heathwick]] | Village | Surface | 0.25 | 25% | 2 of 5 |
| [[Highwall]] | Fort | Surface | 0.25 | 25% | 2 of 6 |
| [[Rottenbow]] | Village | Surface | 0.25 | 25% | 2 of 6 |
| [[Stillwater]] | Village | Surface | 0.25 | 25% | 1 of 6 |
| [[Sunstone]] | Town | Surface | 0.25 | 25% | 1 of 7 |
| [[The Broken Shield]] | Town | Surface | 0.25 | 25% | 1 of 6 |
| [[The Sunken Stair]] | Town | Underground (shallow) | 0.25 | 25% | 2 of 5 |
| [[Thornhaven]] | Town | Surface | 0.25 | 25% | 1 of 7 |
| [[Thornwall]] | Fort | Surface | 0.25 | 25% | 2 of 5 |
| [[Vagrant's Rest]] | Village | Surface | 0.25 | 25% | 1 of 7 |
| [[Wayward Inn]] | Village | Surface | 0.25 | 25% | 2 of 6 |
| [[Wolfspire]] | Town | Surface | 0.25 | 25% | 2 of 5 |
| [[Molehill Outpost]] | Village | Underground (shallow) | 0.2 | 20% | 3 of 4 |
| [[Blackmarket]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Blackthorn]] | Village | Surface | 0.2 | 20% | 2 of 7 |
| [[Bogside]] | Village | Surface | 0.2 | 20% | 3 of 6 |
| [[Border Watch]] | Fort | Surface | 0.2 | 20% | 2 of 7 |
| [[Brasswick]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Cedarlight]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Copper Falls]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Dawngrove]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Drifter's Hollow]] | Village | Surface | 0.2 | 20% | 2 of 7 |
| [[Granitehold]] | Fort | Surface | 0.2 | 20% | 2 of 4 |
| [[Hammerfell]] | Fort | Surface | 0.2 | 20% | 2 of 4 |
| [[Kettlebrook]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.2 | 20% | 1 of 8 |
| [[Pennytop]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Puddlegate]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Sablewood]] | Town | Surface | 0.2 | 20% | 1 of 7 |
| [[Anvilheim]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Appleburrow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Ashen Redoubt]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Azure Court]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Blackcoal]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Bonepath]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Brambleshire]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Burrowton]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Buttercup Hollow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Cindervale]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Cinderwell]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Cloverfield]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Cogsworth]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Copperhollow]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Deephearth Forge]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Deephollow]] | Town | Surface | 0.15 | 15% | 3 of 4 |
| [[Dragonscar]] | Town | Surface | 0.15 | 15% | 3 of 7 |
| [[Dust Market]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Elderpine]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Ember's Edge]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Emberpeak]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Emberport]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Fangwood]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Fenwatch]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Frostden]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Ghazira]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Glacierfall]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Graniteford]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Grayfang Hold]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Hammerbrook]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Honeydale]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Honeystead]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Howl Keep]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Howling Pines]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Irondelve]] | Town | Surface | 0.15 | 15% | 4 of 4 |
| [[Ironhall]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Ironroot]] | Village | Surface | 0.15 | 15% | 5 of 6 |
| [[Lone Watch Fort]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Lonepine]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Long Howl]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Moonfang]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Obsidian Quarter]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Rattletrap]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Ravensfeather]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Redspring]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Reed's End]] | Village | Surface | 0.15 | 15% | 4 of 5 |
| [[Salt Pillar]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Sandgaze]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Scalemire]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Scaleweave]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Scorched Keep]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Shadowmere]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Silverglade]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Slag Market]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Snowwatch]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Sprocketville]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Stonefist]] | Fort | Surface | 0.15 | 15% | 4 of 5 |
| [[Stonehearth]] | Town | Surface | 0.15 | 15% | 3 of 4 |
| [[Stonewallow]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Thistledown]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Tidewash]] | Village | Surface | 0.15 | 15% | 2 of 6 |
| [[Willowdene]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Zephyr's Rest]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Crystalheim]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Rimespire]] | Fort | Surface | 0.15 | 15% | 3 of 5 |
| [[Starfall Glade]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Bloodfield]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Boghollow]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Boglight]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Bonehill]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Broken Palisade]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Crushbone]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Deepforge Hold]] | Fort | Underground (shallow) | 0.1 | 10% | 4 of 5 |
| [[Dragon's Perch]] | Village | Surface | 0.1 | 10% | 5 of 7 |
| [[Dreadmaw]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Evenshade]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Fangmarket]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Gorewhistle]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Grubstake Fort]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Gutstitch]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Hollow Root]] | Village | Underground (shallow) | 0.1 | 10% | 5 of 5 |
| [[Horn's End]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Ironfang Hold]] | Fort | Surface | 0.1 | 10% | 4 of 5 |
| [[Irontooth]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Knifebottom]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Labyrinth's Gate]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Mistwall]] | Village | Surface | 0.1 | 10% | 5 of 7 |
| [[Moonhollow]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Moonleaf Ward]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Moonridge]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Mucksprawl]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Mudburrow]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Nightbloom]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Ratrun]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Rendpost]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Scrapheap]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Scrappers Drift]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Screamhold]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Silverbough]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Skewerden]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Skullcairn]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Spiketown]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Starlight Grove]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Stoneskull]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Thistleveil]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Thornwillow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Tinkerton]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Tumblethorn]] | Village | Surface | 0.1 | 10% | 4 of 4 |
| [[Tusk Hollow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Verdantshade]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[War Drum]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Warg's Rest]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Wyrdleaf]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Nightveil]] | Town | Surface | 0.1 | 10% | 5 of 5 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (9 of 18), [[Reaver Hall]] (3 of 13), [[Blade Circle]] (5 of 10), [[Hunters' Lodge]] (2 of 11), [[Shadow Guild]] (3 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (5 of 12), [[Holy Order]] (8 of 12), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (2 of 7)

**Temple-only backgrounds:** [[Acolyte Militant]], [[Crusader (Background)|Crusader]], [[Penitent]], [[Temple Guard]]

## Lizardfolk

[[Lizardfolk]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Boghollow]] | Village | Surface | 0.45 | 45% | 1 of 6 |
| [[Fenwatch]] | Village | Surface | 0.4 | 40% | 1 of 4 |
| [[Scalemire]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Reed's End]] | Village | Surface | 0.35 | 35% | 1 of 5 |
| [[Bogside]] | Village | Surface | 0.25 | 25% | 1 of 6 |
| [[Marshfield]] | Village | Surface | 0.2 | 20% | 3 of 5 |
| [[Saltgrotto]] | Village | Surface | 0.2 | 20% | 2 of 4 |
| [[Dustfall]] | Village | Surface | 0.15 | 15% | 5 of 5 |
| [[Stillwater]] | Village | Surface | 0.15 | 15% | 5 of 6 |
| [[Tidewash]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Sporewick]] | Village | Surface | 0.1 | 10% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (3 of 18), [[Reaver Hall]] (5 of 13), [[Hunters' Lodge]] (3 of 11), [[Holy Order]] (2 of 12), [[Wildwardens]] (8 of 16), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (4 of 7)

## Minotaur

[[Minotaur]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Horn's End]] | Village | Surface | 0.4 | 40% | 1 of 6 |
| [[Labyrinth's Gate]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Emberheart Forge]] | Fort | Underground (deep) | 0.15 | 15% | 4 of 5 |
| [[Bloodrock]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Crushbone]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Dreadmaw]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Ironfang Hold]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Dragon's Perch]] | Village | Surface | 0.05 | 5% | 7 of 7 |
| [[Dragonscar]] | Town | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (8 of 18), [[Reaver Hall]] (10 of 13), [[Holy Order]] (1 of 12), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (2 of 10)

## Orc

[[Orc]] · threshold 0

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Bloodfield]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Broken Palisade]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Gorewhistle]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Irontooth]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Rendpost]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Screamhold]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Skullcairn]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Stoneskull]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Tusk Hollow]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[War Drum]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Bloodrock]] | Fort | Surface | 0.5 | 50% | 1 of 5 |
| [[Ironfang Hold]] | Fort | Surface | 0.5 | 50% | 1 of 5 |
| [[Bonehill]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Grimtusk Hold]] | Fort | Surface | 0.45 | 45% | 1 of 4 |
| [[Skulltop]] | Village | Surface | 0.45 | 45% | 1 of 5 |
| [[Crushbone]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Dreadmaw]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Warg's Rest]] | Village | Surface | 0.4 | 40% | 1 of 6 |
| [[Stonefist]] | Fort | Surface | 0.35 | 35% | 1 of 5 |
| [[Fort Greymere]] | Fort | Surface | 0.3 | 30% | 1 of 5 |
| [[Battleford]] | Fort | Surface | 0.25 | 25% | 2 of 6 |
| [[Rampart Keep]] | Fort | Surface | 0.25 | 25% | 2 of 5 |
| [[Stormgate]] | Town | Surface | 0.25 | 25% | 2 of 5 |
| [[Thornwall]] | Fort | Surface | 0.25 | 25% | 3 of 5 |
| [[Border Watch]] | Fort | Surface | 0.2 | 20% | 3 of 7 |
| [[Dunmoor]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Dustfall]] | Village | Surface | 0.2 | 20% | 3 of 5 |
| [[Dusthaven]] | Town | Surface | 0.2 | 20% | 3 of 5 |
| [[Dusthaven Depot]] | Trading Post | Surface | 0.2 | 20% | 3 of 5 |
| [[Emberfall]] | Town | Surface | 0.2 | 20% | 4 of 4 |
| [[Flintmarch]] | Fort | Surface | 0.2 | 20% | 3 of 6 |
| [[Fort Ironclad]] | Fort | Surface | 0.2 | 20% | 3 of 5 |
| [[Gallowfield]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Granite Watch]] | Fort | Underground (shallow) | 0.2 | 20% | 2 of 5 |
| [[Granitehold]] | Fort | Surface | 0.2 | 20% | 3 of 4 |
| [[Horn's End]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Iron Tomb Garrison]] | Fort | Underground (mid) | 0.2 | 20% | 3 of 5 |
| [[Last Chance]] | Village | Surface | 0.2 | 20% | 3 of 5 |
| [[Old Garrison]] | Fort | Surface | 0.2 | 20% | 2 of 6 |
| [[Slag Furnace]] | Town | Underground (mid) | 0.2 | 20% | 3 of 5 |
| [[Spiketown]] | Fort | Surface | 0.2 | 20% | 2 of 5 |
| [[The Broken Shield]] | Town | Surface | 0.2 | 20% | 3 of 6 |
| [[Redhill]] | Town | Surface | 0.15 | 15% | 3 of 5 |
| [[Ashenmoor]] | Village | Surface | 0.15 | 15% | 4 of 7 |
| [[Blackmarket]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Boglight]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Catterton]] | Village | Surface | 0.15 | 15% | 3 of 4 |
| [[Coalpit]] | Village | Surface | 0.15 | 15% | 4 of 5 |
| [[Cragmoor]] | Village | Surface | 0.15 | 15% | 4 of 7 |
| [[Crossroads Landing]] | Town | Surface | 0.15 | 15% | 5 of 7 |
| [[Dragonscar]] | Town | Surface | 0.15 | 15% | 4 of 7 |
| [[Drifter's Hollow]] | Village | Surface | 0.15 | 15% | 4 of 7 |
| [[Fangmarket]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Greyport]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Grubstake Fort]] | Fort | Surface | 0.15 | 15% | 2 of 3 |
| [[Gutstitch]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Hammerfell]] | Fort | Surface | 0.15 | 15% | 4 of 4 |
| [[Highwall]] | Fort | Surface | 0.15 | 15% | 4 of 6 |
| [[Ironhaven]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Knifebottom]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Labyrinth's Gate]] | Town | Surface | 0.15 | 15% | 3 of 6 |
| [[Mucksprawl]] | Town | Surface | 0.15 | 15% | 2 of 3 |
| [[Ratrun]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Rottenbow]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.15 | 15% | 4 of 6 |
| [[Scrappers Drift]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Skewerden]] | Village | Surface | 0.15 | 15% | 2 of 3 |
| [[Slag Market]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Vagrant's Rest]] | Village | Surface | 0.15 | 15% | 4 of 7 |
| [[Wolfspire]] | Town | Surface | 0.15 | 15% | 5 of 5 |
| [[Elmhurst]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Rimespire]] | Fort | Surface | 0.15 | 15% | 4 of 5 |
| [[Barrowdale]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Bonepath]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Briarford]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Dragon's Perch]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Elderpine]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Ember's Edge]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Fangwood]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Frostden]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Glacierfall]] | Village | Surface | 0.1 | 10% | 4 of 6 |
| [[Grayfang Hold]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Greenmaw]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Howl Keep]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Kingsmead]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Kingsreach]] | Capital | Surface | 0.1 | 10% | 5 of 8 |
| [[Lone Watch Fort]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Lonepine]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Long Howl]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Moonfang]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Moonridge]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Oxbow]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Rattletrap]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Ravensfeather]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Sanctuary of the Silver Flame]] | Temple | Surface | 0.1 | 10% | 6 of 6 |
| [[Scrapheap]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Snowwatch]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Wayward Inn]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Yarmouth]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Howling Pines]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.05 | 5% | 8 of 8 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (7 of 18), [[Reaver Hall]] (12 of 13), [[Hunters' Lodge]] (1 of 11), [[Holy Order]] (2 of 12), [[Wildwardens]] (3 of 16), [[Cogwrights' Guild]] (2 of 10), [[Sawbones Hall]] (1 of 7)

**Temple-only backgrounds:** [[Penitent]]

## Ratkin

[[Ratkin]] · threshold 12

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Gloomweb Market]] | Town | Underground (mid) | 0.2 | 20% | 3 of 5 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.15 | 15% | 5 of 6 |
| [[The Crawling Dark]] | Village | Underground (deep) | 0.1 | 10% | 5 of 5 |
| [[Greenmaw]] | Village | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (2 of 18), [[Reaver Hall]] (1 of 13), [[Blade Circle]] (1 of 10), [[Hunters' Lodge]] (3 of 11), [[Shadow Guild]] (10 of 17), [[Holy Order]] (1 of 12), [[Wildwardens]] (2 of 16), [[Cogwrights' Guild]] (3 of 10), [[Sawbones Hall]] (2 of 7)

## Spriggan

[[Spriggan]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Sporewick]] | Village | Surface | 0.4 | 40% | 1 of 6 |
| [[Starfall Glade]] | Village | Surface | 0.2 | 20% | 2 of 5 |
| [[Ironroot]] | Village | Surface | 0.2 | 20% | 2 of 6 |
| [[Blackthorn]] | Village | Surface | 0.15 | 15% | 5 of 7 |
| [[Verdantshade]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Whisperwood]] | Village | Surface | 0.15 | 15% | 2 of 5 |
| [[Boghollow]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Bogside]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Cedarlight]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Oakenford]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Reed's End]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Sablewood]] | Town | Surface | 0.1 | 10% | 7 of 7 |
| [[Scalemire]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Thistleveil]] | Village | Surface | 0.1 | 10% | 5 of 5 |
| [[Thornhaven]] | Town | Surface | 0.1 | 10% | 6 of 7 |

**Guild backgrounds open to this race:** [[Reaver Hall]] (1 of 13), [[Blade Circle]] (1 of 10), [[Hunters' Lodge]] (9 of 11), [[Shadow Guild]] (2 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Wildwardens]] (11 of 16), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (3 of 7)

## Stoneman

[[Stoneman]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Abyssal Throne]] | Fort | Underground (deep) | 0.25 | 25% | 2 of 5 |
| [[Emberheart Forge]] | Fort | Underground (deep) | 0.25 | 25% | 2 of 5 |
| [[Iron Tomb Garrison]] | Fort | Underground (mid) | 0.25 | 25% | 2 of 5 |
| [[Granite Watch]] | Fort | Underground (shallow) | 0.2 | 20% | 3 of 5 |
| [[Slag Furnace]] | Town | Underground (mid) | 0.15 | 15% | 4 of 5 |
| [[The Undermoot]] | Town | Underground (mid) | 0.15 | 15% | 5 of 6 |
| [[Crystalspring]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Deepforge Hold]] | Fort | Underground (shallow) | 0.1 | 10% | 5 of 5 |
| [[Deephollow Proper]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Deepkeep]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Echohollow]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Lowveil]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Moonshade Caverns]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Shaftwarden]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Stonefoot]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Underwell]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Vault of Silentstone]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Vault Warden]] | Fort | Surface | 0.1 | 10% | 3 of 3 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (9 of 18), [[Reaver Hall]] (2 of 13), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (1 of 12), [[Wildwardens]] (1 of 16), [[Cogwrights' Guild]] (3 of 10)

## Sylphborne

[[Sylphborne]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Zephyr's Rest]] | Village | Surface | 0.45 | 45% | 1 of 6 |
| [[Moonhollow]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Windhaven]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Willowmere]] | Town | Surface | 0.1 | 10% | 5 of 5 |

**Guild backgrounds open to this race:** [[Blade Circle]] (3 of 10), [[Hunters' Lodge]] (7 of 11), [[Shadow Guild]] (4 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (2 of 12), [[Holy Order]] (2 of 12), [[Wildwardens]] (7 of 16), [[Sawbones Hall]] (2 of 7)

## Tiefling

[[Tiefling]] · threshold 5

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Ashen Redoubt]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Azure Court]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Blackcoal]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Cinderwell]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Dust Market]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Emberport]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Ghazira]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Obsidian Quarter]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Redspring]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Salt Pillar]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Sandgaze]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Scaleweave]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Scorched Keep]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Cindervale]] | Village | Surface | 0.4 | 40% | 1 of 6 |
| [[Ember's Edge]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Shadowmere]] | Town | Surface | 0.25 | 25% | 2 of 5 |
| [[Ashenmoor]] | Village | Surface | 0.2 | 20% | 2 of 7 |
| [[Blackmarket]] | Town | Surface | 0.2 | 20% | 3 of 6 |
| [[Crowsreach]] | Town | Surface | 0.2 | 20% | 2 of 6 |
| [[Dragon's Perch]] | Village | Surface | 0.15 | 15% | 2 of 7 |
| [[Duskhollow]] | Town | Underground (mid) | 0.15 | 15% | 5 of 5 |
| [[Lanternwick]] | Town | Surface | 0.15 | 15% | 5 of 5 |
| [[Lyceum of Ashenmoor]] | Magic Academy | Surface | 0.15 | 15% | 4 of 8 |
| [[Nightbloom]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Silkweb Grotto]] | Village | Surface | 0.15 | 15% | 4 of 4 |
| [[Nightveil]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Academy of the Veiled Star]] | Magic Academy | Surface | 0.1 | 10% | 7 of 7 |
| [[Dragonscar]] | Town | Surface | 0.1 | 10% | 6 of 7 |
| [[Drifter's Hollow]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Dunmoor]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Emberpeak]] | Town | Surface | 0.1 | 10% | 5 of 6 |
| [[Gallowfield]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Mistwall]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Rottenbow]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Scorched Crossing]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[The Blind Bazaar]] | Town | Underground (deep) | 0.1 | 10% | 6 of 6 |
| [[Umbral Gate]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Vagrant's Rest]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Voidreach]] | Town | Underground (deep) | 0.1 | 10% | 6 of 6 |
| [[The Undermoot]] | Town | Underground (mid) | 0.1 | 10% | 6 of 6 |
| [[Kingsreach]] | Capital | Surface | 0.05 | 5% | 8 of 8 |
| [[Rattletrap]] | Town | Surface | 0.05 | 5% | 6 of 6 |
| [[Slag Market]] | Town | Surface | 0.05 | 5% | 6 of 6 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (3 of 18), [[Reaver Hall]] (3 of 13), [[Blade Circle]] (1 of 10), [[Shadow Guild]] (2 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (5 of 12), [[Holy Order]] (5 of 12), [[Sawbones Hall]] (1 of 7)

**Temple-only backgrounds:** [[Penitent]]

## Vampling

[[Vampling]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Nightbloom]] | Village | Surface | 0.35 | 35% | 1 of 6 |
| [[Nightveil]] | Town | Surface | 0.2 | 20% | 2 of 5 |
| [[Mistwall]] | Village | Surface | 0.15 | 15% | 3 of 7 |
| [[Voidreach]] | Town | Underground (deep) | 0.15 | 15% | 4 of 6 |
| [[Ashen Redoubt]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Azure Court]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Barrowdale]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Blackcoal]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Cindervale]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Cinderwell]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Crowsreach]] | Town | Surface | 0.1 | 10% | 6 of 6 |
| [[Dust Market]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Emberport]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Ghazira]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Obsidian Quarter]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Redspring]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Salt Pillar]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Sandgaze]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Scaleweave]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Scorched Keep]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Ravensholme]] | Town | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Blade Circle]] (2 of 10), [[Shadow Guild]] (10 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (4 of 12), [[Holy Order]] (1 of 12), [[Cogwrights' Guild]] (1 of 10), [[Sawbones Hall]] (1 of 7)

## Wild Elf

[[Wild Elf]] · threshold 10

*This race is not in any settlement's population, so it never appears in settlement recruit pools. It can still come from a founding or guild, if the rules above allow it.*

**Guild backgrounds open to this race:** [[Reaver Hall]] (4 of 13), [[Blade Circle]] (1 of 10), [[Hunters' Lodge]] (8 of 11), [[Shadow Guild]] (1 of 17), [[Wildwardens]] (9 of 16), [[Sawbones Hall]] (1 of 7)

## Wolfkin

[[Wolfkin]] · threshold 5

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Bonepath]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Elderpine]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Frostden]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Grayfang Hold]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Howl Keep]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Lone Watch Fort]] | Fort | Surface | 0.75 | 75% | 1 of 3 |
| [[Lonepine]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Long Howl]] | Town | Surface | 0.75 | 75% | 1 of 3 |
| [[Moonfang]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Ravensfeather]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Snowwatch]] | Village | Surface | 0.75 | 75% | 1 of 3 |
| [[Moonridge]] | Village | Surface | 0.5 | 50% | 1 of 6 |
| [[Howling Pines]] | Village | Surface | 0.45 | 45% | 1 of 6 |
| [[Fangwood]] | Town | Surface | 0.4 | 40% | 1 of 6 |
| [[Wolfspire]] | Town | Surface | 0.3 | 30% | 1 of 5 |
| [[Wulfmere]] | Village | Surface | 0.3 | 30% | 2 of 6 |
| [[Oakenford]] | Town | Surface | 0.15 | 15% | 4 of 5 |
| [[Sablewood]] | Town | Surface | 0.15 | 15% | 5 of 7 |
| [[Thistleveil]] | Village | Surface | 0.15 | 15% | 3 of 5 |
| [[Warg's Rest]] | Village | Surface | 0.15 | 15% | 3 of 6 |
| [[Cragmoor]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Drifter's Hollow]] | Village | Surface | 0.1 | 10% | 7 of 7 |
| [[Glacierfall]] | Village | Surface | 0.1 | 10% | 5 of 6 |
| [[Shadowmere]] | Town | Surface | 0.1 | 10% | 5 of 5 |
| [[Whisperwood]] | Village | Surface | 0.1 | 10% | 4 of 5 |
| [[Rimespire]] | Fort | Surface | 0.1 | 10% | 5 of 5 |
| [[Skulltop]] | Village | Surface | 0.05 | 5% | 5 of 5 |
| [[Vagrant's Rest]] | Village | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Reaver Hall]] (4 of 13), [[Hunters' Lodge]] (8 of 11), [[Shadow Guild]] (1 of 17), [[Wildwardens]] (9 of 16), [[Cogwrights' Guild]] (2 of 10), [[Sawbones Hall]] (2 of 7)

## Wraithkin

[[Wraithkin]] · threshold 15

| Settlement | Type | Where | Weight | Share | Rank |
|---|---|---|---|---|---|
| [[Mistwall]] | Village | Surface | 0.35 | 35% | 1 of 7 |
| [[Umbral Gate]] | Fort | Surface | 0.2 | 20% | 2 of 5 |
| [[Voidreach]] | Town | Underground (deep) | 0.2 | 20% | 2 of 6 |
| [[Abyssal Throne]] | Fort | Underground (deep) | 0.15 | 15% | 4 of 5 |
| [[Barrowdale]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Crowsreach]] | Town | Surface | 0.15 | 15% | 4 of 6 |
| [[Ashenmoor]] | Village | Surface | 0.1 | 10% | 6 of 7 |
| [[Ashwoven]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Blackthread]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Moonless]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Nightbloom]] | Village | Surface | 0.1 | 10% | 6 of 6 |
| [[Ravensholme]] | Town | Surface | 0.1 | 10% | 6 of 7 |
| [[Shadowkin]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Silentstep]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Spider Court]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Spider Gate]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Spinelight]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Thornloom]] | Village | Surface | 0.1 | 10% | 3 of 3 |
| [[Umbral Redoubt]] | Fort | Surface | 0.1 | 10% | 3 of 3 |
| [[Veilstone]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Weaver Hall]] | Town | Surface | 0.1 | 10% | 3 of 3 |
| [[Cindervale]] | Village | Surface | 0.05 | 5% | 6 of 6 |
| [[Cragmoor]] | Village | Surface | 0.05 | 5% | 7 of 7 |

**Guild backgrounds open to this race:** [[Fighters' Guild]] (1 of 18), [[Blade Circle]] (2 of 10), [[Shadow Guild]] (9 of 17), [[Arcane Conclave (Guild)|Arcane Conclave]] (4 of 12), [[Holy Order]] (1 of 12), [[Cogwrights' Guild]] (2 of 10), [[Sawbones Hall]] (1 of 7)

## Guild halls

Guild halls offer veterans whose background is rolled by rarity from the guild's list (see each guild page). The data gives guilds no race weights. The guild lines above count how many of a guild's backgrounds appear in that race's `available_backgrounds`. Guilds and races both carry `gear_affinities`, but the data does not say whether these interact, or how.

> [!note]- Developer notes
> Curated core/iconic races eligible to be a clan's Prime. Each must be a common race (recruitment_threshold below 5): the Prime race is only added to town recruit pools once it clears the company-level gate, so an uncommon Prime would be missing from almost every town at level 1.

*Generated from `settlements/*.json`, `races/*.json`, `foundings/foundings.json`, `guilds/guilds.json`, `traits/company_traits.json`, `pois/poi_templates.json`, `backgrounds/*.json`. Edits will be overwritten — put your own notes in Notes/.*
