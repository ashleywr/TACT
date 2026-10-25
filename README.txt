Tiny Alex's Caves Tweaks

https://www.curseforge.com/minecraft/mc-mods/alexs-caves

----------------------------

Adjustments done:

- Added config option to change the stun duration of Primitive Club.

- Added config to allow changing the speed of Nuclear Furnace smelting time.

- Added config option to adjust how many arrows Dreadbow will spawn per arrow type.

- Added config options to change health, armor, and attack damage for nearly all Alex's Caves mobs.

- Added config to change Tremorzilla's health regeneration rates, health regeneration amounts, step height, and walking block griefing. However, turning off the walking block griefing could cause Tremorzilla to get stuck so please do not report pathfinding issues to Alex's Caves if you turn off the block griefing for when Tremorzilla walks.

- Added configs to control the recharge and depletion rate of Subterranodon's flight meter.

- Added configs to control Raygun damaging rates when Gamma enchanted and not enchanted.

- Added configs to control Extinction Spear's melee and ranged damage values.

- Added config option to allow Cloak of Darkness to charge and use ability in bright light areas.

- Added config to allow making Guano, Guano Block, and Guano Layer be usable as Furnace fuel.

- Added config option to disable the End Story replacement that Alex's Caves replaced when beating Ender Dragon. (Not disabled by default)

- Added config option to unlock all pages in the Cave Compendium book on log in. (Config is off by default)

- Added config option to allow eating Biome Treat even when not hungry. This is more due to when other mods overhaul hunger system and accidentally causes Biome Treat to be uneatable with default behavior. This config is a workaround for that.

- Added config to make Gobthumpers spawn Gum Worms from Candy Cavity biome. Also has an option to disable Gobthumpers's Gum Worm spawning ability entirely. Gobthumpers will still attract nearby existing Gum Worms.

- Made Underweed, Tree Star, Fiddlehead, and Curly Fern be replaceable by blocks in your hand just like how vanilla grass and fern can be replaced by player block placing.

- Added Galena and Radrock to `minecraft:stone_crafting_materials` and to `minecraft:stone_tool_materials` item tags so these cobbled-looking stone can be more useful!

- Added all Alex's Cave biomes to `minecraft:is_overworld` tag for compatibility with other mods and datapacks.

- Added Forlorn Hollows, Magnetic Caves, Primordial Caves, Toxic Caves, Candy Cavity to `forge:is_cave` for better mod compat.

- Added Primordial Caves to `forge:is_lush`.

- Added Tree Star, Fiddlehead, and Curly Fern to `minecraft:replaceable` tag so other mods know they can replace these blocks safely like they do for grass.

- Added entity type tag `tact:primitive_club_stun_immune` that players/packmakers can add entities into so Primitive Club cannot stun them.

- Added `tact:radioactive_and_acid_resistant_armor` item tag to allow specifying other mod's armor that should give resistance to radiation and acid.

<!-- ashley-release-information -->

## Ashley's builds

This is an unofficial maintenance fork. Original authors retain ownership and credit. See the [upstream project](https://github.com/TelepathicGrunt/TACT) for the original mod. Local changes do not imply upstream endorsement.

Licensing: **MIT**. Existing license files, copyright notices, attribution and any separate asset terms remain in force. This fork does not relicense upstream work.

Provided **AS IS**, without warranty of any kind. Maintenance, updates and support are best effort; compatibility with every modpack is not guaranteed.

### Downloads and installation

Download a runtime `.jar` from [GitHub Releases](https://github.com/ashleywr/TACT/releases). Use the Minecraft version and loader named in that release and install its required dependencies. Do not install `-sources`, `-dev`, `-slim`, `-common` or test JARs as the mod.

Close Minecraft, back up your world, and place the matching runtime JAR in the instance's `mods/` directory. Replace older versions of this same mod rather than loading duplicates. For content mods, install matching versions on the server and its clients unless the release explicitly says client-only or server-only.

### Building and reporting problems

Use Java 21 and the checked-in Gradle wrapper:

```powershell
.\gradlew.bat build
```

Build outputs are under `build/libs/` or each loader subproject's `build/libs/`. Some projects require the local development dependencies described above; those dependencies are not included in the download.

For a problem report, include the exact release filename, Minecraft and loader versions, relevant mod versions, `logs/latest.log`, and a crash report if one was written. Remove private information before sharing logs. Remove the JAR to uninstall; worlds containing this mod's blocks, entities or world generation may require restoring a backup.
