![tartarus_logo](https://user-images.githubusercontent.com/76827500/179134441-5eb9b4b6-623c-401c-a84a-61bd138140e9.png)

# **Tartarus**
A Minecraft Terra generation pack that adds a ton of new biomes to the Nether!

Tartarus is a Terra world generation pack for Minecraft Java v1.19 that adds 12 custom biomes to the Nether! This includes vanilla biomes, however these biomes have been reworked to fit the scheme of this pack better. 

> **THIS PACK IS STILL WORK IN PROGRESS AND SHOULD NOT BE USED IN PRODUCTION YET**

Tartarus currently does not include any naturally generating ores and may contain bugs. As long as this warning is still here, this pack is not completed yet.

> **THIS PACK DOES NOT WORK WITH STRUCTURES CURRENTLY**

Due to some issues with vanilla Bukkit structure generation, vanilla structures do not generate in this pack. If you have `generate-structures` set to true in `server.properties`, your server will likely crash. This fix this, just disable structure generation. Hopefully in the future, custom structures will be available for Terra and Tartarus will be using that feature to generate structures instead.

## Credits
Tartarus was made possible only through the help and support from the PolyhedralDev team, as well as the default Overworld config packaged with Terra, which some edited configs can be found in various assets in Tartarus. You can check out the pack here: https://github.com/PolyhedralDev/TerraOverworldConfig

## Biome List
> The biome list is still work in progress, however the names of the biomes as well as a few screenshots with accompanying descriptions are available.

A list of screenshots and descriptions of all the biomes included in this pack can be found on the Wiki of this repository.

## Installing this pack
> Currently, you are only able to use this on Bukkit. While you technically *could* install this on other platforms, you have no option to generate this in the Nether. If you want to use this pack on Fabric, Forge, or other supported platforms, and you don't mind having Nether terrain in the Overworld, feel free to use this pack.

Simply install this pack like any other Terra generation pack. Soley add these lines to the end of `Bukkit.yml`. The ID of the pack is `TARTARUS`. However, rather than specifying the pack to generate in `world`, you would insert `world_nether`:

```
worlds:
  world_nether:
    generator: Terra:TARTARUS
```

Obviously, if your Nether world name is named something different, you would rename it to that instead.

## Minor Pack Configuration
Options such as changing the biome sizes, changing the frequency of biomes and/or disabling them completely etc can be edited in `options.yml` of the pack. For more information, check out the Wiki page on how to do that [here](https://github.com/Jason-Ding19/Tartarus/wiki/Modifying-the-Config-Pack).

## Bugs and Features
If you find any bugs in this pack, feel free to report them in the Issues page! Likewise, if you have any feature requests such as biome additions, etc, feel free to post those as well!
