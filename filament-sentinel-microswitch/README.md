## filament-sentinel-microswitch ##
This small board interconnects two increadibly helpful products for 3d-printers:
- Dyze Design Filament Sentinel
- Duet3D Filament Monitor *

<small>* _should work with both the laser as well as the rotating magnet version. tested with the rotating magnet version only (test-reports using the laser version welcome!)_</small>


### Usage ###
1. Connect +3.3V, +5V and GND to the Power-Connector (X4) on the board
2. Connect the Filament Sentinel directly to the board using the Connector labelled with "Filament Sentinel" (X1)
3. Connect either of the 2-pin Connectors labelled "NO" and "NC" (X2/X3) to the Microswitch-Input labelled "SW" on the Duet3D Filament Monitor (you will probably want to go with the "NC"-Output)

The board will pass the Signal from the Filament Sentinel on to the Duet3D Filament Monitor and behave like a simple Microswitch to the Filament Monitor.


#### Side-Notes ####
* Since my 3d-printer is built using Aluminium Linear Extrusion Rails from OpenBuilds, the dimensions and mounting holes are chosen to fit those.
* I am aware that having a Duet3D Filament Monitor along side the Filament Sentinel makes the latter in most situations kind of unneccessary. However, I had both of them available and wanted to use them both - (overall: why not?!)
