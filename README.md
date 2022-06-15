# Real-time Graphics
This project was created for the course "Real-time Graphics Programming for Games 1" Course code (5sd805) by Miguel Redondo. The objective of the course was to look at modern rendering pipeline and fundamental terms and concepts within real-time computer graphics.

The objective of the assignment was to create a scene with objects that were textured and affected by the directional light. The objects had to be constantly moving or rotating. It was also required that one could modify the directional light's color and direction.
There were also specifics about having a dynamic FPS counter as well as a moveable camera, basically just simulating a real game engine without the physics part.

Something that I added even though it was not required was two spheres and a point light which can be seen in the far back of the starting screen. 
The pointlight-spheres do cast shadows(from the directional light) but they are not affected by other objects' shadow. 
This is something that I intend to change later on because I want them be affected by both the directional light and the point light.

I also applied shadow mapping to the scene as well as a post processing effect.

The way one modifies the light direction and color is through hardcoded keybindings. The keybindings can be shown "in-game" by pressing the 'I' key.
The required FPS counter can be toggled on/off by pressing the 'TAB' key.
The post processing effect/filter can be toggled on/off by pressing the 'O' key.

Note that not all code was written by me. The 'neon-core' and 'neon-main' were projects that was given to us by the teacher in order to faster learn about the rendering pipeline. The code in the 'neon-testbed' project was written by me. 

Feel free to contact me if you have any questions or suggestions. I would be very excited to hear about it!
Email: Miggex91@hotmail.com
