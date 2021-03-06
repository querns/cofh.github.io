---
title: Reinforced Bows (Vanilla+ Tools)
nav: vanillaplus-tools
image:
  - alt: Iron reinforced bow
    file: vanillaplus-tools/bow-iron.png
  - alt: Gold reinforced bow
    file: vanillaplus-tools/bow-gold.png
  - alt: Diamond reinforced bow
    file: vanillaplus-tools/bow-diamond.png
  - alt: Stone reinforced bow
    file: vanillaplus-tools/bow-stone.png
recipes:
  crafting:
    - vpt-weapon-bow-stone
    - vpt-weapon-bow-iron
    - vpt-weapon-bow-gold
    - vpt-weapon-bow-diamond
---

**[Bows](https://minecraft.gamepedia.com/Bow)** are weapons in vanilla
Minecraft. [Vanilla+ Tools](/docs/vanillaplus-tools/) adds a set of
**reinforced bows**, which are bows made of materials other than wood.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting with-note=true %}


Usage
-----

### Comparison
{% comment %}
uses = mat.maxUses + 325
arrowDamage = 1 + (mat.attackDamage / 4)
arrowSpeed = 1 + (mat.efficiency / 20)
{% endcomment %}

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Material | Uses | Arrow damage multiplier | Arrow speed multiplier | Enchantability |
|---
| Wood (vanilla) | 384 | × 1 | × 1 | 15 |
|
| Stone | 456 | × 1.25 | × 1.2 | 5 |
| Iron | 575 | × 1.5 | × 1.3 | 14 |
| Gold | 357 | × 1 | × 1.6 | 22 |
| Diamond | 1,886 | × 1.75 | × 1.4 | 10 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}
</div>
{::options parse_block_html="false" /}
