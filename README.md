## WebGL Project
![image](https://github.com/simonlim42/WebGL-Playground/assets/61169518/adf27332-e5d1-4901-98a7-5d244bd4eb21)
![image](https://github.com/simonlim42/WebGL-Playground/assets/61169518/ec992b40-7e18-4a9f-a3b4-f2bd107b6466)

## Introduction
The WebGL project is a 3D visualization application built using Three.js, a popular JavaScript library for creating 3D graphics in the browser. This project showcases various objects, textures, and lighting effects, allowing users to interact with the scene using keyboard inputs.
## How to run
Firstly, it is required that you access the `WebGL-Coursework.html` file and alter the path to the objects/textures loaded. You may run a local web server and access this file, objects, and textures. More information on running things locally can be found at [Three.js Documentation](https://threejs.org/docs/#manual/en/introduction/How-to-run-things-locally). There are 6 textures and 3 objects that paths are required to be altered.

## How to Run

To run the WebGL project, follow these steps:

1. **File Path Configuration:**
   - Access the `WebGL-Coursework.html` file.
   - Modify the paths to the objects and textures loaded in the HTML file. Ensure correct file paths are specified for the 6 textures and 3 objects used in the project.

2. **Local Server Setup:**
   - Run a local web server to host the project files. This can be achieved using tools like Python's SimpleHTTPServer or Node.js's http-server. For example, using Python, navigate to the project directory in the terminal and run:
     ```
     python -m SimpleHTTPServer
     ```
     This will start a local server at `http://localhost:8000`.

3. **Accessing the Project:**
   - Open a web browser and visit `http://localhost:8000/WebGL-Coursework.html` to view the WebGL project.

## Project Requirements

### Requirement 1
- The cube is within the scene when the HTML file is loaded.
- It is centered at (0,0,0).
- No button presses required.

### Requirement 2
- The axes are shown when the scene starts.
- No button presses required.

### Requirement 3
- To rotate the cube along the X axis, press keyboard input '931'94.
- To rotate the cube along the Y axis, press keyboard input '932'94.
- To rotate the cube along the Z axis, press keyboard input '933'94.
- To stop any rotations of the cube along the axis, press the keyboard input again.

### Requirement 4
- Face render mode: 'e' key
- Edges render mode: 'r' key
  ![image](https://github.com/simonlim42/WebGL-Playground/assets/61169518/4b923f48-789f-4842-9d30-a9f9579f79be)
- Vertex render mode: 't' key
  ![image](https://github.com/simonlim42/WebGL-Playground/assets/61169518/96bd1029-1595-4cd0-9476-c4b49300fe93)
### Requirement 5
- Camera move up: 'up arrow' key
- Camera move down: 'down arrow' key
- Camera move left: 'left arrow' key
- Camera move right: 'right arrow' key
- Camera move forward: 'w' key
- Camera move backward: 's' key

### Requirement 6
- Orbit camera horizontally right: 'm' key
- Orbit camera horizontally left: 'n' key
- Orbit camera vertically up: 'i' key
- Orbit camera vertically down: 'k' key

### Requirement 7
- To see textured cube: 'y' key
- You are able to switch between different render modes.

### Requirement 8
- To see the bunny, just turn the cube to wireframe mode/vertex mode. It will be perfectly within the cube.

### Requirement 9
- Bunny face render mode: 'd' key
- Bunny edges render mode: 'f' key
- Bunny vertex render mode: 'g' key
- To rotate the bunny along the X axis, press keyboard input '934'94.
- To rotate the bunny along the Y axis, press keyboard input '935'94.
- To rotate the bunny along the Z axis, press keyboard input '936'94.
- To stop any rotations of the bunny along the axis, press the keyboard input again.

### Requirement 10
- There is no implementation to remove cat and wolf.
- To see the bunny bounce around, press '938'94.
- To have a nice platform to see shadows and take cute pictures of my objects, press '939'94.
