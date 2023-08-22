# CMIOBoard
A tiny, compact IO board for the raspberry compute modules 1/3/3+

![Top View](Images/BoardRender.png)

## Features:
IO Ports:  
* USB-C (Power/USB 2.0)
* HDMI
* USB-Micro B (Slave port)
* Dual-USB-A 2.0
* Ethernet

## Other:
* Three pin 5V fan header
* Three pin boot selector
* 40 pin standard Raspberry Pi GPIO
* 4x2.2mm mounting holes
* Power LED (Red)
* Boot LED (Green)

## Dimensions:
75.66mm x 65.63mm  
2.844mm radius rounded corners
2.2mm diameter mounting holes (M2 or US #1/2 screws)  
69.97mm center distance between horizontally aligned mounting holes.  
59.94mm center distance between vertically aligned mounting holes.  
## Important!
The Raspberry Pi Compute Module requires a 5v, 2+ Amp power supply. (5.1V Recommended)
This board was made by a complete amatuer and should be avoided or subject to harsh scrutiny before used in a real application.

## Directions to Install:
1. Make sure your KiCAD verison is 7.0.6 or higher
2. Rename the "Footprints" folder to "Footprints.pretty"
3. Open the "RPCM1 IO Board.kicad_pro" file
4. Add symbols and footprints from this directory into the "Project Specific Libraries" section of the Symbol Library Manager and the Footprint Library Manager
5. Do whatever you want I guess :)

*License: GNU General Public License v3.0*  
*[gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)*
