# OpenGL GFX Boilerplate

This is a minimalistic GFX (Graphics) programming project boilerplate using GLFW (Graphics Library Framework). 
It serves as a starting point for setting up a GLFW-based project with OpenGL. 

The provided code initializes a GLFW window with an OpenGL context and sets it up for modern OpenGL (Core Profile).

All the libraries used in this project are included in the `dependencies` folder, currently 
running on windows and macOS.

## Getting Started
* Just clone or download this repository to your machine and run the project:
```bash
git clone https://github.com/luansapelli/gfx-foundation.git
```

## Project Structure
* `src/main.cpp` -> Contains the main program logic.
* `dependencies` -> Contains all the libraries used in this project.
* `CMakeLists.txt` -> CMake configuration file for building the project to windows and macOS target.

## Customization
Feel free to modify the main.cpp file to include your graphics rendering logic. 
Add shaders, textures, and other OpenGL components as needed for your specific project.

## Notes
* The provided code sets up a GLFW window and OpenGL context with a version of 4.6, using the core profile.
* I am using CLion as IDE for this project, the current configuration was made to CLion IDE. You can use any IDE
of your preference, but some configurations may be needed.
