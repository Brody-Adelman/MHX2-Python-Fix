# MHX2-Python-Fix
Run-Once Program for MHX2 Armatures to Fix SheepIt Restriction of Python Scripts

Since the [SheepIt!](https://www.sheepit-renderfarm.com/) Render Farm [does not allow Python scripts to be run at render time](https://www.sheepit-renderfarm.com/faq.php#faq37641), one must jump through a lot of hoops to use animated MakeHuman 3D models in a project submitted to the render farm. This series of commands can be pasted into the Blender Python console to perform all of these steps automagically!

## How to Use

1. Download a copy of the code from the repo. It'll be called something along the lines of "MHX2 Python Scripts Fix Code V1.txt"
2. Change the `Name` line to the name of your model so that the program knows what model to operate on.
3. Change the `Layer` line to the layer your model is currently on.
4. Change the `GizmoScrapLayer` line to the layer number you want to put the miscellaneous extra handles (most of which don't do anything) onto to get them out of the way. 
5. Read the Directions and Instructions PDF included in the repo for more details.
