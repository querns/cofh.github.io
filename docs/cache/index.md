---
title: Cache
nav: thermal-expansion
image:
  - alt: Cache (Basic)
    file: thermal-expansion/cache-basic.png
  - alt: Cache (Hardened)
    file: thermal-expansion/cache-hardened.png
  - alt: Cache (Reinforced)
    file: thermal-expansion/cache-reinforced.png
  - alt: Cache (Signalum)
    file: thermal-expansion/cache-signalum.png
  - alt: Cache (Resonant)
    file: thermal-expansion/cache-resonant.png
  - alt: Cache (Creative)
    file: thermal-expansion/cache-creative.png
redirect_from:
  - /docs/thermal-expansion/storage/caches/
  - /thermal-expansion/items/cache-2/
  - /docs/thermal-expansion/storage/cache/
recipes:
  crafting:
    - cache-basic
---

A **cache** is a block that stores a large amount of a single item.


Obtaining
---------

A placed cache can be instantly picked up by dismantling it with a [crescent
hammer](/docs/crescent-hammer/). Its stored items and configuration are
preserved in the item.

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}

### Upgrading
A cache is initially at the lowest [tier](#tiers) (basic). It can be upgraded to
higher tiers using [upgrade kits](/docs/upgrade-kits/) and [conversion
kits](/docs/conversion-kits/).


Usage
-----

### Placement
When placed, a cache faces the player. It can face any of the four cardinal
directions, and can be rotated using a [crescent hammer](/docs/crescent-hammer/)
or similar.

The front of a cache displays the item it stores and roughly how full it is.

### Manual usage
Items can be stored in a cache by using them on the cache. Up to a full stack of
items is stored at a time. When this is done twice in rapid succession, all
items of the same type in the player's inventory are stored in the cache.

Items can be taken out of a cache by punching it. A single item is taken out at
a time. Full stacks can be taken out by punching the cache while sneaking.

When a cache is used while sneaking, it is locked to only accept the currently
stored item, even when it is empty. It can be unlocked by using it while
sneaking again.

The exact amount of items that a cache stores can be read using a
[multimeter](/docs/multimeter/).

### Input and output
Items can enter and exit a cache through any of its sides.

### Enchantments
A cache can be enchanted with [Holding](/docs/holding/) to increase its
capacity.

| Holding level | Capacity multiplier |
|---
| I | × 1.5 |
| II | × 2 |
| III | × 2.5 |
| IV | × 3 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}

### Redstone comparators
When placed next to a cache, a [redstone
comparator](https://minecraft.gamepedia.com/Redstone_Comparator) emits a signal
strength of between 0 and 15, depending on how full the cache is.


Tiers
-----

Caches come in six [tiers](/docs/tiers/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Tier | Capacity | Note |
|---
| Basic | 20,000 |
| Hardened | 80,000 |
| Reinforced | 180,000 |
| Signalum | 320,000 |
| Resonant | 500,000 |
| Creative | N/A | Provides an unlimited amount of the item it stores. |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-semi-compress}
</div>
{::options parse_block_html="false" /}