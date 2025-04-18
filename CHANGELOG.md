# Version 1.3.0 
## Main File:
### Bug Fixes/General Changes
- Forwarded new fixes from YUPDate
- Fixed Joe Cobb and the Fiend Jailers' karma not being -500
- Fixed Arcade not consuming ammo
- Fixed missing sneak requirement on Alertness perk
- Fixed ammo DR reduction being inconsistent amoung various ammo types
- Fixed some raw meats giving +2 STR instead of -2
- Added automatic detection for any NPCs in evil factions to automatically set karma to -500 for parity with this mod's karma changes
- Optimization pass on all scripts
### Economy and Loot
- Nerfed cap output in a few missed loot containers
- Reworked Garbage item pools to be more logical while still making scavenging viable/useful
### Weapons/Armor/Equipment
- Lowered Cattle Prod melee requirement to 50 in the hopes of making it a little less niche
- Gave Omertas .45 Auto SMGs and Silenced 22 SMGs to fit their "mobster" aesthetic
- Deleveled unplayable NPC weapons from DLCs so they deal the same amount of damage regardless of level
- Integrated the Sturdy Caravan Shotgun, Lightweight Leather Armor, and Lightweight Metal Armor as generic weapons/armor for variety (can be found in the same places as their normal variants)
- Reworked Sturdy Caravan Shotgun as a 12 Gauge Variant of the Caravan Shotgun
- Increased Leather Armor DT from 6 -> 8
- Changed the Liberator to use the Broad Machete mesh, as it previously lacked a unique model and the unique Broad Machete mesh is only found in-game if you pick the Tribal Alternate Start option
- Gave all laser weapons 1.5x crit mult and all plasma weapons 2.0x mult 
- Nerfed Q-35 Matter Modulator, as it is an extremely easy to get early weapon that was extremely powerful
- Reworked the LAER, now has more health, does more damage, but uses 3 ammo per shot
- Removed ability to mod Elijah's Advanced LAER
- Minor tweaks to weapon stats across the board to boost viability of some (such as the Flamer and Incinerator)
### Combat
- Reduced intensity of gunshot volumes in gameplay (only in terms of NPC reactions, not actual sounds)
### World
- Swapped .308 rounds in Primm Sheriff's house to .357 Magnum, which makes more sense given the Cowboy Repeaters in the same house

## Caravan Travel:
- Added Fields' Shack as a travel location to make trecks to Nellis less tedious 
- Reworked AI of Caravaneers so they are no longer essential, flee from combat, and will respawn if killed (same behavior as vanilla Traveling Merchants)
- Optimization pass on all scripts

## Transcended Alternate Start:
- This file has been retired, as all changes are now made in the main Transcendence mod still without requiring Alternate Start as a master

## Transcended Goodies:
- Updated for the latest version of Goodies

## Transcended TLD:
- Updated for the latest version of The Living Desert

# Version 1.2.0 
## Main File:
### Bug Fixes/General Changes
- Integrated the Ed-E and Radiation hotfix files
- Fixed losing Karma in illogical places, such as killing hostile creatures
- Fixed gamesettings for spread using the unused Fallout 3 settings rather than the proper NV ones
- Removed Lonesome Road Ed-E's need for ammo to prevent any softlocks
- Added patches for Goodies, Essential DLC Enhancements Merged, and Essential Vanilla Enhancements Merged (all highly recommended)
- Removed overlapping features with Goodies
- Made the plugin an ESM due to YUPDate allowing it to be an ESM without needing a separate patch for YUP's NPC fixes
- Generated FaceGen with Mostly Fixed FaceGen Tints as a base
- Packed files into a BSA
### Economy and Loot
- Lowered the reward for telling Pretty Sarah about Cook-Cook from 300 to 150
- Balanced No-Bark Noonan and Ambassador Crockers' caravan cap pools (also no longer use the same caravan container)
- Balanced the Lonesome Road Commissary's cap totals to be inline with the rest of the Mojave vendors
### Combat
- Buffed the three boss fiends from Three Card Bounties to be more like boss fights
- Placed a Sentry Bot in Hopeville Missle Silo where Ed-E is unlocked to prevent the classic exploit of running through the first half of Hopeville Missle Silo without encountering any enemies and cashing in on thousands of caps worth of loot in the process.
### World
- Prevented Mr. Holdout from chasing down the player to initiate dialogue to keep with his illicit nature
- Slightly increased starvation rate
- Greatly expanded upon DLC integration, adding some logical DLC consumables like Wasteland Tequila and Black Coffee to various lists
- Sgt. Astor now gives the player a Radiation Suit along with the other supplies before starting the Searchlight quest

## Caravan Travel:
- Packed files into a BSA


# Version 1.1.0 
## Main File:
### Economy and Loot
- Placed loot balanced around Boulder City/REPCONN HQ
- Replaced a handful of instances of LootGunCabinetNVGunsLocked being used on unlocked containers
- Cliff Briscoe no longer buys chems
- Alexander now only trades Weapons, Misc, and Ammo
- Changed Quartermaster Baron's (Camp Forlorn Hope) cap pool from medium to small
- Lowered the value of Long Fuse Dynamite to 15 to match regular Dynamite
- Increased the ratio of dirty:purified water in some overlooked leveled lists
- Slightly lowered the cap loor in cash registers
- Lowered value of Yao Gui meat from 30 to 20
### Weapons/Armor/Equipment
- Expanded upon Binoculars integration into vendor lists
- Increased zoom on Binoculars to give them relevency even with scoped weapons
- Reduced weight of Bladed Gauntlet/Cram Opener to 5 to give it some relevence over Spiked Knuckles
- Added recipe to create dynamite with 1x Duct Tape, 1x Scrap Electronics, 1x Detergent, and 5x Rifle Powder (Requries 35 Explosvies)
- Added recipes to convert Long Fuse Dynamite to regular and vice versa
    - These changes give Dynamite some more relevency later into the game
- Lowered weight of Scissors from 1 to 0.1
- Expanded Legion/NCR inventory changes to previously overlooked NPCs
- Removed Grenade Rifles/Launchers from a few more basic NPC types that were overlooked
### Combat
- Gave Oscar Velasco a Sniper Rifle instead of a Grenade Launcher
- Reduced ranged weapon multiplier of basic enemies from 2.0 to 1.5 (compared to 1.0 in vanilla)
- Removed the changes to combat music as they were extremely inconsistent and combat music usually ended up not playing at all
### World
- Tweaked some NPC packages to make them run to certain locations to speed things up where it made sense
- Fixed Ada Straus's outfit
- Renamed the dead Raider outside of Novac to Viper Gunslinger for consistency
- Replaced some static containers in Nelson with lootable versions
- Added a small amount of value to the Empty Hydra Syringe quest item from Medical Mystery (valueless items can be pickpocketed for free, bypassing a majority of the quest without consequence)
- Integrated Black Coffee from Honest Hearts into some base game drink lists
- Changed message when looting graves without a shovel from a pop-up to a corner message

## Alternate Start Patch
- Changed starting Karma of the Regulator/Contract Killer backgrounds, as karma is a bit harder to come by with this mod

## The Living Desert Patch
- Fixed some missed conflicts
- Renamed some "Dead x" NPCs to just "x" for consitency with changes to vanilla NPCs
- Balanced some loot

## Simple Currency Patch
- Created, solves conflicts and balances quest rewards to match their changes in the main mod
