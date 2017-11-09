---
title: 'Augment: Trivection Chamber'
nav: thermal-expansion
image:
  - alt: Trivection chamber augment
    file: thermal-expansion/augment-machine-furnace-food.png
redirect_from:
  - /docs/thermal-expansion/augments/redstone-furnace-specialization/
recipes:
  crafting:
    - augment-machine-furnace-food
recipe-list:
  - food
---

A **trivection chamber** is an [augment](/docs/augments/) that doubles the
amount of cooked [food](https://minecraft.gamepedia.com/Food) a [redstone
furnace](/docs/redstone-furnace/) produces when processing raw food.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}


Usage
-----

### Installation
A trivection chamber can be installed in the Augmentation tab in a [redstone
furnace](/docs/redstone-furnace/)'s GUI. It is a specialization that cannot be
installed together with other specialization augments.

### Effects
An installed trivection chamber replaces a [redstone
furnace](/docs/redstone-furnace/)'s recipe set with [its own](#recipes). This
recipe set consists only of cooking
[food](https://minecraft.gamepedia.com/Food), though with double the amount of
output.

A trivection chamber also increases the amount of energy required per operation
by 50%. For convenience, the energy amounts shown below are the resulting
amounts after this increase is applied. The true energy amounts are the listed
amounts divided by 1.5. When other augments are installed that increase the
amount of energy required per operation, all the energy increase percentages are
added together before being applied to the true amount of energy, including the
50% from this augment.


Recipes
-------

{% include recipe-table.html type='redstone-furnace-food' recipes=page.recipe-list %}