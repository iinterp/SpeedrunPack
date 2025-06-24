# SpeedrunPack

Contains all mods that are verifiable on [speedrun.com](https://www.speedrun.com/mc) for modern versions of Minecraft.

### Includes:
- **SeedQueue** - Generate many worlds at once with a built-in wall screen on one instance
- **WorldPreview** - Preview worlds while they are still generating, allowing you to reset early
- **Atum** - Automatically creates a new world when you leave one, with a keybind to reset instantly
- **Many many performance mods** to increase FPS and make world generation faster

## Installation

**Java 17-22 is required.**

**Windows:** [Install Java 21 here](https://adoptium.net/temurin/releases/?os=windows&arch=x64&package=jre), download and run the .msi file.

**Mac:** [You can follow these instructions](https://www.youtube.com/watch?v=GomIeW5xdBM) to install everything except the mods, since the modpack does that bit for you.

**Linux:** Install OpenJDK 21 from your systems package manager.

<details><summary>Modrinth App</summary>

### Browse -> Search for SpeedrunPack -> Click Install
> Optionally, navigate to the Versions tab to select a version to install
## To Install Java
### View Instance -> Options
### Override global java installations -> Auto detect -> Select Java 21

</details>

<details><summary>Prism Launcher & MultiMC</summary>

### Add Instance -> Modrinth -> Search for SpeedrunPack -> Select OK
> Optionally, select a version to install in the dropdown
## To Install Java
### Edit Instance -> Settings -> Java
### Java Installation -> Auto-detect -> Select Java 21 -> Skip Java Compatibility Checks

</details>

<details><summary>ATLauncher</summary>

### Packs -> Modrinth -> Search for SpeedrunPack -> New Instance -> Install
> Optionally, select a version to install in the dropdown
## To Install Java
### Instance -> Settings -> Java/Minecraft
### Runtime Override -> Select Java 21

</details>

## What Minecraft version should I choose?

### Unsure? -> 1.16.1

<details><summary>Why?</summary>
	
You might think you should use the latest version of Minecraft, but there are many reasons that make **1.16.1** the most popular version for speedrunning. Not only is it the fastest version of the game, it also relies way less on RNG to complete a run than newer versions.

Because of this, 1.16.1 gets the most support when it comes to speedrunning specific mods, resources, and guides. At the moment, 1.16.1 is the only version to have the _SeedQueue_ mod, which is a single-instance way to generate many worlds at the same time, making resetting much faster and easier.

However, other versions of Minecraft are still popular to speedrun. **1.15.2** is popular due to being the last version before The Nether Update, which dramatically changed Minecraft speedruns. This means that the speedrun route for 1.15.2 and below is very different from newer versions of the game.

Of course, if you still want to speedrun the latest versions of the game, go ahead! Just know that it will be very different from what most people play: you will find piglin brutes in bastions; the rates at which you get ender pearls from piglins are much worse; the new world generation makes getting to the nether difficult; the F3 pie chart works differently; and much more.

</details>

## My settings keep reverting to defaults!

This is due to the StandardSettings mod, which changes your settings to a preset default every time you load a new world.

To fix this, you can either disable the mod or set it up to revert to the settings you choose.

### Steps (MC 1.16.1)

1. In the options menu, click on the Mod Configs button (the book icon)
2. Open the StandardSettings config
3. To disable StandardSettings set 'Use StandardSettings' to 'OFF'  
Otherwise, change the settings in this menu to the ones you would usually use. You can press 'CTRL+F' to search for a setting.

<details><summary>For MC versions other than 1.16.1</summary>
Versions other than 1.16.1 use an older version of the StandardSettings mod which does not have an in-game GUI. 

**To disable StandardSettings in this version you have to manually remove or disable the mod .jar file.**

If instead you want to setup StandardSettings, there are instructions [here](https://github.com/KingContaria/StandardSettings/tree/a090442f287ccae46dbfa8837a94f663cc6cbc12?tab=readme-ov-file#how-can-i-edit-my-standardsettings).

</details>

## How to set up The Wall (MC 1.16.1 Only)
> Generate many worlds at once on a single-instance using SeedQueue

[Here's a video guide to setup SeedQueue](https://youtu.be/fGu2MYZxh_c). The guide is for MultiMC, but the steps should be similar in most other launchers.  
You don't need to watch the separate video mentioned as the modpack does that setup for you.

## Other Resources

**[Ninjabrain Bot](https://github.com/Ninjabrain1/Ninjabrain-Bot)** - An accurate stronghold calculator legal for Minecraft speedrunning

**[MCSR Ranked](https://modrinth.com/mod/mcsr-ranked)** - Ranked speedrunning mod 

**[The MCSR Practice Map](https://github.com/Dibedy/The-MCSR-Practice-Map/releases/latest)** - All-in-one practice map

& more at **[MinecraftSpeedrunning.com](https://www.minecraftspeedrunning.com/public-resources)**

---

> This is an unofficial source and may not always be up-to-date. The official source for legal mods can be found [here](https://mods.tildejustin.dev).
