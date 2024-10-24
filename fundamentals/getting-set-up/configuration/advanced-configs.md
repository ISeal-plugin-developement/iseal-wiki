# 📝 Advanced Configs

<details>

<summary>Where to find these files</summary>

Open your server's file manager and then go to:

`~/plugins/PowerGems/config/`

Open the files using a text editor

_<mark style="color:yellow;">Note: it is the folder</mark>_

</details>

{% hint style="info" %}
If the files are empty or almost empty, use each ability at least once to fill them up.
{% endhint %}

## recipes.yml

{% hint style="warning" %}
For expert users only.
{% endhint %}

For the recipes: the shape is how it is built, one letter per material and has to be the same, intruded by "," and the ingredients are the materials, first the letter, then the material as it is described in [here](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)

### cooldown.yml

{% hint style="info" %}
Suggested to be changed
{% endhint %}

Set the cooldown (in seconds) in this config file (default 60) for gems at level one; the timer will reduce based on `cooldownBoostPerLevelInSeconds` what's set in the config.yml.

### activeGems.yml

Used to disable some gems.

### GemLore.yml

Used to configure the gem's lore. Applies to new gems only.

### gemMaterials.yml

Used to edit each gem's material (see [here](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html) for material list)
