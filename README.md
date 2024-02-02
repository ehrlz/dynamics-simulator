
# Particle Simulator
This is a simple particle simulator implemented in Python using the OpenGL library. The simulator creates and simulates particles in a 2D environment with realistic physics, including collisions and interactions.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
## How to Use
Left Click: Creates a new particle at the clicked location.
Right Click: Clears all particles from the simulation.

## Physics Constants
- **radius**: Radius of the particles in pixels.
- **g**: Gravitational acceleration vector.
- **BOUNCE_CONST**: Coefficient of restitution for bouncing off the walls.
- **SLIDE_CONST**: Coefficient of friction for sliding along the walls.
- **VEL_MAX**: Maximum velocity magnitude.

## Particle Class
The Object class represents a particle with position and velocity. It has methods to update its physics, handle collisions, and display information.

## Simulation
Particles interact with each other through volume collisions. When two particles collide, their velocities and positions are updated based on the laws of physics.

## Window Size
The window size is set to 800x800 pixels, and the simulation space is defined within this window.

## OpenGL Setup
The OpenGL setup includes window initialization, orthographic projection, and model view settings.

## How to Run
Ensure you have **JupyterNotebook** and the necessary libraries installed, such as **OpenGL** and **NumPy**. Run the script, and the particle simulator window will appear. Use left and right clicks to interact with the simulation.

Feel free to customize and enhance this simulator for your specific needs or use it as a starting point for more complex simulations.