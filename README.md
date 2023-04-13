# 5TEN KiCAD Toolkit
## Features
1.	Generates gerber files in correct format for production
2.	Generates BOM file in correct format for production
3.	Generates Pick and Place file in correct format for assembly
4.	Generates IPC netlist file

## Installation

### Manual installation
Download the [latest release](https://github.com/bennymeg/JLC-Plugin-for-KiCad/releases) ZIP file. Open the "Plugin and Content Manager" from the KiCads main window and install the ZIP file via "Install from File".

## Usage
Click on the Fabrication Toolkit <img src="https://github.com/bennymeg/JLC-Plugin-for-KiCad/blob/master/resources/icon.png?raw=true" style="magin-bottom: 8px;" alt="Logo" height=24> button on the top tool box inside KiCad pcb editor (pcbnew).

## Options


### Ignore Footprint in Production Files
Select 'Exclude from board' or 'Exclude from BOM' in the symbol's attributes property in order to ignore the footprint from the relevant file.

<img src="https://github.com/bennymeg/JLC-Plugin-for-KiCad/blob/master/assets/attributes.png?raw=true" height=420>

Select 'Exclude from position files' or 'Exclude from BOM' in the footprint's fabrication attributes property in order to ignore the footprint from the relevant file.

<img src="https://github.com/bennymeg/JLC-Plugin-for-KiCad/blob/master/assets/fabrication.png?raw=true" height=505>

### Offset Component Position
The position of components in KiCad Footprints does not always match the orientation in the JLC library because KiCad and JLCPB used different variation of the same standard. To the exception cases: add an 'JLC Position Offset' field with an comma seperated x,y position offset to correct it.

<img src="https://github.com/bennymeg/JLC-Plugin-for-KiCad/blob/master/assets/position.png?raw=true" height=420>


## Author
Usman J

Adapted from Benny Megidish
