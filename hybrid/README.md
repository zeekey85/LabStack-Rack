# Hybrid Aluminum / 3D-Printed Printing and Assembly Instructions

## 3D-Printed Parts Slicer Configuration and Info
* The mount model is saved in the correct orientation to the build plate.  You can rotate the part, but do not change the side that touches the bed!
* The mount model does NOT require supports.  Turn supports off in your slicer.
* Recommanded Slicing Settings:
	* Layer Height: 0.2mm
	* Perimeters: 4
	* Top/Bottom Layers: 5
	* Infill: 40%

## Aluminum Part Info and Configuration
* The DXF files for each configuration option are located in the DXF folder.
* You will need to upload ONE of the DXF files to SendCutSend or similar vendor to have laser cut.
	* Both "Short" models, and full-width 1U options are available.
	* All versions are able to be used in either "Left" or "Right" mount configurations (mirrorable).
* Recommended Options (for SendCutSend, specifically):
	* Measurement Units: mm (millimeter)
	* Material Type: 5052 H32 Aluminum
	* Material Thickness: 0.125" (3.2mm)
	* Services: None
	* Finishing:
		* Full 1U Width - Deburring
		* 1 or 2 Module Short - Tumbling (will lose the brushed finish, but will be smooth; deburring not avaialble on parts this small)

## 3D-Printed Part Info and Assembly
* Print as many of the "1x Module Hybrid" file in the STL folder as needed for the total number of JetKVM modules in use (1-6 total).
### Assembly
1. Install 2x heatset inserts into each of the module mount, up to 12x in total, with a soldering iron (and heatset insert tip, if available).
2. Unscrew the 2x Phillips head screws from the top of the JetKVM module, and slide the module into the 3D-printed housing until the screw holes in the printed part align with the holes in the JetKVM device.
3. Install 2x M2x16mm SHCS machine screws (per module) thru the printed part and into the JetKVM module.  Snug the screws using an Allen Key of the correct size.
4. Slide the JetKVM assembly into the laser-cut aluminum front panel and line up the holes in the panel with the heatsets in the printed part.
5. Install 2x M3x8mm BHCS machine screws (per module) thru the aluminum front panel and into the heatset in the printed part.  Snug screws using an Allen Key of the correct size.
6. Connect cables to the JetKVM device, and install JetKVM into rack.

![Image](../images/hybridparts.png)
![Image](../images/hybridpartialassembly.png)
![Image](../images/hybridpartialassembly2.png)
![Image](../images/hybridpassembled.png)