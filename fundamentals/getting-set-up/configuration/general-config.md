# 📝 General Config

<details>

<summary>Where to find the file to edit</summary>

Open your server's file manager and then go to:

`~/plugins/PowerGems/config.yml`

Open the file using a text editor

_<mark style="color:yellow;">Note: it is not the /config/ folder, that contains other config files</mark>_

</details>

### Plugin prefix (`pluginPrefix`):

Set the prefix that will be used in console

### Allow only one Gem (`allowOnlyOneGem`):

If set to true, only allow one gem per person

### Can drop gems (`canDropGems`):

If set to true, gems cannot be dropped by players.

### Give a gem on the first logon (`giveGemOnFirstLogin`):

If set to false, gems will not be given to players when they first log in.

### Allow gem upgrading (`canUpgradeGems`):

If set to false, gems will not be able to be upgraded.

### Allow gem crafting (`canCraftGems`):

If set to false, new gems cannot be crafted.

### Keep gems on death (`keepGemsOnDeath`):

If set to false, gems will drop on player death.

### Gives gems descriptions (`gemsHaveDescriptions`):

If set to true, it will give new gems the description shown on the plugin page.

### Allow fire gem to destroy blocks (`explosionDamageAllowed`):

If set to false, destructive abilities will be less destructivg.

### Prevent gem power tampering. (`preventGemPowerTampering`):

If set to true, gem abilities which can be interacted with (ex. a fireball) will not be able to be interacted with (ex. deflecting a fireball).

### Do gem decay (`doGemDecay`):

If set to true, gems will "decay" when the player dies (subtract 1 level), and they will stop decaying at level 1 unless `doDecayOnLevel1` is set to true

### Gem Decay on level 1 (`doDecayOnLevel1`):

If set to true, while `doGemDecay` is set to true, gems will not stop decaying at level 1; if gems decay at level 1, they will get destroyed.

### Dragon Egg Halves cooldown (`dragonEggHalfCooldown`):

As mentioned on the page [the-gems-and-their-ablities](../../../overview/the-gems-and-their-ablities/ "mention"), when the player has a dragon egg in their inventory, it halves their gem ability cooldown. If this is set to false, then the dragon egg will no **longer** halve the cooldown.

### Randomized Colors (`randomizedColors`):

If set to true, the plugin will be much more _<mark style="color:blue;">C</mark><mark style="color:purple;">o</mark><mark style="color:orange;">l</mark><mark style="color:red;">or</mark><mark style="color:yellow;">f</mark><mark style="color:green;">u</mark><mark style="color:blue;">l</mark>!_ The gems will spawn in random colors, making each Gem unique!

### Cooldown Boost Per Level (`cooldownBoostPerLevelInSeconds`):

The time to remove from each ability's cooldown per level.

### Delay to use gems (`delayToUseGemsOnJoin`):

Delay in seconds to wait to use gems when a player logs in.

### Gem Creation Attempts (`gemCreationAttempts`):

The number of attempts the plugins will make to avoid doubles before giving up, lower this if you are having lag on gem creation.

### Blocked Replacing Blocks (`blockedReplacingBlocks`):

The blocks which abilities may not overwrite.

### Allow Moving Gems (`allowMovingGems`):

{% hint style="danger" %}
Currently not implemented. Raccomended to keep to false.
{% endhint %}

Allow moving gems between containers (chests, etc.)

### Allow metrics (`allowMetrics`):

If true, sends anonymus usage statistics to help make the plugin better.

(The stats are **in no way** tracable to the server or the players)

### Run updater (`runUpdater`):

If true, runs the plugin updater, sending admins a message if an update is found

### Max gem level (`maxGemLevel`):

Maximium gem level achievable through upgrades.

### Allow cosmetic particle effects (`allowCosmeticParticleEffects`):

If true, particles related to the gems they have will start appearing close to the players

### Cosmetic particle effect interval (cosmeticParticleEffectInterval):

Define the amount of time (in ticks) between each particle spawn.

Lower this if your players have performance problems.
