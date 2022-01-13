# Universal Episode Menu

![Example Menu](https://i.imgur.com/3MPsi4Nl.png "Example Menu")  
A utility package for GZDoom and Zandronum to display multiple MAPINFO-changing mods together.

_Full support for **[GZDoom v4+](https://zdoom.org)**_  
_Partial support for **[Zandronum v3.1](https://zandronum.com)**_

[Visit us on the ZDoom forums!](https://forum.zdoom.org/viewtopic.php?f=43&t=74376)

### [DOWNLOAD](https://github.com/FelesNoctis/UniversalEpisodeMenu/releases "Download Link")  

![Stable Version](https://img.shields.io/github/v/release/FelesNoctis/UniversalEpisodeMenu?label=stable "Stable Version")  
![Experimental Version](https://img.shields.io/github/v/release/FelesNoctis/UniversalEpisodeMenu?include_prereleases&label=experimental "Experimental Version")

## Usage

- Load as the last file, or as late as you can
- See _Current Features_ below for support list if something is missing, and report it!

## Description

Universal Episode Menu's primary purpose is to provide flexible support for all non-replacer mapset menus, as well as mods that may reset the EpisodeMenu list for various reasons. It's secondary purpose is to (eventually) provide a custom episode-selection menu that will avoid GZDoom reverting to the console-styled small text list by introducing (probably zscripted) submenus.

## Features

- Layout modifications to allow for 11 episode entries (may be reverted when submenus are introduced)
- Only displays episodes you have installed  
&#10240;
- **EpisodeMenu** support:
  - Wadsmoosh, _any configuration_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=52757)) ([itch.io](https://jp.itch.io/wadsmoosh))
  - Doom Episodes 1-4
  - SIGIL
  - Doom 2: Hell on Earth
  - Doom 2: No Rest for the Living
  - Final Doom _(Hell on Earth, TNT: Evilution, and The Plutonia Experiment are still exclusive to each other without using Wadsmoosh)_
  - Doom 2: The Master Levels _(with Wadsmoosh)_
  - Works of the Masters _v7_ ([itch.io](https://jp.itch.io/deluxe-master-levels))
  - Knee-Deep in ZDoom ([DRDTeam](https://kdizd.drdteam.org/intro.php)) ([/idgames](https://www.doomworld.com/idgames/levels/doom/Ports/megawads/kdizd_12))
  - The Compendium _v1.0_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=61211))
  - The Sentinel's Lexicon _v133_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=62724)) ([ModDB](https://www.moddb.com/mods/the-sentinels-lexicon))  

## Future Plans

- Submenus to prevent space overrun and reverting to the small text list
- Custom font, or possibly customized graphics for each item?

## Known Issues

- **(Zandronum)** does not appear to have game filtering, and may display the wrong names for some episodes.
  - _**MAPINFO** assigns maps by their internal name (ex: MAP01). With GZDoom's filtering, name corrections can be made based on the primary IWAD. However, in Zandronum, the following episodes will display incorrectly due to shared map filenames:_
    - _**Hell On Earth:** TNT: Evilution, The Plutonia Experiment, FreeDOOM Phase 2_

## Something Missing?

### The more submissions the better! Please let me know if you discover a mapset or mod that defines a custom episode list! I'll test and add it as quickly as I can.
