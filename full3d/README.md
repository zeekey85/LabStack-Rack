# 3D-Printed Printing and Assembly Instructions

## Slicer Configuration and Info
* All models are saved in the correct orientation to the build plate.  You can rotate the part, but do not change the side that touches the bed!
* NONE of the models require supports.  Turn supports off in your slicer for these models.
* Recommended Slicing Settings:
	* Layer Height: 0.2mm
	* Perimeters: 4
	* Top/Bottom Layers: 5
	* Infill: 40%
* To help prevent part warping, please wait until the bed has fully cooled before removing the part from the bed! (This goes double for the full-width parts!)

## Short Model Info and Assembly
* Choose your specific configuration from the STL files in the list, and import into your slicer.
	* Short models will be listed with "Short" in their title.
	* Files listed as "Left Mount" will mount on the left half of the rack.  Files listed as "Right Mount" will mount on the right half of the rack.
### Assembly
1. Unscrew the 2x Phillips head screws from the top of the JetKVM module, and slide the module into the 3D-printed housing until the screw holes in the printed part align with the holes in the JetKVM device.
2. Install 2x M2x16mm SHCS machine screws (per module) thru the printed part and into the JetKVM module.  Snug the screws using an Allen Key of the correct size.
3. Connect cables to the JetKVM device, and install JetKVM into rack.
	* Be careful when screwing the printed mount into your server/network rack, and take care not to tighten the rack screws too tight!

![Image](../images/full3dprintedassembled.png)

## Full-Width Model Info and Assembly
* You will need one "Left" and one "Right" option for a full-width 1U mount.
	* Pick one of the 3 module options for each side: 1x Module, 2x Module, Blank
		* 1x Module Left + Blank Module Right = 1x JetKVM module on the left side of the rackmount.
		* 2x Module Left + 1x Module Right = 3x JetKVM modules total, with 2 on the left side and one on the right side of the rackmount.
		* 1x Blank Module Left + 1x Blank Module Right = Full Blanking panel with a JetKVM logo...  Not useful for mounting JetKVM devices, but useful as a blanking plate!
* You will need a printed brace to join the Left and Right halves.  The brace is in the STL folder, and is just called "Brace".

### Assembly
1. Install 3x heatset inserts into each of the Left and Right halves, 6x in total, with a soldering iron (and heatset insert tip, if available).
2. Install the Brace over the two halves of the 1U rackmount.
3. Insert 6x M3x10 SHCS machine screws into the base and tighten down.  NOTE: The screws will start to feel tight before bottoming; continue to screw in until tight!  This acts as a lock washer inside the printed part.
4. Unscrew the 2x Phillips head screws from the top of the JetKVM module, and slide the module into the 3D-printed housing until the screw holes in the printed part align with the holes in the JetKVM device.
5. Install 2x M2x16mm SHCS machine screws (per module) thru the printed part and into the JetKVM module.  Snug the screws using an Allen Key of the correct size.
6. Connect cables to the JetKVM device, and install JetKVM into rack.
	* Be careful when screwing the printed mount into your server/network rack, and take care not to tighten the rack screws too tight!

![Image](../images/full3dprintedfullwidthheatset.png)
![Image](../images/full3dprintedbraceinstalled.png)
![Image](../images/full3dprintedfullwidthassembled.png)