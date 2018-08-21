# A4000DB

This is a recreation of the Amiga 4000 Daughter Board made from ground using the A4000 original schematics. It includes all the Zorro slots and also include a VGA 15khz output connector to use with a VGA metal bracket. The ISA ports has been removed from the design.

This work great on all the Amiga 4000 versions, except of course the A4000T.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

I will try to add more features to this DB when I can. The idea is to have a good DB replacement or a better one if you don't have any.

Gerbers are on the gerbers folder. Remember to say to your favorite pcb service that is a good recommendation to make bevel cut on the edge connectors (knows as 45º chamfered border)

Important! If you like this project, buy me a beer or a Mercedes Benz SLR whatever you want :) - info@arananet.net

# Images

<img src="https://github.com/arananet/A4000db/blob/master/img/1.png?raw=true" width="700"/>
<img src="https://github.com/arananet/A4000db/blob/master/img/2.png?raw=true" width="700"/>

# Vga bracket

<img src="https://github.com/arananet/A4000db/blob/master/img/vgabracket.jpg?raw=true?raw=true" width="700"/>

# Updates
21/08/2018 Initial release.

# Bill of materials
| Part          | Value                   | Package                        |
| ------------- | ----------------------- | ------------------------------ |          
| C1            | 100NF                   | 1206                           |
| C3            | 100NF                   | 1206                           |
| C5            | 100NF                   | 1206                           |
| C600          | 220uf/16v               | E2,5-7                         |
| C601          | 220uf/16v               | E2,5-7                         |
| C602          | 220uf/16v               | E2,5-7                         |
| CN6           | 2-5530843-2 in half     | SLOTVIDEO                      |
| CN600         | 2-5530843-2             | SLOT_100                       |
| CN601         | 2-5530843-2             | SLOT_100                       |
| CN602         | 2-5530843-2             | SLOT_100                       |
| CN603         | 2-5530843-2             | SLOT_100                       |
| CN621/CN622   | 2-5530843-2 in half     | SLOTVIDEO                      |
| FAN           | 1X2                     | 1X2                            |
| FB1           | 2512061517Y3            | FB1206                         |
| H1            | 2X8                     | 2X8                            |
| IC1           | 7407D                   | SO14                           |
| IC3           | 74HCT32D                | SO14                           |
| IC5           | 74LS08D                 | SO14                           |
| J2            | 15-24-4441              | 15-24-4441                     |
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

Note: For the videoslot you need to dremel a 100 pin connector in half in order to put it on place.
