**Since Incendium is a datapack, this addon work by overwriting data/incendium/loot_table**
Therefore you need the pack to load after Incendium, if Incendium is installed as a mod this will always work, if it isn't then you should install Incendium first, then this pack right after.

This addon will only add the Better Combat features to items obtained after installing the addon, if you obtained an item before installing the addon you need to manually update it with a command, I'll drop a tool for this later.

You can changes the Better Combat preset pretty easily if you want to, so you can do it yourself in like 30 seconds if the pack goes unmaintained / outdated by modifying the files.
This is what you need to look for in the files
```
            { 
              "function": "minecraft:set_components",
              "components": {
                "bettercombat:preset_id": "bettercombat:claymore"
              }
```
The line "bettercombat:presetid": "bettercombat:claymore" is the preset settings, simply change sword to other presets found here:
https://github.com/ZsoltMolnarrr/BetterCombat/tree/1.21.11/common/src/main/resources/data/bettercombat/weapon_attributes

For example, you want the witherbane to be a 2 handed katana, just change the bettercombat:sword to bettercombat:katana, simple!

