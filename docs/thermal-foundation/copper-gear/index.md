---
title: Copper Gear
nav: thermal-foundation
redirect_from:
  - /docs/thermal-foundation/items/materials/gears/copper-gear/
  - /docs/copper-gear/
recipes:
  crafting:
    - tf2-gear-copper
  compactor-gear:
    - gear-copper
usage-recipes:
  crafting:
    - te5-machine-furnace
    - te5-machine-pulverizer
    - te5-machine-sawmill
    - te5-machine-smelter
    - te5-machine-insolator
    - te5-machine-compactor
    - te5-machine-crucible
    - te5-machine-transposer
    - te5-machine-charger
    - te5-machine-centrifuge
    - te5-machine-crafter
    - te5-machine-precipitator
    - te5-machine-extruder
    - te5-frame-device
    - te5-dynamo-steam
    - te5-augment-machine-furnace-food
    - te5-augment-machine-extruder-no-water
  smelter:
    - recycling-gear-copper
---

![Copper gear](/assets/images/thermal-foundation/gear-copper.png){:style="height: 128px"}


**Copper gears** are crafting materials made of [copper](/docs/thermal-foundation/copper-ingot/).


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}

### Compactor with Gearworking Die
{% include recipe-table.html type='compactor-te5-gear' recipes=page.recipes.compactor-gear no-result=true %}


Usage
-----

### Crafting ingredient
{% include recipe-table.html type='crafting' recipes=page.usage-recipes.crafting %}

### Induction Smelter ingredient
{% include recipe-table.html type='smelter-te5' recipes=page.usage-recipes.smelter %}
