---
title: Retrievers
nav: thermal-dynamics
image:
  - alt: Retriever
    file: thermal-dynamics/retriever-basic.png
  - alt: Hardened retriever
    file: thermal-dynamics/retriever-hardened.png
  - alt: Reinforced retriever
    file: thermal-dynamics/retriever-reinforced.png
  - alt: Signalum retriever
    file: thermal-dynamics/retriever-signalum.png
  - alt: Resonant retriever
    file: thermal-dynamics/retriever-resonant.png
redirect_from:
  - /docs/thermal-dynamics/attachments/retrievers/
  - /docs/retrievers/
recipes:
  crafting:
    - td2-retriever-basic
    - td2-retriever-hardened
    - td2-retriever-reinforced
    - td2-retriever-signalum
    - td2-retriever-resonant
  crafting-upgrading:
    - td2-retriever-hardened-upgrade
    - td2-retriever-reinforced-upgrade
    - td2-retriever-signalum-upgrade
    - td2-retriever-resonant-upgrade
---

**Retrievers** are items that can be installed on [itemduct](/docs/thermal-dynamics/itemduct/)
and [fluiduct](/docs/thermal-dynamics/fluiduct/) connections. They pull items or fluids towards
themselves from other blocks connected to the duct network.


Obtaining
--------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting %}

### Upgrading
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting-upgrading %}


Usage
-----

### Installation
A retriever can be installed on an [itemduct](/docs/thermal-dynamics/itemduct/) or
[fluiduct](/docs/thermal-dynamics/fluiduct/) connection by using it on the connection. It can be
removed by using a [wrench](/docs/wrenches/) on it.

### Configuration
An installed retriever can be configured by using it. The available options
depend on whether the retriever is installed on an [itemduct](/docs/thermal-dynamics/itemduct/)
or on a [fluiduct](/docs/thermal-dynamics/fluiduct/).

A retriever's configuration can be saved on a [redprint](/docs/thermal-foundation/redprint/) to be
copied to other retrievers, [servos](/docs/thermal-dynamics/servos/) or
[filters](/docs/thermal-dynamics/filters/).

### Redstone control
By default, a retriever is only active when powered with
[redstone](https://minecraft.gamepedia.com/Redstone). However, this is
configurable. A retriever can be in one of three modes:

Ignored
: Redstone control is disabled. The retriever is always active.

Low
: The retriever is active when *not* powered. When powered, it becomes inactive.

High
: The retriever is only active when powered. This is the default mode.

### Item transfer
When installed on an [itemduct](/docs/thermal-dynamics/itemduct/) connection, an active retriever
extracts items from blocks in the network and inserts them into the block it is
connected to.

Items are extracted from blocks in stacks. The maximum size of each stack and
the speed at which stacks are extracted depends on the retriever's
[tier](#tiers). The maximum stack size can be configured to be lower.

Retrievers at higher tiers give extracted items a speed boost, causing them to move
faster through the itemducts.

A retriever can be configured to limit the total stored amount of an item in the
connected block. This option is only available at higher tiers, and its maximum
value depends on the tier. By default, any amount of items is allowed.

### Item filtering
A retriever can be configured to only retrieve items that match a given list of
items. It has various options that determine how this list is used to match
items. Some of these are only available at higher [tiers](#tiers).

Blacklist/Whitelist
: Treat the list of items as a blacklist (retrieve all items except these) or as
a whitelist (only retrieve these items). The list is used as a blacklist by
default.

Metadata
: Match items by their exact metadata / damage value. This is used by default.

NBT
: Match items by their exact NBT data. This is used by default.

Ore Dictionary
: Match items that are considered equivalent, like the various versions of
copper and tin ingots added by different mods. This is ignored by default.

Mod Owner
: Match items that are added by the same mod. This is ignored by default.

### Item routing
At higher [tiers](#tiers), a retriever can be configured to prefer extracting
items from certain blocks in the network.

Nearest-First
: Items are extracted from the connected block that has the shortest path to it
first, taking into account [dense and vacuum
itemducts](/docs/thermal-dynamics/itemduct/#item-transfer). This is the default mode.

Furthest-First
: Items are extracted from the connected block that has the longest path to it
first, taking into account [dense and vacuum
itemducts](/docs/thermal-dynamics/itemduct/#item-transfer).

Random
: Each item is extracted from a random connected block.

Round Robin
: Items are extracted from each connected block in a repeating order.

### Fluid transfer
When installed on a [fluiduct](/docs/thermal-dynamics/fluiduct/) connection, an active retriever
extracts fluids from blocks in the network and inserts them into the block it is
connected to. The rate at which fluids are extracted depends on the retriever's
[tier](#tiers).

### Fluid filtering
A retriever can be configured to only retrieve fluids that match a given list of
fluids. The retriever has various options that determine how this list is used
to match fluids.

Blacklist/Whitelist
: Treat the list of fluids as a blacklist (retrieve all fluids except these) or
as a whitelist (only retrieve these fluids). The list is used as a blacklist by
default.

NBT
: Match fluids by their exact NBT data. This is used by default.


Tiers
-----

Retrievers come in five [tiers](/docs/thermal-foundation/tiers/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Tier | Item extraction rate | Max. item stack size | Item speed boost | Item filter options | Max. total stored items limit | Extracts from multiple slots | Configurable item routing | Fluid extraction rate | Filter slots |
|---
| Basic | 3s | 8 | - | Blacklist/Whitelist | - | No | No | 50% | 3 |
| Hardened | 2s | 16 | - | Blacklist/Whitelist, Metadata | - | No | No | 75% | 6 |
| Reinforced | 1s | 32 | - | All | 64 | No | Yes | 100% | 9 |
| Signalum | 0.5s | 64 | × 2 | All | 128 | Yes | Yes | 150% | 12 |
| Resonant | 0.5s | 64 | × 3 | All | 320 | Yes | Yes | 200% | 15 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small}
</div>
{::options parse_block_html="false" /}
