# Info

This program will allow you to utilize MakeHuman armatures with online render farms that disable the use of python scripts (i.e. SheepIt). Version 1.0 currently only allows utilization of IK (Inverse Kinematics) rigging.

#### Future Updates Will Include:
  * Visemes
  * Expressions
  * Poses
  * Motion Capture (BVH) Utilization
  * FK/IK Switch


## Instructions:
1. Uncheck `Auto Run Python Scripts` in user preferences. This step isn’t necessary. However, it can help you detect issues before you send your file out to render.

<img src="https://i.imgur.com/cPrVwUW.png" alt="User Preferences" style="width:200px;"/>

2. Select `Import MHX2` from the `File > Import` menu.

<img src="https://i.imgur.com/pCAvmuV.png" alt="Import MH2X" style="width:200px;"/>

3. Select your character that you want to use and click `Override Exported Data`. Set the settings as you would like. The rig must be MHX in order for the program to work. Then click import. 
  *This program doesn’t work with other rigs because I tested them and found that MXH was the only one that imported correctly without python scripts enabled.
  
<img src="https://i.imgur.com/MWs1LbV.png" alt="Overwrite Exported Data" style="width:200px;"/>

4. Download the code and open it in a text editing software. Insert the name of your model into the beginning of the code, where specified. The model layer and gizmo scrap layer are also adjustable, but the usual default layer numbers are written in the code. 

<img src="https://i.imgur.com/tH2iFwF.png" alt="Change Name" style="width:200px;"/>

5. Copy the entirety of the code.

<img src="https://i.imgur.com/CbHIcKO.png" alt="Copy all of the code" style="width:200px;"/>

6. Open the python console. 
  *I would suggest saving your work before the next step because Blender may crash.*
  
<img src="https://i.imgur.com/aqqYuIV.png" alt="Open Python Console" style="width:200px;"/>
  
7. Paste the code into the python console. Enjoy your new IK rig capable of rendering with SheepIt render farm!

<img src="https://i.imgur.com/jxEfrRS.png" alt="All done!" style="width:200px;"/>
