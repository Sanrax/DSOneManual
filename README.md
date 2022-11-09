# SuperCard DSOne Manual/Setup Guide

## Initial Setup

##### [Download the DSOne-SDHC Evolution kernel](http://flashcard-archive.ds-homebrew.com/SuperCard/DSONE_SDHC_DSONEi/SuperCard_DSONE_SDHC_EOS_sp6_20121206.zip)

1.  Confirm your card is formatted to fat32. If you're on Windows and using a 64GB SD, you can use [guiformat](http://ridgecrop.co.uk/index.htm?guiformat.htm) to do this.
2. Unzip the files in the kernel zip, and copy them to the root of the sd card.

## Further Setup - (Cheats)

The Evolution kernel has support for cheats, but doesn't come with any cheats included by default. They needed to be added manually in the form of a usrcheat.dat file. If you don't care about cheats you can skip this part of setup.

1. One of the most up-to-date cheat databases can be [found here.](https://bitbucket.org/DeadSkullzJr/nds-i-cheat-databases/src/master/Cheat%20Databases/) Download the usrcheat.dat file.

2. After you have downloaded the usrcheat file, copy it to the `_dsone` directory on your DSOne's SD card.

## EOS Options (Home Menu)

### SD Speed

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-SD-Speed.jpg" width="260px">

Sets the speed of the SD card. It is recommended to use a value above 3x on modern cards to avoid issues with running games, as the 3x value can cause problems according to the Supercard FAQ:

> "Some games need a high speed flash memory card, such as "Castlevania PoR", this game need a high speed memory card and Speed need to be set to 4X."

If you experience a white screen after increasing the SD speed, that means your card is too slow for that speed. Decrease the sd speed setting step-by-step until games load.

### Run Mode

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Patch.jpg" width="260px">

Switch between applying patches for games when running them or run them as is.

This setting should be left on patch to avoid issues with anti-piracy measures and games not booting.

### Languages

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Lang.jpg" width="260px">

Fairly self-explanatory, this option changes the language of the menu.

### Brightness

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Brightness.jpg" width="260px">

Changes the screen brightness level of the DS. However, it only applies to the DS Lite and OG DS. It does nothing on DSi and 3DS.

### Multi-Saver

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Saves.jpg" width="260px">

This is for swapping save slots using the DSOne's multi-save ability. It allows you to have 4 separate save files per game. The default save slot is #0. #1 - #3 are the extra slots if you'd like to have more than one save. Just switch to that slot and run the game to use the associated save file.

### Theme

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Skins.jpg" width="260px">

Changes the menu theme. If you found a theme you want to add, you can put it on the sd card and select it from this menu.

### Hotkeys

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Hotkeys.jpg" width="260px">

Settings for the in-game menu button combo. The buttons that are checked in this menu all need to be pressed simultaneously while running a game to bring up the menu. You can configure what button combo you'd like to use by toggling the checkmarks next to each button. Hit A to save, B to cancel changes.

### GBA Extend

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-GBA.jpg" width="260px">

Options for GBA Slot-2 carts, for DS Lite and original NDS systems.
