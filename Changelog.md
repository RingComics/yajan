# Changelog

<details>

<summary>Versioning</summary>

```md
> X.Y.ZpN

# X = Major change, not save game safe! Start a new game.

# Y = Minor change, should be save game safe, but you may run into issues

# Z = Fixes, will not break your saves (hopefully)

# p = Indicates this is a pre-release (Preview Builds)

# N = Which preview build this is
```

</details>

<details>
<summary>Template</summary>

```md
## version

Summary

### Added mods

-

### Removed mods

-

### Changes

-

### Updated mods

-

### TODO

-
```

</details>

## v6.0.0p1 - Introducing Preview Builds!

Whenever I finish work on something related to YAJAN, it will be compiled and posted on GitHub, but not uploaded to the Wabbajack Gallery. This way I can update mods, make small changes, and experiment between official releases, as well as use the release page as a changelog. If you want to test out the latest features and gain access to the `#mod-suggestions` channel on Discord.

Preview versions are denoted a `p[preview version]` at the end of the version. This is the first preview working towards a `6.0.0` release, so it is `v6.0.0p1`

WARNING: Preview Builds are likely to be unstable and may have more bugs/stability issues than the current Wabbajack version. Please report them [here](https://github.com/RingComics/yajan/issues).

### Added mods

- [Watch the Skies](https://www.nexusmods.com/morrowind/mods/48636)
- [More believable bandit camps - an addon for Ashfall](https://www.nexusmods.com/morrowind/mods/50066)
- [NPCs Go Home](https://github.com/celediel/Morrowind-NPCs-Go-Home)
- [The Corprusarium Experience](https://www.nexusmods.com/morrowind/mods/49738)
- [Subtle Animated Menu Background Assemble](https://www.nexusmods.com/morrowind/mods/50037)
- [Fish with Fishing Poles Expansion](https://www.nexusmods.com/morrowind/mods/50065)
- [Shield Spells Reforged Pt. 1](https://www.nexusmods.com/morrowind/mods/50073)
- [Opponent Fatigue Indicator](https://www.nexusmods.com/morrowind/mods/50060)
- [Save the Date](https://www.nexusmods.com/morrowind/mods/50074)
- [Ket's Poison](https://www.nexusmods.com/morrowind/mods/48911)
- [Brevur of Balmora](https://www.nexusmods.com/morrowind/mods/47557)

### Removed mods

- Happy Harvesting
  - _Covered by Graphic Herbalism_
- Atmospheric Delights
  - _Merged into BCoM_
- Endrek's Sixth House
- The Tribe Unmourned
  - _I will likely add these mods back later on, but right now I'm focusing on compatibility with the core mods. New content will be next after I'm happy with the current load order's stability. New gameplay/immersion/QoL mods will continue to be installed and tweaked until then._

### Changes

- Started work on alternate graphics presets (requested by Paradoxial on Discord)
- Sorted load order
- Updated `Merged Objects.esp`
- Updated `multipatch.esp`
- Disabled `Ashfall`'s Blight transmission mechanics as they are covered by `The Blight`
- Enabled "Alternative Armor Weight Mechanic" for `Character Sound Overhaul`
- Disabled lockbashing with fists.
- Disabled guards following the player when caught sneaking for compatibility with companion mods.
- Updated meta files
- Removed manifest from source code, manifests will be contained on the release page exclusively.
- Updated Changelog policy and format.
- Updated `README.md`
- `YAJAN Additional Files` is now compressed using the `.7z` format

### Updated mods

- `Magicka Expanded` to v2.06
- `MGE XE` to v0.13.5
- `Ashfall` to v2.2.1
- Fixed version for `Mantle of Ascension`
- `Vanilla friendly creatures and undeads expansion` to v1.8.0
- `MWSE State-Based Health` to v1.3
- `Memory Monitor` to v2.2.1
- `Sophisticated Save System` to v2.0
- `Perfect Placement` to v2.0
- `Taddeus' Foods of Tamriel` to v1.3.5
- `Friends and Foes` to v1.6
- `The Blight` to v1.4
- `UI Expansion` to v1.5.1
- `Beautiful Cities of Morrowind` (core mod, grass, and associated patches) to v2.1.2
- `YAJAN Additional Files` to v4

### TODO

- Run Fixit
- Regen Distant Land
- Clean loose files
