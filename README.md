# Midi Fighter Twister - Open Source Firmware

## Compilation

### How to build using Microchip Studio (Windows-only)
You need Microchip Studio which can be downloaded [here](https://www.microchip.com/en-us/tools-resources/develop/microchip-studio)

1. Inside Micropchip Studio, open the *Midi_Fighter_Twister.atsln* solution
1. Select the desired configuration (*Debug* or *Release*)
1. Build the solution via *Build > Build Solution*

The resulting *Midi_Fighter_Twister.hex* file now can be found in the respective *Debug* or *Release* target directory

## Installation
You need the Midi Fighter Utility which can be downloaded [here](https://store.djtechtools.com/pages/midi-fighter-utility)
1. Connect the Midi Fighter Twister to your computer directly (DO NOT USE A USB HUB!)
1. Launch the Midifighter Utility software which should automatically detect the connected device. (If not, make sure that no other software is currently using the Midifighter Twister!)
1. *Tools > Midifighter > Load Custom Firmware > For a Twister*
1. Navigate to the *Midi_Fighter_Twister.hex* file and open it
1. Choose "Yes" to proceed
1. Wait until the firmware update process is completed
