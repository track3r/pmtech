# pmtech [![Build Status](https://travis-ci.org/polymonster/pmtech.svg?branch=master)](https://travis-ci.org/polymonster/pmtech) [![Build Status](https://ci.appveyor.com/api/projects/status/5n3aguiq1ppjrhws?svg=true)](https://ci.appveyor.com/project/polymonster/pmtech)

Follow work in progress: 
[trello](https://trello.com/b/ciujzpUT)

A lightweight code base with powerful features that can be used for games and real-time graphics applications. This project focuses on data-oriented and multithreaded systems with minimalistic c-style api's and a strong emphasis on performance.

Take a look at: 
[demos...](https://polymonster.github.io/index.html)

**Platforms**  
- OS: Windows, MacOS, Linux, iOS, Android (wip).   
- Renderers: Direct3D11, OpenGL3.1+, OpenGLES3+.   
- Compilers: vs2017, Clang 6, Apple LLVM 9, Gcc 7. 

**Features**  
- Multithreaded - Async render, physics, audio and component entity system. 
- Data-oriented Component Entity System - SoA memory layout for blazing fast scene representation.
- PMFX - High level data driven renderer, shader and post-processing system.
- Hot loading - reload configs, shaders, models and textures in real time for rapid development.
- Tools - Graphical editor, volume texture / signed distance field generator.
- Asset Pipeline - binary model and skeleton format, texture compression, platform agnostic shader compilation. 

**Getting started** 

To build data and generate example projects run build.sh or build.bat. Workspace and projects are generated in examples/build/platform.

For more information about how to use different toolsets or hook into the sdk, take a look at this [guide](https://polymonster.github.io/articles.html#getting-started)

**Shoutout!**  
- [Jsmn](https://github.com/zserge/jsmn)
- [Premake](https://github.com/premake/premake-core)
- [Bullet](https://github.com/bulletphysics/bullet3)
- [ImGui](https://github.com/ocornut/imgui)
- [NVTT](https://github.com/castano/nvidia-texture-tools)

