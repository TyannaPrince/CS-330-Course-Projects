Welcome to the repository for the various projects from my CS 330 Computer Graphics and Visualization class at SNHU Online! This class focused on creating 3-dimensional objects in space using the OpenGl libraries for C++. The base program originated from various tutorials, but the URender method for rendering shapes to the screen was refactored by me. Additionally, the separate classes for ShapeBuild(er)ing and SceneBuild(er)ing were developed from scratch by me. The final project showcases how these classes and their methods work together to create a module, user-friendly program that anyone can use to create a simple 3D scene. Feel free to browse my code and check out the various applications that I developed during the semester. 
You are welcome to clone any files and use them for your own projects as you see fit. I've included commenting in the "Scenebuilder.cpp" file to explain how to use it properly. If all you want to do is render shapes in an environement, then that file is all you'll need to modify! 
________________________________________
Final Project: A 3D Scene
Scene
The overall scene. Requirements were to have at least one complex shape and a light source; I added several of each.
This pen was the first complex shape I built, using a cone and serveral cylinders. The texture was created by hand in Adobe Illustrator

Coffee
The coffee cup in the scene is made from a combinations of shapes, including a several hollow cylinders and a flat circle.
Many of the textures are visual tricks. This tablet's buttons are textured to look shadowed, but in fact this is a flat surface.

Tablet
Many of the textures are visual tricks. This tablet's buttons are textured to look shadowed, but in fact this is a flat surface.

Scene Builder and Shape Builder algorithms
All algorithms for constructing shapes in the scene were written by me, from scratch. Each algorithm builds the shape as well as writes the coordinates for the imported textures.

The Final Product: The Scene
There were several requirements of the final project (as can be seein the documentation above). In this animation the multiple light sources can be seen, including one that is colored. The colored light can be turned on and off with the '[' and ']' keys, and the revolving white light can be made stationary with the left or right 'alt' keys. The white light can also be repositioned with the letter keys on the right of the keyboard.
The camera can be moved using the WASD keys, as well as QE for altitude changes. The speed of the camera can be changed with the mouse wheel, and the view is changed through mouse movement. Wireframe models are viewable with left and right arrow keys.

I hope everyone enjoys! 
```Tyanna
