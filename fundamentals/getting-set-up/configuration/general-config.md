# 📝 General Config

<details>

<summary>Where to find the file to edit</summary>

Open your server's file manager and then go to:

`~/plugins/PowerGems/config.yml`

Open the file using a text editor

_<mark style="color:yellow;">Note: it is not the folder containing other config files</mark>_

</details>

### Allow only one Gem (`allowOnlyOneGem`):

If set to true, only allow one Gem per person

### Can drop gems (`canDropGems`):

If set to true, it doesn't allow people to drop gems.

### Give a gem on the first logon (`giveGemOnFirstLogin`):

If set to false, gems will not be given to players when they first log in.

### Allow gem upgrading (`canUpgradeGems`):

If set to false, it will stop gems from upgrading.

### Allow gem crafting (`canCraftGems`):

If set to false, it will stop new gems from being crafted.

### Keep Gem on death (`keepGemsOnDeath`):

If set to false, gems will drop.

### Gives gems descriptions (`gemsHaveDescriptions`):

If set to true, it will give gems the description shown on the plugin page.

### Allow fire gem to destroy blocks (`explosionDamageAllowed`):

If set to false, fire gem ability that spawns fireballs will not destroy blocks.

### Stops reflect fire gem's fireball, etc. (`preventGemPowerTampering`):

If set to true, it will not allow deflection of the fire gem's fireball or similar.

### Do Gem Decay (`doGemDecay`):

If set to true, gems will "decay" when the player dies (subtract 1 level), and they will stop decaying at level 1 unless `doDecayOnLevel1` is set to true

### Gem Decay on level 1 (`doDecayOnLevel1`):

If set to true, while `doGemDecay` is set to true, gems will not stop decaying at level 1; if it goes below level 1, the Gem will "decay" so much, destroying it&#x20;

### Dragon Egg Halves cooldown (`dragonEggHalfCooldown`):

As mentioned on the page [the-gems-and-their-ablitys](../../../overview/the-gems-and-their-ablitys/ "mention"), when the player has a dragon egg in their inventory, it halves their gem ability cooldown. If this is set to false, then the dragon egg will no **longer** halve the cooldown.

### Randomized Colors (`randomizedColors`):

If set to true, the plugin will be much more _<mark style="color:blue;">C</mark><mark style="color:purple;">o</mark><mark style="color:orange;">l</mark><mark style="color:red;">or</mark><mark style="color:yellow;">f</mark><mark style="color:green;">u</mark><mark style="color:blue;">l</mark>!_ The gems will spawn in random colors, making each Gem unique!

### Cooldown Boost Per Level (`cooldownBoostPerLevelInSeconds`):

The cooldown time is to remove it in seconds per Gem level.

### Delay to use gems (`delayToUseGemsOnJoin`):

There is a delay in seconds when you can not use the gems when you join the server.

### Gem Creation Attempts (`gemCreationAttempts`):

The number of attempts the plugins will make to avoid doubles before giving up.

### Blocked Lava Blocks (`blockedLavaBlocks`):

{% hint style="danger" %}
This config is currently utterly useless as the ability for the lava gem that affects this config is completely disabled in the plugin itself ( meaning there is no way to enable it )
{% endhint %}

The blocks which the lava wall ability may not overwrite.
