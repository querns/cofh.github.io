---
title: Sickles (Thermal Foundation)
nav: thermal-foundation
redirect_from:
  - /docs/thermal-foundation/equipment/sickles/
  - /docs/thermal-foundation/equipment/tools/sickles/
  - /docs/sickles/
  - /docs/tf-sickles/
recipes:
  crafting:
    - tf2-tool-sickle-wood
    - tf2-tool-sickle-stone
    - tf2-tool-sickle-iron
    - tf2-tool-sickle-gold
    - tf2-tool-sickle-diamond
    - tf2-tool-sickle-copper
    - tf2-tool-sickle-tin
    - tf2-tool-sickle-silver
    - tf2-tool-sickle-lead
    - tf2-tool-sickle-aluminum
    - tf2-tool-sickle-nickel
    - tf2-tool-sickle-platinum
    - tf2-tool-sickle-steel
    - tf2-tool-sickle-electrum
    - tf2-tool-sickle-invar
    - tf2-tool-sickle-bronze
    - tf2-tool-sickle-constantan
usage-recipes:
  smelter:
    - recycling-tool-sickle-iron
    - recycling-tool-sickle-gold
    - recycling-tool-sickle-copper
    - recycling-tool-sickle-tin
    - recycling-tool-sickle-silver
    - recycling-tool-sickle-lead
    - recycling-tool-sickle-aluminum
    - recycling-tool-sickle-nickel
    - recycling-tool-sickle-platinum
    - recycling-tool-sickle-steel
    - recycling-tool-sickle-electrum
    - recycling-tool-sickle-invar
    - recycling-tool-sickle-bronze
    - recycling-tool-sickle-constantan
  pulverizer:
    - recycling-tool-sickle-wood
    - recycling-tool-sickle-diamond
---

![Sickles](/assets/images/thermal-foundation/sickles.gif){:style="height: 128px"}


**Sickles** are tools that can be used to break large amounts of plant-like
blocks at once. They are especially useful for harvesting crops quickly.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting with-note=true %}


Usage
-----

When a plant-like block is broken with a sickle, up to 49 plant-like blocks in a
7x7 area around it are broken as well. This also works on
[cobwebs](https://minecraft.gamepedia.com/Cobweb). When sneaking, a sickle
breaks only one block at a time.

Sickles use 1 durability for every individual block broken.

### Comparison
{% comment %}
uses = mat.maxUses * 4
{% endcomment %}

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Material | Uses | Attack speed | Attack damage | Enchantability |
|---
| Wood | 236 | 1.4 | 3.5 | 15 |
| Stone | 524 | 1.4 | 4.5 | 5 |
| Iron | 1,000 | 1.4 | 5.5 | 14 |
| Gold | 128 | 1.4 | 3.5 | 22 |
| Diamond | 6,244 | 1.4 | 6.5 | 10 |
|
| Copper | 700 | 1.4 | 4.5 | 7 |
| Tin | 600 | 1.4 | 4.5 | 7 |
| Silver | 300 | 1.4 | 4.5 | 25 |
| Lead | 400 | 1.4 | 4.5 | 9 |
| Aluminum | 900 | 1.4 | 4.5 | 14 |
| Nickel | 1,200 | 1.4 | 6 | 18 |
| Platinum | 5,600 | 1.4 | 7 | 16 |
| Steel | 1,600 | 1.4 | 6 | 10 |
| Electrum | 400 | 1.4 | 4 | 30 |
| Invar | 1,700 | 1.4 | 6 | 12 |
| Bronze | 1,300 | 1.4 | 5.5 | 10 |
| Constantan | 1,100 | 1.4 | 5 | 12 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}
</div>
{::options parse_block_html="false" /}

### Enchantments
Sickles can be enchanted with the following
[enchantments](https://minecraft.gamepedia.com/Enchanting):

* [Curse of Vanishing](https://minecraft.gamepedia.com/Enchanting#Curse_of_Vanishing)
* [Efficiency](https://minecraft.gamepedia.com/Enchanting#Efficiency)
* [Fortune](https://minecraft.gamepedia.com/Enchanting#Fortune)
* [Mending](https://minecraft.gamepedia.com/Enchanting#Mending)
* [Silk Touch](https://minecraft.gamepedia.com/Enchanting#Silk_Touch)
* [Unbreaking](https://minecraft.gamepedia.com/Enchanting#Unbreaking)
* [Leech](/docs/cofh-core/leech/)
* [Vorpal](/docs/cofh-core/vorpal/)
* [Soulbound](/docs/cofh-core/soulbound/)

### Induction Smelter ingredient
{% include recipe-table.html type='smelter-te5' recipes=page.usage-recipes.smelter %}

### Pulverizer ingredient
{% include recipe-table.html type='pulverizer-te5' recipes=page.usage-recipes.pulverizer %}
