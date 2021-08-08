# python-final-assignment
# Ardak Mukanova
\
I wanted to explore the inner tools we can create using python that natively Cinema 4D doesn’t allow us to use quickly. These tools can help us to create custom commands and templates for an efficient workflow. Also, it is good to have these tools to use in teams working on the same projects or the same production space.
I worked in C4D Script Manager to write and execute code in the viewport instantly. There were a lot of iterations of some commands because they did not always work correctly.
\
\
Goals:
- Use python to create custom commands in Cinema 4D for the convenient workspace. 
- Try to optimize the commands for future project use. 
\
\
Some benefits of using customization: 
- Save time for creating basic objects or commands we use often
- Assigning hotkeys to various tools and functions
- Docking custom buttons into the shelf to access them 
- Scripting can allow us to do commands that Cinema doesn’t allow by default
\
\
Custom Commands list I was able to make so far:
- Center Position (center all axis to 0)
- Camera position with tags (target and spline tags)
- Light Center
- Materials (random color)
- Simple MoGraph
- Instance Object
- Simple Stage (cameras, light)
- Render Settings
\
\
Problems:
- The code from the script log sometimes requires a different interpretation.
- Sometimes, it is hard to access the inner properties of objects, effects, or materials. 
- Names in the console can be different from the names to access the specific object properties.
- Need to know all C4D terminology to find objects and their properties.
\
\
Future goals:
- Fix some bugs, make StartUndo() to all scripts.
- Rewrite function names where needed for better view and understanding.
- Make a layout template with the custom command buttons that can be shared between projects. 
\
\
\
Resources:
\
Python C4D documentation:
\
https://developers.maxon.net/docs/Cinema4DPythonSDK/html/index.html
\
\
Helpful tutorials and introduction to Python in C4D:
\
https://www.motionmixture.com/python
\
\
Mike Udin tutorials:
\
https://www.youtube.com/c/МихаилЮдин/videos
\
\
Arttu Rautio tutorials:
\
https://aturtur.com/category/cinema-4d/
\
\
Final Project Presentation:
\
https://docs.google.com/presentation/d/13ySGF3zbK5qJngzfkdGUPzoBPga4aw4IDGtkKM9_U9I/edit?usp=sharing
