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
  * Crystals & Oscillators
  * EMC & RFI Components
  * Inductors
  * Resistors
  * Signal & Communications
  * Transformers


* WE - Power Modules
  * LED Driver
  * Step Down Converter
  * Isolated Converter


## How to use the DB Lib in Altium
Go to component panel and install the DB library as the way of integrated library installation.
![](https://github.com/bjch-eisos/Pics/blob/main/ComponentPanel.png)<br>


## Mechanical Layer Definition
![](https://github.com/bjch-eisos/Pics/blob/main/MechanicalLayer.png)<br>
* Assembly (M9 paired with M10)<br>
 0.1 mm line width<br>
 maximum component contour<br>
* Designator (M11 paired with M12)<br>
  contains a .Designator text string in the footprint center<br>
 font type: Stroke, Sans Serif, stroke width 0.1 mm, text height 1 mm, justification: center; center<br>
* 3D Body (M13 paired with M14)<br>
embedded 3D model<br>
exact component contour, line width 0.1 mm<br>
* Component Courtyard (M15 paired with M16)<br>
0.05 mm line width<br>
minimum 0.2 mm distance from line center to Assembly line center<br>
minimum 0.2 mm distance from line center to pad edges<br>
* Component Center (M17 paired with M18)<br>
contains a cross mark in the origin<br>
line length 1 mm, line width 0.1 mm<br>


* Board Shape (M1)<br>
* V-Cut (M6)<br>
* Assembly Notes (M8)<br>


* Silkscreen<br>
0.2 mm line width<br>
maximum component contour<br>
minimum 0.2 mm clearance from line edge to pad edge<br>
minimum 0.1 mm distance from line center to Assembly line center<br>
may contain polarity mark<br>


## Troubleshooting
#### No Components or Connection Error<br>  
![](https://github.com/bjch-eisos/Pics/blob/main/ErrorMessageAltium.png)<br>
How to fix this issue:<br>
[Using Database Libraries with 32-bit and 64-bit Altium Design Software on the same Computer](https://www.altium.com/documentation/altium-designer/using-database-libraries-with-32-64-bit-altium-design-software-same-computer)  <br>

