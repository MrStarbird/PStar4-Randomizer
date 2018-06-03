Phantasy Star IV Randomizer v1.3.1
by: MrStarbird
contributions by: Lory_90
Date: Mar. 20, 2018

Contents:
1. Version History
2. About the Phantasy Star IV Randomizer
3. Features and Options
4. Known Issues
5. Thanks

1. Version History

v1.3.1 - Mar. 20, 2018
-Fixed bug where Chest Randomization would crash the Program.
-Fixed bug where Chest Randomization would sometimes give only Meseta.
-Fixed bug where Power-Up Rods option wasn't setting its flag correctly.

v1.3.0 - Jan. 16, 2018
-Added Batch Randomization.
-Added an option to allow Saving at any location, including inside dungeons.
-Added Items to the price randomization.
-Added Preset options.
-Fixed issue where program was forced to close after ROM generation.
-Fixed equipment price randomization to scale off original price.
-Fixed bug where Hahn's Level capped at 18.
-Fixed bug where Open Armor let some people equip weapons not intended.
-Cleaned up UI, separated options again for the time being.
-Rewrote entire program to allow for easier debugging on developer's end.
-Temporarily removed the Spoiler option due to having rewrote the program.

v1.2.1 - Nov. 14, 2017
-Fixed a bug where Open Armor option wasn't working on Phantasm Robe, Algo Ring, Mahlay Ring, and would prevent Reflect Robe from being equipped.

v1.2 - Nov. 10, 2017
-Cleaned up the UI, removed and consolidated a few options into one. Enemy HP/Meseta/XP sliders have been removed for simpler design.
-Added an option to create a spoiler text file
-Added Mental Stat and TP Pools to Wren and Demi for the Humanize Wren/Demi option.
-Fixed a bug where the Eclipse Torch room would automatically start the cutscene without opening the chest.
-Fixed a bug where Hahn was not gaining levels beyond level 18.

v1.1.0 - Oct 25, 2017
-Fixed a bug with the message at the end showing the entire save path instead of just seed and flag numbers.
-Added Open Armor option, allowing all characters to equip any piece of armor.
-Added character stat randomization.
-Removed radio button configuration for shop randomization. Now is just a checkbox instead.
-Minor UI changes.

v1.0.0 - Aug 20, 2017
-Flags now set automatically when selecting and deselecting options.
-Added option for Cyber Suit to cast Vision.
-Seed# and Flags will be added to end of rom filename automatically.
-Removed Recover from the humanoid Skill pool.
-Removed Vehicle Attack Randomization option due to game crashing during normal battles.
-Fixed bug where Shift was targeting all allies.
-Fixed bug where Enemy HP Randomization was scaling upwards of 400% instead of the limit of 200%.
-Changed and cleaned up UI some more

v0.5.1 - Aug 13, 2017
-Added option to allow Androids to be healed by items and skills reserved for humanoids inside of battle.
-Added option to allow Gryz to use Daggers.
-Added option to fix Vision skill.
-Added options for Enemy Randomization and Customization.
-Added option for Item Element Randomization.
-Added Vehicle Attack Randomization.
-Cleaned up UI

v0.4.2 - Jun 12, 2017
-Fixed Text Skipping option. Should now work without issue.

v0.4.1 - May 19, 2017
-Fixed a bug in Text Skipping option

v0.4 - May 15, 2017
-Added experimental Text Skipping.
-Added Skill Randomization.
-Moved 5 Techniques to Mid-Level pool to balance out support techniques.
-Removed use of Pulse Laser and Pulse Vulcan for Demi
-Fixed bug where a chest in Plate System always gave the Laser Knife (its original item).

v0.3.1 - May 6, 2017
-Fixed bug where Randomizing Techniques would cause the program to crash.

v0.3 - May 5, 2017
-Added option to randomize equipment prices for shops.
-Added option to my Rykros Ring wearable by Kyra, Raja, Hahn, Gryz, and Demi
-Added Technique Randomization.
-Added option to allow Laser Barrier to cast Barrier in battle.
-Added option to allow Swift Helmet, Mahlay Shield, and Laser Barrier to target all allies in battle.
-Randomize Chests and Shuffle Chests will now randomize Meseta Chests.

v0.2.1 - April 26, 2017
-Fixed bug where Defeat Axe would deal 999 damage and then crash the game against a boss.

v0.2 - April 26, 2017
-Added option to shuffle original treasure contents.
-Added option to allow Demi to use weapons exclusive to Wren.
-Added Flags.
-Added the ability to choose .gen and .bin files as a source rom file.
-Added prices to Defeat Axe and Shadow Blade
-Fixed bug where Tonoe's Basement Chests and Karady's Chest were not randomizing.
-Removed Air Castle Eclipse Torch chest from randomization (it had caused a bug that would overflow the inventory and max out your meseta).

v0.1 - April 24, 2017
-Original version with Chest and Shop Randomization.

2. About the Phantasy Star IV Randomizer

The PS4 Randomizer was designed to change the around so that it would feel like a fresh experience every time you played this Genesis classic. It has gone through many revisions but is now at a stable enough point with all the options I've wanted on it. 

Uninstall any previous version of the randomizer before running it. 

Pick your options, choose your save path and file name (you can leave the file extention blank, as this will be filled in later). When you press "Randomize Rom", select your ORIGINAL rom file (don't worry, it will remain unchanged) and then a new, randomized rom will be created at your selected path and with your file name, along with the seed and flags.

3. Features and Options
By mousing over each option, you can see a brief tool-tip about what the option does and any issues or notes with the option.

Text Skipping:
By choosing "Text Skpping Enabled", text will automatically advance until you have control, either by choosing a Yes/No option or until you can move again. NOTE: There is an issue that is non-game breaking but annoying. In the Air Castle, the room with the Eclipse Torch chest and Lashiec will automatically trigger its event upon entering the room instead of opening the chest. Unfortunately, until I get in touch with Lory_90 again, I cannot fix this as Text Skipping was mostly his work. The way around it is to just make sure you do your preparations before entering the room.

Save Anywhere:
By choosing the "Save Anywhere" option, you remove the restriction of where you can save. This provides a safer method of gameplay as you can save at any point in any dungeon now as well.

Chest Options:
Chest contents can either remain as "Default" or can be either "Randomized" or "Shuffled. By choosing "Default Chest Contents", the chests will have the same items that they would in the original version of the game. By choosing "Randomize Chests", each chest will have a random, non-key item inserted into it. By choosing "Shuffle Chests", the game takes the original pool of chests and shuffles them around (key items are still in their original chests due to how flags work in the game).

Shop Options:
Selecting the "Randomize Shop Inventories" option will create all shops to have random items for sale. All shops will still sell only items of their categories. You can also choose to randomized equipment prices.

Technique/Skill Randomization:
By choosing "Randomize Techniques/Skills", every character will learn a random Technique and Skill from a pool. The levels of which they learn an ability and what they learn at that level remain unchanged (for instance, in the original, Chaz learns Tsu at Level 4 and Crosscut at Level 6). Techniques will still be learned at a level the character would learn a technique and same with skills (Chaz wouldn't learn Crosscut at Level 4 and Tsu at Level 6 for instance).

Techniques are sorted into three different categories before being distributed: Low-Level, Mid-Level, and High-Level. This is to prevent getting techniques like NaSar at Level 1 without the TP to use it. Characters will not learn the same technique twice. Megid is shuffled into the pool, though Chaz can still learn Megid on his own from Anger Tower at the end of the game. Also, Wren, Demi, and Seth still do not learn Techniques.

-Low-Level Techniques (Levels 1-13): Foi, Wat, Tsu, Zan, Gra, Gelun, Rimit, Res, Sar, Saner, Deban, Anti, Arows, Ryuka, Hinas
-Mid-Level Techniques (Levels 14-28): GiFoi, GiWat, GiThu, GiZan, GiGra, Brose, Vol, Doran, Seals, GiRes, GiSar, Shift, Rimpa, Rever
-High-Level Techniques (Levels 29+): NaFoi, NaWat, NaThu, NaZan, NaGra, Megid, SaVol, NaRes, NaSar, Regen

Skills are randomized a bit differently. Each character only has a certain set of skills they can use without the game crashing. Those that are safe to use are randomized for that character. Wren and Demi retain Recover as their first skill, have their other initial skills randomized, and must still learn Phonon, Hijammer, Burstroc, and Positron through the same events. Spark and Barrier are all Demi's version of the skill, which is coded to be weaker, though Wren will still keep his version. Hahn and Rika will still have their own version of  Eliminate in their own pools (since they are the only ones that can use it) as will Rune and Kyra get their own versions of Flaeli, Hewn, and Tandle into their own pools. There are a few skills that are included in everybody's pool. A character will not learn the same skill twice.

-Everyone: Flare, Corrosion, Explode, Spark, Deathspell, Shadow, Stasisbeam, Mindblast, Barrier, Vision
-Chaz: Crosscut, Rayblade, Astral, Airslash, Earth
-Alys: Vortex, St.Fire, Death, Moonshade, War Cry, Blessing, Miracle, Ataraxia
-Hahn: Astral, Eliminate, Moonshade, War Cry, Blessing, Miracle, Ataraxia
-Rune: Flaeli, Hewn, Tandle, Efess, Legeon, Diem, Negatis, Moonshade, Bindwa, War Cry, Miracle, Ataraxia
-Gryz: Sweeping, Moonshade, Crash, War Cry, Blessing, Miracle, Ataraxia
-Rika: Doubleslash, Disrupt, Eliminate, Illusion
-Demi: Recover (Automatic 1st slot), MedicPower
-Wren: Recover (Automatic 1st slot), MedicPower
-Raja: St.Fire, Holyword, Moonshade, Blessing, Miracle, Ataraxia
-Kyra: Flaeli, Vortex, Hewn, Tandle, St.Fire, Telele, Moonshade, Bindwa, Wary Cry, Blessing, Warla, Medice, Miracle, Ataraxia

Due to the nature of randomization, it is possible to get multiple characters with the same technique or skill and have others completely absent from the game. 

Randomizing Character Statistics:
Normally, the game has fixed stats based on their level. By selecting "Randomize Character Stats", each characters HP, TP, Strength, Mental, Agility, and Dexterity are randomized during the randomization process. HP/TP cannot exceed 999, all other stats cannot exceed 99.

HP gains range from 2-12 per level.
TP gains range from 2-10 per level, except for Demi, Wren, and Seth, who will still have no gains.
All other stat gains range from 0-2, except for Demi and Wren who will not gain any Mental. The process for randomizing these stats are a little different, as it attempts NOT to give you a 0 stat gain. If a 0 is rolled during the randomization process, it will attempt one more time to get a number. If it rolls a 0 for a second time, that will be your stat gain for that level.

Humanizing Androids:
By selecting "Humanize Wren/Demi", both Wren and Demi will be able to be the targets of items and techniques that would normally not be able to target them. This only works in battle as using them outside of battle will still fail to work, which is why I kept the inclusion of Recover for both Wren and Demi.

The following will now affect Wren and Demi in battle: Monomate, Dimate, Trimate, Res, GiRes, NaRes, Sar, GiSar, NaSar, Rever, Regen, Guard Rod, Medic Power, Shift.

Also, Wren and Demi will now also have their own TP and Mental stat. Wren's stats will be lower than Demi's and naturally he will learn Brose, Vol, and Savol. Demi will learn Res-Line and Tsu-Line techniques, as well as Deban, Gelun, Doran, and Arows. To compensate for a Mental stat, Compo, Elastic, Laconia, and Guard Armors now have their MDef stat reduced to similar stats of Robe/Mail items of similar quality.

This process is done BEFORE any other randomization, so if you choose to randomize characters along with this option, their Techniques, TP, and Mental stat will also be included in the randomization.

Extra Weapons for Gryz and Demi.
Selecting this option will allow Demi to use Wren's non-Pulse weapons and Gryz will be able to use all Daggers (except for the Mahlay Dagger).

Fixing Skills:
With this option selected, Vision will now scale off the caster's Mental stat and Medical Power will now scale off the caster's Strength stat.

Wearing the Rykros Ring:
The Rykros Ring was always one of those items like "Okay, what's the point?". Everyone else can wear their rings but the 5th character always couldn't use the last one. Selecting "Make Rykros Ring Wearable" will allow Hahn, Gryz, Demi, Raja, and Kyra to equip the Rykros Ring. The Rykros Ring also carries with it the following stats: MTL +3, AGI +3, DEF +20, MDEF +10.

Extra Item Buffs:
This will allow the Laser Barrier to cast Barrier, the Cyber Suit to cast Vision, and will make those items along with the Swift Helm and Mahlay Shield target all allies.

"Randomize Weapon Set Elements" is a bit trickier to explain. Each weapon has their attack element randomized, but it is worth noting that all weapons are divided into certain "sets" that all have the same element. For instance, Titanium Weapons will all have the same element, as will Ceramic weapons. The sets and the weapons are as follows:

-Set 1: Alis' Sword, Boomerang, Dagger, Wood Cane
-Set 2: Hunting Knife, Steel Sword, Slasher, Claw, Impacter
-Set 3: Titanium Sword/Slasher/Dagger/Axe, Stun Shot
-Set 4: Ceramic Sword/Knife, Saber Claw, Broad Axe, Struggle Axe
-Set 5: Laser Sword/Slasher/Knife/Claw/Axe, Wave Shot, Pulse Laser, Force Cane
-Set 6: Plasma Sword/Dagger/Rifle/Claw/Launcher, Silver Rod
-Set 7: Laconia Sword/Slasher/Dagger/Rod/Claw/Axe, Pulse Vulcan
-Set 8: Guardian Sword/Rod/Claw, Photon Eraser
-Set 9: Genocyde Claw, Sonic Buster, Shadow Blade, Moon Slasher, Mahlay Dagger, Defeat Axe

As of right now, the following "set" is staying with the Anti-Evil/Tsu element.
-Set 10: Elsydeon, Silver Tusk, Psycho Wand

Enemy Randomization and Customization:
There are different ways to randomize an enemy in this randomizer. Selecting "Randomize Element Strengths" will randomize what element each enemy is weak to or strong against. Due to the possibility of complete damage immunity, I have decided that no enemy will have complete immunity to damage, so the strongest they could be against any element would be to reduce the damage by 50%. Due to this, however, three enemies had to have their HP values changed. Haunt goes from 3 HP to 100 HP, Dimensworm goes from 4 HP to 200 HP, and Outerbeast goes from 6 HP to 300 HP. "Randomize Status Strengths" randomizes each enemy's resistances to debuffs and status effects. This includes bosses as well, making your status techniques and skills much more useful. "Randomized Insta-death Strengths" randomizes each enemy's resistances to instant death abilities. This also holds true for bosses, meaning that they possibly can be killed in one shot. With this option, both Spark and Hijammer are no longer exclusive to mechanical enemies and can work on enemies regardless of type.

There are also three slider bars that will change an Enemy's HP and how much Meseta and Experience they drop. You can set each of them so that all enemies have 50%, 150%, 100%, or 200% of their original values. If on the slider, you choose ???%, it will randomizes the value of each individual enemy between 50%, 100%, 150%, and 200%. For instance, one enemy could have twice as much HP and then the next could have half as much. 

The only enemy immune to these changes is Zio 1 (the unbeatable one in Zio's Fort). This is because actually beating him crashes the game.

4. Known Issues

Item Buffs Multi-Target:
As noted above, there is a small, non-breaking graphical bug with this option selected where the animation will only appear over one character. All characters will show up on the screen, noting that they are being targeted. They are being buffed properly, but it's just something that can't be fixed.

Character Stat Randomization:
There is a slight possibility of stats being randommized incorrectly and giving huge bonuses in the hundreds. This should NOT happen but without further testing, there is a small possibility.

5. Thanks

Thanks and shoutouts to the Phantasy Star IV speedrunning community for inspiring me to work on this randomizer and those who have offered to test the program out. These include but are not limited to: Jencey86, KillerSPER, Zexerousheroes, kaiten619, TylertheDriver, Jiseed, and Bichphuongballs.

Big thanks to Lory_90 for contributing all of the information needed to allow for Text Skipping, Save Anywhere, and Chest Randomization/Shuffling.

Huge thanks to Serria for putting up with me working on this Randomizer for months now.
