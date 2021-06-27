# python-midterm-assignment
# Ardak Mukanova
\
Since I’ve been working in Cinema 4d for a while, I wanted to explore the inner tools we can create using python that natively Cinema 4D doesn’t have or doesn’t allow us to use quickly. It can be similar to creating custom templates for the workflow. And maybe, different types of workspaces to save time. Also, it is good to have these tools to use in teams working on the same projects or the same production space.
\
\
Goal:
\
Use python to create custom commands in Cinema 4D for the convenient workspace. 
\
\
Some benefits of using customization:
 
- Making working time more efficient
 
- Save time for creating basing objects or commands we use often

- Assigning hotkeys to various tools and functions

- Docking custom buttons into the shelf to access them quickly

- Scripting can allow us to do something that Cinema 4D doesn’t allow us to do

\
As an example I started with basic commands I use often. First is Center Position, which centers the active object to 0 position. And the Second is a Custom Camera that is aligned to spline and has a target tag. 
\
Center Position was easier to replicate from the C4D script log. I assigned default coordinates for the position and rotation. Also scaling can be added. 
\
For the second example - Custom Camera interpreting the script log was a lot harder. Since c4d doesn't show everything that is happening in the program I needed to find some steps manually. Such as assign target object or spline object. And when they were assigned there was an issue that c4d takes the wrong object for the tags. It took me several hours before I could solve the problem with object assignment. Now the script is working, but I also want to add some keyframes for the spline.
\
\
Problems

- Saving the progress, accidentally can overwrite the existing script, and create errors. Hard to go back.
 
- Script log doesn’t show all the commands. Need to search manually. 

- The code from the script log sometimes requires a different interpretation.

- Python with C4D doesn’t seem very popular, sometimes hard to find the specific solution to a problem. 

\
Future goals:
\
Get more familiar with the C4D python documentation
\
Create selected customized commands and make a small showcase of these tools in Cinema 4D
\
Some of the commands possibly can be used as templates If working in a team on the same/similar project.
\
\
\
Python C4D documentation
\
https://developers.maxon.net/docs/Cinema4DPythonSDK/html/index.html
