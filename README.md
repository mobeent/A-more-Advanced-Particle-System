# A-more-Advanced-Particle-System

Project Video:
https://youtu.be/IcBPjTIQ2tQ

Source Code cannot be uploaded as I do not own the base engine that this project works on. Below is the general description of the project. Programming language used is C++ with Directx9, Directx11 and OpenGL

* Added support for multiple Emitters at a single time.
* Made a separate Class which handles the updates, creation and rendering of the emitters.
* Added a fire effect and smoke effect using emitters.
* Attached emitters to soldiers so that it gives the effect of breathing in cold air.
* Attached emitters are linked with the movement state machine which gives each emitter the direction and current position of the soldier using which the update function moves the particles accordingly in the given direction and spawns new particles at the current position of the soldier.
* Added alpha blending to the particles.
* Passed the ratio of current age and original age to the vertex and pixel shaders using the same technique as last project to send velocity.
* Set this ratio as the alpha value in the pixel shader.
