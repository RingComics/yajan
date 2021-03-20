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
## Requirements
- Steam or GOG version of Morrowind (Bethesda.net version untested)
- DirectX 9 or later
- Visual C++ 2019
- 4GB+ of VRAM
- Nexus Premium (for automatic installation, list can still be downloaded the long way through Wabbajack with a free account)

# Installation
1. Install Morrowind somewhere outside of Program Files.
2. Install [Wabbajack](https://www.wabbajack.org/#/) on the same drive as Morrowind, preferably close to the root of your drive.
3. Make a folder on the same drive as Morrowind for YAJAN.
4. Download the [latest .wabbajack file](https://github.com/RingComics/yajan/releases/latest) and double click it to start the installation.
5. Make the folder you created in step 3 your install folder in Wabbajack.
6. Click install!
    - Head over to the [RingComics Discord](http://discord.gg/6wusMF6) for support if you get stuck here!
7. Move the contents of the Game Folder Files folder to your Morrowind installation.
    - Note to Azura’s Star users: You can only have one Morrowind modlist installed at any time due to the need for patching the executable. I’m currently looking for a solution to this problem, but for now this is the way things are.
8. Follow the below steps for running the Morrowind Code Patch. DO NOT RUN MCP IN MOD ORGANIZER. Options not listed below can be configured to your taste.
    - Game Mechanics - ALL ON EXCEPT:
      - Swift casting
      - Pickpocket Overhaul
      - Followers defend immediately
      - Healthy appetite
      - Racial variation in speed fix
      - Strength-based hand to hand damage
      - Spellmaking max. magnitude increase
      - Spellmaker/enchant multiple effects
    - Visuals:
      - Rain/snow Collision: On
      - Bump/reflect map local lighting: On
      - Over-the-shoulder third person camera: Off
      - Reduce camera clipping: On
    - Mod Specific - ALL OFF EXCEPT:
      - Scripted music uninterruptible
      - Seperate axe inventory sounds
      - Hi-def cutscene support
    - Interface Changes:
      - Map expansion: Off
      - Disable map smoothing: Off
      - Level-up skills tooltip: On
      - Persuasion improvement: On
      - Spellmaker/enchanting improvement: On
      - Better typography: Off
      - Ownership tooltip: Off
    - Bug Fixes - ALL ON
9. Hit “Apply Chosen Patches”
10. MGE XE is already mostly configured, but you should launch MGEXEgui through Mod Organizer and double check the settings are configured to your liking.
    - Changing shader settings at all will wipe my current configs, so be careful
    - It is not recommended you increase view distance further than 10 cells in the Distant Land Window
11. Run MWSE-Update.exe ***OUTSIDE OF MO2***.
12. You can now launch the game through MO2 using the "Morrowind" executable.


# Troubleshooting
- If you get a CTD on launch, find MGE in your downloads folder and extract it to your Morrowind install, overwriting the old one. Reconfigure and update MWSE
- If you get this error, just hit yes to all

![Error](https://cdn.discordapp.com/attachments/783306335675875329/809672689648140338/unknown.png)
- If you can’t type in a text box in game, change the “background keyboard” line in morrowind.ini to 1
- If your game crashes when loading a save, uninstall Morrowind completely, and reinstall. This usually happens when updating YAJAN to a new version.



# Credits
Curated by RingComics

Check YAJAN.wabbajack.manifest (found in releases) on this page to get the full list of mods
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
