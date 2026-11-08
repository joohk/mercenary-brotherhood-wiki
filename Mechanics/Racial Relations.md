---
type: mechanics
tags:
  - type/mechanics
source: races/_racial_relations.json
---

How well races get along inside your company, from -3 (blood feud) to +3 (close kin). Pairs not listed are 0 (strangers, no tension).

## -3 (5 pairs)

| Race | Race | Reason |
|---|---|---|
| [[Dwarf]] | [[Goblin]] | goblins gnaw at every dwarfhold from below |
| [[Elf]] | [[Dark Elf]] | the sundered kin, and there is no hatred like it |
| [[Human]] | [[Wraithkin]] | the living recoil from the death-touched |
| [[Orc]] | [[Elf]] | an ancient blood-feud neither side has forgiven |
| [[Vampling]] | [[Wolfkin]] | the blood-drinkers and the moon-runners, hunter and hunted since the first night |

## -2 (15 pairs)

| Race | Race | Reason |
|---|---|---|
| [[Arachne]] | [[Elf]] | the spider-folk and the fair folk share a hatred as old as the deep wood |
| [[Dwarf]] | [[Dark Elf]] | rival delvers who war in the dark |
| [[Elf]] | [[Goblin]] | the fair folk name goblins vermin and act on it |
| [[Elf]] | [[Wraithkin]] | an affront to the fair folk's love of living things |
| [[Gnoll]] | [[Human]] | raiders and the raided |
| [[Half-Ogre]] | [[Elf]] | brute strength offends the graceful folk |
| [[Half-Troll]] | [[Elf]] | the fair folk cannot abide the troll-blooded |
| [[Halfling]] | [[Gnoll]] | gnoll war-bands prey on the shire-folk |
| [[Halfling]] | [[Goblin]] | burned burrows are not forgotten |
| [[Halfling]] | [[Orc]] | the raided remember the raiders |
| [[Human]] | [[Dark Elf]] | surface fear of the folk beneath |
| [[Human]] | [[Vampling]] | old dread of the blood-drinking line |
| [[Orc]] | [[Dwarf]] | generations of border wars over the deep places |
| [[Ratkin]] | [[Dwarf]] | vermin in the deep halls |
| [[Ratkin]] | [[Human]] | plague-blame and old pogroms |

## -1 (13 pairs)

| Race | Race | Reason |
|---|---|---|
| [[Arachne]] | [[Dwarf]] | webs in the mines are a killing matter |
| [[Arachne]] | [[Human]] | instinctive human dread of the many-legged |
| [[Deepkin]] | [[Human]] | the deep folk find sunlight and surfacers alike suspect |
| [[Frostborn]] | [[Human]] | the cold-blooded keep the warm folk at arm's length |
| [[Gnoll]] | [[Elf]] | the wood-folk hunt gnoll packs on sight |
| [[Gnome]] | [[Goblin]] | tinker-folk despise goblin sabotage |
| [[Half-Ogre]] | [[Gnome]] | big folk and small folk grate in a shared camp |
| [[Human]] | [[Tiefling]] | suspicion of the infernal blood |
| [[Lizardfolk]] | [[Human]] | swamp-folk and dry-landers trust each other little |
| [[Minotaur]] | [[Human]] | the horned recall being penned as beasts |
| [[Ratkin]] | [[Halfling]] | larder-thieves and larder-keepers |
| [[Sylphborne]] | [[Deepkin]] | the sky-born and the earth-deep are opposed in their natures |
| [[Wolfkin]] | [[Gnoll]] | two beast-kin who will not share a hunting ground |

## +1 (16 pairs)

| Race | Race | Reason |
|---|---|---|
| [[Dark Elf]] | [[Deepkin]] | neighbors of the deep dark |
| [[Dwarf]] | [[Human]] | trade-partners and shield-companions of old |
| [[Dwarf]] | [[Stoneman]] | a shared reverence for stone and depth |
| [[Elf]] | [[Human]] | old allies of the long wars |
| [[Elf]] | [[Sylphborne]] | a shared fey and airy grace |
| [[Frostborn]] | [[Stoneman]] | elemental-blooded who understand one another |
| [[Goblin]] | [[Ratkin]] | underfolk who scheme well together |
| [[Halfling]] | [[Human]] | neighborly folk of the settled lands |
| [[Orc]] | [[Goblin]] | greenskin war-bands march together often enough |
| [[Orc]] | [[Half-Troll]] | brute-kin at home in the same war-camp |
| [[Orc]] | [[Minotaur]] | warriors who measure worth by the fight |
| [[Spriggan]] | [[Stoneman]] | old spirits of wood and stone |
| [[Spriggan]] | [[Sylphborne]] | fey folk recognize their own |
| [[Tiefling]] | [[Vampling]] | the misjudged blood-lines find kinship in being feared |
| [[Wild Elf]] | [[Wolfkin]] | kindred spirits of the untamed places |
| [[Wraithkin]] | [[Vampling]] | a grim kinship of the death-touched |

## +2 (7 pairs)

| Race | Race | Reason |
|---|---|---|
| [[Dark Elf]] | [[Arachne]] | the drow revere the spider; the spider-folk are honored kin |
| [[Dragolin]] | [[Lizardfolk]] | scaled kin of the reptile line |
| [[Dwarf]] | [[Gnome]] | craft-folk who honor the same forge-lore |
| [[Elf]] | [[Wild Elf]] | sundered but still kin, blood calls to blood |
| [[Halfling]] | [[Gnome]] | the small folk look out for one another |
| [[Orc]] | [[Half-Ogre]] | war-kin who respect a strong arm |
| [[Wild Elf]] | [[Spriggan]] | children of the same wild wood |

> [!note]- Developer notes
> Race-pair enmity/kinship table for the Company Culture & racial-tension system (systems/company_culture.py). Symmetric: a pair is looked up in either order. Values run -3 (blood-feud) .. +3 (close kin); unlisted pairs default to `default` (0 = strangers, no tension). NOT a race def — the leading underscore keeps DataLoader._load_directory from trying to key it by race_id. Read via DataLoader.get_racial_relations(). Same-race pairs are treated as kin in code and are not listed here.

*Generated from `races/_racial_relations.json`. Edits will be overwritten — put your own notes in Notes/.*
