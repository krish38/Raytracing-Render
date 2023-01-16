# What it does
Using Raytracing, a virtual space is displayed using realistic physics of how light rays travel and reflect off surfaces. 



# How it works
This is done so by projecting a ray from the camera through each pixel of the screen onto the plane. Each ray is then tracked and if it intersects an object on the plane, the new reflected ray is calculated. The colour of each point of intersection is then calculated using the Blinn-Phong Model. 
