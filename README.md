# VulkanProject
3D rendering engine written from scratch in ***C++*** and ***Vulkan API***, created to render simple models.

## Showcase
<img width="797" height="628" alt="image" src="https://github.com/user-attachments/assets/04f57198-159a-49ad-af06-4cdcccd29c60" />
<img width="797" height="628" alt="image" src="https://github.com/user-attachments/assets/5873ee1f-17a5-4161-a733-288c69828745" />
<img width="797" height="628" alt="image" src="https://github.com/user-attachments/assets/cadbfdff-a12c-47bc-b059-ec2e06eaa842" />


## Controls
Use ***W A S D*** to move the camera around the world.

Use ***Shift*** and ***Space*** to move up and down.

Use ***ESC*** to close the simulator.

## Prerequisites
This engine was tested on **Linux/Unix** (Manjaro) environment using ***NVIDIA RTX 4050 Laptop***.

Due to complexity in Vulkan API it might not work on every device.

In order to build and run this application, you must have a C++17 compiler (`g++`) and `make` installed, along with the following dependencies:
* **Vulkan SDK**
* **GLFW 3**
* **STB Image** 
* **OpenAL**, **mpg123**
* **Standard Linux/X11 development packages**


## Build and run

Run this command in terminal to compile GLSL shaders and source code along with starting the engine:
```bash
make exec
```

To clean up the compiled binaries run:
```bash
make clean
```

# Reference
https://vulkan-tutorial.com/
