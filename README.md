# module-8-assignment-cs330
# CS 330: Computational Graphics and Visualization

## Final Project: 3D Desktop Scene

In my final project I recreated a desktop scene in OpenGL using basic 3D shapes. The scene includes a lamp, a stack of books, a glass coffee cup, a plant, and a gold plate with pieces of chocolate. I worked on the placement of each object, then added materials, textures, lighting, and camera controls to bring the scene together.

**Project files:** CS330_3D_Scene.zip contains my Visual Studio project, source code, shaders, textures, and executables. `CS330_Design_Decisions.docx` explains the choices I made while building the scene.

### Viewing the project

The project was created with C++ and OpenGL in Visual Studio 2022. Extract the 3D Scene ZIP before opening Projects/7-1_FinalProjectMilestones/7-1_FinalProjectMilestones.sln or running the included Windows executable. Keep the folder structure intact so the project can find its shaders and textures.

The camera supports WASD for movement, Q and E for moving up or down, right mouse drag to look around, the mouse wheel to change movement speed, and P to switch between perspective and orthographic views.

## Reflection

### How do I approach designing software?

Working on this project taught me to think about the layout before I start writing too much code. I used a photograph of a desk as my reference and broke the objects down into shapes I could create with OpenGL. The books were mostly boxes, while the coffee cup, lamp, and plant needed several shapes put together. I had to pay a lot of attention to scale, rotation, and positioning of the objects in the scene than I expected because even minor changes could make the whole scene look different.

I started with the larger objects to get the basic arrangement in place, then worked on smaller details, textures, and lighting. I also learned that I don't need to model every detail for an object to be recognizable. This is an approach I can use in future projects: figure out the important parts first, make a workable version, and improve it from there instead of trying to get everything right at once.

### How do I approach developing programs?

I worked on the scene in stages rather than trying to add everything at the same time. First I focused on building and placing the objects. Later I adjusted the materials, added lighting, and worked on the camera so the user could move around the scene. Seeing the results on the screen helped me catch problems that weren't always obvious from reading the code. I spent a lot of time making small changes, running the program, and checking whether each change actually improved the scene.

One useful change was using a drawing function that takes an object's shape, position, size, color, and material as arguments. It kept me from repeating the same setup for every part of the scene. I also had to pay attention to how the program located its shader and texture files when it was launched from different folders. By the end of the milestones, I was more comfortable keeping different tasks in separate functions and testing changes as I went. That made the final project much easier to manage.

### How can computer science help me reach my goals?

I may not work directly with 3D graphics in my career, however, this course gave me more practice with C++, debugging, and understanding how different parts of a program work together. I also got a better understanding of transformations, camera movement, lighting, and how a 3D scene is displayed on a 2D screen. Those concepts will be useful if I work with visual applications or more advanced programming projects in future courses.

Professionally, I want to keep building my technical skills and move into a computer science role. This project reminded me that programming involves more than getting the code to compile. I also need to plan what I'm building, solve problems as they come up, and make sure the finished result works as intended. Those are skills I can use in software development and other technical areas, even when the project has nothing to do with graphics.
