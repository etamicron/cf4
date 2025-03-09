This page is where you can view and download CMEaWoT 3d Game Engine. A .zip download of the latest version is available in the "current" folder. Older versions can be found in the "historical" folder.

# Installation Instructions

This program requires [Java](https://www.oracle.com/java/technologies/downloads/) and [Processing](https://processing.org/download). Download the .zip folder and extract it. Then, go into the "cmw_ADH" folder and move the "Launch CMEaWoT" shortcut to your desktop. Use this to launch the demo. You can then put the unzipped folder anywhere on your computer (I'd recommend Program Files).

If the command line window that pops up when you attempt to open the game closes immediately, you may need to add Processing to your environment variables. To do so, follow these steps:

1. Find the Processing folder. If you have a desktop shortcut for Processing, you can right-click that and select "Open File Location".
2. Click the down-pointing-arrow at the right of the bar at the top.
3. Press Ctrl+C to copy the highlighted text.
4. Using the Windows search bar, search and open "Edit the System Environment Variables".
5. Allow Administrator access if needed.
6. Click "Environment Variables".
7. Under "System Variables", scroll until you find "Path". Select it and click "Edit".
8. In the "Variable Name" box, add a semicolon (;) and paste what you have copied using Ctrl+V.
9. Click "Ok"
10. Click "Ok"
11. Click "Ok"
12. Try launching the demo again.

# CMEaWoT Patch Notes

## v0.1 - The 3d Update, SAVE the World
- Models can now be saved in the new .bxt file format
- BXT will now be included in all engine packages
- ADH has been retired in favor of the CCME model editor

## v0.0.1 - The 3d Update, Occlusion Patch
- Occlusion updated to fix certain issues
- Added basic model support; models can rotate and move independently from each other
- Added more buttons to the ADH to control models

## v0.0 - The 3d Update
- Added vertices
- Added triangles
- Added colors
- Added a 3d camera to see these colorful triangles
- Added occlusion to see less colorful triangles
- Intersecting triangles will be partially occluded (i.e. they will look normal)
- Version includes ADH (Alpha Demo Handler) to provide models and camera control
- Fixed bug where there was no code in `cmeawot.pde`
