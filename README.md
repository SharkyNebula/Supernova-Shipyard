This mod brings Escape Velocity ship graphics to the next level with boosted ship sizes, as well as unique shields, engine glows, running lights, visually appropriate weapon exit points, and weapon glows for every ship.

[See available ships and art breakdown at my Github wiki.](https://github.com/NebulaTank/Supernova-Shipyard-Wiki/wiki/1-Ship-Index)

[Nexusmods Page](https://www.nexusmods.com/escapevelocitynova/mods/5). 

### What this _is_:

A total conversion for viewing new graphics and seeing NPC ships fight with them. There are 245 ships in total. 85 are unique. 161 are factional variants.

### What this _isn't_:

A plug-in for the base EV Nova scenario. If you place these plug-ins into your Nova Plug-ins folder, overwriting the base scenario, things **WILL** look funky.

A total conversion that remakes the EV Nova universe while including the Supernova Shipyard designs. If you want that, wait for EVN: Triskelion.

### System requirements:

Base: 0.65GB of RAM.
Animated Hyperioids: +0.2GB of RAM.
Fitted shields: +0.45GB of RAM.
Total: 1.3GB of RAM.

WinNova will crash if it has to load ~1GB, so don't load everything at once.

### How to install (Windows): 

1) Copy and Paste your EV Nova folder.
1) Delete the Nova Files and Plug-ins folders in the duplicated folder.
1) Extract the Supernova Shipyard archive and place the contents (replacement Nova Files and Plug-ins folders) in your duplicated EV Nova folder.

### Important note about WinNova memory limits:

**Windows EV Nova can only load about 1GB of assets** into memory before it will refuse to load. The fitted shields (400MB) and animated Hyperioids (180MB) have been excised from the Nova Files folder so the game can run on Windows. Please ensure the total number of files that your WinNova has to load is below 1GB, or test it on MacNova instead. **MacNova can load up to 4GB.** [Or wait for Cosmic Frontier, which loads files in a smarter way.](https://www.kickstarter.com/projects/cosmicfrontier/cosmic-frontier-override)

### Where do I find the ships:

* You can find Federation, Civilian, Pirate and Insurgency ships fighting in the Federation system. This is the system you start in.
* Auroran Empire, Dani, Heraan, Moash, Tekel and Vella ships are in the Auroran system.
* Polaris, Nil'kemorya, Hyperioid, Ulterioid, Krypt, Wraith, Olympian and Nephilim ships are in the Polaris system.
* Wild Geese, Association, Bureau, Domain and Replicant ships are in the Wild Geese system.
* Escape Velocity: Trader, Criminal, Mercenary, Confed, Rebel and Scourge ships are in the Escape Velocity system.
* United Earth, Citizen, Militia, Renegade, Voinian, Emalgha, Hinwar and Miranu ships are in the United Earth system.
* Crescent, Zachit, Strandless, Azdgari, Zidagar, Igadzra and Crescent Renegade ships are in the Crescent system.

### Can I use this in my own mod:

Yes. The contents of this mod are licensed under the [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/). 

Attribution: you must credit me and link to the source of my artwork.

[Read about the implications of ShareAlike](https://wiki.creativecommons.org/wiki/ShareAlike_interpretation). 

The only things that need to be released under the same license are things directly derived from my work. Your own original work does not need to be released under the same license.

[Read about the implications of NonCommercial](https://wiki.creativecommons.org/wiki/NonCommercial_interpretation).
You are allowed to accept donations or funding. You are allowed to sell your own work. You are not allowed to sell my work or derivatives of my work, but it can be included alongside a commercial project where the selling point is something original that you've made.

### Can I make a EV Nova graphics mod with this?

That's already been done by the BASED DrFiveMinusMinus. You can find it here: [SuperNOVA Graphical Overhaul.](https://www.nexusmods.com/escapevelocitynova/mods/6)

### I want technical info!

You can find it here, as a Spreadsheet on Google Sheets: [Supernova Shipyard info.](https://docs.google.com/spreadsheets/d/11uJtZSP5wY4b6OLVUfjmHOF7JlvfjJez6DbdDmBfz-U/)

That spreadsheet contains the following sheets:

* ID Order: a technical listing of which rleDs, descs and picture IDs are assigned to which ship
* Dudes: which dudes are assigned to what system and what govt has which ID and tech level
* Render Info: the sizes that ships and their effects should be rendered at, as well as how their gaussian blurs should be colored
* Frame Count: the frame counts for animated ships
* Faction Colors: the hex codes for faction colors
* Sizes Stats: the placeholder stats I assigned to ship size categories
* Width/Length: a sheet for deriving the lore width, length and height of each ship

### I want the Novalike camera angles for rendering.
You can find them at [GitHub](https://github.com/NebulaTank/Supernova-Shipyard-Source). Here's the [Ship Template](https://github.com/NebulaTank/Supernova-Shipyard-Source/blob/main/Blends-%20Ships/Ship%20Template.blend).
