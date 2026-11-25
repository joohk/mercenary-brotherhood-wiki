---
type: page
aliases:
  - Background Locations
  - Where to find backgrounds
tags:
  - type/page
source:
  - "backgrounds/*.json"
  - "races/*.json"
  - guilds/guilds.json
  - "settlements/*.json"
up: "[[Your Company]]"
---

[[Home]] › [[Your Company]]

Where each background can be recruited: which races can roll it, how heavily it is weighted, which guild halls offer it, and which settlements are most likely to supply it.

## How backgrounds are rolled

- A settlement recruit's race is picked first (see [[Where Races Live]]). The background is then rolled from that race's `available_backgrounds`.
- Only 13 of 115 backgrounds set an explicit `recruitment_weight`. The rest leave it blank, so the game uses a default the data doesn't show (rarity likely plays a part). For that reason this page gives no exact odds: it shows the weight where the data sets one ("—" where it doesn't) and the rarity.
- **Settlement presence** adds up the population shares of the hireable races that can roll the background. It shows where the right races live, not the odds of rolling the background itself.
- Backgrounds marked `temple_only` are offered only at temples.
- **Guild halls** roll the background by rarity from the guild's own list, weighted up by hire level (see each guild page).
- "Cost mod" is the background's `recruitment_cost_modifier`, a multiplier on the hiring price.

## Background finder

| Background | Rarity | Weight | Cost mod | Temple only | Races | Guild halls |
|---|---|---|---|---|---|---|
| [[Where Backgrounds Come From#Acolyte\|Acolyte]] | Common | 30 | 0.6 |  | 8 | [[Holy Order]] |
| [[Where Backgrounds Come From#Acolyte Militant\|Acolyte Militant]] | Common | — | 0.75 | Yes | 4 | [[Holy Order]] |
| [[Where Backgrounds Come From#Alchemist\|Alchemist]] | Uncommon | — | 1.02 |  | 5 | [[Cogwrights' Guild]], [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Arcane Prodigy\|Arcane Prodigy]] | Legendary | — | 2.14 |  | 5 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Assassin\|Assassin]] | Rare | — | 1.49 |  | 4 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Bard\|Bard]] | Rare | — | 1.55 |  | 7 | — |
| [[Where Backgrounds Come From#Beast Tamer\|Beast Tamer]] | Uncommon | — | 0.93 |  | 5 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Beastmaster\|Beastmaster]] | Rare | — | 1.55 |  | 3 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Beggar\|Beggar]] | Common | — | 0.59 |  | 6 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Berserker\|Berserker]] | Uncommon | — | 1.14 |  | 8 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Blade Dancer\|Blade Dancer]] | Rare | — | 1.58 |  | 5 | [[Blade Circle]] |
| [[Where Backgrounds Come From#Blood Initiate\|Blood Initiate]] | Common | 25 | 0.65 |  | 14 | — |
| [[Where Backgrounds Come From#Blood Shaman\|Blood Shaman]] | Rare | — | 1.55 |  | 2 | [[Wildwardens]], [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Bonecarver\|Bonecarver]] | Common | — | 0.57 |  | 2 | — |
| [[Where Backgrounds Come From#Bounty Hunter\|Bounty Hunter]] | Uncommon | — | 1.25 |  | 3 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Candle Witch\|Candle Witch]] | Common | 30 | 0.6 |  | 10 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Caravan Guard\|Caravan Guard]] | Common | — | 0.89 |  | 9 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Cave Crawler\|Cave Crawler]] | Common | — | 0.55 |  | 7 | — |
| [[Where Backgrounds Come From#Champion\|Champion]] | Rare | — | 2.16 |  | 2 | [[Fighters' Guild]], [[Blade Circle]] |
| [[Where Backgrounds Come From#Chaplain\|Chaplain]] | Uncommon | — | 1.15 |  | 7 | [[Holy Order]] |
| [[Where Backgrounds Come From#Corsair\|Corsair]] | Uncommon | — | 1.08 |  | 3 | [[Reaver Hall]], [[Blade Circle]] |
| [[Where Backgrounds Come From#Crusader\|Crusader]] | Rare | — | 2 | Yes | 2 | [[Holy Order]] |
| [[Where Backgrounds Come From#Cultist\|Cultist]] | Uncommon | — | 0.85 |  | 7 | — |
| [[Where Backgrounds Come From#Death Dealer\|Death Dealer]] | Legendary | — | 2.32 |  | 6 | — |
| [[Where Backgrounds Come From#Deserter\|Deserter]] | Common | — | 0.82 |  | 2 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Dragon Slayer\|Dragon Slayer]] | Legendary | — | 2.5 |  | 2 | — |
| [[Where Backgrounds Come From#Dreadnought\|Dreadnought]] | Rare | — | 1.85 |  | 5 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Druid\|Druid]] | Uncommon | — | 1.04 |  | 7 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Duelist\|Duelist]] | Uncommon | — | 1.23 |  | 5 | [[Blade Circle]] |
| [[Where Backgrounds Come From#Enforcer\|Enforcer]] | Uncommon | — | 1.14 |  | 5 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Executioner\|Executioner]] | Rare | — | 1.78 |  | 6 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Farmhand\|Farmhand]] | Common | — | 0.56 |  | 2 | — |
| [[Where Backgrounds Come From#Feral Champion\|Feral Champion]] | Legendary | — | 2.14 |  | 8 | [[Reaver Hall]], [[Wildwardens]] |
| [[Where Backgrounds Come From#First Blade\|First Blade]] | Legendary | — | 2.28 |  | 3 | [[Blade Circle]] |
| [[Where Backgrounds Come From#Fisherman\|Fisherman]] | Common | — | 0.58 |  | 4 | — |
| [[Where Backgrounds Come From#Forager\|Forager]] | Common | — | 0.55 |  | 11 | [[Hunters' Lodge]], [[Wildwardens]], [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Fortune Teller\|Fortune Teller]] | Common | 30 | 0.6 |  | 7 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Fungus Farmer\|Fungus Farmer]] | Common | — | 0.5 |  | 5 | — |
| [[Where Backgrounds Come From#Geomancer\|Geomancer]] | Uncommon | — | 0.96 |  | 2 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Gladiator\|Gladiator]] | Uncommon | — | 1.24 |  | 6 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Grand Master\|Grand Master]] | Legendary | — | 2.43 |  | 3 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Grave Digger\|Grave Digger]] | Common | — | 0.54 |  | 7 | — |
| [[Where Backgrounds Come From#Grave Knight\|Grave Knight]] | Uncommon | — | 1.35 |  | 2 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Grave Tender\|Grave Tender]] | Common | 30 | 0.58 |  | 10 | [[Holy Order]], [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Guardian\|Guardian]] | Rare | — | 1.71 |  | 4 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Hedge Knight\|Hedge Knight]] | Uncommon | — | 1.32 |  | 2 | [[Fighters' Guild]], [[Blade Circle]] |
| [[Where Backgrounds Come From#Hedge Wizard\|Hedge Wizard]] | Common | 30 | 0.65 |  | 7 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Herb Apprentice\|Herb Apprentice]] | Common | 30 | 0.55 |  | 9 | [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Herbalist\|Herbalist]] | Uncommon | — | 0.77 |  | 4 | [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Hunter\|Hunter]] | Uncommon | — | 1.27 |  | 5 | [[Hunters' Lodge]] |
| [[Where Backgrounds Come From#Iron Warden\|Iron Warden]] | Rare | — | 1.92 |  | 4 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Laborer\|Laborer]] | Common | — | 0.53 |  | 9 | [[Fighters' Guild]], [[Reaver Hall]], [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Legendary Hunter\|Legendary Hunter]] | Legendary | — | 2.36 |  | 7 | [[Hunters' Lodge]], [[Wildwardens]] |
| [[Where Backgrounds Come From#Mariner\|Mariner]] | Uncommon | — | 0.91 |  | 1 | — |
| [[Where Backgrounds Come From#Master Archer\|Master Archer]] | Rare | — | 1.63 |  | 3 | [[Hunters' Lodge]] |
| [[Where Backgrounds Come From#Militia\|Militia]] | Common | — | 0.89 |  | 9 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Mind Shaper\|Mind Shaper]] | Rare | — | 1.55 |  | 5 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Miner\|Miner]] | Uncommon | — | 1.1 |  | 3 | [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Minstrel\|Minstrel]] | Common | 30 | 0.75 |  | 4 | — |
| [[Where Backgrounds Come From#Monk\|Monk]] | Uncommon | — | 0.91 |  | 3 | [[Holy Order]] |
| [[Where Backgrounds Come From#Mudfoot\|Mudfoot]] | Common | 30 | 0.6 |  | 12 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Nightblade\|Nightblade]] | Rare | — | 1.78 |  | 5 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Outrider\|Outrider]] | Uncommon | — | 1.18 |  | 5 | [[Hunters' Lodge]] |
| [[Where Backgrounds Come From#Pathfinder\|Pathfinder]] | Uncommon | — | 0.97 |  | 5 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Penitent\|Penitent]] | Uncommon | — | 1.15 | Yes | 5 | [[Holy Order]] |
| [[Where Backgrounds Come From#Phantom Lord\|Phantom Lord]] | Legendary | — | 2.08 |  | 6 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Pilgrim\|Pilgrim]] | Common | 30 | 0.58 |  | 4 | [[Holy Order]] |
| [[Where Backgrounds Come From#Pit Fighter\|Pit Fighter]] | Rare | — | 1.5 |  | 7 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Pit Slave\|Pit Slave]] | Common | — | 0.67 |  | 6 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Poacher\|Poacher]] | Uncommon | — | 1.1 |  | 7 | [[Hunters' Lodge]], [[Wildwardens]] |
| [[Where Backgrounds Come From#Raider\|Raider]] | Uncommon | — | 1.02 |  | 2 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Ranger\|Ranger]] | Uncommon | — | 1.25 |  | 6 | [[Hunters' Lodge]], [[Wildwardens]] |
| [[Where Backgrounds Come From#Rat Catcher\|Rat Catcher]] | Common | — | 0.6 |  | 3 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Ravager\|Ravager]] | Rare | — | 1.54 |  | 4 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Royal Exile\|Royal Exile]] | Legendary | — | 2.2 |  | 2 | [[Blade Circle]] |
| [[Where Backgrounds Come From#Runecarver\|Runecarver]] | Uncommon | — | 0.96 |  | 5 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Saboteur\|Saboteur]] | Uncommon | — | 1.02 |  | 5 | [[Shadow Guild]], [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Scavenger\|Scavenger]] | Common | — | 0.59 |  | 7 | [[Shadow Guild]], [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Scout\|Scout]] | Uncommon | — | 1.02 |  | 10 | [[Hunters' Lodge]] |
| [[Where Backgrounds Come From#Scroll Scribe\|Scroll Scribe]] | Common | 30 | 0.6 |  | 5 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Sellsword\|Sellsword]] | Uncommon | — | 1.15 |  | 3 | [[Fighters' Guild]], [[Blade Circle]] |
| [[Where Backgrounds Come From#Shade Walker\|Shade Walker]] | Rare | — | 1.31 |  | 8 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Shadow Blade\|Shadow Blade]] | Rare | — | 1.59 |  | 5 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Shadow Mage\|Shadow Mage]] | Uncommon | — | 1.25 |  | 4 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Shaman\|Shaman]] | Common | 30 | 0.65 |  | 5 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Shepherd\|Shepherd]] | Common | — | 0.62 |  | 5 | [[Hunters' Lodge]], [[Wildwardens]] |
| [[Where Backgrounds Come From#Shield Master\|Shield Master]] | Rare | — | 1.69 |  | 2 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Siege Breaker\|Siege Breaker]] | Rare | — | 1.71 |  | 5 | [[Fighters' Guild]], [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Smith\|Smith]] | Uncommon | — | 1.04 |  | 2 | [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Soldier\|Soldier]] | Uncommon | — | 1.32 |  | 12 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Spymaster\|Spymaster]] | Rare | — | 1.74 |  | 5 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Stalker\|Stalker]] | Rare | — | 1.66 |  | 8 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Street Urchin\|Street Urchin]] | Common | — | 0.67 |  | 5 | [[Blade Circle]], [[Shadow Guild]] |
| [[Where Backgrounds Come From#Tanner\|Tanner]] | Common | — | 0.74 |  | 2 | [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Templar\|Templar]] | Rare | — | 1.86 |  | 1 | [[Holy Order]] |
| [[Where Backgrounds Come From#Temple Guard\|Temple Guard]] | Common | — | 0.85 | Yes | 4 | [[Fighters' Guild]], [[Holy Order]] |
| [[Where Backgrounds Come From#Thief\|Thief]] | Uncommon | — | 0.93 |  | 7 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Tinkerer\|Tinkerer]] | Uncommon | — | 1.15 |  | 2 | [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Tomb Robber\|Tomb Robber]] | Uncommon | — | 0.97 |  | 3 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Torch Bearer\|Torch Bearer]] | Common | — | 0.53 |  | 5 | — |
| [[Where Backgrounds Come From#Trapper\|Trapper]] | Common | — | 0.65 |  | 10 | [[Hunters' Lodge]], [[Wildwardens]] |
| [[Where Backgrounds Come From#Tribal Warrior\|Tribal Warrior]] | Uncommon | — | 1.03 |  | 9 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Undying Sentinel\|Undying Sentinel]] | Legendary | — | 2.35 |  | 5 | [[Fighters' Guild]] |
| [[Where Backgrounds Come From#Vagabond\|Vagabond]] | Common | — | 0.55 |  | 3 | [[Blade Circle]], [[Shadow Guild]] |
| [[Where Backgrounds Come From#Venom Adept\|Venom Adept]] | Rare | — | 1.54 |  | 2 | [[Sawbones Hall]] |
| [[Where Backgrounds Come From#Void Touched\|Void Touched]] | Legendary | — | 2.01 |  | 6 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#War Mage\|War Mage]] | Rare | — | 1.57 |  | 1 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#War Priest\|War Priest]] | Rare | — | 1.75 |  | 2 | [[Holy Order]] |
| [[Where Backgrounds Come From#Warchief\|Warchief]] | Legendary | — | 2.28 |  | 5 | [[Reaver Hall]] |
| [[Where Backgrounds Come From#Warden\|Warden]] | Uncommon | — | 1.23 |  | 5 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Warlock\|Warlock]] | Uncommon | — | 1.35 |  | 5 | [[Arcane Conclave (Guild)\|Arcane Conclave]] |
| [[Where Backgrounds Come From#Witch Doctor\|Witch Doctor]] | Common | 30 | 0.62 |  | 1 | [[Wildwardens]] |
| [[Where Backgrounds Come From#Witch Hunter\|Witch Hunter]] | Uncommon | — | 1.27 |  | 1 | [[Shadow Guild]] |
| [[Where Backgrounds Come From#Woodcutter\|Woodcutter]] | Common | — | 0.65 |  | 4 | [[Hunters' Lodge]], [[Wildwardens]], [[Cogwrights' Guild]] |
| [[Where Backgrounds Come From#Zealot\|Zealot]] | Uncommon | — | 1.07 |  | 5 | [[Holy Order]] |

## Acolyte

[[Acolyte]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Elf]] | 0 | Yes | 30 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Stoneman]] | 15 | Yes | 17 |
| [[Sylphborne]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Willowmere]] 100%, [[Appleburrow]] 100%, [[Brassburrow Fort]] 100%, [[Buttercup Hollow]] 100%, [[Buttonwood]] 100%, [[Cogwhisper]] 100%

**Guild halls:** [[Holy Order]] (common)

## Acolyte Militant

[[Acolyte Militant]] · Common · weight — (default) · **temple only**

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Guild halls:** [[Holy Order]] (common)

## Alchemist

[[Alchemist]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Saltgrotto]] 80%, [[Boglight]] 75%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Crystalspring]] 75%

**Guild halls:** [[Cogwrights' Guild]] (uncommon), [[Sawbones Hall]] (uncommon)

## Arcane Prodigy

[[Arcane Prodigy]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Starfall Glade]] 80%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Crystalspring]] 75%, [[Deephollow Proper]] 75%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (legendary)

## Assassin

[[Assassin (Background)|Assassin]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Boglight]] 75%, [[Fangmarket]] 75%, [[Grubstake Fort]] 75%, [[Knifebottom]] 75%

**Guild halls:** [[Shadow Guild]] (rare)

## Bard

[[Bard]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Willowmere]] 100%, [[Appleburrow]] 100%, [[Buttercup Hollow]] 100%, [[Elmsworth]] 100%, [[Evenshade]] 100%, [[Hollowfield]] 100%

## Beast Tamer

[[Beast Tamer]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%, [[Howl Keep]] 75%, [[Lone Watch Fort]] 75%

**Guild halls:** [[Wildwardens]] (uncommon)

## Beastmaster

[[Beastmaster]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%, [[Howl Keep]] 75%, [[Lone Watch Fort]] 75%

**Guild halls:** [[Wildwardens]] (rare)

## Beggar

[[Beggar]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Nightveil]] 90%, [[Ashen Redoubt]] 85%, [[Azure Court]] 85%, [[Blackcoal]] 85%, [[Cinderwell]] 85%, [[Dust Market]] 85%

**Guild halls:** [[Shadow Guild]] (common)

## Berserker

[[Berserker (Background)|Berserker]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Frostborn]] | 15 | Yes | 19 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Bonepath]] 85%, [[Elderpine]] 85%, [[Frostden]] 85%, [[Grayfang Hold]] 85%, [[Howl Keep]] 85%

**Guild halls:** [[Reaver Hall]] (uncommon)

## Blade Dancer

[[Blade Dancer]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Evenshade]] 90%, [[Moonleaf Ward]] 90%, [[Silverbough]] 90%, [[Starlight Grove]] 90%, [[Thornwillow]] 90%, [[Wyrdleaf]] 90%

**Guild halls:** [[Blade Circle]] (rare)

## Blood Initiate

[[Blood Initiate]] · Common · weight 25

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 100%, [[Ashwoven]] 100%, [[Azure Court]] 100%, [[Blackcoal]] 100%, [[Blackthread]] 100%, [[Bonepath]] 100%

## Blood Shaman

[[Blood Shaman]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Lizardfolk]] | 0 | Yes | 23 |

**Settlement presence** (combined share of eligible races): [[Crystalspring]] 75%, [[Deephollow Proper]] 75%, [[Deepkeep]] 75%, [[Echohollow]] 75%, [[Lowveil]] 75%, [[Moonshade Caverns]] 75%

**Guild halls:** [[Wildwardens]] (rare), [[Sawbones Hall]] (rare)

## Bonecarver

[[Bonecarver]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%, [[Howl Keep]] 75%, [[Lone Watch Fort]] 75%

## Bounty Hunter

[[Bounty Hunter]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnome]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Vampling]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Aldwick]] 75%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Elmsworth]] 75%, [[Filigree Glen]] 75%

**Guild halls:** [[Shadow Guild]] (uncommon)

## Candle Witch

[[Candle Witch]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Dragolin]] | 15 | Yes | 19 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Academy of the Veiled Star]] 100%, [[Cedarlight]] 100%, [[Aldwick]] 100%, [[Appleburrow]] 100%, [[Ashgate]] 100%, [[Blackthorn]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (common)

## Caravan Guard

[[Caravan Guard]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 100%, [[Elderpine]] 100%, [[Emberfall]] 100%, [[Frostden]] 100%, [[Grayfang Hold]] 100%, [[Howl Keep]] 100%

**Guild halls:** [[Fighters' Guild]] (common)

## Cave Crawler

[[Cave Crawler]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 90%, [[Blackthread]] 90%, [[Moonless]] 90%, [[Shadowkin]] 90%, [[Silentstep]] 90%, [[Spider Court]] 90%

## Champion

[[Champion (Background)|Champion]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 75%, [[Hollowfield]] 75%, [[Rivermere]] 75%, [[Stillbrook]] 75%, [[Aldwick]] 65%, [[Duskfield]] 60%

**Guild halls:** [[Fighters' Guild]] (rare), [[Blade Circle]] (rare)

## Chaplain

[[Chaplain]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 100%, [[Brassburrow Fort]] 100%, [[Buttercup Hollow]] 100%, [[Buttonwood]] 100%, [[Cogwhisper]] 100%, [[Deephearth Forge]] 100%

**Guild halls:** [[Holy Order]] (uncommon)

## Corsair

[[Corsair]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Boglight]] 75%, [[Fangmarket]] 75%, [[Grubstake Fort]] 75%, [[Knifebottom]] 75%

**Guild halls:** [[Reaver Hall]] (uncommon), [[Blade Circle]] (uncommon)

## Crusader

[[Crusader (Background)|Crusader]] · Rare · weight — (default) · **temple only**

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Human]] | 0 | Yes | 36 |

**Guild halls:** [[Holy Order]] (rare)

## Cultist

[[Cultist]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 100%, [[Blackthread]] 100%, [[Moonless]] 100%, [[Shadowkin]] 100%, [[Silentstep]] 100%, [[Spider Court]] 100%

## Death Dealer

[[Death Dealer]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 85%, [[Blackthread]] 85%, [[Moonless]] 85%, [[Shadowkin]] 85%, [[Silentstep]] 85%, [[Spider Court]] 85%

## Deserter

[[Deserter]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Human]] | 0 | Yes | 36 |
| [[Orc]] | 0 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 85%, [[Broken Palisade]] 85%, [[Gorewhistle]] 85%, [[Irontooth]] 85%, [[Rendpost]] 85%, [[Screamhold]] 85%

**Guild halls:** [[Fighters' Guild]] (common)

## Dragon Slayer

[[Dragon Slayer (Background)|Dragon Slayer]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Frostborn]] | 15 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Glacierfall]] 45%, [[Dragon's Perch]] 40%, [[Rimespire]] 40%, [[Dragonscar]] 30%, [[Emberfall]] 20%, [[Cragmoor]] 15%

## Dreadnought

[[Dreadnought]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Emberheart Forge]] 90%, [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%

**Guild halls:** [[Fighters' Guild]] (rare)

## Druid

[[Druid (Background)|Druid]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Whisperwood]] 95%, [[Starfall Glade]] 90%, [[Brassburrow Fort]] 90%, [[Buttonwood]] 90%, [[Cogwhisper]] 90%, [[Evenshade]] 90%

**Guild halls:** [[Wildwardens]] (uncommon)

## Duelist

[[Duelist (Background)|Duelist]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Elf]] | 0 | Yes | 30 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 85%, [[Blackthread]] 85%, [[Moonless]] 85%, [[Shadowkin]] 85%, [[Silentstep]] 85%, [[Spider Court]] 85%

**Guild halls:** [[Blade Circle]] (uncommon)

## Enforcer

[[Enforcer]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Bloodfield]] 75%

**Guild halls:** [[Fighters' Guild]] (uncommon)

## Executioner

[[Executioner (Background)|Executioner]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Bloodfield]] 75%

**Guild halls:** [[Reaver Hall]] (rare)

## Farmhand

[[Farmhand]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Human]] | 0 | Yes | 36 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 90%, [[Azure Court]] 90%, [[Blackcoal]] 90%, [[Cinderwell]] 90%, [[Dust Market]] 90%, [[Emberport]] 90%

## Feral Champion

[[Feral Champion]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Bonepath]] 85%, [[Elderpine]] 85%, [[Frostden]] 85%, [[Grayfang Hold]] 85%, [[Howl Keep]] 85%

**Guild halls:** [[Reaver Hall]] (legendary), [[Wildwardens]] (legendary)

## First Blade

[[First Blade]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Elf]] | 0 | Yes | 30 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 85%, [[Evenshade]] 85%, [[Hollowfield]] 85%, [[Moonleaf Ward]] 85%, [[Rivermere]] 85%, [[Silverbough]] 85%

**Guild halls:** [[Blade Circle]] (legendary)

## Fisherman

[[Fisherman]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Evenshade]] 75%, [[Filigree Glen]] 75%, [[Kettlebridge]] 75%

## Forager

[[Forager]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Whisperwood]] 95%, [[Starfall Glade]] 90%, [[Brassburrow Fort]] 90%, [[Buttonwood]] 90%, [[Cogwhisper]] 90%, [[Evenshade]] 90%

**Guild halls:** [[Hunters' Lodge]] (common), [[Wildwardens]] (common), [[Sawbones Hall]] (common)

## Fortune Teller

[[Fortune Teller]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Human]] | 0 | Yes | 36 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 100%, [[Azure Court]] 100%, [[Blackcoal]] 100%, [[Cindervale]] 100%, [[Cinderwell]] 100%, [[Crowsreach]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (common)

## Fungus Farmer

[[Fungus Farmer]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Saltgrotto]] 80%, [[Boglight]] 75%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Crystalspring]] 75%

## Geomancer

[[Geomancer (Background)|Geomancer]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (uncommon)

## Gladiator

[[Gladiator (Background)|Gladiator]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Bloodfield]] 75%

**Guild halls:** [[Reaver Hall]] (uncommon)

## Grand Master

[[Grand Master]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Fighters' Guild]] (legendary)

## Grave Digger

[[Grave Digger]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Stoneman]] | 15 | Yes | 17 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Crystalspring]] 100%, [[Deephollow Proper]] 100%, [[Deepkeep]] 100%, [[Echohollow]] 100%, [[Lowveil]] 100%, [[Moonshade Caverns]] 100%

## Grave Knight

[[Grave Knight]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Mistwall]] 50%, [[Nightbloom]] 45%, [[Voidreach]] 35%, [[Barrowdale]] 25%, [[Crowsreach]] 25%, [[Umbral Gate]] 20%

**Guild halls:** [[Fighters' Guild]] (uncommon)

## Grave Tender

[[Grave Tender]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 100%, [[Ashwoven]] 100%, [[Azure Court]] 100%, [[Blackcoal]] 100%, [[Blackthread]] 100%, [[Bloodfield]] 100%

**Guild halls:** [[Holy Order]] (common), [[Sawbones Hall]] (common)

## Guardian

[[Guardian]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Fighters' Guild]] (rare)

## Hedge Knight

[[Hedge Knight]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 75%, [[Hollowfield]] 75%, [[Rivermere]] 75%, [[Stillbrook]] 75%, [[Aldwick]] 65%, [[Duskfield]] 60%

**Guild halls:** [[Fighters' Guild]] (uncommon), [[Blade Circle]] (uncommon)

## Hedge Wizard

[[Hedge Wizard]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Elf]] | 0 | Yes | 30 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Aldwick]] 100%, [[Appleburrow]] 100%, [[Ashgate]] 100%, [[Brambleshire]] 100%, [[Burrowton]] 100%, [[Buttercup Hollow]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (common)

## Herb Apprentice

[[Herb Apprentice]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Willowmere]] 100%, [[Appleburrow]] 100%, [[Brassburrow Fort]] 100%, [[Buttercup Hollow]] 100%, [[Buttonwood]] 100%, [[Cogwhisper]] 100%

**Guild halls:** [[Sawbones Hall]] (common)

## Herbalist

[[Herbalist]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Starfall Glade]] 90%, [[Brassburrow Fort]] 90%, [[Buttonwood]] 90%, [[Cogwhisper]] 90%, [[Evenshade]] 90%, [[Filigree Glen]] 90%

**Guild halls:** [[Sawbones Hall]] (uncommon)

## Hunter

[[Hunter]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%, [[Howl Keep]] 75%, [[Lone Watch Fort]] 75%

**Guild halls:** [[Hunters' Lodge]] (uncommon)

## Iron Warden

[[Iron Warden]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Fighters' Guild]] (rare)

## Laborer

[[Laborer]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Emberfall]] 100%, [[Fort Ironclad]] 95%, [[Horn's End]] 90%, [[Redhill]] 90%, [[Deephearth Forge]] 90%, [[Emberheart Forge]] 90%

**Guild halls:** [[Fighters' Guild]] (common), [[Reaver Hall]] (common), [[Cogwrights' Guild]] (common)

## Legendary Hunter

[[Legendary Hunter]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Whisperwood]] 95%, [[Starfall Glade]] 90%, [[Brassburrow Fort]] 90%, [[Buttonwood]] 90%, [[Cogwhisper]] 90%, [[Evenshade]] 90%

**Guild halls:** [[Hunters' Lodge]] (legendary), [[Wildwardens]] (legendary)

## Mariner

[[Mariner]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 75%, [[Hollowfield]] 75%, [[Rivermere]] 75%, [[Stillbrook]] 75%, [[Aldwick]] 65%, [[Duskfield]] 60%

## Master Archer

[[Master Archer]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Starfall Glade]] 80%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Evenshade]] 75%, [[Filigree Glen]] 75%

**Guild halls:** [[Hunters' Lodge]] (rare)

## Militia

[[Militia]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Stoneman]] | 15 | Yes | 17 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 90%, [[Azure Court]] 90%, [[Blackcoal]] 90%, [[Cinderwell]] 90%, [[Deephearth Forge]] 90%, [[Dragon's Perch]] 90%

**Guild halls:** [[Fighters' Guild]] (common)

## Mind Shaper

[[Mind Shaper]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 90%, [[Blackthread]] 90%, [[Moonless]] 90%, [[Shadowkin]] 90%, [[Silentstep]] 90%, [[Spider Court]] 90%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (rare)

## Miner

[[Miner]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Emberheart Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%

**Guild halls:** [[Cogwrights' Guild]] (uncommon)

## Minstrel

[[Minstrel]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 100%, [[Evenshade]] 100%, [[Hollowfield]] 100%, [[Moonleaf Ward]] 100%, [[Rivermere]] 100%, [[Silverbough]] 100%

## Monk

[[Monk]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Buttercup Hollow]] 75%, [[Crystalspring]] 75%, [[Deephollow Proper]] 75%, [[Deepkeep]] 75%, [[Echohollow]] 75%

**Guild halls:** [[Holy Order]] (uncommon)

## Mudfoot

[[Mudfoot]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Stoneman]] | 15 | Yes | 17 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 100%, [[Bloodrock]] 100%, [[Boglight]] 100%, [[Bonehill]] 100%, [[Bonepath]] 100%, [[Broken Palisade]] 100%

**Guild halls:** [[Reaver Hall]] (common)

## Nightblade

[[Nightblade (Background)|Nightblade]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 85%, [[Blackthread]] 85%, [[Moonless]] 85%, [[Shadowkin]] 85%, [[Silentstep]] 85%, [[Spider Court]] 85%

**Guild halls:** [[Shadow Guild]] (rare)

## Outrider

[[Outrider]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Elf]] | 0 | Yes | 30 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Bonepath]] 75%, [[Elderpine]] 75%, [[Evenshade]] 75%, [[Frostden]] 75%

**Guild halls:** [[Hunters' Lodge]] (uncommon)

## Pathfinder

[[Pathfinder]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Starfall Glade]] 80%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Evenshade]] 75%, [[Filigree Glen]] 75%

**Guild halls:** [[Wildwardens]] (uncommon)

## Penitent

[[Penitent]] · Uncommon · weight — (default) · **temple only**

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Guild halls:** [[Holy Order]] (uncommon)

## Phantom Lord

[[Phantom Lord]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Boglight]] 75%, [[Buttercup Hollow]] 75%, [[Fangmarket]] 75%, [[Grubstake Fort]] 75%, [[Honeystead]] 75%

**Guild halls:** [[Shadow Guild]] (legendary)

## Pilgrim

[[Pilgrim]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Sylphborne]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 100%, [[Evenshade]] 100%, [[Hollowfield]] 100%, [[Moonleaf Ward]] 100%, [[Rivermere]] 100%, [[Silverbough]] 100%

**Guild halls:** [[Holy Order]] (common)

## Pit Fighter

[[Pit Fighter]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 90%, [[Azure Court]] 90%, [[Blackcoal]] 90%, [[Cinderwell]] 90%, [[Dust Market]] 90%, [[Emberport]] 90%

**Guild halls:** [[Reaver Hall]] (rare)

## Pit Slave

[[Pit Slave]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Crushbone]] 75%, [[Dreadmaw]] 75%

**Guild halls:** [[Reaver Hall]] (common)

## Poacher

[[Poacher]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Orc]] | 0 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Evenshade]] 75%, [[Gorewhistle]] 75%, [[Irontooth]] 75%, [[Moonleaf Ward]] 75%

**Guild halls:** [[Hunters' Lodge]] (uncommon), [[Wildwardens]] (uncommon)

## Raider

[[Raider]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Frostborn]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Gorewhistle]] 75%, [[Irontooth]] 75%, [[Rendpost]] 75%, [[Screamhold]] 75%

**Guild halls:** [[Reaver Hall]] (uncommon)

## Ranger

[[Ranger (Background)|Ranger]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Whisperwood]] 85%, [[Bonepath]] 75%, [[Elderpine]] 75%, [[Evenshade]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%

**Guild halls:** [[Hunters' Lodge]] (uncommon), [[Wildwardens]] (uncommon)

## Rat Catcher

[[Rat Catcher]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Boglight]] 75%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Fangmarket]] 75%, [[Filigree Glen]] 75%

**Guild halls:** [[Shadow Guild]] (common)

## Ravager

[[Ravager (Background)|Ravager]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 85%, [[Elderpine]] 85%, [[Frostden]] 85%, [[Grayfang Hold]] 85%, [[Howl Keep]] 85%, [[Lone Watch Fort]] 85%

**Guild halls:** [[Reaver Hall]] (rare)

## Royal Exile

[[Royal Exile]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Human]] | 0 | Yes | 36 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 90%, [[Azure Court]] 90%, [[Blackcoal]] 90%, [[Cinderwell]] 90%, [[Dust Market]] 90%, [[Emberport]] 90%

**Guild halls:** [[Blade Circle]] (legendary)

## Runecarver

[[Runecarver]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Crystalspring]] 100%, [[Deephollow Proper]] 100%, [[Deepkeep]] 100%, [[Echohollow]] 100%, [[Lowveil]] 100%, [[Moonshade Caverns]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (uncommon)

## Saboteur

[[Saboteur]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Boglight]] 75%, [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Fangmarket]] 75%, [[Filigree Glen]] 75%

**Guild halls:** [[Shadow Guild]] (uncommon), [[Cogwrights' Guild]] (uncommon)

## Scavenger

[[Scavenger]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 85%, [[Blackthread]] 85%, [[Moonless]] 85%, [[Shadowkin]] 85%, [[Silentstep]] 85%, [[Spider Court]] 85%

**Guild halls:** [[Shadow Guild]] (common), [[Cogwrights' Guild]] (common)

## Scout

[[Scout]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Cedarlight]] 100%, [[Willowmere]] 100%, [[Aldwick]] 100%, [[Appleburrow]] 100%, [[Ashgate]] 100%, [[Brambleshire]] 100%

**Guild halls:** [[Hunters' Lodge]] (uncommon)

## Scroll Scribe

[[Scroll Scribe]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Dragolin]] | 15 | Yes | 19 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 85%, [[Evenshade]] 85%, [[Hollowfield]] 85%, [[Moonleaf Ward]] 85%, [[Rivermere]] 85%, [[Silverbough]] 85%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (common)

## Sellsword

[[Sellsword (Background)|Sellsword]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Goblin]] | 0 | Yes | 25 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |

**Settlement presence** (combined share of eligible races): [[Boglight]] 85%, [[Fangmarket]] 85%, [[Grubstake Fort]] 85%, [[Knifebottom]] 85%, [[Mucksprawl]] 85%, [[Ratrun]] 85%

**Guild halls:** [[Fighters' Guild]] (uncommon), [[Blade Circle]] (uncommon)

## Shade Walker

[[Shade Walker]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Evenshade]] 90%, [[Moonleaf Ward]] 90%, [[Silverbough]] 90%, [[Starlight Grove]] 90%, [[Thornwillow]] 90%, [[Wyrdleaf]] 90%

**Guild halls:** [[Shadow Guild]] (rare)

## Shadow Blade

[[Shadow Blade]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 100%, [[Blackthread]] 100%, [[Moonless]] 100%, [[Shadowkin]] 100%, [[Silentstep]] 100%, [[Spider Court]] 100%

**Guild halls:** [[Shadow Guild]] (rare)

## Shadow Mage

[[Shadow Mage]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 85%, [[Ashwoven]] 85%, [[Azure Court]] 85%, [[Blackcoal]] 85%, [[Blackthread]] 85%, [[Cinderwell]] 85%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (uncommon)

## Shaman

[[Shaman]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Crystalspring]] 75%, [[Deephollow Proper]] 75%, [[Deepkeep]] 75%, [[Echohollow]] 75%

**Guild halls:** [[Wildwardens]] (common)

## Shepherd

[[Shepherd]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Elmsworth]] 100%, [[Evenshade]] 100%, [[Hollowfield]] 100%, [[Moonleaf Ward]] 100%, [[Rivermere]] 100%, [[Silverbough]] 100%

**Guild halls:** [[Hunters' Lodge]] (common), [[Wildwardens]] (common)

## Shield Master

[[Shield Master]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Fighters' Guild]] (rare)

## Siege Breaker

[[Siege Breaker]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Crushbone]] 75%, [[Dreadmaw]] 75%

**Guild halls:** [[Fighters' Guild]] (rare), [[Cogwrights' Guild]] (rare)

## Smith

[[Smith]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Cogwrights' Guild]] (uncommon)

## Soldier

[[Soldier]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Human]] | 0 | Yes | 36 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Stoneman]] | 15 | Yes | 17 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Emberfall]] 100%, [[Fort Ironclad]] 95%, [[Horn's End]] 90%, [[Redhill]] 90%, [[Ashen Redoubt]] 90%, [[Azure Court]] 90%

**Guild halls:** [[Fighters' Guild]] (uncommon)

## Spymaster

[[Spymaster]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Ratkin]] | 12 | Yes | 24 |

**Settlement presence** (combined share of eligible races): [[Aldwick]] 100%, [[Appleburrow]] 100%, [[Brambleshire]] 100%, [[Burrowton]] 100%, [[Buttercup Hollow]] 100%, [[Cloverfield]] 100%

**Guild halls:** [[Shadow Guild]] (rare)

## Stalker

[[Stalker (Background)|Stalker]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Bonepath]] 75%, [[Buttercup Hollow]] 75%, [[Elderpine]] 75%

**Guild halls:** [[Shadow Guild]] (rare)

## Street Urchin

[[Street Urchin]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Ashwoven]] 75%, [[Blackthread]] 75%, [[Boglight]] 75%, [[Buttercup Hollow]] 75%, [[Fangmarket]] 75%

**Guild halls:** [[Blade Circle]] (common), [[Shadow Guild]] (common)

## Tanner

[[Tanner]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Grayfang Hold]] 75%, [[Howl Keep]] 75%, [[Lone Watch Fort]] 75%

**Guild halls:** [[Cogwrights' Guild]] (common)

## Templar

[[Templar (Background)|Templar]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Dragon's Perch]] 40%, [[Dragonscar]] 30%, [[Ember's Edge]] 10%, [[Sunstone]] 10%, [[Emberpeak]] 5%

**Guild halls:** [[Holy Order]] (rare)

## Temple Guard

[[Temple Guard]] · Common · weight — (default) · **temple only**

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Elf]] | 0 | Yes | 30 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |

**Guild halls:** [[Fighters' Guild]] (common), [[Holy Order]] (common)

## Thief

[[Thief (Background)|Thief]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Human]] | 0 | Yes | 36 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Aldwick]] 90%, [[Appleburrow]] 90%, [[Buttercup Hollow]] 90%, [[Duskfield]] 90%, [[Elmsworth]] 90%, [[Greenbank]] 90%

**Guild halls:** [[Shadow Guild]] (uncommon)

## Tinkerer

[[Tinkerer]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Gnome]] | 0 | Yes | 28 |

**Settlement presence** (combined share of eligible races): [[Brassburrow Fort]] 85%, [[Buttonwood]] 85%, [[Cogwhisper]] 85%, [[Deephearth Forge]] 85%, [[Filigree Glen]] 85%, [[Graniteford]] 85%

**Guild halls:** [[Cogwrights' Guild]] (uncommon)

## Tomb Robber

[[Tomb Robber]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Buttercup Hollow]] 75%, [[Honeystead]] 75%, [[Thistledown]] 75%, [[Willowdene]] 75%, [[Brambleshire]] 55%

**Guild halls:** [[Shadow Guild]] (uncommon)

## Torch Bearer

[[Torch Bearer]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Gnome]] | 0 | Yes | 28 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Saltgrotto]] 80%, [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Boglight]] 75%, [[Brassburrow Fort]] 75%

## Trapper

[[Trapper]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Elf]] | 0 | Yes | 30 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Goblin]] | 0 | Yes | 25 |
| [[Halfling]] | 0 | Yes | 28 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Wild Elf]] | 10 | Yes | 19 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Whisperwood]] 100%, [[Verdantshade]] 90%, [[Evenshade]] 90%, [[Moonleaf Ward]] 90%, [[Silverbough]] 90%, [[Sporewick]] 90%

**Guild halls:** [[Hunters' Lodge]] (common), [[Wildwardens]] (common)

## Tribal Warrior

[[Tribal Warrior]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Frostborn]] | 15 | Yes | 19 |
| [[Gnoll]] | 12 | Yes | 18 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Ratkin]] | 12 | Yes | 24 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Bloodrock]] 85%, [[Grimtusk Hold]] 80%, [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Crushbone]] 75%, [[Dreadmaw]] 75%

**Guild halls:** [[Reaver Hall]] (uncommon)

## Undying Sentinel

[[Undying Sentinel]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Half-Ogre]] | 5 | Yes | 17 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Emberheart Forge]] 90%, [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%

**Guild halls:** [[Fighters' Guild]] (legendary)

## Vagabond

[[Vagabond]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Halfling]] | 0 | Yes | 28 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Appleburrow]] 75%, [[Buttercup Hollow]] 75%, [[Honeystead]] 75%, [[Thistledown]] 75%, [[Willowdene]] 75%, [[Brambleshire]] 55%

**Guild halls:** [[Blade Circle]] (common), [[Shadow Guild]] (common)

## Venom Adept

[[Venom Adept]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Arachne]] | 15 | No | 20 |
| [[Gnome]] | 0 | Yes | 28 |

**Settlement presence** (combined share of eligible races): [[Brassburrow Fort]] 75%, [[Buttonwood]] 75%, [[Cogwhisper]] 75%, [[Filigree Glen]] 75%, [[Kettlebridge]] 75%, [[Lensmoor]] 75%

**Guild halls:** [[Sawbones Hall]] (rare)

## Void Touched

[[Void Touched]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Sylphborne]] | 15 | Yes | 21 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 100%, [[Blackthread]] 100%, [[Moonless]] 100%, [[Shadowkin]] 100%, [[Silentstep]] 100%, [[Spider Court]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (legendary)

## War Mage

[[War Mage]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Crystalspring]] 75%, [[Deephollow Proper]] 75%, [[Deepkeep]] 75%, [[Echohollow]] 75%, [[Lowveil]] 75%, [[Moonshade Caverns]] 75%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (rare)

## War Priest

[[War Priest]] · Rare · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Cinderwell]] 75%, [[Dust Market]] 75%, [[Emberport]] 75%

**Guild halls:** [[Holy Order]] (rare)

## Warchief

[[Warchief]] · Legendary · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Half-Troll]] | 15 | Yes | 18 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Orc]] | 0 | Yes | 24 |
| [[Wild Elf]] | 10 | Yes | 19 |

**Settlement presence** (combined share of eligible races): [[Bloodfield]] 75%, [[Broken Palisade]] 75%, [[Gorewhistle]] 75%, [[Irontooth]] 75%, [[Rendpost]] 75%, [[Screamhold]] 75%

**Guild halls:** [[Reaver Hall]] (legendary)

## Warden

[[Warden]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dragolin]] | 15 | Yes | 19 |
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Lizardfolk]] | 0 | Yes | 23 |
| [[Stoneman]] | 15 | Yes | 17 |

**Settlement presence** (combined share of eligible races): [[Deephearth Forge]] 75%, [[Graniteford]] 75%, [[Hammerbrook]] 75%, [[Ironhall]] 75%, [[Stonewallow]] 75%, [[Granite Watch]] 60%

**Guild halls:** [[Wildwardens]] (uncommon)

## Warlock

[[Warlock (Background)|Warlock]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dark Elf]] | 5 | Yes | 24 |
| [[Deepkin]] | 15 | Yes | 20 |
| [[Tiefling]] | 5 | Yes | 25 |
| [[Vampling]] | 15 | Yes | 21 |
| [[Wraithkin]] | 15 | Yes | 20 |

**Settlement presence** (combined share of eligible races): [[Ashwoven]] 100%, [[Blackthread]] 100%, [[Moonless]] 100%, [[Shadowkin]] 100%, [[Silentstep]] 100%, [[Spider Court]] 100%

**Guild halls:** [[Arcane Conclave (Guild)|Arcane Conclave]] (uncommon)

## Witch Doctor

[[Witch Doctor]] · Common · weight 30

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Goblin]] | 0 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Boglight]] 75%, [[Fangmarket]] 75%, [[Grubstake Fort]] 75%, [[Knifebottom]] 75%, [[Mucksprawl]] 75%, [[Ratrun]] 75%

**Guild halls:** [[Wildwardens]] (common)

## Witch Hunter

[[Witch Hunter (Background)|Witch Hunter]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Cinderwell]] 75%, [[Dust Market]] 75%, [[Emberport]] 75%

**Guild halls:** [[Shadow Guild]] (uncommon)

## Woodcutter

[[Woodcutter]] · Common · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Dwarf]] | 0 | Yes | 26 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Spriggan]] | 15 | Yes | 21 |
| [[Wolfkin]] | 5 | Yes | 21 |

**Settlement presence** (combined share of eligible races): [[Bonepath]] 75%, [[Deephearth Forge]] 75%, [[Elderpine]] 75%, [[Frostden]] 75%, [[Graniteford]] 75%, [[Grayfang Hold]] 75%

**Guild halls:** [[Hunters' Lodge]] (common), [[Wildwardens]] (common), [[Cogwrights' Guild]] (common)

## Zealot

[[Zealot (Background)|Zealot]] · Uncommon · weight — (default)

| Race | Thr | Hireable | Backgrounds this race can roll |
|---|---|---|---|
| [[Deepkin]] | 15 | Yes | 20 |
| [[Dragolin]] | 15 | Yes | 19 |
| [[Frostborn]] | 15 | Yes | 19 |
| [[Minotaur]] | 15 | Yes | 19 |
| [[Tiefling]] | 5 | Yes | 25 |

**Settlement presence** (combined share of eligible races): [[Ashen Redoubt]] 75%, [[Azure Court]] 75%, [[Blackcoal]] 75%, [[Cinderwell]] 75%, [[Crystalspring]] 75%, [[Deephollow Proper]] 75%

**Guild halls:** [[Holy Order]] (uncommon)

*Generated from `backgrounds/*.json`, `races/*.json`, `guilds/guilds.json`, `settlements/*.json`. Edits will be overwritten — put your own notes in Notes/.*
