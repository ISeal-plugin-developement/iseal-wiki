# 📝 Advanced Configs

<details>

<summary>Where to find these files</summary>

Open your server's file manager and then go to:

`~/plugins/PowerGems/config/`

Open the files using a text editor

_<mark style="color:yellow;">Note: it is the folder</mark>_&#x20;

</details>

## crafting.yml

For the recipes: the shape is how it is built, one letter per material and has to be the same, intruded by "," and the ingredients are the materials, first the letter, then the material as it is described in [https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)

### cooldown.yml

{% hint style="info" %}
Not suggested to be changed
{% endhint %}

Set the cooldown (in seconds) in this config file (default 60) for gems at level one; the timer will reduce based on `cooldownBoostPerLevelInSeconds` what's set in the config.yml.

### gem\_active.yml

{% hint style="info" %}
Not suggested to be changed
{% endhint %}

Set which gem would be disabled (unusable).
