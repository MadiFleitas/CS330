# CS330 Final Project - 3D Scene Management

This project is part of the CS330 course, focusing on Computational Graphics and Visualization. The project involves creating a 3D scene management system using OpenGL, which includes managing textures, materials, lighting, and rendering various 3D shapes.

## Features
- 3D scene management with transformations (scaling, rotation, translation).
- Material properties definition for different objects (e.g., wood, metal, glass).
- Multiple light source configurations (directional, point, and spotlight).
- Texture loading and application to various 3D shapes.
- Shapes included: plane, cylinder, cone, sphere, and box.

## Project Structure
The main source files for the project are located in the `Projects/7-1_FinalProjectMilestones` directory. Key components include:

- `SceneManager.cpp`: Handles the preparation and rendering of the 3D scene.
- `ViewManager.h/cpp`: Manages the view and camera settings.
- Textures are located in the `textures/` folder.
- Material definitions are managed within the `DefineObjectMaterials()` function.

## Getting Started

### Prerequisites
To run this project, you need:
- **OpenGL and GLM**: Ensure you have these libraries installed.
- **C++ Development Environment**: Visual Studio 2022 or a similar IDE that supports modern C++.
- **Git**: For version control.

### Cloning the Repository
1. Clone the repository using:
   ```bash
   git clone https://github.com/MadiFleitas/CS330.git
