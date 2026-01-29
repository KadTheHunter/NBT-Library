# NBT Library
The NBT Library is a collection of hotbar files containing a wide array of Kits, Items and Books made with NBT Data/Components

# Installation
It is highly recommended that you use the [Librarian](https://modrinth.com/mod/librarian) mod by _videogamesm12_, which allows you to access the entire library at once via pagination, as well as have titles and important metadata for each page/hotbar.

The Library is still usable without Librarian, but you will have to manually rename one of the files to `hotbar.nbt`, move it to the root `.minecraft/` directory, and relaunch Minecraft in order to use it.

Please note that the NBT Library is for **Java Edition**. It will **not** work on Bedrock Edition. Furthermore, support will not be provided to users attempting to run Java Edition on a mobile device.

## With Librarian Mod
1. Download the NBT Library from [Releases](https://github.com/KadTheHunter/NBT-Library/releases)
2. Copy and Extract the `NBT-Library-vX.X.X.zip` file to `.minecraft/hotbars/`
3. If done correctly, you should see a number of new files, named `hotbar.-1.nbt`, `hotbar.-2.nbt`, etc.
   1. If you're *not* using Librarian, please jump to step 2 of [Without Librarian](#without-librarian-mod)
4. Launch Minecraft *or* run `/lb cache clear`
5. Open the Hotbars tab of the Creative Inventory, and use the arrow buttons to navigate to the left/negative pages to verify the Library loads correctly.

## Without Librarian Mod
1. Follow the first 3 steps of [With Librarian](#with-librarian-mod)
2. Choose one of the new files, rename it to `hotbar.nbt` and move it to the root `.minecraft/` directory
   1. **WARNING**: *This will overwrite any existing hotbar file in the root directory. Please make a backup of any such file beforehand.*
3. Launch or Re-Launch Minecraft 
4. Open the Hotbars tab of the Creative Inventory, to verify the hotbar loaded correctly.

# Usage
The NBT Library is intended for use in single-player or on applicable creative servers. All entries are divided and subdivided into [Categories](#categories), each of which is a single "Page" (hotbar file). 

By default, the Library is immutable, meaning you cannot add or remove entries without using the vanilla keybinds (and the Librarian mod prevents accidental overwriting). Entries can be copied from the Library to your inventory with normal Left, Middle or Right clicks.

Users with [Better Saved Hotbars](https://modrinth.com/mod/better-saved-hotbars) installed should be wary of accidental modification of Library pages; Default BSH settings will **remove** entries on Middle click, and **add** entries when an item is Left or Right-clicked on an empty slot.

Support will **not** be provided for using the NBT Library and its associated files/components outside the instructions detailed in [Installation](#installation), and intended usage in creative mode single or multi-player. Any such issues or requests (i.e. "How to use this in survival" or "Bedrock support?) will be immediately closed, locked and ignored.

## Categories
The NBT Library is currently divided into 9 categories:
### 1. Utility / Abuse
   - Kits and Items deemed useful, or intended to abuse and exploit
   - Subdivided into Building, Functional, and Fun (for Utility), and All-In-One, Specific, Spawn Eggs, Spawners, and Command Blocks (for Abuse)
### 2. PvP
   - Kits and Items intended for Player vs Player combat
   - Subdivided into OP/NBT, Meme/Theme, and Related (for Kits), and Melee Weapons, Ranged Weapons, and Armor (for Items)
### 3. Potions
   - All types of Potions, 
   - Subdivided into Offensive, Neutral, Defensive, and Suicidal
### 4. Fireworks / Spawn Eggs
   - Individual and Bulk Fireworks and Spawn Eggs
   - Subdivided into Single, Launcher, and Bundle/Box (for Fireworks), and Area Effect, Troll, Misc., Build, and Bundle/Box (for Spawn Eggs)
### 5. Misc. Functional
   - Kits and Items with functionality, but no definable category
   - Subdivided into Command Blocks, True Misc., and Fun (for Kits), and Command Block, Display Entities, and True Misc. (for Items)
### 6. Lore / Non Func.
   - Any Kit or Item where the primary feature is Lore, or there is no real feature.
   - Subdivided into S, A, B, and C tiers (for Lore), and Kits, and Items (for Non-Func.)
### 7. Books
   - A small collection of interesting or useful books
   - Subdivided into Fiction, Misc. The Heptameron, and Utility
### 8. SongPlayer
   - Items and Bundles/Kits of Items for use with the [SongPlayer](https://modrinth.com/mod/songplayer) mod.
   - Subdivided into Kits/Playlists, and Single Song Items
### 9. Txsla / MarioKartWii
   - Kits and Items made by _txsla or MarioKartWii
   - Subdivided into Txsla, and MarioKartWii

 _These categories and subdivisions are subject to change with any update, and are created and modified at the current Librarian's discretion._

# Updates
The NBT Library will try to update to new versions of Minecraft as quickly as possible. 

Due to the increasingly version-specific nature of NBT, and Mojangs unfortunate habit of omitting important and breaking changes to NBT from the changelog/patch-notes, updates may take a week or more.

Library entries can and will be removed between updates as needed. Unlike its predecessor "The Shulker Archives", the NBT Library is not focused on forcing every item to update and work on the newest version; Instead, items are removed if they are broken or outdated, and ideally are replaced with newer, working items.

# Contributing
Contributions to the NBT Library are welcome!

## Entries
To contribute entries to the NBT Library, please do one of the following:
- Open an issue here using the [Submit Entry]() Template
- Post your entry in the [Discord](https://discord.com/invite/cfq25qURfv) Server, `#new-items` channel
- DM your entry to `@kaddicus` on [Discord](https://discord.com/invite/cfq25qURfv)

Please only do *one* of these! Creating duplicate submissions will vastly reduce the odds of your entry being accepted into the NBT Library.

## Bugfixes, Changes, Recategorization, etc.
To contribute to the NBT Library in other ways, i.e. bugfixes, title changes, recategorizing entries, improving this README, etc., please do one of the following:
- Open an issue here using the [Other Contribution]() Template
- Make a post on the [Discord](https://discord.com/invite/cfq25qURfv), `#library-discussion` forum
- DM your contribution to `@kaddicus` on [Discord](https://discord.com/invite/cfq25qURfv)

# About NBT Library
The NBT Library was created when its predecessor, [The Shulker Archives](https://github.com/KadTheHunter/ShulkerArchives) became increasingly difficult to maintain and update. The reasons mentioned above in [Updates](#updates) were amplified in The Shulker Archives by way of the sheer quantity of items, and the fact that entries were rarely ever removed. 
<br>This resulted in each update being a dice-roll as to how many items would loudly fail to update and log errors to the console, and how many items would *silently* fail to update, and just quietly be broken until someone noticed.

By reducing the total number of entries, and effectively "containerizing" frequently problematic categories like [Utility / Abuse](#1-utility--abuse) (not to mention allowing the removal of entries as needed), the NBT Library makes it much easier to handle broken entries with each update.

Additionally, the NBT Library takes the "curated" aspect of The Shulker Archives, and actually makes it useful.
<br>Entries are not only curated, with "slop" items being filtered out alongside anything outdated or useless, but are made far more accessible than before. No need to leave the world or server you're on just to go get an item: now you have every worthwhile item at your fingertips.