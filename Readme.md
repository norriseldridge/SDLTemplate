# SDL Project Template
This is a completely bare bones Visual Studio 2022 project setup for starting a new SDL2 project.
The basic SDL2 library is added into an "External" directory and hooked up in the project properties to build and run.
Simply follow this convention for added any new libraries in the future.

Note that SDL2.dll is also added as a Resource file in the project and marked as "Copy file". This is so the DLL is always copied to the output directory as it is required for the project to run.
