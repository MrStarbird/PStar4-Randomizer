Phantasy Star IV Randomizer v1.0
by: MrStarbird
contributions by: Lory_90
Date: Aug 20, 2017

Contents:
1. Version History
2. About the Phantasy Star IV Randomizer
3. Features and Options
4. Known Issues
5. Thanks

1. Version History

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

The PS4 Randomizer was designed to change the around so that it would feel like a fresh experience every time you played this Genesis classic. It has gone through many revisions but is
now at a stable enough point with all the options I've wanted on it. 

3. Features and Options
By mousing over each option, you can see a brief tool-tip about what the option does and any issues or notes with the option.

Text Skipping:
By choosing "Text Skpping Enabled", text will automatically advance until you have control, either by choosing a Yes/No option or until you can move again. NOTE: There is an issue
that is non-game breaking but annoying. In the Air Castle, the room with the Eclipse Torch chest and Lashiec will automatically trigger its event upon entering the room instead of
opening the chest. Unfortunately, until I get in touch with Lory_90 again, I cannot fix this as Text Skipping was mostly his work. The way around it is to just make sure you do your
preparations before entering the room.

Chest Options:
Chest contents can either remain as "Default" or can be either "Randomized" or "Shuffled. By choosing "Default Chest Contents", the chests will have the same items that they would
in the original version of the game. By choosing "Randomize Chests", each Item Chest will have a random, non-key item inserted into them and Meseta chests will have a random value
inserted into it between 100 and 10000 Meseta. By choosing "Shuffle Chests", the Item Chests will have a random item from a pool of the original chest contents and Meseta chests will
have a random value from a pool of all Meseta chests in the game. Key items (Alshline, Psycho Wand, Eclipse Torch, Aero Prism, and the 5 Rings) as well as Wren and Demi's skills 
are unchanged and remain in their same spot. Elsydeon and Silver Tusks cannot be placed into a chest and must be gotten by normal means.

Shop Options:
Shops can either remain as "Default" or "Randomized". By choosing "Default Shops", all shops in game will remain the same. By choosing "Randomize Shops", all shops will have random
items for sale. Weapon shops still only sell Weapons, Armor shops still only sell Armor, and Item shops still only sell items.

Technique/Skill Randomization:
By choosing "Randomize Techniques/Skills", every character will learn a random Technique and Skill from a pool. The levels of which they learn an ability and what they learn at that
level remain unchanged (for instance, in the original, Chaz learns Tsu at Level 4 and Crosscut at Level 6). Techniques will still be learned at a level the character would learn a
technique and same with skills (Chaz wouldn't learn Crosscut at Level 4 and Tsu at Level 6 for instance).

Techniques are sorted into three different categories before being distributed: Low-Level, Mid-Level, and High-Level. This is to prevent getting techniques like NaSar at Level 1 without
the TP to use it. Characters will not learn the same technique twice. Megid is shuffled into the pool, though Chaz can still learn Megid on his own from Anger Tower at the end of the
game. Also, Wren, Demi, and Seth still do not learn Techniques.

-Low-Level Techniques (Levels 1-13): Foi, Wat, Tsu, Zan, Gra, Gelun, Rimit, Res, Sar, Saner, Deban, Anti, Arows, Ryuka, Hinas
-Mid-Level Techniques (Levels 14-28): GiFoi, GiWat, GiThu, GiZan, GiGra, Brose, Vol, Doran, Seals, GiRes, GiSar, Shift, Rimpa, Rever
-High-Level Techniques (Levels 29+): NaFoi, NaWat, NaThu, NaZan, NaGra, Megid, SaVol, NaRes, NaSar, Regen

Skills are randomized a bit differently. Each character only has a certain set of skills they can use without the game crashing. Those that are safe to use are randomized for that
character. Wren and Demi retain Recover as their first skill, have their other initial skills randomized, and must still learn Phonon, Hijammer, Burstroc, and Positron through the same
events. Spark and Barrier are all Demi's version of the skill, which is coded to be weaker, though Wren will still keep his version. Hahn and Rika will still have their own version of 
Eliminate in their own pools (since they are the only ones that can use it) as will Rune and Kyra get their own versions of Flaeli, Hewn, and Tandle into their own pools. There are
a few skills that are included in everybody's pool. A character will not learn the same skill twice.

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

Due to the nature of randomization, it is possible to get multiple characters with the same technique or skill and have others completely absent from the
game. 

Humanizing Androids:
By selecting "Humanize Androids", both Wren and Demi will be able to be the targets of items and techniques that would normally not be able to target them.
This only works in battle as using them outside of battle will still fail to work, which is why I kept the inclusion of Recover for both Wren and Demi.

The following will now affect Wren and Demi in battle: Monomate, Dimate, Trimate, Res, GiRes, NaRes, Sar, GiSar, NaSar, Rever, Regen, Guard Rod, Medic Power, Shift

Demi using Wren's Weapons:
By selecting "Demi can use Wren's Weapons", Demi will now be able to equip the Plasma Laser, Napalm Shot, Plasma Launcher, and Photon Eraser. She cannot
use Pulse Laser and Pulse Vulcan due to a non-breaking graphical glitch.

Gryz using Daggers:
By selecting "Gryz can use Daggers", Gryz will be able to equip every dagger and knife except for the Mahlay Dagger. There was an unused animation in the
game for Gryz to use daggers, so there are no issues allowing him to use them.

Fixing Vision:
In the US version of the game, Vision was nerfed compared to how it worked in Japan. A flat +8 to Dexterity is nice early on but got phased out a lot
later in the game. Selecting "Fix Vision Buff" will allow Vision's power to scale off the caster's Mental stat, making it much more handy to use.

Fixing Medic Power:
Medic Power is commonly overlooked late in game. The revive is nice, but the HP restoration is too low. Selecting "Power up Medic Power" will give the ability
power that is slightly less than what GiSar would do.

Wearing the Rykros Ring:
The Rykros Ring was always one of those items like "Okay, what's the point?". Everyone else can wear their rings but the 5th character always couldn't use the last
one. Selecting "Make Rykros Ring Wearable" will allow Hahn, Gryz, Demi, Raja, and Kyra to equip the Rykros Ring. The Rykros Ring also carries with it the following
stats: MTL +3, AGI +3, DEF +20, MDEF +10.

Equipment Randomization/Buffs:
There are a few options you can select for items that are pretty straight forward. "Laser Barrier casts Barrier" and "Cyber-Suit casts Vision" are exactly as they
sound. Using them as an item in battle will give a flat buff with a strength similar to that of the Swift Helm, Power Shield, and Mahlay Dagger. Selecting
"Buff Items Multi-Target" will take the Swift Helm, Mahlay Shield, Laser Barrier, and Cyber-Suit (if selected) to target all allies in battle. There is a graphical
bug with this that will not show the animation over all allies when used, but it does work. Also, this does not affect the Power Shield since its technique
equivilant is also single-target.

"Randomize Equipment Prices" also does exactly what it sounds like. Each piece of equipment has a random price attached to it. It is possible for stronger items
to be cheaper than weaker pieces. Consumable items are still priced as normal.

"Randomize Weapon Set Elements" is a bit trickier to explain. Each weapon has their attack element randomized, but it is worth noting that all weapons are divided into
certain "sets" that all have the same element. For instance, Titanium Weapons will all have the same element, as will Ceramic weapons. The sets and the weapons are as
follows:

-Set 1: Alis' Sword, Boomerang, Dagger, Wood Cane
-Set 2: Hunting Knife, Steel Sword, Slasher, Claw, Impacter
-Set 3: Titanium Sword/Slasher/Dagger/Axe, Stun Shot
-Set 4: Ceramic Sword/Knife, Saber Claw, Broad Axe, Struggle Axe
-Set 5: Laser Sword/Slasher/Knife/Claw/Axe, Wave Shot, Pulse Laser, Force Cane
-Set 6: Plasma Sword/Dagger/Rifle/Claw/Launcher, Silver Rod
-Set 7: Laconia Sword/Slasher/Dagger/Rod/Claw/Axe, Pulse Vulcan
-Set 8: Guardian Sword/Rod/Claw, Photon Eraser
-Set 9: Genocyde Claw, Sonic Buster, Shadow Blade, Moon Slasher, Mahlay Dagger, Defeat Axe
-Set 10: Elsydeon, Silver Tusk, Psycho Wand

Enemy Randomization and Customization:
There are different ways to randomize an enemy in this randomizer. Selecting "Randomize Element Strengths" will randomize what element each enemy is weak to or strong
against. Due to the possibility of complete damage immunity, I have decided that no enemy will have complete immunity to damage, so the strongest they could be against any
element would be to reduce the damage by 50%. Due to this, however, three enemies had to have their HP values changed. Haunt goes from 3 HP to 100 HP, Dimensworm goes
from 4 HP to 200 HP, and Outerbeast goes from 6 HP to 300 HP. "Randomize Status Strengths" randomizes each enemy's resistances to debuffs and status effects. This
includes bosses as well, making your status techniques and skills much more useful. "Randomized Insta-death Strengths" randomizes each enemy's resistances to instant
death abilities. This also holds true for bosses, meaning that they possibly can be killed in one shot. With this option, both Spark and Hijammer are no longer exclusive
to mechanical enemies and can work on enemies regardless of type.

There are also three slider bars that will change an Enemy's HP and how much Meseta and Experience they drop. You can set each of them so that all enemies have
50%, 150%, 100%, or 200% of their original values. If on the slider, you choose ???%, it will randomizes the value of each individual enemy between 50%, 100%, 150%, and 
200%. For instance, one enemy could have twice as much HP and then the next could have half as much. 

The only enemy immune to these changes is Zio 1 (the unbeatable one in Zio's Fort). This is because actually beating him crashes the game.

4. Known Issues

Item Buffs Multi-Target:
As noted above, there is a small, non-breaking graphical bug with this option selected where the animation will only appear over one character. All characters will show
up on the screen, noting that they are being targeted. They are being buffed properly, but it's just something that can't be fixed.

Text Skipping in the Air Castle:
As noted above, entering the room with the Eclipse Torch chest will automatically start the fight with the Specter and then continue onto Lashiec. Normally you have to open the chest
with the fake Eclipse Torch first in order to start the fights. 

5. Thanks

Thanks and shoutouts to the Phantasy Star IV speedrunning community for inspiring me to work on this randomizer and those who have offered to test the program out. These include but
are not limited to: Jencey86, KillerSPER, Zexerousheroes, kiaten619, TylertheDriver, Jiseed, and Bichphuongballs.

Big thanks to Lory_90 for contributing all of the information needed to allow for Text Skipping.

Huge thanks to Serria for putting up with me working on this Randomizer for months now.