Defender for the Tandy Colour Computer 3 with 512k of RAM

* Important *
Once you're done playing Defender don't turn off your CoCo.  To save your settings and scores while still in the game press BREAK and
the game will exit back to BASIC but the scores and other data are still in RAM.  To save it to disk for future use type:
RUN"SAVE [ENTER]

To start playing a game simply type:
RUN"DEFENDER [ENTER]

Controls for the game are the same as MAME:
Insert a coin - 5
Start a one player game - 1
Start a two player game - 2


To configure Defender for your CoCo setup type:
RUN"CONFIG [ENTER]

From there you can change:
1) Monitor type
2) Number of lives which also gives you a smart bomb for each live you start with
3) Difficulty level
4) Configure which keys to use for the game
5) When the game starts Defender shows a Rug pattern while doing a memory test, you can enable or disable seeing this
6) Number of Disk drives you have on your CoCo setup, if you have two or more drives put Disk2 in the 2nd drive otherwise select One drive and you will have to swap disks while the game loads

If you press the spacebar you can also reset the high scores and other game collecting info.

Once you're happy with your settings press ENTER.  It will save the settings and start loading the game.

From that point on as long as you're happy with the settings then you can load the game byte typing:
RUN"DEFENDER [ENTER]

If you're using the disk images on a CoCo SDC the easiest way to setup the game is to copy the DISK1.DSK and DISK2.DSK to the SD Card and once you start the CoCo type:
DRIVE0,"DISK1 [ENTER]
DRIVE1,"DISK2 [ENTER]
RUN"CONFIG [ENTER]

Make sure to change option 6 to # OF DRIVES TWO OR MORE

There's currently a bug in MAME that should be fixed in the next release, thanks to Tim Lindner.  The bug in MAME is that it won't exit back to BASIC when you hit the BREAK key, it just gives you a green screen.
The current version 0.235 and has the bug.  The next version which tends to come out at the end/start of each month should be 0.236 and it will include the fix.
I've compiled version 0.235 with Tim's fix and it does work.

I’d like to thank Einar Saukas for his cool ZX0 compressor and Doug Masten for porting the decompressor code to 6809 assembly and sharing it for us all to use.

Enjoy Defender on the CoCo 3,
Glen Hewlett
