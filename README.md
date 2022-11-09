# SuperCard DSOne Manual/Setup Guide

## Initial Setup

##### [Download the DSOne-SDHC Evolution kernel](http://flashcard-archive.ds-homebrew.com/SuperCard/DSONE_SDHC_DSONEi/SuperCard_DSONE_SDHC_EOS_sp6_20121206.zip)

1.  Confirm your card is formatted to fat32. If you're on Windows and using a 64GB or above MicroSD card, you can use [guiformat](http://ridgecrop.co.uk/index.htm?guiformat.htm) to do this.
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

Options for GBA Slot-2 carts, when running on DS Lite and original NDS systems. Rumble option is for use with the Rumble Pak or SuperCard Mini SD Rumble Slot-2 flashcart to provide force-feedback.

## EOS Options (Per-Game Settings)

### Game Options Menu

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Game-Options.jpg" width="260px">

This menu can be accessed by highlighting a game with the dpad, and then hitting the Y button. It allows you to override the global options set in the EOS home menu on a per-game basis. For example, if your saver slot is currently set to slot #0 in the home menu but you want specifically GTA Chinatown Wars to load the Slot #1 save, you can set that here without affecting other games. If cheats are turned off globally, they can be turned on for specific games in this menu.

The saver size can be modified for each game in this menu as well, but is generally unneccessary as the EOS kernel already knows the correct save size for practically all retail roms and will set this option automatically.

Anti-piracy patching should be left on at all times as discussed earlier to avoid gameplay issues.

### Cheats Sub-Menu

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Cheats.jpg" width="260px">

The cheats configuration is accessed by entering the game options menu discussed above, and then hitting Y again or using the stylus to click the cheats button. Note that this requires the **Further Setup (Cheats)** step to be completed, since no cheats will be available without a usrcheat database.

Here you can select what cheats you want to be available once the game is loaded with cheats turned on. Simply put checkmarks next to each cheat you want enabled.

### In-Game Menu

<img style="left" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-InGame-Menu.jpg" width="260px">
