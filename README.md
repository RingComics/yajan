# You Are Just an N'wah
> A Morrowind overhaul modlist focused on bringing Morrowind to 2020 in gameplay and graphics.

[Discord](http://discord.gg/6wusMF6) | [YouTube](https://www.youtube.com/channel/UCif_YWnOGA1HLlkH_4rvIwA) | [Twitch](https://www.twitch.tv/ringcomics) | [Patreon](https://www.patreon.com/ringcomics)
## Inspiration
- The [Ultimate Skyrim](https://www.ultimateskyrim.com/) modlist for Skyrim by Dylan Perry
- [Morrowind Overall Improvement Suite Enhanced (MOISE)](https://www.fgsmodlists.com/moise) by Forgotten Glory
- [Alternative to Morrowind Rebirth](https://www.nexusmods.com/morrowind/mods/48812?tab=description) by RandomPal
- [Morrowind Graphics Guide](https://wiki.nexusmods.com/index.php/Morrowind_graphics_guide) (formerly the S.T.E.P guide) by DassiD
- [Morrowind Immersive Overhaul](https://docs.google.com/document/d/19n-4coZka9hcvzaufWSuv-SVbwHplXyhCE7BAhuzxUA) by u/MorrowindNostalgia
## Goals
- Overhaul Morrowind’s gameplay to feel more modern without sacrificing the original feel of the game.
- Create a “living” dynamic world more akin to later Elder Scrolls titles.
- Add mechanics that encourage roleplaying while being engaging.
- Capture the experience of surviving in a harsh, alien land.
- Carefully balance gameplay, visuals, and performance to avoid low framerates.
- Update the visuals to more closely represent today’s standards without sacrificing the original art style.
## Introduction
You Are Just an N'wah adds 300+ mods to overhaul the land of Vvardenfell (and beyond, if you choose) to really send home the idea that you are an outlander in an alien land. You need to eat, drink, sleep, and pay attention to the weather. You can become injured, reducing your stats. You can no longer level *all* of your skills to ungodly levels, but those skills you do focus on can now go beyond vanilla limits. Skills are now more useful than they were before. As an example, Acrobatics is no longer just how far you can jump with the new Climbing Equipment, now you can reach areas that were previously only accessable with Levitate by scaling the wall. Enemies (and allies) have been tweaked so rats are no longer as hostile, but you'll find other enemies are now far deadlier. And you can't just drink 5 bottles of Sujamma to cheese every battle.

Graphics have seen a facelift, with the goal not being add as many high res textures as possible, rather maintain the same feeling you'd have gotten in 2002, booting up the game for the first time and experiencing an alien land without thinking about how new or dated the graphics look.

The name of the game is roleplaying in YAJAN; don't worry about minmaxing your character, simply play the way you feel your character would and progression will come naturally. If you wish to learn about more of added mechanics in detail, check out the [wiki!](https://github.com/RingComics/yajan/wiki)

## Tamriel Rebuilt
If you want to use Tamriel Rebuilt, change the MO2 profile from YAJAN to Tamriel Rebuilt. All of the needed patches and changes are installed automatically, including distant land! Keep in mind that even with the fixes installed, TR is still in development and there will be issues. I will not be making custom patches for problems caused by TR. The western side of the mainland is only the *preview* version, so there will be limited to no content over there outside of exploration.

Tamriel Rebuilt also has memory issues with YAJAN, so you may experience a lot of crashing. I recommend [this](https://www.nexusmods.com/morrowind/mods/45696) mod to avoid losing progress. It will be included with future versions of YAJAN TR

## Requirements
- A legal copy of Morrowind (pirated versions are not supported)
  - YAJAN WILL ***NOT*** WORK WITH OPENMW
- DirectX 9 or later
- Visual C++ 2019
- 4GB+ of VRAM
- Nexus Premium (for automatic installation, list can still be downloaded the long way through Wabbajack with a free account)

## GOG / Bethesda.net versions of Morrowind
YAJAN is compiled using the Steam version of Morrowind. If you use the GOG or Bethesda.net version, you can patch your `Morrowind.exe` file to work with the YAJAN installation. You can find the patch [here](https://github.com/RingComics/yajan/tree/main/exe%20patch). Make sure to backup your exe file before patching it. Once it has been patched and YAJAN has been installed, you must replace the `Morrowind.exe` in your Stock Game Folder directory in the YAJAN install with the backup, then run Morrowind Code Patch. The Code Patch options have been saved, you just need to hit "Apply Patches" and exit.

Other versions of Morrowind are ***NOT SUPPORTED***

# Installation
1. Install Morrowind somewhere outside of Program Files, for example `C:\Games\Morrowind`.
2. Install [Wabbajack](https://www.wabbajack.org/#/) on the same drive as Morrowind, preferably close to the root of your drive (`C:\Wabbajack`).
3. Make a folder on the same drive as Morrowind for YAJAN (`C:\Games\YAJAN`).
4. Download the [latest .wabbajack file](https://github.com/RingComics/yajan/releases/latest) and double click it to start the installation.
5. Make the folder you created in step 3 your install folder in Wabbajack, the other fields should fill in automatically.
6. Click install!
    - If the install fails, try restarting it (it can take two or more restarts sometimes). Wabbajack will remember its place and will only download what it's missing.
    - Head over to the [RingComics Discord](http://discord.gg/6wusMF6) for support if you get stuck here!
7. Run `Morrowind.exe` in Stock Game Folder to the menu, then exit.
  - GOG/Bethesda.net users: If you get a Steam error when you run Morrowind, you need to replace the exe in Stock Game Folder with your original, unpatched vanilla one, then run the Morrowind Code Patch (see above in the "GOG / Bethesda.net versions of Morrowind" section of this readme.)
11. Run `MWSE-Update.exe` in your Stock Game Folder (`C:\Games\YAJAN\Stock Game Folder`) to make sure MWSE is updated.
12. MGE XE is already mostly configured, but you should launch MGEXEgui through Mod Organizer and double check the settings are configured to your liking.
    - Changing shader settings at all will wipe my current configs, so be careful
    - It is not recommended you increase view distance further than 10 cells in the Distant Land Window
14. You can now launch the game through MO2 using the "Morrowind" executable.

# Troubleshooting
- If you get a CTD on launch, find MGE in your downloads folder and extract it to your Morrowind install, overwriting the old one. Reconfigure and update MWSE
- If you get this error, just hit yes to all

![Error](https://cdn.discordapp.com/attachments/783306335675875329/809672689648140338/unknown.png)
- If you can’t type in a text box in game, change the “background keyboard” line in morrowind.ini to 1
- If you get a missing ESP or MCP error message when running the game, replace the exe in `Stock Game Folder` with the vanilla one from your install, then run the MCP again. The MCP options are saved, just hit `Apply Patches`
- Check the pinned messages in `#yajan-support` in the [RingComics Discord](http://discord.gg/6wusMF6) server before asking for help, your problem may already be listed!
- If `Morrowind.exe` is missing during installation, and you are using the GOG or Bethesda.net version of Morrowind, follow the instructions in the "GOG / Bethesda.net versions of Morrowind" section of the readme.
- If WJ fails to download a mod multiple times, please let me know on the [RingComics Discord](http://discord.gg/6wusMF6) server! There was likely an update and I need to recompile the list with the new mod file.

# Credits
Curated by RingComics

Check YAJAN.wabbajack.manifest (found in releases) on [this](https://www.wabbajack.org/#/modlists/manifest) page to get the full list of mods and their authors.
## Testing
- [LooseNooseMooseGoose](https://www.twitch.tv/loosenoosemoosegoose)
- [ChaoticTabris](https://www.twitch.tv/chaotictabris)
- Phinocio
- Algeddon
- rrrrrrrrr
## Special Thanks
- The Morrowind Modding Community Discord for freely sharing their wealth of knowledge kindly and patiently
- The Ultimate Skyrim dev team, for inspiring and supporting me (<3 u guys)
- The Wabbajack modlist-development-help channel for answering my stupid questions
- RandomPal, Merlord, ForgottenGlory, and NullCascade for inspiring and helping me to get into modding/modmaking for Morrowind
- You, for reading this far and playing YAJAN. You may just be an N'wah, outlander, but it means a lot.
