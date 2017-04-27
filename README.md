# PStar4-Randomizer v0.2b
Randomizer for the Sega Genesis RPG Phantasy Star IV

DISCLAIMER: By using this Randomizer, you assume all risks involved and do not hold me liable for any damages or file corruptions that may happen. USE AT YOUR OWN RISK!!!

Thank you for taking the interest in viewing the Phantasy Star IV randomizer. The code is written in vb.net so there may possibly be some issues with compatibility on the .NET Framework.

USING THE RANDOMIZER

0. Download the .zip file and run setup. If you already have a previous version installed, uninstall it prior to installing the new version if you have issues with the intall.
1. Select what options you want to have OR enter in Flags into the Flag field and press Set Flags button (Capital letters only)
2. Enter in any number from 0 to 99999999 (optional) into the "Seed #" field
3. Click on the "Save Path" button and choose the location and file name you wish to save to
4. Click on the "Randomize Rom" button and choose your ORIGINAL Rom file.
5. The Randomized Rom of Phantasy Star IV will be saved to your chosen location and file name and the program will be CLOSED.

NOTE: Though there is a validation process in the program to validate the rom, it only checks the first 304 bytes of the file to see if it compares. Also, I am aware that there are different versions of the rom out there. Currently, the randomizer only takes the rom that is 3,145,728 bytes large. From what I am seeing, the different versions of the rom have their data in different spots, but I will look into it more to see if there is a different header offset. If anyone has any information regarding this, please let me know. My twitch ID is MrStarbird and I am on in some form nearly daily.

It is also possible that other Genesis/Megadrive roms have the same first 304 bytes as Phantasy Star IV. If this happens, please let me know.

Version History:

4/26/17 - version 0.2.1b

-Fixed bug with Defeat Axe where it would do 999 damage and crash the game against a boss. Should work now.

4/26/17 - version 0.2b

-Fixed bug where shops could have duplicate items (hopefully)

-Added option to shuffle original treasure contents.

-Added option to balance Demi by letting her use Wren's Weapons

-Added Flags

-Added 2 other file types to choose from when selecting original rom. Both .gen and .bin are now accepted, but will still be made into a .smd file

-Added prices to the Defeat Axe and Shadow Blade if you choose to randomize shops or chests. This makes it so that these powerful weapons are not dirt cheap and are considered a fair price for the power of the weapon.

-Added Kadary's chest into the code (was slightly overlooked before).

-Fixed bug where Tonoe Basement's chests weren't randomizing correctly.

-Removed Air Castle's Eclipse Torch chest from the randomization (was added by mistake). A bug was found (albeit a beneficial bug to the player) where opening this chest with a full inventory and it not containing the eclipse torch would add over a million meseta to your current pool. By selling any item, the value would underflow to 9999999 Meseta. It's a possible bug in the game's original programming that only can be really exploited by a hack of some sort.

4/24/17 - version 0.1b

Here is what the Randomizer currently does:

1. Change shop inventories
*User can choose to randomize shop inventories. These are still separated by type: Weapon, Armor, Item. Item prices have not changed.

2. Change Item Chest contents
*User can choose to randomize the contents of items in chests that originally have items in the game. Chests that contain Meseta will still contain the original amount. Key items are still in their original chests. It is possible to have multiple of the same item from many chests.

*User can choose to shuffle the contents of items in chests that were in the original game. Chests that contain Meseta will still contain the original amount for now. Key items are still in their original chests.

Here is what I want to do for future releases:

1. Randomize enemy stats
There would still be a bit of balancing that would need to be done, but it is possible.

2. Randomize character techniques and stats.
I know there are some limits to this and skills are almost set on a per character basis, but seeing differet characters with different techniques would be fun.

3. Randomize what characters can equip.
This shouldn't be a problem with armor, but for weapons it could be a problem.

4. Randomize equipment stats.
Explains itself. Can be done, but would I want to?

5. Randomize money chest contents
Shouldn't be difficult.

Known Bugs/Issues:

Thanks goes to Lory_90 for his ps4 disassembly information. Without it, the randomizer would not be possible.

Special thanks to Serria for not complaining that I wanted to do a second randomizer. I don't dare tell her that I plan for Phantasy Star III to be randomized at some point as well.
