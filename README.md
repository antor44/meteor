# Meteor
MSX Basic game, a clone of Lunar Rescue.

Meteor is a free MSX Basic game, developed with default Basic without inserting machine code.

How to play: The player controls a ship, which must land on some rocks, then return to the mother ship. Additional ships every 1000 points.


Repository for downloads:
https://github.com/antor44/meteor

Requirements:

-MSX 1/2/2+ Europe or USA BIOS

-Or OpenMSX emulator with Basic ROM

-Or WebMSX:  https://webmsx.org/


For MSX turbo R Europe or USA BIOS add this Basic line:

5 DEFUSR=39+PEEK(-2385)+PEEK(-2384)*256:IFUSR(0)THENLINE>0COPY0&H80F6OR384ALLYOURBASEAREBELONGTOUS!
