#### Dinkum Mod (A mod for Dinkum, adds new configuration options.)

# Dinkum Tweaks

### Description

Hello 🙂 looking for mod users who are interested in testing an early preview of my current mod.

I mostly need feedback on the bugs/issues and such, and what does or doesn't work yet.

As with all mods please use with caution and make save backups if you need to!

This mod adds a range of custom tweaks to the game that are all configurable.

### Features
🗒️ Configurable

### Installation
- Install [BepInEx](https://builds.bepinex.dev/projects/bepinex_be/572/BepInEx_UnityMono_x64_9c2b17f_6.0.0-be.572.zip)
- Extract ``Octr_DinkumTweaks.dll`` folder into _(Dinkum folder)/BepInEx/plugins_

### Configuration
DinkumTweaks supports the following configuration settings, available in `Octr_DinkumTweaks.cfg`
### Steam\steamapps\common\Dinkum\BepInEx\config\

Mining Pass:
- `miningPassType` [default `Reuse`]: Sets MiningPass Requirements [acceptable values `Required`, `Skip`, `Reuse`].
- `miningPassPrice` [default `15000`]: Modify the value of the MiningPass Item, use default price by setting to -1. [acceptable values `any number`, `-1`]

Options:
- `Enabled` [default `true`]: You can disable the mod quickly by editing this value to false. [acceptable values `true`, `false`].
- `Notify` [default `false`]: You can turn on notifications for the mod in-game by setting this to true. [acceptable values `true`, `false`]

Stamina:
- `lateTiredStatus` [default `false`]: Set to false to remove the stamina reduction during "Late Night".  [acceptable values `true`, `false`].
- `_isTooFull` [default `-1`]: Set the maximum amount of food you can eat before getting "Full". -1 = Never Full  [acceptable values `any number`, `-1`]

Storage:
- `lockBugsAndFishFromChest` [default `true`]: Set as true to allow storing Bugs and Fish in storage [acceptable values `true`, `false`].
- `stackBugsAndFish` [default `true`]: Set as true to allow stacking of Bugs and Fish. [acceptable values `true`, `false`]


### Support
- Post an issue on the [Github repository](https://github.com/Octr/DinkumTweaks/issues)
- Contact me on the [Dinkum Discord](https://discord.gg/dinkum) via modding channel.

### Changelog
`0.0.0` Beta

#### Formatting borrowed from Arwent's [Auto Pickup](https://github.com/jokeruarwentto/AutoPickup)
