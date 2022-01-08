# Universal Episode Menu
![Example Menu](https://i.imgur.com/3MPsi4Nl.png "Example Menu")  
A flexible utility package for GZDoom to display multiple MAPINFO-changing mods together.  
_Currently only tested on **[GZDoom v4+](https://zdoom.org)**._

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
  - Doom Episodes 1-4
  - SIGIL
  - Doom 2
  - Doom 2: No Rest for the Living
  - Doom 2: The Master Levels
  - TNT: Evilution
  - The Plutonia Experiment
  - Wadsmoosh, _any configuration_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=52757)) ([itch.io](https://jp.itch.io/wadsmoosh))
  - The Compendium _v1.0_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=61211))
  - The Sentinel's Lexicon _v133_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=62724)) ([ModDB](https://www.moddb.com/mods/the-sentinels-lexicon))  
&#10240;
- **TITLEMAP** support:
  - The Sentinel's Lexicon _v133_ ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=62724)) ([ModDB](https://www.moddb.com/mods/the-sentinels-lexicon))
  - Kinsie's DRLA Fluff ([ZDoom](https://forum.zdoom.org/viewtopic.php?t=64025))

## Future Plans
- Submenus to prevent space overrun and reverting to the small text list
- Custom font, or possibly customized graphics for each item?

## Known Issues
- **(ENGINE)** Custom episode maps that share the same name will conflict and override each other.  
  - _**UEM** currently only provides the ability to see installed "unique" episodes/mapsets at the same time, it still assigns maps by their internal name (ex: NV_MAP01).
A conflict list may be created as these cases are discovered._

## Something Missing?
### The more submissions the better! Please let me know if you discover a mapset or mod that defines a custom episode list, let me know! I'll test and add it as quickly as I can.
