`Altium Database Libraries for Würth Elektronik Products`
=========
## Component Classification
* WE - Electromechanical Components<br>
  * Assembly
  * Connectors
  * REDCUBE Terminals
  * Switches

* WE - Optoelectronic Components
  * 7 Segments Display
  * Infrared
  * Laser
  * LEDs
  * Optocoupler
  * Ultraviolet

* WE - Passive Components
  * Capacitors
  * EMC Components
  * Power Magnetics
  * Signal & Communications
  * Resistors
  * Quartz Crystals & Oscillators


* WE - Power Modules
  * LED Driver
  * Step Down Converter
  * Isolated Converter


## How to use the DB Lib in Altium
Go to component panel and install the DB library as the way of integrated library installation.
![](https://github.com/bjch-eisos/Pics/blob/main/ComponentPanel.png)<br>


## Mechanical Layer Definition
![](https://github.com/bjch-eisos/Pics/blob/main/MechanicalLayer.png)<br>
* Assembly Outline (M11 paired with M12)<br>
 0.1mm line thickness<br>
 exact component contour<br>
 including a .Designator text string in the footprint center<br>
* 3D Body (M13 paired with M14)<br>
0.1mm line thickness<br>
exact component contour and embedded 3D model<br>
* Component Courtyard (M15 paired with M16)<br>
0.05mm line thickness<br>
min. 0.2mm distance from silk lines<br>
min. 0.2mm distance from line center to pad edges<br>
including a cross mark in the origin<br>
* Milling (M8)
* V-Cut (M9)
* Notes (M2)
* Silkscreen
0.2mm line thickness<br>
component contour based on the maximum dimensions<br>
min. 0.2mm clearance from pads<br>
min 0.1mm distance from assembly outlines<br>
polarity mark<br>


## Troubleshooting
#### No Components or Connection Error<br>  
![](https://github.com/bjch-eisos/Pics/blob/main/ErrorMessageAltium.png)<br>
How to fix this issue:<br>
1, For Altium Designer 17 and older: Download and install [MSSQL Native Client 32 Bit](https://go.microsoft.com/fwlink/?LinkID=239647&clcid=0x409)  <br>
2, For Altium Designer 18 and newer: Download and install [MSSQL Native Client 64 Bit](https://go.microsoft.com/fwlink/?LinkID=239648&clcid=0x409)  <br>
