# BCA Kicad Project Template

This repository is a template for BCA kicad projects. It contains two folders for documentation & gerber files, a kicad project template, and a BOM template (inside the documentation folder). The PCB file has an outline of the enclosure on its dwg.user layer, pre-defined jack locations, and a board outline. These may be modified as required. To create a new repository from this template, a couple steps are required:

 - Rename the appropriate files, replacing "kicad-template-1590XX" with the project name. 

From there, a tag should be added to the git project every time a new PCB revision is made. From right to left, the three digit numbers should be incremented for every: minor schematic or component value revision, PCB revision with no changes to external controls, and PCB revision with changes to the external controls. A brief descriptor should be made for each new tag as shown below.

## v1.0.0-build
