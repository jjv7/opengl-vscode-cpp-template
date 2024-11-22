# OpenGL C++ template for VS Code
This is a template for OpenGL projects in C++ designed for use with Visual Studio Code. It uses the GLAD and GLFW libraries, based on the tutorials at [Learn OpenGL](https://learnopengl.com/).

## Requirements
To run this template you must have:
- x64 Windows 10/11
- The GCC compiler
- The C/C++ extension for VS Code

### Install GCC and C++ for VS Code
Follow the instructions at https://code.visualstudio.com/docs/cpp/config-mingw#_prerequisites

### GLAD and GLFW Library Files
GLAD and GLFW files were obtained from the following sites and were placed in the include folder: 
- **GLAD**: https://glad.dav1d.de/
- **GLFW**: https://www.glfw.org/download.html

## Quick Start

1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/jjv7/opengl-vscode-cpp-template
   ```
2. **Define the path to the gcc compiler in `.vscode/tasks.json`**: Update the `command` field with the path to your GCC compiler. For example:
   
   ```json
   "command": "C:/path/to/your/compiler/g++.exe"
   ```
3. **Build and run the project**:
    From the VS Code menu, go to **Run** > **Run Without Debugging**
4. **Check the output**:
   If successful, a resizeable window of dark green-blueish colour should appear

## License
This project is licensed under the MIT License. You may use, modify, and distribute it freely without the need for attribution. See the [LICENSE](LICENSE) file for more details.
