# CS-330-Final-Project
3D scene created using C++ and OpenGL demonstrating textures, lighting, and camera movement.

This project is an interactive 3D scene built using C++ and OpenGL.

## Features
- Textured floor using UV scaling
- 3D mug created from primitive shapes
- Phong lighting with multiple light sources
- Camera navigation (W/A/S/D + mouse)

## Controls
- W/S: Move forward/backward
- A/D: Move left/right
- Q/E: Move up/down
- Mouse: Look around

## Project Overview
This portfolio artifact was created for CS 330: Computational Graphics and Visualization at Southern New Hampshire University. The project demonstrates a fully realized 3D scene built with C++ and OpenGL. My scene includes a coffee mug on a coaster, a notebook, and a textured floor. The project uses primitive shapes, textures, lighting, materials, and camera navigation to create an interactive 3D environment.

## Design Reflection

### How do I approach designing software?
I approach designing software by first breaking down the problem into smaller parts. For this project, I looked at my reference scene and identified the basic shapes needed to represent each object. The mug was built from a cylinder and torus, the coaster from a cylinder, the notebook from a box, and the floor from a plane. This helped me plan the scene before writing the code.

### What new design skills has your work on the project helped you craft?
This project helped me improve my ability to think in 3D space. I learned how to arrange objects using X, Y, and Z coordinates and how scale, rotation, and translation work together. I also learned how textures, materials, and lighting affect the final appearance of a scene.

### What design process did you follow for your project work?
My process was iterative. I started with the basic shapes, then adjusted their size and position until the scene looked correct. After that, I added textures, lighting, and camera controls. I tested the project often and made changes when objects looked misaligned or unrealistic.

### How could tactics from your design approach be applied in future work?
The same approach can be used in future software projects by breaking large problems into smaller pieces, testing frequently, and improving the design through iteration. Planning the structure first makes the coding process easier and reduces errors.

### How do I approach developing programs?
I approach development step by step. I try to get one feature working before moving to the next. In this project, I first focused on object creation, then textures, then lighting, and finally camera navigation and polish.

### What new development strategies did you use while working on your 3D scene?
I used modular functions such as `SetTransformations`, `SetShaderTexture`, `SetShaderMaterial`, `DefineObjectMaterials`, and `SetupSceneLights`. These functions helped keep the code organized and reduced repeated code.

### How did iteration factor into your development?
Iteration was very important. Some objects did not look right the first time, such as the mug appearing too high above the coaster. I adjusted the position values and tested the scene until the objects looked properly aligned. I also changed the mug material to make it look more realistic.

### How has your approach to developing code evolved throughout the milestones?
At the beginning of the course, I focused mostly on getting shapes to appear. As the milestones progressed, I became more comfortable organizing the scene, adding textures, applying lighting, and improving navigation. My approach became more structured because I learned to test each feature before adding the next one.

### How can computer science help me in reaching my goals?
Computer science helps me build problem-solving skills that are useful in many areas of software development. This course showed me how programming can be used not only for logic and data, but also for visual and interactive experiences.

### How do computational graphics and visualizations apply to my future educational pathway?
Computational graphics gave me a better understanding of rendering, transformations, lighting, and camera systems. These concepts will help me in future courses that involve software engineering, visualization, user interfaces, or interactive applications.

### How do computational graphics and visualizations apply to my future professional pathway?
Professionally, these skills can support work in front-end development, UI/UX, WebGL, Three.js, game development, or interactive visualization. Since I already have experience with web development, learning OpenGL gives me a stronger foundation for creating more visual and interactive applications.

## Repository Contents
- 3D Scene ZIP folder
- Design Decisions document
- README reflection

## AI Usage Acknowledgment
I used AI tools to help review, organize, and refine explanations for this project while making sure the final work reflected my own understanding and implementation.
