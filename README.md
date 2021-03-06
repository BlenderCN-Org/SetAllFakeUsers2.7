# SetAllFakeUsers2.7
Blender addon for setting all fake users in datablocks.

## Why
Makes it easy to:  
* Add fake users to everything if you want to keep everything in the blend file.  
* Remove fake users to decrease the blend file's size.  
### Features
Can set fake users for following datablocks:
* Brush
* Camera
* Curve
* Font
* Image
* Lamp
* Lattice
* Mask
* Material
* Mesh
* Metaball
* Movieclip
* Node Group
* Object
* Particle
* Texture
* World

## Installation  
### Requirements  
Works on Windows, Mac, and Linux.  
Meant for Blender 2.79b, but may work on previous versions too.  
### How to Install  
Download the python file (put it in a place where you can easily find it, like your desktop)  
In Blender's settings, go to the addons tab  
At the bottom, click "Install from File"  
Find where you put the python file, select it, and click "Install from File" 

## Using
1. Run the operator from...
* File menu > External Data > Set All Fake Users
* Operator Search > Set All Fake Users  
2. A dialog will appear. Set the action to add or remove, and check the datablocks you want to change.
3. Click "Done" at the bottom of the dialog.  

## Notes
The UI may not update automatically to show the change to fake users.  
To fix this, move your mouse cursor over the fake user icon, and it should update.
