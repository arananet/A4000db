# A4000DB

This is a recreation of the Amiga 4000 DaughterBoard. I have made it from ground using the A4000 original schematics. It includes all the Zorro slots and also include a VGA 15khz output connector to use with a VGA metal bracket. The ISA ports has been removed from the design. Some new options has beed added on the new version 1.2.

This work great on all the Amiga 4000 revisions, except of course the A4000T.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

I will try to add more features to this DB when I can. The idea is to have a good DB replacement or a better one if you don't have any.

Note: For the videoslot you need to dremel a 100 pin connector in half in order to put it on place.

#### Gerbers are separated in two version / folders:  

#### Version 1.2 fixes a few mistakes and improves others.

* Adjusted Zorro slots ½ mm to the left.
* Video connector, less wide at bottom.
* Changed Molex connector to a floppy type.
* Changed entire board to make it 4 Layer instead of 2 layers and routed it again.
* Bottom connectors are now rounded so they can fit nicely on the onboard connectors.
* Added a breakout part than can be removed in case more space for cables needed.
* Add an external clock footprint to in case main clock must be different from the onboard clock. This can be enable or disabled by setting a jumper on place. Usefull for boards like videotoaster.
* Added the /C1 signal on the VGA connector (pin 16) in case a future S-VIDEO/Composite hat is developed. (thx. to Chucky for the tip).  

## BOM is inside the version 1.2 folder.

#### Version 1.1 is the first release of the board.

Update 27/12/2018: Some users have found a little of difficulty to plug large boards like CV3D or Fastlane using the Daughterboard. An easy fix is to remove the plastic guides from the front of the a4000 (those brown ones) on the slots that is gonna be used for the large boards. The zorro slots are displaced like ½mm to the right and must go to the left.

# PCB order info for version 1.2 (to setup on your favorite PCB fabricator).

Dimensions :	102 x 302 mm  
Layers :	4 layers  
Layer order: GTL, G1, G2, GBL  
Finished Copper :	1 oz Cu  
PCB Kinds:	2 (because the breakable area)  
Track/Spacing:	6/6mil  
Blind/Buried Via:	No  
Material :	Normal FR-4 Board TG150  
Thickness :	1.6 mm  
Solder Mask :	Whatever color you want :)  
Silkscreen :	Whatever color you want :)  
Surface Finish :	Immersion gold (recommended)  
Hole Size :	0.4  
Golden Finger Beveling:	Yes  

# Images

V1.2  

<img src="https://github.com/arananet/A4000db/blob/master/img/v2top.png?raw=true" width="700"/>
<img src="https://github.com/arananet/A4000db/blob/master/img/v2bottom.png?raw=true" width="700"/>

V1.1  

<img src="https://github.com/arananet/A4000db/blob/master/img/1.png?raw=true" width="700"/>
<img src="https://github.com/arananet/A4000db/blob/master/img/2.png?raw=true" width="700"/>

# Vga bracket

<img src="https://github.com/arananet/A4000db/blob/master/img/vgabracket.jpg?raw=true?raw=true" width="400"/>

https://www.ebay.de/itm/original-Asus-Slotblech-VGA-FLATKabel-15P-TO-16P-P-N-14001-00450000/201663185333 

# VGA pinout (Starting from right to left):

| TOP PINROW    | BOTTOM PINROW |
| ------------- | ------------- |
| 1 RED         | 2 GREEN       |
| 3 BLUE        | 4 NC          |
| 5 NC          | 6 GND         |
| 7 GND         | 8 GND         |
| 9 NC          | 10 GND        |
| 11 NC         | 12 NC         |
| 13 HSYNC      | 14 VSYNC      |
| 15 NC         | 16 /C1        |

# Updates

12/11/2019: Updated license stuff (I usually not do this but I must start it with this).

09/01/2019 Release of the second version of the DB.

27/12/2018 Notes updated about using large boards.

21/08/2018 Initial release.

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Feedback

If you find any error on this description, please drop me an email to info@arananet.net or you could also buy me a beer :p
