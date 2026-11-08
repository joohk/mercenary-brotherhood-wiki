---
type: vendetta_loot_page
tags:
  - type/vendetta_loot_page
source: vendetta/vendetta_loot.json
---

When you kill a [[Vendetta|vendetta]], it drops a trophy: a real item from the game's item lists, renamed after the rival and given bonus stats that grow with its power level.

## How trophies work

- A template picks a real base item by equipment slot and required item tags; the base item's tier depends on the vendetta's power level.
- The trophy keeps everything from the base item (type, icon, price, slot) and adds the vendetta's name, an adjective and the bonus stats below.
- Bonus stats are rolled within the listed range, then the per-level amount is added for each power level up to a cap; beyond the cap a higher-tier base item is used instead.

## Templates

| Trophy | Slot | Required item tags | Rarity |
|---|---|---|---|
| [[Vendetta Trophies#Trophy Weapon (Melee)\|Trophy Weapon (Melee)]] | Weapon | Melee | Uncommon |
| [[Vendetta Trophies#Trophy Weapon (Ranged)\|Trophy Weapon (Ranged)]] | Ranged | Ranged | Uncommon |
| [[Vendetta Trophies#Trophy Armor\|Trophy Armor]] | Body Armor | any | Uncommon |
| [[Vendetta Trophies#Trophy Helm\|Trophy Helm]] | Helmet | any | Rare |
| [[Vendetta Trophies#Trophy Shield\|Trophy Shield]] | Offhand | Shield | Uncommon |
| [[Vendetta Trophies#Trophy Trinket\|Trophy Trinket]] | Accessory | Trinket | Rare |

## Trophy Weapon (Melee)

|  | Value |
|---|---|
| Slot | Weapon |
| Required item tags | Melee |
| Rarity | Uncommon |
| Name pattern | `{vendetta_name}'s {adjective} {item}` |
| Example | *Grimjaw's Bloodied ‹base item›* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Damage Min\|Damage Min]] | +3 to +7 | +1 |
| [[Stats#Damage Max\|Damage Max]] | +5 to +10 | +2 |
| [[Stats#Melee Attack\|Melee Attack]] | +5 to +12 | +2 |

**Adjectives:** Bloodied, Notched, Scarred, Cruel, Merciless, Wicked, Grim

## Trophy Weapon (Ranged)

|  | Value |
|---|---|
| Slot | Ranged |
| Required item tags | Ranged |
| Rarity | Uncommon |
| Name pattern | `{vendetta_name}'s {adjective} {item}` |
| Example | *Grimjaw's Keen ‹base item›* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Damage Min\|Damage Min]] | +2 to +5 | +1 |
| [[Stats#Damage Max\|Damage Max]] | +4 to +8 | +1 |
| [[Stats#Ranged Attack\|Ranged Attack]] | +5 to +12 | +2 |

**Adjectives:** Keen, Far-Reaching, Silent, Deadly, Precise, Vicious

## Trophy Armor

|  | Value |
|---|---|
| Slot | Body Armor |
| Required item tags | any |
| Rarity | Uncommon |
| Name pattern | `{vendetta_name}'s {adjective} {item}` |
| Example | *Grimjaw's Scarred ‹base item›* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Armor\|Armor]] | +3 to +8 | +1 |
| [[Stats#Max HP\|Max HP]] | +5 to +15 | +3 |

**Adjectives:** Scarred, Battle-Worn, Reinforced, Dented, Blood-Stained, Trophied

## Trophy Helm

|  | Value |
|---|---|
| Slot | Helmet |
| Required item tags | any |
| Rarity | Rare |
| Name pattern | `{adjective} {item} of {vendetta_name}` |
| Example | *Horned ‹base item› of Grimjaw* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Armor\|Armor]] | +2 to +4 | +1 |
| [[Stats#Willpower\|Willpower]] | +5 to +15 | +3 |
| [[Stats#Initiative\|Initiative]] | +3 to +8 | +1 |

**Adjectives:** Horned, Crowned, Spiked, Crested, Visored, Skull-Adorned

## Trophy Shield

|  | Value |
|---|---|
| Slot | Offhand |
| Required item tags | Shield |
| Rarity | Uncommon |
| Name pattern | `{vendetta_name}'s {adjective} {item}` |
| Example | *Grimjaw's Battered ‹base item›* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Melee Defense\|Melee Defense]] | +5 to +12 | +2 |
| [[Stats#Ranged Defense\|Ranged Defense]] | +3 to +8 | +1 |

**Adjectives:** Battered, Iron-Bound, Dented, War-Scarred, Spiked, Heavy

## Trophy Trinket

|  | Value |
|---|---|
| Slot | Accessory |
| Required item tags | Trinket |
| Rarity | Rare |
| Name pattern | `{adjective} {item} of {vendetta_name}` |
| Example | *Cursed ‹base item› of Grimjaw* |

| Stat | Bonus | Per power level |
|---|---|---|
| [[Stats#Initiative\|Initiative]] | +3 to +8 | +1 |
| [[Stats#Willpower\|Willpower]] | +5 to +10 | +2 |
| [[Stats#Vision\|Vision]] | +1 to +2 | 0 |

**Adjectives:** Cursed, Enchanted, Fetid, Glowing, Runic, Dark

## Related

- **Vendetta system:** [[Vendetta]]

> [!note]- Developer notes
> Trophy loot dropped when a vendetta is slain. A template does NOT describe a whole item — it selects a REAL base item out of data/items/ (matched by 'slot' + 'require_tags', tier picked from the vendetta's power level) and then layers the vendetta's name, adjective and bonus stats on top of it.
>
> That indirection is deliberate: the instance inherits type / slot / tags / base_price / damage_category / passive_effects from the base item, which is what makes the trophy show an icon, sell for real gold and fit a paperdoll slot. Templates that invent their own slot strings (the old 'shield') produce items no screen can equip. Slots must be the canonical equipment slots: weapon / ranged / body_armor / helmet / offhand / accessory.
>
> stat_additions are RANGES added on top of the base item's own stats. power_level_scaling is added per vendetta power level, counted up to TROPHY_SCALING_CAP levels — above that the trophy grows by drawing a higher-tier base item instead.
>
> name_pattern is the ENGLISH composition ONLY. name_style names the shape so every other language supplies its own word order through the 'trophy_patterns' table in data/locale/magic_names_<lang>.json (French moves the adjective after the noun and the owner behind 'de'; Chinese prepends '<owner>的' with no spaces). A new adjective or style must be added to EVERY locale's trophy_adjectives / trophy_patterns table — tests/test_vendetta_trophy_names.py fails on any that is missing.

*Generated from `vendetta/vendetta_loot.json`. Edits will be overwritten — put your own notes in Notes/.*
