# SuperCard DSOne Manual/Setup Guide

## Initial Setup

##### [Download the DSOne-SDHC Evolution kernel](http://flashcard-archive.ds-homebrew.com/SuperCard/DSONE_SDHC_DSONEi/SuperCard_DSONE_SDHC_EOS_sp6_20121206.zip)

1.  Confirm your card is formatted to fat32. If you're on Windows and using a 64GB SD, you can use [guiformat](http://ridgecrop.co.uk/index.htm?guiformat.htm) to do this.
2. Unzip the files in the kernel zip, and copy them to the root of the sd card.

## Further Setup - (Cheats)

The Evolution kernel has support for cheats, but doesn't come with any cheats included by default. They needed to be added manually in the form of a usrcheat.dat file. If you don't care about cheats you can skip this part of setup.

1. One of the most up-to-date usrcheat.dat's can be [found here.](https://bitbucket.org/DeadSkullzJr/nds-i-cheat-databases/src/master/Cheat%20Databases/)

2. After you have download the usrcheat.dat file, copy it to the `_dsone` directory on your DSOne's SD card.

## EOS Options (Home Menu)

### SD Speed

<img style="float: left; margin-right: 30px;" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-SD-Speed.jpg" width="260px">

Sets the speed of the SD card. It is recommended to use a value above 3x on modern cards to avoid issues with running games, as the 3x value can cause problems according to the Supercard FAQ:

> "Some games need a high speed flash memory card, such as "Castlevania PoR", this game need a high speed memory card and Speed need to be set to 4X."

If you experience a white screen after increasing the SD speed, that means your card is too slow for that speed. Decrease the sd speed setting step-by-step until games load.

### Run Mode

<img style="float: left; margin-right: 30px;" src="https://raw.githubusercontent.com/Sanrax/DSOneManual/main/Pictures/DSOne-Patch.jpg" width="260px">

Switch between applying patches for games when running them or run them as is.

This setting should be left on patch to avoid issues with anti-piracy measures and games not booting.
