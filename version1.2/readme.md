# This new release fixes a few things:

* Adjusted Zorro slots ½ mm to the left.
* Video connector, less wide at bottom.
* Changed Molex connector to a floppy type.
* Changed entire board to make it 4 Layer instead of 2 layers and routed it again.
* Bottom connectors are now rounded so they can fit nicely on the onboard connectors.
* Added a breakout part than can be removed in case more space for cables needed.
* Add an external clock footprint to in case main clock must be different from the onboard clock. This can be enable or disabled by setting a jumper on place. Usefull for boards like videotoaster.
* Added the /C1 signal on the VGA connector (pin 16) in case a future S-VIDEO/Composite hat is developed. (thx. to Chucky for the tip).

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


# PCB order info (to setup on your favorite PCB fabricator).

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

# BOM

# Bill of materials
| Part          | Value                   | Package                        |
| ------------- | ----------------------- | ------------------------------ |          
| C1            | 100NF                   | 1206                           |
| C3            | 100NF                   | 1206                           |
| C5            | 100NF                   | 1206                           |
| C559          | 220uf/16v               | E2,5-7                         |
| C600          | 220uf/16v               | E2,5-7                         |
| C601          | 220uf/16v               | E2,5-7                         |
| C602          | 220uf/16v               | E2,5-7                         |
| CN6           | 2-5530843-2 in half     | SLOTVIDEO                      |
| CN600         | 2-5530843-2             | SLOT_100                       |
| CN601         | 2-5530843-2             | SLOT_100                       |
| CN602         | 2-5530843-2             | SLOT_100                       |
| CN603         | 2-5530843-2             | SLOT_100                       |
| CN621/CN622   | 2-5530843-2 in half     | SLOTVIDEO                      |
| FB1           | 2512061517Y3            | FB1206                         |
| H1            | 2X8                     | 2X8                            |
| IC1           | 7407D                   | SO14                           |
| IC3           | 74HCT32D                | SO14                           |
| IC5           | 74LS08D                 | SO14                           |
| EXTRAPWR      | 22-27-2041-04           | 22-27-2041-04                  |
| R1            | 100                     | 1206                           |
| R601          | 470                     | 1206                           |
| R603          | 470                     | 1206                           |
| R600          | 1k                      | 1206                           |
| R602          | 1k                      | 1206                           |
| R605          | 1k                      | 1206                           |
| R606          | 1k                      | 1206                           |
| R607          | 1k                      | 1206                           |
| R608          | 1k                      | 1206                           |
| R610          | 1k                      | 1206                           |
| RP602         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP603         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP604         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP605         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP606         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP607         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| RP608         | 4610X-104-221/331LF     | RESISTOR_ARRAY_10              |
| ENABLE        | JUMPER                  | 1X02                           |
| EXTERNALXCLK  | EXTERNALCLOCK           | DIL14S                         |

# Feedback

If you find any error on this description, please drop me an email to info@arananet.net.
