# Shattered Sky Minecraft Mod Configs

Configurations for the Shattered Sky community modpack for Minecraft.

## Abbreviations and Acronyms
Definition list for shorthand used in this README.md.

* **HC** - Pam's HarvestCraft
* **ThF** - Thermal Foundation
* **TwF** - Twilight Forest
* **TAN** - ToughAsNails
* **SD** - SimpleDifficulty (replaces TAN)
* **AE2** - Applied Energistics 2
* **BOP** - Biomes O Plenty
* **PVJ** - Project: Vibrant Journeys


## Notable Config files

### Temperature (TAN / SD)
* **simpledifficulty/armorTemperatures.json** - Temperature resistance of armor.
* **simpledifficulty/blockTemperatures.json** - Temperature of blocks. Vanilla, HC, ThF, and Lycanites Mobs blocks are already setup.
* **simpledifficulty/fluidTemperatures.json** - Temperature of fluids. Only configured for hot_spring_water.
* **simpledifficulty/heldItemTemperatures.json** - Temperature of held items. Currently used for vanilla, HC and TF items that warm the player.

### Oregen
* **geolosys.cfg** - Oregen for prospectable veins. This config is disabling vanilla oregen.
* **cofh/world/00_minecraft.json** - Oregen for vanilla.
* **cofh/world/01_thermalfoundation_ores.json** - Oregen for copper, tin, silver, lead, nickel, and platinum (currently disabled).
* **cofh/world/04_overworld_ores.json** - Oregen for AE2 quartz, Forestry apatite (disabled), TF aluminum, and TF iridium.
* **Bewitchment.cfg** - Oregen for Bewitchment. Generates amethyst, garnet, opal, salt, and silver. Structuregen for cambion homes, menhir, stone circles and wickermen.

### Biomes
* **harvestcraft_fruittree.cfg** - Biomes fruit trees spawn in. Setup for vanilla and BOP.
* **familiarfauna/butterfly_biomes.json** - Biomes butterflies spawn in. Setup for vanilla, BOP, Traverse and TwF.

### Spawnrates
* **exoticbirds.cfg** - Spawnrates for birds.
* **bloodmoon.cfg** - Spawnrates for Blood Moon, occurrence frequency and other.
* **champions.cfg** - Spawnrates for Champions.
* **infernalmobs.cfg** - Spawnrates for Infernal mobs.
* **ice_and_fire.cfg** - Spawnrates for Ice & Fire mobs.

### Other
* **bettercaves-1_12_2.cfg** - Worldgen for caves.
* **AppliedEnergistics2/AppliedEnergistics2.cfg** - Worldgen for meteors.
* **carryon.cfg** - Blacklist items or entities that cannot be picked up.
* **hardcoredarkness.cfg** - Intensity of moonlight. Minimum 0.05 moonlight.
* **horsepower.cfg** - Whitelisted entities for horsepower. Grindstone and chopping block recipes.
* **jei/itemBlacklist.cfg** - Blacklist items to prevent from showing in JEI. Primarly conceals facades and creative-only items.


## Contributors

* **Teqed** - *Initial setup and project lead* - [Teqed](https://github.com/Teqed)
* **Taeleus** - *Contributions to Shattered Sky server infrastructure and hosting* - [Taeleus](https://github.com/Taeleus)
* **Noctuae** - *Miscellaneous configs*
* **JeiMuzu** - *Extensive testing & feedback*

See also the list of [contributors](https://github.com/Teqed/minecraft-shattered-sky/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* The many mod authors who provided the default configurations these are based upon.
* Modpack authors who have shared their own configurations that inspired this project.
