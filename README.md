# What it does
Using Raytracing, a virtual space is displayed using realistic physics of how light rays travel and reflect off surfaces. 

![image](https://user-images.githubusercontent.com/28311916/212610459-6c6beae3-c605-4b7a-bb39-ec68947fd0c8.png)

# How it works
This is done so by projecting a ray from the camera through each pixel of the screen onto the plane. Each ray is then tracked and if it intersects an object on the plane, the new reflected ray is calculated. The colour of each point of intersection is then calculated using the Blinn-Phong Model. 
