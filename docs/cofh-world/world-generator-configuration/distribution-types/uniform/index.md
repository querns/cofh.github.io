---
title: uniform
nav: cofh-world
---

**`uniform`** is one of the [distribution
types](/docs/cofh-world/world-generator-configuration/distribution-types/)
provided by [CoFH World](/docs/cofh-world/). It distributes features evenly
between a minimum and maximum altitude. Most
[ores](https://minecraft.gamepedia.com/Ore) are distributed like this.

When using this distribution type, the
[`cluster`](/docs/cofh-world/world-generator-configuration/feature-types/cluster/)
feature type is used by default, and the value `material` of [feature type
configurations](/docs/cofh-world/world-generator-configuration/feature-format/#feature-type-configuration)
is set to [stone](https://minecraft.gamepedia.com/Stone) by default.


Options
-------

When using this distribution type, the following values must be added to the
[feature
entry](/docs/cofh-world/world-generator-configuration/feature-format/#features).

<div class="uk-overflow-container">
    <table class="uk-table uk-table-striped uk-text-small">
        <thead>
            <tr>
                <th>Name</th>
                <th>Type</th>
                <th>Default</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td markdown="span">`min-height`</td>
                <td markdown="span">Number</td>
                <td markdown="span">-</td>
                <td markdown="span">
                    The minimum altitude to place features at.
                </td>
            </tr>
            <tr>
                <td markdown="span">`max-height`</td>
                <td markdown="span">Number</td>
                <td markdown="span">-</td>
                <td markdown="span">
                    The maximum altitude to place features at.
                </td>
            </tr>
        </tbody>
    </table>
</div>


Examples
--------

Coming soon...