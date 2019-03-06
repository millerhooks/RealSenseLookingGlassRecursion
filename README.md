# RealSenseLookingGlassRecursion
Experimenting with the fact that the Intel RealSense will get depth data from 3d content on the Looking Glass Display

Inspired by this tweet (https://twitter.com/jun_mh4g/status/1102932506901307398) by @jun_mh4g
![alt text](https://raw.githubusercontent.com/millerhooks/RealSenseLookingGlassRecursion/master/Docs/Images/tweet.png)

Here I have set up a project with the Intel Realsense (https://github.com/IntelRealSense/librealsense) and Looking Glass Display Holoplay
with the goal of trying to undertand new and interesting interaction patterns by looping depth display on itself. 

There is a scene in `Scenes/RSRecursion` that is set up to display an RS point cloud at about 20-40cm from a D315 and render
with the LookingGlass Holodisplay Game Camera.

My results have been mixed so far, but I see a lot of potential in the pattern. Potentially a D415 is better suited for this 
than the wide angle D435 More updates to come.
