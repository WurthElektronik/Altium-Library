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
* Component Outline (M11 paired with M12)<br>
 0.1mm line thickness<br>
 exact component contour<br><br>
 * Designator (M3 paired with M4)<br>
 including a .Designator text string in the footprint center<br><br>
* 3D Body (M13 paired with M14)<br>
embedded step model<br><br>
* Component Courtyard (M15 paired with M16)<br>
0.05mm line thickness<br>
min. 0.2mm distance from silk lines<br>
min. 0.2mm distance from line center to pad edges<br>
* Component Center (M17 paired with M18)<br>
including a cross mark in the origin<br>
(available for the PCB libraries release since 6th June 2023)<br>

* Assembly Notes (M2)<br>

* V-Cut (M9)<br><br>

* Silkscreen<br>
0.2mm line thickness<br>
component contour based on the maximum dimensions<br>
min. 0.2mm clearance from pads<br>
min 0.1mm distance from assembly outlines<br>
polarity mark<br>


## Troubleshooting
#### No Components or Connection Error<br>  
![](https://github.com/bjch-eisos/Pics/blob/main/ErrorMessageAltium.png)<br>
How to fix this issue:<br>
[Using Database Libraries with 32-bit and 64-bit Altium Design Software on the same Computer](https://www.altium.com/documentation/altium-designer/using-database-libraries-with-32-64-bit-altium-design-software-same-computer)  <br>

