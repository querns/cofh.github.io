---
title: Boots (Thermal Foundation)
nav: thermal-foundation
redirect_from:
  - /docs/thermal-foundation/equipment/armor/boots/
  - /docs/boots/
  - /docs/tf-boots/
recipes:
  crafting:
    - tf2-armor-boots-copper
    - tf2-armor-boots-tin
    - tf2-armor-boots-silver
    - tf2-armor-boots-lead
    - tf2-armor-boots-aluminum
    - tf2-armor-boots-nickel
    - tf2-armor-boots-platinum
    - tf2-armor-boots-steel
    - tf2-armor-boots-electrum
    - tf2-armor-boots-invar
    - tf2-armor-boots-bronze
    - tf2-armor-boots-constantan
usage-recipes:
  smelter:
    - recycling-armor-boots-copper
    - recycling-armor-boots-tin
    - recycling-armor-boots-silver
    - recycling-armor-boots-lead
    - recycling-armor-boots-aluminum
    - recycling-armor-boots-nickel
    - recycling-armor-boots-platinum
    - recycling-armor-boots-steel
    - recycling-armor-boots-electrum
    - recycling-armor-boots-invar
    - recycling-armor-boots-bronze
    - recycling-armor-boots-constantan
---

![Boots](/assets/images/thermal-foundation/boots.gif){:style="height: 128px"}


**[Boots](https://minecraft.gamepedia.com/Boots)** are a type of
[armor](https://minecraft.gamepedia.com/Armor) in vanilla Minecraft. [Thermal
Foundation](/docs/thermal-foundation/) adds a set of boots made of various
metals.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting %}


Usage
-----

### Comparison
{% comment %}
durability = mat.durability * 13
defense = mat.reductionAmounts[0]
{% endcomment %}

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Material | Durability | Defense | Toughness | Enchantability |
|---
| Leather | 65 | 1 | | 15 |
| Chain | 195 | 1 | | 12 |
| Iron | 195 | 2 | | 9 |
| Gold | 91 | 1 | | 25 |
| Diamond | 429 | 3 | 2 | 10 |
|
| Copper | 130 | 1 | | 8 |
| Tin | 104 | 1 | | 9 |
| Silver | 104 | 2 | | 25 |
| Lead | 156 | 2 | | 9 |
| Aluminum | 156 | 1 | | 14 |
| Nickel | 195 | 2 | | 18 |
| Platinum | 455 | 3 | 2 | 16 |
| Steel | 286 | 2 | 1 | 10 |
| Electrum | 104 | 2 | | 30 |
| Invar | 273 | 2 | 1 | 12 |
| Bronze | 234 | 2 | 1 | 10 |
| Constantan | 169 | 2 | | 12 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}
</div>
{::options parse_block_html="false" /}

### Induction Smelter ingredient
{% include recipe-table.html type='smelter-te5' recipes=page.usage-recipes.smelter %}
