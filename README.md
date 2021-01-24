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

* *simpledifficulty/armorTemperatures.json* - Armor that should offer temperature resistance are configured here.
* *simpledifficulty/blockTemperatures.json* - Blocks that should generate heat for SD can be added here. Vanilla, HC, ThF, and Lycanites Mobs blocks are already setup.
* *simpledifficulty/fluidTemepratures.json* - Fluids that should have temperature. Only configured for hot_spring_water.
* *simpledifficulty/heldItemTemperatures.json* - Held items which should have temperature. Currently used for vanilla, HC and TF items that warm the player.
* *geolosys.cfg* - Controls prospectable ore veins. This config is disabling vanilla oregen.
* *cofh/world/00_minecraft.json* - Controls vanilla oregen.
* *cofh/world/01_thermalfoundation_ores.json* - Controls copper, tin, silver, lead, nickel, and platinum (currently disabled).
* *cofh/world/04_overworld_ores.json* - Controls AE2 quartz, Forestry apatite (disabled), TF aluminum, and TF iridium.
* *harvestcraft_fruittree.cfg* - Controls which biomes fruit trees spawn in. Setup for vanilla and BOP.
* *familiarfauna/butterfly_biomes.json* - Controls which biomes butterflies spawn in. Setup for vanilla, BOP, Traverse and TwF.

## Dimension Registry Analysis
Info about the various dimensions in the pack. 

| Name            | Id    | Spawn |
|-----------------|-------|-------|
| overworld       | 0     | true  |
| the nether      | -1    | false |
| the end         | 1     | false |
| twilight forest | 7     | false |
| CompactMachines | 144   | false |
| limbo           | 684   | false |
| private pockets | 685   | false |
| public pockets  | 686   | false |
| dungeon pockets | 687   | false |
| emptiness       | 14676 | false |
| Storage Cell    | -11   | true  |

# Biome Registry Analysis

This contains information about how mods are using the biome registry. 50
out of 256 ids available. 19.531% of this registry is still available.

| Mod Name            | Entries | Utilization |
|---------------------|---------|-------------|
| biomesoplenty       | 73      | 28.516%     |
| minecraft           | 62      | 24.219%     |
| traverse            | 24      | 9.375%      |
| twilightforest      | 20      | 7.813%      |
| pvj                 | 9       | 3.516%      |
| dimdoors            | 4       | 1.563%      |
| netherex            | 4       | 1.563%      |
| thaumcraft          | 3       | 1.172%      |
| thaumicaugmentation | 3       | 1.172%      |
| vampirism           | 1       | 0.391%      |
| iceandfire          | 1       | 0.391%      |
| futureminecraf      | 1       | 0.391%      |
| appliedenergistics2 | 1       | 0.391%      |

# Block Registry Analysis

This contains information about how mods are using the block registry.
-2068 out of 4096 ids available. -50.488% of this registry is still available. We've bypassed the block registry limit by using NotEnoughIDs which produces negative numbers.

| Mod Name             | Entries | Utilization |
|----------------------|---------|-------------|
| quark                | 442     | 10.791%     |
| mcwfurnitures        | 378     | 9.229%      |
| pvj                  | 367     | 8.960%      |
| bewitchment          | 311     | 7.593%      |
| undergroundbiomes    | 302     | 7.373%      |
| futureminecraf       | 266     | 6.494%      |
| chisel               | 256     | 6.250%      |
| minecraft            | 254     | 6.201%      |
| botania              | 235     | 5.737%      |
| harvestcraft         | 223     | 5.444%      |
| enderio              | 210     | 5.127%      |
| thaumcraft           | 200     | 4.883%      |
| twilightforest       | 171     | 4.175%      |
| natura               | 153     | 3.735%      |
| adchimneys           | 147     | 3.589%      |
| biomesoplenty        | 128     | 3.125%      |
| naturalpledge        | 116     | 2.832%      |
| tconstruct           | 110     | 2.686%      |
| lycanitesmobs        | 108     | 2.637%      |

Results with Entries =< 100 have been omitted.

# Enchantment Registry Analysis

This contains information about how mods are using the enchantment
registry. 32691 out of 32766 ids available. 99.771% of this registry is still
available.

| Mod Name         | Entries | Utilization |
|------------------|---------|-------------|
| minecraft        | 30      | 0.092%      |
| cofhcore         | 8       | 0.024%      |
| ebwizardry       | 7       | 0.021%      |
| aquaculture      | 7       | 0.021%      |
| enderio          | 5       | 0.015%      |
| vampirism        | 3       | 0.009%      |
| openblocks       | 3       | 0.009%      |
| astralsorcery    | 2       | 0.006%      |
| simpledifficulty | 2       | 0.006%      |
| naturalpledge    | 2       | 0.006%      |
| endercore        | 2       | 0.006%      |
| bewitchment      | 1       | 0.003%      |
| jaff             | 1       | 0.003%      |
| spartanshields   | 1       | 0.003%      |
| yoyos            | 1       | 0.003%      |

# Entity Registry Analysis

This file contains information about how mods are using the entity registry.
67107687 out of 67108863 ids available. 99.998% of this registry is still
available.

| Mod Name               | Entries | Utilization |
|------------------------|---------|-------------|
| lycanitesmobs          | 168     | <0.001%     |
| animania               | 155     | <0.001%     |
| minecraft              | 83      | <0.001%     |
| twilightforest         | 80      | <0.001%     |
| ebwizardry             | 70      | <0.001%     |
| iceandfire             | 51      | <0.001%     |
| thaumcraft             | 43      | <0.001%     |
| exoticbirds            | 39      | <0.001%     |
| primitivemobs          | 30      | <0.001%     |
| bewitchment            | 25      | <0.001%     |
| mowziesmobs            | 24      | <0.001%     |
| vampirism              | 24      | <0.001%     |
| quark                  | 23      | <0.001%     |
| roots                  | 22      | <0.001%     |
| eim                    | 22      | <0.001%     |
| netherex               | 20      | <0.001%     |
| pvj                    | 19      | <0.001%     |
| botania                | 19      | <0.001%     |
| tfspellpack            | 19      | <0.001%     |
| astralsorcery          | 14      | <0.001%     |
| mysticalworld          | 14      | <0.001%     |
| toroquest              | 12      | <0.001%     |
| openblocks             | 11      | <0.001%     |
| thaumicaugmentation    | 11      | <0.001%     |
| inventorypets          | 10      | <0.001%     |
| bloodmagic             | 10      | <0.001%     |
| minecolonies           | 10      | <0.001%     |

Results with Entries =< 10 have been omitted.

# Item Registry Analysis

This contains information about how mods are using the item registry. 20966
out of 32000 ids available. 65.519% of this registry is still available.

| Mod Name              | Entries | Utilization |
|-----------------------|---------|-------------|
| harvestcraft          | 1310    | 4.094%      |
| bewitchment           | 460     | 1.438%      |
| minecraft             | 417     | 1.303%      |
| pvj                   | 395     | 1.234%      |
| mcwfurnitures         | 387     | 1.209%      |
| quark                 | 383     | 1.197%      |
| iceandfire            | 372     | 1.163%      |
| botania               | 336     | 1.050%      |

Results with Utilization =< 1% have been omitted.

# Potion Registry Analysis

This file contains information about how mods are using the potion registry. 16
out of 256 ids available. 6.250% of this registry is still available.


| Mod Name             | Entries | Utilization |
|----------------------|---------|-------------|
| bewitchment          | 41      | 16.016%     |
| minecraft            | 27      | 10.547%     |
| lycanitesmobs        | 26      | 10.156%     |
| ebwizardry           | 24      | 9.375%      |
| bloodmagic           | 17      | 6.641%      |
| vampirism            | 9       | 3.516%      |
| thaumcraft           | 9       | 3.516%      |
| naturalpledge        | 8       | 3.125%      |
| tconstruct           | 7       | 2.734%      |
| immersiveengineering | 7       | 2.734%      |
| roots                | 7       | 2.734%      |
| botania              | 6       | 2.344%      |
| simpledifficulty     | 6       | 2.344%      |
| quark                | 6       | 2.344%      |
| rpsideas             | 6       | 2.344%      |
| netherex             | 6       | 2.344%      |
| astralsorcery        | 5       | 1.953%      |
| mowziesmobs          | 4       | 1.563%      |
| champions            | 3       | 1.172%      |

Results with Utilization =< 1% have been omitted.

# Recipes Registry Analysis

This contains information about how mods are using the recipes registry.
67094343 out of 67108863 ids available. 99.978% of this registry is still
available.

| Mod Name              | Entries | Utilization |
|-----------------------|---------|-------------|
| enderio               | 1810    | 0.003%      |
| harvestcraft          | 1286    | 0.002%      |
| botania               | 1008    | 0.002%      |
| quark                 | 720     | 0.001%      |

Results with Utilization =< 0.001% have been omitted.

# Load Time Info

| Mod                                                | Total Time |
|----------------------------------------------------|------------|
| Thaumcraft                                         | 19.095s    |
| Tinkers' Construct                                 | 8.389s     |
| Immersive Engineering                              | 4.48s      |
| Astral Sorcery                                     | 3.851s     |
| Quark                                              | 3.685s     |
| Ender IO                                           | 3.587s     |
| Applied Energistics 2                              | 2.633s     |
| Animania                                           | 1.992s     |
| Lycanites Mobs                                     | 1.786s     |
| LibrarianLib Stage 2                               | 1.53s      |
| Village Names                                      | 1.304s     |
| Thermal Expansion                                  | 1.151s     |
| OpenBlocks                                         | 1.053s     |
| Biomes O' Plenty                                   | 1.045s     |
| Tetra                                              | 1.012s     |

Results with Total Time =< 1s have been omitted.

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
